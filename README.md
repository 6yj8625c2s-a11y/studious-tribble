<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kenneth Hoop Store</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="bg-dark text-white py-3">
        <div class="container">
            <h1 class="mb-0">Kenneth Hoop Store</h1>
            <p class="mb-0">Featuring top brands like Nike</p>
        </div>
    </header>

    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item"><a class="nav-link" href="#shoes">Shoes</a></li>
                    <li class="nav-item"><a class="nav-link" href="#balls">Balls</a></li>
                    <li class="nav-item"><a class="nav-link" href="#apparel">Apparel</a></li>
                    <li class="nav-item"><a class="nav-link" href="#accessories">Accessories</a></li>
                </ul>
                <button class="btn btn-primary ms-auto" onclick="showCart()">Cart (<span id="cart-count">0</span>)</button>
            </div>
        </div>
    </nav>

    <main class="container my-4">
        <section id="shoes" class="mb-5">
            <h2>Shoes</h2>
            <div class="row">
                <div class="col-12 col-md-6 col-lg-4">
                    <div class="card">
                        <img src="c:\Users\PC1\Downloads\AIR+ZOOM+PEGASUS+41+EK.avif" class="card-img-top" alt="Nike Air Zoom" onclick="showProductDetails('Nike Air Zoom Pegasus', 'The Nike Air Zoom Pegasus is designed for basketball players who need responsive cushioning and support. Features Zoom Air units in the forefoot for energy return, durable rubber outsole for traction, and a lightweight mesh upper for breathability. Perfect for on-court performance and all-day comfort.', 150)">
                        <div class="card-body">
                            <h5 class="card-title">Nike Air Zoom Pegasus</h5>
                            <p class="card-text">High-performance basketball shoes with Zoom Air technology for superior cushioning.</p>
                            <p class="card-text fw-bold">$150</p>
                            <button class="btn btn-success" onclick="addToCart('Nike Air Zoom Pegasus', 150)">Add to Cart</button>
                        </div>
                    </div>
                </div>
                <div class="col-12 col-md-6 col-lg-4">
                    <div class="card">
                        <img src="c:\Users\PC1\Downloads\download.webp" class="card-img-top" alt="Adidas D.O.N" onclick="showProductDetails('Adidas D.O.N Issue 7', 'The Adidas D.O.N Issue 7 delivers exceptional energy return with BOOST technology in the midsole. It features a lightweight Primeknit upper for a snug fit, Continental rubber outsole for superior grip, and innovative lacing system for customized lockdown. Ideal for explosive movements on the court.', 140)">
                        <div class="card-body">
                            <h5 class="card-title">Adidas D.O.N Issue 7</h5>
                            <p class="card-text">Energy return basketball shoes with BOOST cushioning and Primeknit upper.</p>
                            <p class="card-text fw-bold">$140</p>
                            <button class="btn btn-success" onclick="addToCart('Adidas D.O.N Issue 7', 140)">Add to Cart</button>
                        </div>
                    </div>
                </div>
                <div class="col-12 col-md-6 col-lg-4">
                    <div class="card">
                        <img src="c:\Users\PC1\Downloads\AIR+JORDAN+1+MID+(GS).avif" class="card-img-top" alt="Jordan 1" onclick="showProductDetails('Air Jordan 1 High', 'The Air Jordan 1 High is an iconic basketball sneaker that revolutionized the game. Featuring premium leather upper, Nike Air cushioning in the heel, and the legendary Wings logo. It offers durability, style, and performance for both on and off the court. A must-have for any basketball enthusiast.', 170)">
                        <div class="card-body">
                            <h5 class="card-title">Air Jordan 1 High</h5>
                            <p class="card-text">Iconic basketball sneakers with premium leather and Air cushioning.</p>
                            <p class="card-text fw-bold">$170</p>
                            <button class="btn btn-success" onclick="addToCart('Air Jordan 1 High', 170)">Add to Cart</button>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="balls" class="mb-5">
            <h2>Balls</h2>
            <div class="row">
                <div class="col-12 col-md-6 col-lg-4">
                    <div class="card">
                        <img src="c:\Users\PC1\Downloads\download (2).webp" class="card-img-top" alt="Wilson Evolution" onclick="showProductDetails('Wilson Evolution Indoor Basketball', 'The Wilson Evolution is an official size indoor basketball designed for serious play. Made with composite leather for superior grip and control, it features deep channels for better ball handling and a butyl bladder for consistent air retention. Perfect for indoor courts and professional games.', 50)">
                        <div class="card-body">
                            <h5 class="card-title">Wilson Evolution Indoor Basketball</h5>
                            <p class="card-text">Official size indoor basketball with composite leather for excellent grip.</p>
                            <p class="card-text fw-bold">$50</p>
                            <button class="btn btn-success" onclick="addToCart('Wilson Evolution Indoor Basketball', 50)">Add to Cart</button>
                        </div>
                    </div>
                </div>
                <div class="col-12 col-md-6 col-lg-4">
                    <div class="card">
                        <img src="c:\Users\PC1\Downloads\download (3).webp" class="card-img-top" alt="Spalding TF-1000" onclick="showProductDetails('Spalding TF-1000', 'The Spalding TF-1000 is a durable outdoor basketball built for tough play. Constructed with rugged composite leather, it has a deep channel design for enhanced grip and control. The ball maintains its shape and performance even in wet conditions, making it ideal for outdoor courts and recreational play.', 45)">
                        <div class="card-body">
                            <h5 class="card-title">Spalding TF-1000</h5>
                            <p class="card-text">Durable outdoor basketball with composite leather for all-weather performance.</p>
                            <p class="card-text fw-bold">$45</p>
                            <button class="btn btn-success" onclick="addToCart('Spalding TF-1000', 45)">Add to Cart</button>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="apparel" class="mb-5">
            <h2>Apparel</h2>
            <div class="row">
                <div class="col-12 col-md-6 col-lg-4">
                    <div class="card">
                        <img src="c:\Users\PC1\Downloads\LAL+MNK+DF+SWGMN+JSY+ICN+22.avif" class="card-img-top" alt="Nike Dri-FIT" onclick="showProductDetails('Nike Dri-FIT Jersey', 'The Nike Dri-FIT Jersey is engineered for maximum performance on the court. Made with moisture-wicking fabric that keeps you dry and comfortable, it features a tailored fit, breathable mesh panels, and durable construction. Available in team colors, it\'s perfect for players who demand the best in comfort and style.', 80)">
                        <div class="card-body">
                            <h5 class="card-title">Nike Dri-FIT Jersey</h5>
                            <p class="card-text">Moisture-wicking basketball jersey with breathable fabric for all-day comfort.</p>
                            <p class="card-text fw-bold">$80</p>
                            <button class="btn btn-success" onclick="addToCart('Nike Dri-FIT Jersey', 80)">Add to Cart</button>
                        </div>
                    </div>
                </div>
                <div class="col-12 col-md-6 col-lg-4">
                    <div class="card">
                        <img src="c:\Users\PC1\Downloads\OIP.webp" class="card-img-top" alt="Under Armour Shorts" onclick="showProductDetails('Under Armour Charged Shorts', 'Under Armour Charged Shorts provide superior compression and support for basketball players. Featuring Charged Cotton technology for moisture management, a compression fit to reduce muscle vibration, and a secure waistband. They offer comfort during intense workouts and games, helping you stay focused and perform at your best.', 40)">
                        <div class="card-body">
                            <h5 class="card-title">Under Armour Charged Shorts</h5>
                            <p class="card-text">Compression basketball shorts with moisture-wicking technology.</p>
                            <p class="card-text fw-bold">$40</p>
                            <button class="btn btn-success" onclick="addToCart('Under Armour Charged Shorts', 40)">Add to Cart</button>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="accessories" class="mb-5">
            <h2>Accessories</h2>
            <div class="row">
                <div class="col-12 col-md-6 col-lg-4">
                    <div class="card">
                        <img src="c:\Users\PC1\Downloads\download (4).webp" class="card-img-top" alt="Spalding Hoop" onclick="showProductDetails('Spalding Portable Hoop', 'The Spalding Portable Hoop is a versatile basketball system for home or outdoor use. Features adjustable height from 7.5 to 10 feet, a breakaway rim for safety, and a sturdy base that fills with sand or water for stability. Easy to assemble and move, it\'s perfect for practice sessions and recreational play.', 200)">
                        <div class="card-body">
                            <h5 class="card-title">Spalding Portable Hoop</h5>
                            <p class="card-text">Adjustable height basketball hoop with breakaway rim and stable base.</p>
                            <p class="card-text fw-bold">$200</p>
                            <button class="btn btn-success" onclick="addToCart('Spalding Portable Hoop', 200)">Add to Cart</button>
                        </div>
                    </div>
                </div>
                <div class="col-12 col-md-6 col-lg-4">
                    <div class="card">
                        <img src="c:\Users\PC1\Downloads\R.jfif" class="card-img-top" alt="Nike Arm Sleeve" onclick="showProductDetails('Nike Compression Arm Sleeve', 'The Nike Compression Arm Sleeve provides targeted support and protection for basketball players. Made with breathable, moisture-wicking fabric, it offers compression to reduce muscle fatigue, improve circulation, and prevent injuries. Lightweight and comfortable, it\'s essential gear for serious athletes.', 25)">
                        <div class="card-body">
                            <h5 class="card-title">Nike Compression Arm Sleeve</h5>
                            <p class="card-text">Protective arm sleeve with compression technology for injury prevention.</p>
                            <p class="card-text fw-bold">$25</p>
                            <button class="btn btn-success" onclick="addToCart('Nike Compression Arm Sleeve', 25)">Add to Cart</button>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <div id="cart-modal" class="modal" style="display: none;">
        <div class="modal-content">
            <span class="close" onclick="closeCart()">&times;</span>
            <h2>Your Cart</h2>
            <ul id="cart-items" class="list-group mb-3"></ul>
            <p>Total: $<span id="cart-total">0</span></p>
            <button class="btn btn-primary" onclick="checkout()">Checkout</button>
        </div>
    </div>

    <div id="product-modal" class="modal" style="display: none;">
        <div class="modal-content">
            <span class="close" onclick="closeProductModal()">&times;</span>
            <h2 id="product-title"></h2>
            <p id="product-description"></p>
            <p class="fw-bold">Price: $<span id="product-price"></span></p>
            <button class="btn btn-success" onclick="addFromModal()">Add to Cart</button>
        </div>
    </div>

    <footer class="bg-dark text-white py-3 mt-5">
        <div class="container text-center">
            <p>&copy; 2026 Basketball Equipment Store. All rights reserved.</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script src="script.js"></script>
</body>
</html>
