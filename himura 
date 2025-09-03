<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Himura Drop Shipping - Jumia Partner</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        :root {
            --primary: #ff9900;
            --secondary: #ff6600;
            --dark: #333;
            --light: #f8f8f8;
        }
        body {
            background-color: #f9f9f9;
            color: var(--dark);
            line-height: 1.6;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        /* Header */
        header {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            padding: 20px 0;
            color: white;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo {
            display: flex;
            align-items: center;
            gap: 10px;
        }
        .logo-text {
            font-size: 24px;
            font-weight: 800;
            color: white;
        }
        .logo span {
            color: black;
        }
        nav ul {
            display: flex;
            list-style: none;
            gap: 30px;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s ease;
        }
        nav a:hover {
            color: black;
        }
        .mobile-menu-btn {
            display: none;
            background: none;
            border: none;
            color: white;
            font-size: 24px;
            cursor: pointer;
        }
        /* Hero Section */
        .hero {
            padding: 80px 0;
            background: url('https://images.unsplash.com/photo-1607082350899-7e105aa886ae?ixlib=rb-4.0.3&auto=format&fit=crop&w=1920&q=80') no-repeat center center/cover;
            color: white;
            text-align: center;
            position: relative;
        }
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.6);
        }
        .hero-content {
            position: relative;
            z-index: 1;
            max-width: 800px;
            margin: 0 auto;
        }
        .hero h1 {
            font-size: 48px;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
        .hero p {
            font-size: 20px;
            margin-bottom: 30px;
        }
        .btn {
            display: inline-block;
            background: var(--primary);
            color: white;
            padding: 15px 30px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 700;
            font-size: 18px;
            transition: all 0.3s ease;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
        }
        .btn:hover {
            background: var(--secondary);
            transform: translateY(-3px);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.3);
        }
        /* Features */
        .features {
            padding: 80px 0;
            background: white;
        }
        .section-title {
            text-align: center;
            margin-bottom: 50px;
            font-size: 36px;
            color: var(--dark);
            position: relative;
        }
        .section-title::after {
            content: '';
            display: block;
            width: 80px;
            height: 5px;
            background: var(--primary);
            margin: 15px auto;
            border-radius: 5px;
        }
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }
        .feature-card {
            background: var(--light);
            padding: 30px;
            border-radius: 15px;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: all 0.3s ease;
        }
        .feature-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
        }
        .feature-icon {
            font-size: 50px;
            color: var(--primary);
            margin-bottom: 20px;
        }
        .feature-card h3 {
            margin-bottom: 15px;
            font-size: 22px;
        }
        /* Products */
        .products {
            padding: 80px 0;
            background: #f2f2f2;
        }
        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }
        .product-card {
            background: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: all 0.3s ease;
        }
        .product-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
        }
        .product-img {
            height: 200px;
            background: var(--light);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 60px;
            color: var(--primary);
        }
        .product-content {
            padding: 20px;
            text-align: center;
        }
        .product-content h3 {
            margin-bottom: 10px;
        }
        /* How It Works */
        .how-it-works {
            padding: 80px 0;
            background: white;
        }
        .steps {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            margin-top: 50px;
        }
        .step {
            flex: 1;
            min-width: 250px;
            text-align: center;
            padding: 30px;
            background: var(--light);
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        }
        .step-number {
            display: inline-block;
            width: 50px;
            height: 50px;
            background: var(--primary);
            color: white;
            border-radius: 50%;
            line-height: 50px;
            font-size: 24px;
            font-weight: 700;
            margin-bottom: 20px;
        }
        /* Contact */
        .contact {
            padding: 80px 0;
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
        }
        .contact-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 50px;
        }
        .contact-info {
            text-align: center;
        }
        .contact-info h3 {
            margin-bottom: 20px;
            font-size: 28px;
        }
        .contact-detail {
            margin: 20px 0;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 15px;
        }
        .contact-icon {
            font-size: 30px;
        }
        .contact-form {
            background: white;
            padding: 30px;
            border-radius: 15px;
            color: var(--dark);
        }
        .form-group {
            margin-bottom: 20px;
        }
        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 600;
        }
        .form-control {
            width: 100%;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 8px;
            font-size: 16px;
        }
        textarea.form-control {
            min-height: 150px;
            resize: vertical;
        }
        /* Footer */
        footer {
            background: var(--dark);
            color: white;
            padding: 50px 0 20px;
            text-align: center;
        }
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-bottom: 30px;
        }
        .footer-section h3 {
            margin-bottom: 20px;
            font-size: 22px;
            color: var(--primary);
        }
        .social-icons {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin: 20px 0;
        }
        .social-icon {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 40px;
            height: 40px;
            background: var(--primary);
            color: white;
            border-radius: 50%;
            font-size: 20px;
            text-decoration: none;
            transition: all 0.3s ease;
        }
        .social-icon:hover {
            background: white;
            color: var(--primary);
            transform: translateY(-5px);
        }
        .copyright {
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
        }
        /* Responsive */
        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                text-align: center;
                gap: 20px;
            }
            nav ul {
                flex-direction: column;
                gap: 15px;
            }
            .hero h1 {
                font-size: 36px;
            }
            .hero p {
                font-size: 18px;
            }
            .mobile-menu-btn {
                display: block;
                position: absolute;
                top: 20px;
                right: 20px;
            }
            nav {
                display: none;
                width: 100%;
                margin-top: 20px;
            }
            nav.active {
                display: block;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <div class="header-content">
                <div class="logo">
                    <i class="fas fa-box-open fa-2x"></i>
                    <div class="logo-text">Himura <span>Drop Shipping</span></div>
                </div>
                <button class="mobile-menu-btn">
                    <i class="fas fa-bars"></i>
                </button>
                <nav id="nav">
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#features">Features</a></li>
                        <li><a href="#products">Products</a></li>
                        <li><a href="#how-it-works">How It Works</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="container">
            <div class="hero-content">
                <h1>Jumia Products Delivered to Your Doorstep at BIP</h1>
                <p>Free delivery on campus • Pay when you receive your order</p>
                <a href="#contact" class="btn">Order Now</a>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="features" id="features">
        <div class="container">
            <h2 class="section-title">Why Choose Us</h2>
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-truck"></i>
                    </div>
                    <h3>Free Delivery</h3>
                    <p>We deliver directly to your hostel or classroom at no extra cost</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-money-bill-wave"></i>
                    </div>
                    <h3>Pay on Delivery</h3>
                    <p>Only pay when you receive and verify your order</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-shield-alt"></i>
                    </div>
                    <h3>Secure Payment</h3>
                    <p>Your money is safe with our secure payment system</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-headset"></i>
                    </div>
                    <h3>24/7 Support</h3>
                    <p>We're always available to answer your questions</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section class="products" id="products">
        <div class="container">
            <h2 class="section-title">Popular Products</h2>
            <div class="products-grid">
                <div class="product-card">
                    <div class="product-img">
                        <i class="fas fa-mobile-alt"></i>
                    </div>
                    <div class="product-content">
                        <h3>Phones & Tablets</h3>
                        <p>Latest smartphones and tablets at great prices</p>
                    </div>
                </div>
                <div class="product-card">
                    <div class="product-img">
                        <i class="fas fa-laptop"></i>
                    </div>
                    <div class="product-content">
                        <h3>Computers</h3>
                        <p>Laptops, accessories and computing devices</p>
                    </div>
                </div>
                <div class="product-card">
                    <div class="product-img">
                        <i class="fas fa-tshirt"></i>
                    </div>
                    <div class="product-content">
                        <h3>Fashion</h3>
                        <p>Clothing, shoes and accessories</p>
                    </div>
                </div>
                <div class="product-card">
                    <div class="product-img">
                        <i class="fas fa-home"></i>
                    </div>
                    <div class="product-content">
                        <h3>Home Goods</h3>
                        <p>Everything you need for your room</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- How It Works Section -->
    <section class="how-it-works" id="how-it-works">
        <div class="container">
            <h2 class="section-title">How It Works</h2>
            <div class="steps">
                <div class="step">
                    <div class="step-number">1</div>
                    <h3>Browse Jumia</h3>
                    <p>Find products you want on Jumia and note the details</p>
                </div>
                <div class="step">
                    <div class="step-number">2</div>
                    <h3>Contact Us</h3>
                    <p>Send us the product details and your delivery location</p>
                </div>
                <div class="step">
                    <div class="step-number">3</div>
                    <h3>We Order</h3>
                    <p>We place the order on your behalf using our Jumia account</p>
                </div>
                <div class="step">
                    <div class="step-number">4</div>
                    <h3>Receive & Pay</h3>
                    <p>We deliver to you on campus and you pay upon receipt</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <div class="container">
            <h2 class="section-title" style="color: white;">Contact Us</h2>
            <div class="contact-grid">
                <div class="contact-info">
                    <h3>Get In Touch</h3>
                    <div class="contact-detail">
                        <div class="contact-icon">
                            <i class="fas fa-phone"></i>
                        </div>
                        <div class="contact-text">
                            <h4>Phone</h4>
                            <p>+256786306260</p>
                        </div>
                    </div>
                    <div class="contact-detail">
                        <div class="contact-icon">
                            <i class="fas fa-envelope"></i>
                        </div>
                        <div class="contact-text">
                            <h4>Email</h4>
                            <p>orders@himuradropshipping.com</p>
                        </div>
                    </div>
                    <div class="contact-detail">
                        <div class="contact-icon">
                            <i class="fas fa-map-marker-alt"></i>
                        </div>
                        <div class="contact-text">
                            <h4>Location</h4>
                            <p>Busoga International Polytechnic</p>
                        </div>
                    </div>
                </div>
                <div class="contact-form">
                    <h3>Send Order Request</h3>
                    <form id="orderForm">
                        <div class="form-group">
                            <label for="name">Your Name</label>
                            <input type="text" id="name" class="form-control" required>
                        </div>
                        <div class="form-group">
                            <label for="email">Email Address</label>
                            <input type="email" id="email" class="form-control" required>
                        </div>
                        <div class="form-group">
                            <label for="product">Product Details (Jumia Link Preferred)</label>
                            <textarea id="product" class="form-control" required></textarea>
                        </div>
                        <button type="submit" class="btn">Submit Request</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>Himura Drop Shipping</h3>
                    <p>Your trusted Jumia partner on campus. We make online shopping hassle-free for students.</p>
                </div>
                <div class="footer-section">
                    <h3>Connect With Us</h3>
                    <div class="social-icons">
                        <a href="#" class="social-icon"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="social-icon"><i class="fab fa-instagram"></i></a>
                        <a href="#" class="social-icon"><i class="fab fa-whatsapp"></i></a>
                        <a href="#" class="social-icon"><i class="fab fa-twitter"></i></a>
                    </div>
                </div>
                <div class="footer-section">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#features">Features</a></li>
                        <li><a href="#products">Products</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
            </div>
            <div class="copyright">
                <p>&copy; 2023 Himura Drop Shipping. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        const mobileMenuBtn = document.querySelector('.mobile-menu-btn');
        const nav = document.getElementById('nav');
        
        mobileMenuBtn.addEventListener('click', () => {
            nav.classList.toggle('active');
        });
        
        // Form submission
        const orderForm = document.getElementById('orderForm');
        
        orderForm.addEventListener('submit', (e) => {
            e.preventDefault();
            alert('Thank you for your order request! We will contact you shortly.');
            orderForm.reset();
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                if (targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                    
                    // Close mobile menu if open
                    nav.classList.remove('active');
                }
            });
        });
    </script>
</body>
</html>