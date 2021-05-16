<!DOCTYPE html>

<head>
    <title>title</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <nav>

    </nav>
    <section>
        <div class="info">
            <p>NEW PRODUCTS<br>NEW HOODIES<br>NEW T-SHIRTS<br>NEW COLLECTION </p>
        </div>
        <div class="product">
            <img src="images/hoodie1.png">
        </div>
        <div class="link">
            <a href="index.html">HOME</a>
            <a href="shop.html">SHOP</a>
            <a href="sizing.html">SIZING</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="logo">
            <img src="images/logo.png">
        </div>
        <div class="box">
        </div>
    </section>
</body>

<!DOCTYPE html>

<head>
    <title></title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <nav>

    </nav>
    <section>
        <div class="link">
            <a href="index.html">HOME</a>
            <a href="shop.html">SHOP</a>
            <a href="sizing.html">SIZING</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="logo">
            <img src="images/logo.png">
        </div>
        <div>
            <ul class="shop">
                <li>
                    <img src="images/black%20tshirt.png">
                    <h1>Black Shirt</h1>
                    <p>$30</p>
                </li>
                <li>
                    <img src="images/white%20tshirt.png">
                    <h1>White Shirt</h1>
                    <p>$30</p>
                </li>
                <li>
                    <img src="images/white%20hoddie.png">
                    <h1>White Hoodie</h1>
                    <p>$45</p>
                </li>
                <li>
                    <img src="images/black%20hoodie.png">
                    <h1>Black Hoodie</h1>
                    <p>$45</p>
                </li>
            </ul>
        </div>
    </section>
</body>

<!DOCTYPE html>

<head>
    <title></title>
    <link rel="stylesheet" href="styles.css">
    <script>
        function calulate() {
            var data = document.getElementById("neck").value;
            if (data <= 15) {
                document.getElementById("answer").innerHTML = 'You are smaller than the smallest size';
            }
            if (data >= 15 && data < 15.5) {
                document.getElementById("answer").innerHTML = 'Your size is S';
            }
            if (data >= 15.5 && data < 15.75) {
                document.getElementById("answer").innerHTML = 'Your size is M';
            }
            if (data >= 16 && data < 16.5) {
                document.getElementById("answer").innerHTML = 'Your size is L';
            }
            if (data >= 17 && data < 17.5) {
                document.getElementById("answer").innerHTML = 'Your size is XL';
            }
            if (data >= 18 && data < 18.5) {
                document.getElementById("answer").innerHTML = 'Your size is XXL';
            }
            if (data >= 18.5) {
                document.getElementById("answer").innerHTML = 'You are bigger than the biggest size';
            }
        }

    </script>
</head>

<body>
    <nav>
    </nav>
    <section>
        <div class="link">
            <a href="index.html">HOME</a>
            <a href="shop.html">SHOP</a>
            <a href="sizing.html">SIZING</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="logo">
            <img src="images/logo.png">
        </div>
        <div class="size">
            <input type="number" name="size" id="neck">
            <button type="submit" onclick="calulate()">Submit</button>
            <p id='answer'></p>
        </div>
        <div class="info2">
            <p>Put your neck size(inchs) into the box then click submit. </p>
        </div>
    </section>
</body>

<!DOCTYPE html>

<head>
    <title></title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <nav>

    </nav>
    <section>
        <div class="link">
            <a href="index.html">HOME</a>
            <a href="shop.html">SHOP</a>
            <a href="sizing.html">SIZING</a>
            <a href="contact.html">CONTACT</a>
        </div>
        <div class="logo">
            <img src="images/logo.png">
        </div>
    </section>
</body>

html {
    background: rgb(54, 83, 162);
    background: linear-gradient(276deg, rgba(54, 83, 162, 1) 10%,
            rgba(21, 184, 193, 1) 100%);
}

section {
    display: grid;
    grid-template-columns: 2% 1fr 2fr 2fr 1fr 2%;
    grid-template-rows: 250px 400px;
}

.info {
    font-family: "Rogueland Free";
    grid-column: 3/4;
    grid-row: 2/3;
    font-size: 270%;
    border-right: 4px solid black;
    height: 90%;
    margin: 15px;
    margin-left: 50px;
}

.product {
    grid-column: 4/5;
    grid-row: 2/3;
    justify-self: center;
}

.link {
    font-family: "Urusans Personal Use";
    font-size: 250%;
    grid-column: 2/4;
    grid-row: 1/2;
    justify-self: center;
    margin: 20px;
    border-bottom: 3px solid black;
    margin-bottom: 180px;
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

a:hover {
    color: white;
}

.shop {
    display: grid;
    margin: 80px;
    grid-template-columns: 240px 240px 240px 240px;
    grid-gap: 40px;
}

a {
    color: black;
    text-decoration: none;
}


li {
    list-style: none;
}

li img {
    width: 100%;
}

li h1 {
    font-family: "Rogueland Free";
}

li p {
    font-family: "Scratch Boys Demo";
    font-size: 125%;
}

.size {
    font-size: 150%;
    margin: 100px;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 40px;
}

p {
    grid-column: 1/3;
    grid-row: 2/3;
    font-family: "Scratch Boys Demo";
}
.info2 {
    margin:60px; 
    font-size: 200%;
}
