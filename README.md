<html lang="en"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->
  
    <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
    <link rel="stylesheet" href="Product_Preview_Card.css">
    <!-- <title>Frontend Mentor | Product preview card component</title> -->
  <!-- Fuente importada 1 -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,700&family=Montserrat:wght@500&display=swap" rel="stylesheet">
  <!-- Fuente importada 2 -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,700&family=Montserrat:wght@500&display=swap" rel="stylesheet">
  <!-- Fuente importada 3 -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,700&family=Montserrat:ital,wght@1,700&display=swap" rel="stylesheet">
  <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
    <style>
     *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.container{
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
    background-color: hsl(30, 38%, 92%);
    padding: 0 20px;
}
.card-container{
    display: flex;
    width: 600px;
    height: auto;
    background:white;
    border-radius: 0.8rem;
    
}
.card-container:hover{
    box-shadow: 1px 1px 2px rgba(0, 0, 0 , 2) ;
    transition: 1s;
}
.header{
    display: flex;
    align-items: left;
}
.User-interfaz{
    margin-right:0;
    text-align: left;

}
.header img{
    width: 300px;
    padding: auto;
    margin: -1.25rem 0 -1.25rem -1.25rem;
    border-top-left-radius: 0.8rem;
    border-bottom-left-radius: 0.8rem;
}
.header, .user-interfaz{
    padding: 20px;
    
}
.header h4{
    padding: 10px;
    text-align: left;
    font-family:'Montserrat', sans-serif;
    font-weight: 700;
    margin-left: 0.4rem;
    font-size: 15px;
    margin-top: -1rem;
    opacity: 60%;
    
}
.header h2{
    text-align: left;
    margin-left: 0.5rem;
    padding: 5px;
    font-size: 30px;
    font-family:'Fraunces', serif;
    font-weight: 700;

}
.header p{
    padding: 0.8rem;
    text-align: left;
    font-size: 14px;
    font-family: 'Montserrat', sans-serif;
    margin-bottom:5px;
    opacity: 60%;

}

span{
    color: hsl(158, 36%, 37%);
    font-family: 'Fraunces', serif;
    font-size: 30px;
    float: right;
    margin-top: 0.7rem;
    
    
}
button{
    background-color: hsl(158, 36%, 37%);
    color:white;
    padding: 12px 72px;
    text-align: center;
    margin-left: 1.2rem;
    border-radius: 6px;
    border: 0;
    font-family: 'Montserrat', sans-serif;;
    margin-top: 5px;
}
button:hover{
    box-shadow: 2px 2px 2px 2px hsl(158, 36%, 37%);
    transition: .5s;
    cursor: pointer;
}
.carrito{
    display: flex;
    align-items: left;
}

.old-price{
    float: right;
    font-family: 'Fraunces', serif;
    text-decoration: line-through;
    margin-top: 1rem;
}

@media (max-width:640px){
    .card-container{
        display:block;
    }
    .header{
        padding:20px 20px 5px 20px ;
        border:none;
    }
    .user-interfaz{
        padding: 5px 20px 20px 20px ;
        background: transparent;
    }
    .header h4{
        margin:0;
    }
}

    </style>
  </head>
  <body>
    
    <div class="container">
      <div class="card-container">
        <div class="header">
          <img src="Img/image-product-desktop.jpg">
        <div class="UI-DIV">
      <div class="user-interfaz">
        <h4>P E R F U M E</h4>
        <h2>Gabrielle<br>Essence Eau<br> De Parfum</h2>
        <p>A floral, solar and voluptous interpretation composed by Olivier Poige, Perfumer-Creator for the house of CHANEL.</p>
        <div class="prices">
        <p class="old-price">$169.99</p>
        <span>$149.99</span>
        <button>Add to cart</button>
        </div>
        </div>
      </div>
    </div>

    
