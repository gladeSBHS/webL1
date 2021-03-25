<!DOCTYPE html>

<head>
    <title></title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <nav>
       
    </nav>
    <section>
        <div class="info">
            <h1>welcome</h1>
            <p>ihiufhsiufh</p>
        </div>
        <div class="product">

            <img src="images/hoodie1.png">
        </div>
        <div class="link">
            <a href="index.html">HOME</a>
            <a href="index.html">SHOP</a>
            <a href="index.html">CONTACT</a>
            <a href="index.html">SIZING</a>
        </div>
        <div class="logo">
            <img src="images/logo.png">
        </div>
        <div class="box">


        </div>
    </section>
</body>
html {

    background: rgb(54, 83, 162);
    background: linear-gradient(276deg, rgba(54, 83, 162, 1) 10%, rgba(21, 184, 193, 1) 100%);
}

nav {
    background-color: crimson;
    grid-column: 3/4;
    grid-row: 1/2;
}

section {
    display: grid;
    grid-template-columns: 2% 1fr 2fr 2fr 1fr 2%;
    grid-template-rows: 100px 400px;
}

.info {
    font-family: "Rogueland Free";
    grid-column: 3/4;
    grid-row: 2/3;
}

.product {
    grid-column: 4/5;
    grid-row: 2/3;
    justify-self: center;
}

.link {
    font-family: "Urusans Personal Use";
    font-size: 250%;
    grid-column: 3/4;
    grid-row: 1/2;
    justify-self: center;
    margin: 20px;
}

.logo {
    grid-column: 5/6;
    grid-row: 1/2;
    justify-self: end;
}

.box {
    box-shadow: 1px 1px 2px black, 0 0 45px black, 0 0 10px black;
    grid-column: 3/5;
    grid-row: 2/3;
}
