
 
 <script>
import { page } from '$app/stores';
const greetings ={
    en: 'hello!',
    es: 'hola!',
    fr: 'bonjour!'
}
const {lang} = $page.params;
const greeting = greetings[lang];

function reloadPage(event) {
            event.preventDefault();
            window.location.href = event.target.href;
        }
</script>
<h1>{greeting}</h1>
<h1><a href="/lang/en" on:click={reloadPage(e)}>ENGLISH</a></h1>
<h1><a href="/lang/es" on:click={reloadPage(e)}>SPANISH</a></h1>
<h1><a href="/lang/fr" on:click={reloadPage(e)}>FRENCH</a></h1>

