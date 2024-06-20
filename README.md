# Prasunet_WD_1
Task 1:Responsive Landing Page Using Html Code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Starbucks</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <figure class="logo">
            <img src="images/logo.png" alt="">
        </figure>
        <nav class="main-nav">
            <ul>
                <li><a href="#">Menu</a></li>
                <li><a href="#">Coffee</a></li>
                <li><a href="#">About</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="carousel next">
            <div class="list">
                <article class="item other_1">
                    <div class="main-content" style="background-color: #9c4d24;">
                        <div class="content">
                            <h2>Caffe Latte, a new product</h2>
                            <p class="price">Rs. 250</p>
                            <p class="description">
                                Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores labore animi voluptatibus sequi illo, earum molestias explicabo officiis iste neque? Quis quod eligendi fugit, dolore nam itaque modi exercitationem voluptatem corrupti aut aspernatur. Quos non in sed ratione tenetur harum.
                            </p>
                            <button class="cart">
                                Add To Cart
                            </button>
                        </div>
                    </div>
                    <figure class="image">
                        <img src="images/1.png" alt="">
                        <figcaption>Caffe Latte, a new prodduct</figcaption>
                    </figure>
                </article>

                <article class="item active">
                    <div class="main-content" style="background-color: #f5bfaf;">
                        <div class="content">
                            <h2>Straberry mocha, a new product</h2>
                            <p class="price">Rs. 250</p>
                            <p class="description">
                                Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores labore animi voluptatibus sequi illo, earum molestias explicabo officiis iste neque? Quis quod eligendi fugit, dolore nam itaque modi exercitationem voluptatem corrupti aut aspernatur. Quos non in sed ratione tenetur harum.
                            </p>
                            <button class="cart">
                                Add To Cart
                            </button>
                        </div>
                    </div>
                    <figure class="image">
                        <img src="images/2.png" alt="">
                        <figcaption>Straberry mocha, a new prodduct</figcaption>
                    </figure>
                </article>

                <article class="item other_2">
                    <div class="main-content" style="background-color: #dedfe1;">
                        <div class="content">
                            <h2>Doppio espresso, a new product</h2>
                            <p class="price">Rs. 250</p>
                            <p class="description">
                                Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores labore animi voluptatibus sequi illo, earum molestias explicabo officiis iste neque? Quis quod eligendi fugit, dolore nam itaque modi exercitationem voluptatem corrupti aut aspernatur. Quos non in sed ratione tenetur harum.
                            </p>
                            <button class="cart">
                                Add To Cart
                            </button>
                        </div>
                    </div>
                    <figure class="image">
                        <img src="images/3.png" alt="">
                        <figcaption>Doppio espresso, a new prodduct</figcaption>
                    </figure>
                </article>

                <article class="item">
                    <div class="main-content" style="background-color: #7eb63d;">
                        <div class="content">
                            <h2> Matcha latte macchiato, a new product</h2>
                            <p class="price">Rs. 250</p>
                            <p class="description">
                                Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores labore animi voluptatibus sequi illo, earum molestias explicabo officiis iste neque? Quis quod eligendi fugit, dolore nam itaque modi exercitationem voluptatem corrupti aut aspernatur. Quos non in sed ratione tenetur harum.
                            </p>
                            <button class="cart">
                                Add To Cart
                            </button>
                        </div>
                    </div>
                    <figure class="image">
                        <img src="images/4.png" alt="">
                        <figcaption>Matcha latte macchiato, a new prodduct</figcaption>
                    </figure>
                </article>
            </div>
            <div class="arrows">
                <button id="prev"><</button>
                <button id="next">></button>
            </div>
        </section>
    </main>

    <div class="section">
        <div class="categories">
            <h2>Handcrafted Curations</h2>
                <div class="variety">
                    <div class="items">
                        <img src="images/Bestseller.jpg" alt="">
                        <p>Bestseller</p>
                    </div>
                    <div class="items">
                        <img src="images/Drinks.jpg" alt="">
                        <p>Drinks</p>
                    </div>
                    <div class="items">
                        <img src="images/Food.jpg" alt="">
                        <p>Food</p>
                    </div>
                    <div class="items">
                        <img src="images/Merchandise.jpg" alt="">
                        <p>Merchandise</p>
                    </div>
                    <div class="items">
                        <img src="images/CoffeeAtHome.jpg" alt="">
                        <p>CoffeeAtHome</p>
                    </div>
                    <div class="items">
                        <img src="images/ReadyToEat.jpg" alt="">
                        <p>ReadyToEat</p>
                    </div>
                </div>
        </div>
    </div>

    <div class="recommends">
        <h2>Barista Recommends</h2>
        <div class="cards">
           <div class="card">
            <img src="images/starbucks1.jpg" alt="">
                <p>Rs 283.<span>50</span></p>
                <p class="name">Cappuccino</p>
                <button>Add Item</button>
           </div>
           <div class="card">
            <img src="images/starbucks2.jpg" alt="">
                <p>Rs 299.<span>25</span></p>
                <p class="name">Cold Brew Black</p>
                <button>Add Item</button>
           </div>
           <div class="card">
            <img src="images/starbucks3.jpg" alt="">
                <p>Rs 294.<span>00</span></p>
                <p class="name">Hot Chocolate</p>
                <button>Add Item</button>
           </div>
           <div class="card">
            <img src="images/starbucks4.jpg" alt="">
                <p>Rs 367.<span>50</span></p>
                <p class="name">Vanilla Milkshake</p>
                <button>Add Item</button>
           </div>
           <div class="card">
            <img src="images/starbucks1.jpg" alt="">
                <p>Rs 267.<span>50</span></p>
                <p class="name">Frappuccino</p>
                <button>Add Item</button>
           </div>
           <div class="card">
            <img src="images/starbucks1.jpg" alt="">
                <p>Rs 283.<span>50</span></p>
                <p class="name">Straberry Moccha</p>
                <button>Add Item</button>
           </div>
        </div>
    </div>
<script src="app.js"></script>
</body>
</html>
