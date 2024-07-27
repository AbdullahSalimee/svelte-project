<header><style>
    ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
      overflow: hidden;
      background-color: #333;
    }
    
    li {
      float: left;
    }
    
    li a {
      display: block;
      color: white;
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
    }
    
    li a:hover:not(.active) {
      background-color: #111;
    }
    
    .active {
      background-color: #04AA6D;
    }
    </style>
    
    <script>
        export let productId =100;
    </script>
        
    <ul>
      <li><a class="active" href="/">Home</a></li>
      <li><a href="/blog">blog</a></li>
      <li><a href="/products">products</a></li>
      <li><a href="/profile">profile</a></li>
      <li><a href="/docs">Document</a></li>
      <li><a href="/lang/en">lang</a></li>
      <li><a href="/about">About</a></li>
    </ul></header>
<slot/>