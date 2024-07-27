
<script>
    import { page } from '$app/stores';
    let productid = $page.params.productid;
</script>
<h1>details of products <br> product {productid}</h1>
<h2><a href="/products/{productid}/reviews/{productid}">The review of the product{productid}</h2>