<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Phone Spot by Niazi Enterprises - Your Premium Mobile Destination</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #2563eb;
            --secondary: #1e40af;
            --accent: #f59e0b;
            --light: #f8fafc;
            --dark: #1e293b;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            scroll-behavior: smooth;
        }
        
        .hero-gradient {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
        }
        
        .product-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .product-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.15);
        }
        
        .contact-info-card {
            background: linear-gradient(145deg, #ffffff 0%, #f1f5f9 100%);
            border-left: 4px solid var(--accent);
        }
        
        .feature-icon {
            width: 60px;
            height: 60px;
            background: var(--primary);
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 1rem;
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Header -->
    <header class="bg-white shadow-lg sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-4">
            <div class="flex justify-between items-center">
                <div class="flex items-center">
                    <div class="w-12 h-12 bg-blue-600 rounded-lg flex items-center justify-center mr-3">
                        <i class="fas fa-mobile-alt text-white text-2xl"></i>
                    </div>
                    <div>
                        <h1 class="text-xl font-bold text-gray-800">Phone Spot</h1>
                        <p class="text-sm text-gray-600">by Niazi Enterprises</p>
                    </div>
                </div>
                
                <div class="hidden md:flex space-x-8">
                    <a href="#home" class="text-gray-700 hover:text-blue-600 font-medium">Home</a>
                    <a href="#products" class="text-gray-700 hover:text-blue-600 font-medium">Products</a>
                    <a href="#services" class="text-gray-700 hover:text-blue-600 font-medium">Services</a>
                    <a href="#about" class="text-gray-700 hover:text-blue-600 font-medium">About</a>
                    <a href="#contact" class="text-gray-700 hover:text-blue-600 font-medium">Contact</a>
                </div>
                
                <div class="md:hidden">
                    <button id="menu-btn" class="text-gray-700">
                        <i class="fas fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
            
            <!-- Mobile Menu -->
            <div id="mobile-menu" class="hidden md:hidden mt-4 pb-4">
                <div class="flex flex-col space-y-3">
                    <a href="#home" class="text-gray-700 hover:text-blue-600 font-medium py-2">Home</a>
                    <a href="#products" class="text-gray-700 hover:text-blue-600 font-medium py-2">Products</a>
                    <a href="#services" class="text-gray-700 hover:text-blue-600 font-medium py-2">Services</a>
                    <a href="#about" class="text-gray-700 hover:text-blue-600 font-medium py-2">About</a>
                    <a href="#contact" class="text-gray-700 hover:text-blue-600 font-medium py-2">Contact</a>
                </div>
            </div>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero-gradient text-white py-20">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <h2 class="text-4xl md:text-5xl font-bold mb-6 leading-tight">
                        Your Premium Destination for Mobile Excellence
                    </h2>
                    <p class="text-xl mb-8 text-blue-100">
                        Discover the latest smartphones, accessories, and expert repair services at Phone Spot. Excellence in mobile technology since 2010.
                    </p>
                    <div class="flex flex-col sm:flex-row gap-4">
                        <a href="#products" class="bg-white text-blue-600 px-8 py-3 rounded-lg font-semibold hover:bg-gray-100 transition-colors text-center">
                            Explore Products
                        </a>
                        <a href="#contact" class="border-2 border-white text-white px-8 py-3 rounded-lg font-semibold hover:bg-white hover:text-blue-600 transition-colors text-center">
                            Contact Us
                        </a>
                    </div>
                </div>
                <div class="md:w-1/2 flex justify-center">
                    <div class="relative">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/25a81f11-e300-42c8-acc0-e9663d10e37d.png" alt="Modern smartphone display with colorful apps and sleek design against dark background" class="rounded-xl shadow-2xl">
                        <div class="absolute -bottom-4 -right-4 bg-white p-4 rounded-lg shadow-lg">
                            <div class="text-center">
                                <p class="text-sm text-gray-600">Featured</p>
                                <p class="font-bold text-blue-600">Latest iPhone & Samsung</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Why Choose Phone Spot?</h2>
                <p class="text-lg text-gray-600 max-w-2xl mx-auto">
                    We provide exceptional service and quality products that make us stand out in the mobile industry
                </p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <div class="text-center p-6">
                    <div class="feature-icon mx-auto">
                        <i class="fas fa-shield-alt text-white text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Genuine Products</h3>
                    <p class="text-gray-600">100% authentic smartphones and accessories with warranty coverage</p>
                </div>
                
                <div class="text-center p-6">
                    <div class="feature-icon mx-auto">
                        <i class="fas fa-tools text-white text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Expert Repairs</h3>
                    <p class="text-gray-600">Professional technicians for all your mobile repair needs</p>
                </div>
                
                <div class="text-center p-6">
                    <div class="feature-icon mx-auto">
                        <i class="fas fa-headset text-white text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">24/7 Support</h3>
                    <p class="text-gray-600">Round-the-clock customer service and technical support</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="py-16 bg-gray-50">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Featured Products</h2>
                <p class="text-lg text-gray-600">Discover our latest collection of premium smartphones</p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Product 1 -->
                <div class="product-card bg-white rounded-xl p-6 shadow-md">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/f238ce7c-9aa1-4983-ad11-e85263687e63.png" alt="Samsung Galaxy S23 Ultra with premium black finish and stylus pen" class="w-full h-48 object-contain mb-4">
                    <h3 class="text-xl font-semibold mb-2">Samsung Galaxy S23 Ultra</h3>
                    <p class="text-gray-600 mb-4">Flagship performance with advanced camera system</p>
                    <div class="flex justify-between items-center">
                        <span class="text-2xl font-bold text-blue-600">Rs. 199,999</span>
                        <button class="bg-blue-600 text-white px-4 py-2 rounded-lg hover:bg-blue-700">
                            View Details
                        </button>
                    </div>
                </div>
                
                <!-- Product 2 -->
                <div class="product-card bg-white rounded-xl p-6 shadow-md">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/5cd6ee21-1a56-403c-929c-cc02e68bfde7.png" alt="iPhone 14 Pro Max in deep purple color with dynamic island display" class="w-full h-48 object-contain mb-4">
                    <h3 class="text-xl font-semibold mb-2">iPhone 14 Pro Max</h3>
                    <p class="text-gray-600 mb-4">Pro camera system with cinematic mode</p>
                    <div class="flex justify-between items-center">
                        <span class="text-2xl font-bold text-blue-600">Rs. 219,999</span>
                        <button class="bg-blue-600 text-white px-4 py-2 rounded-lg hover:bg-blue-700">
                            View Details
                        </button>
                    </div>
                </div>
                
                <!-- Product 3 -->
                <div class="product-card bg-white rounded-xl p-6 shadow-md">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/df60cef4-9881-4752-9958-e176bd092450.png" alt="Google Pixel 7 Pro with sleek aluminum frame and advanced camera bar" class="w-full h-48 object-contain mb-4">
                    <h3 class="text-xl font-semibold mb-2">Google Pixel 7 Pro</h3>
                    <p class="text-gray-600 mb-4">Pure Android experience with AI features</p>
                    <div class="flex justify-between items-center">
                        <span class="text-2xl font-bold text-blue-600">Rs. 149,999</span>
                        <button class="bg-blue-600 text-white px-4 py-2 rounded-lg hover:bg-blue-700">
                            View Details
                        </button>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <a href="#contact" class="bg-blue-600 text-white px-8 py-3 rounded-lg font-semibold hover:bg-blue-700 transition-colors inline-block">
                    View All Products
                </a>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Our Services</h2>
                <p class="text-lg text-gray-600">Comprehensive mobile solutions for all your needs</p>
            </div>
            
            <div class="grid md:grid-cols-2 gap-8">
                <div class="p-8 bg-gray-50 rounded-xl">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-blue-600 rounded-lg flex items-center justify-center mr-4">
                            <i class="fas fa-mobile text-white text-xl"></i>
                        </div>
                        <h3 class="text-xl font-semibold">Screen Replacement</h3>
                    </div>
                    <p class="text-gray-600">Quick and professional screen replacement for all major brands with warranty</p>
                </div>
                
                <div class="p-8 bg-gray-50 rounded-xl">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-blue-600 rounded-lg flex items-center justify-center mr-4">
                            <i class="fas fa-battery-full text-white text-xl"></i>
                        </div>
                        <h3 class="text-xl font-semibold">Battery Replacement</h3>
                    </div>
                    <p class="text-gray-600">Genuine battery replacements to restore your phone's original performance</p>
                </div>
                
                <div class="p-8 bg-gray-50 rounded-xl">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-blue-600 rounded-lg flex items-center justify-center mr-4">
                            <i class="fas fa-unlock text-white text-xl"></i>
                        </div>
                        <h3 class="text-xl font-semibold">Software Solutions</h3>
                    </div>
                    <p class="text-gray-600">Operating system updates, unlocking, and software troubleshooting</p>
                </div>
                
                <div class="p-8 bg-gray-50 rounded-xl">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 bg-blue-600 rounded-lg flex items-center justify-center mr-4">
                            <i class="fas fa-shopping-cart text-white text-xl"></i>
                        </div>
                        <h3 class="text-xl font-semibold">Accessories</h3>
                    </div>
                    <p class="text-gray-600">Premium cases, screen protectors, chargers, and other accessories</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 bg-gray-50">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/a0571334-fde1-4908-8a2d-7e03b5879f0f.png" alt="Modern phone store interior with glass displays and well-lit showcase of smartphones" class="rounded-xl shadow-lg">
                </div>
                <div class="md:w-1/2 md:pl-12">
                    <h2 class="text-3xl font-bold text-gray-800 mb-6">About Phone Spot</h2>
                    <p class="text-lg text-gray-600 mb-6">
                        Established in 2010, Phone Spot by Niazi Enterprises has been serving the Gouri Town community with quality mobile products and exceptional service. We take pride in being your trusted partner for all mobile needs.
                    </p>
                    <p class="text-lg text-gray-600 mb-8">
                        Our team of certified technicians and sales professionals are dedicated to providing you with the best mobile experience, from purchase to after-sales support.
                    </p>
                    <div class="grid grid-cols-2 gap-4">
                        <div class="text-center p-4 bg-white rounded-lg shadow-sm">
                            <div class="text-3xl font-bold text-blue-600">13+</div>
                            <div class="text-sm text-gray-600">Years Experience</div>
                        </div>
                        <div class="text-center p-4 bg-white rounded-lg shadow-sm">
                            <div class="text-3xl font-bold text-blue-600">5000+</div>
                            <div class="text-sm text-gray-600">Happy Customers</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Get In Touch</h2>
                <p class="text-lg text-gray-600">We're here to help with all your mobile needs</p>
            </div>
            
            <div class="grid md:grid-cols-2 gap-12">
                <div>
                    <div class="contact-info-card p-8 rounded-xl mb-8">
                        <h3 class="text-xl font-semibold mb-4">Store Information</h3>
                        <div class="space-y-4">
                            <div class="flex items-center">
                                <div class="w-10 h-10 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                                    <i class="fas fa-map-marker-alt text-blue-600"></i>
                                </div>
                                <div>
                                    <p class="font-medium">Address</p>
                                    <p class="text-gray-600">Gouri Town, Islamabad, Pakistan</p>
                                </div>
                            </div>
                            
                            <div class="flex items-center">
                                <div class="w-10 h-10 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                                    <i class="fas fa-phone-alt text-blue-600"></i>
                                </div>
                                <div>
                                    <p class="font-medium">Phone</p>
                                    <p class="text-gray-600">0304-5127690</p>
                                </div>
                            </div>
                            
                            <div class="flex items-center">
                                <div class="w-10 h-10 bg-blue-100 rounded-full flex items-center justify-center mr-4">
                                    <i class="fas fa-clock text-blue-600"></i>
                                </div>
                                <div>
                                    <p class="font-medium">Business Hours</p>
                                    <p class="text-gray-600">Mon-Sat: 10:00 AM - 8:00 PM<br>Sun: 12:00 PM - 6:00 PM</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="bg-gray-50 p-6 rounded-xl">
                        <h3 class="text-xl font-semibold mb-4">Follow Us</h3>
                        <div class="flex space-x-4">
                            <a href="#" class="w-12 h-12 bg-blue-600 rounded-full flex items-center justify-center text-white hover:bg-blue-700">
                                <i class="fab fa-facebook-f"></i>
                            </a>
                            <a href="#" class="w-12 h-12 bg-pink-600 rounded-full flex items-center justify-center text-white hover:bg-pink-700">
                                <i class="fab fa-instagram"></i>
                            </a>
                            <a href="#" class="w-12 h-12 bg-blue-400 rounded-full flex items-center justify-center text-white hover:bg-blue-500">
                                <i class="fab fa-twitter"></i>
                            </a>
                            <a href="#" class="w-12 h-12 bg-red-600 rounded-full flex items-center justify-center text-white hover:bg-red-700">
                                <i class="fab fa-youtube"></i>
                            </a>
                        </div>
                    </div>
                </div>
                
                <div class="bg-gray-50 p-8 rounded-xl">
                    <h3 class="text-xl font-semibold mb-6">Send us a Message</h3>
                    <form class="space-y-6">
                        <div>
                            <label class="block text-gray-700 mb-2">Name</label>
                            <input type="text" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500">
                        </div>
                        <div>
                            <label class="block text-gray-700 mb-2">Email</label>
                            <input type="email" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500">
                        </div>
                        <div>
                            <label class="block text-gray-700 mb-2">Message</label>
                            <textarea rows="5" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500"></textarea>
                        </div>
                        <button type="submit" class="w-full bg-blue-600 text-white py-3 rounded-lg font-semibold hover:bg-blue-700 transition-colors">
                            Send Message
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-12">
        <div class="container mx-auto px-6">
            <div class="grid md:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-xl font-bold mb-4">Phone Spot</h3>
                    <p class="text-gray-400 mb-4">Your trusted partner for mobile solutions in Gouri Town, Islamabad.</p>
                    <p class="text-gray-400">© 2023 Niazi Enterprises. All rights reserved.</p>
                </div>
                
                <div>
                    <h4 class="font-semibold mb-4">Quick Links</h4>
                    <ul class="space-y-2">
                        <li><a href="#home" class="text-gray-400 hover:text-white">Home</a></li>
                        <li><a href="#products" class="text-gray-400 hover:text-white">Products</a></li>
                        <li><a href="#services" class="text-gray-400 hover:text-white">Services</a></li>
                        <li><a href="#about" class="text-gray-400 hover:text-white">About</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="font-semibold mb-4">Services</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white">Phone Sales</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Screen Repair</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Battery Replacement</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">Software Solutions</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="font-semibold mb-4">Contact Info</h4>
                    <p class="text-gray-400 mb-2">Gouri Town, Islamabad</p>
                    <p class="text-gray-400 mb-2">0304-5127690</p>
                    <p class="text-gray-400">Mon-Sat: 10AM-8PM</p>
                </div>
            </div>
            
            <div class="border-t border-gray-700 mt-8 pt-8 text-center">
                <p class="text-gray-400">Designed with ❤️ for the mobile community of Islamabad</p>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        document.getElementById('menu-btn').addEventListener('click', function() {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        });

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                    
                    // Close mobile menu if open
                    document.getElementById('mobile-menu').classList.add('hidden');
                }
            });
        });

        // Simple form validation
        const contactForm = document.querySelector('form');
        if (contactForm) {
            contactForm.addEventListener('submit', function(e) {
                e.preventDefault();
                alert('Thank you for your message! We will get back to you soon.');
                this.reset();
            });
        }
    </script>
</body>
</html>


## License

MIT License

Copyright (c) [2022] [Abdellatif Anaflous]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.



---

