# POOJA-ENTERPRISE
I AM CHEMICAL DEALER IN AHMEDABAD. I DEALS WITH ALL TYPES OF CHEMICAL SOLVENTS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pooja Enterprise - Chemical & Solvent Dealer</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('https://images.unsplash.com/photo-1611273130330-69405a2e3358?q=80&w=2070') no-repeat center center/cover;
        }
        .chemical-icon {
            font-size: 2.5rem;
            color: #3b82f6;
        }
        .contact-card {
            transition: transform 0.3s ease;
        }
        .contact-card:hover {
            transform: translateY(-5px);
        }
    </style>
</head>
<body class="font-sans">
    <!-- Navigation -->
    <nav class="bg-white shadow-lg sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-20 items-center">
                <div class="flex-shrink-0 flex items-center">
                    <span class="text-blue-600 font-bold text-2xl">POOJA ENTERPRISE</span>
                </div>
                <div class="hidden md:block">
                    <div class="ml-10 flex items-center space-x-8">
                        <a href="#home" class="text-gray-800 hover:text-blue-600 px-3 py-2 font-medium">Home</a>
                        <a href="#about" class="text-gray-800 hover:text-blue-600 px-3 py-2 font-medium">About</a>
                        <a href="#products" class="text-gray-800 hover:text-blue-600 px-3 py-2 font-medium">Products</a>
                        <a href="#contact" class="text-gray-800 hover:text-blue-600 px-3 py-2 font-medium">Contact</a>
                    </div>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero text-white py-32">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h1 class="text-4xl md:text-6xl font-bold mb-6">Quality Chemicals & Solvents</h1>
            <p class="text-xl md:text-2xl mb-8">Your trusted partner for premium chemical solutions since 2010</p>
            <div class="flex justify-center gap-4">
                <a href="#contact" class="bg-blue-600 hover:bg-blue-700 text-white px-8 py-3 rounded-full font-medium transition duration-300">Contact Us</a>
                <a href="tel:9624238309" class="bg-white hover:bg-gray-100 text-blue-600 px-8 py-3 rounded-full font-medium transition duration-300">Call Now</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">About Pooja Enterprise</h2>
                <div class="w-20 h-1 bg-blue-600 mx-auto"></div>
            </div>
            <div class="flex flex-col md:flex-row items-center gap-10">
                <div class="md:w-1/2">
                    <p class="text-lg text-gray-600 mb-6 leading-relaxed">
                        Pooja Enterprise, established in 2010 by Mr. Dinesh Vishnoi, has been a leading name in the chemical and solvent distribution industry. We pride ourselves on providing high-quality products with reliable service to industries across various sectors.
                    </p>
                    <p class="text-lg text-gray-600 mb-6 leading-relaxed">
                        Our mission is to deliver superior chemical solutions while maintaining the highest standards of safety, quality, and customer satisfaction. We source our products from reputed manufacturers and maintain strict quality control measures.
                    </p>
                    <div class="bg-blue-50 p-6 rounded-lg border border-blue-100">
                        <p class="text-blue-800 font-medium">
                            <i class="fas fa-star text-blue-500 mr-2"></i> 13+ Years of Industry Experience
                        </p>
                        <p class="text-blue-800 font-medium mt-2">
                            <i class="fas fa-certificate text-blue-500 mr-2"></i> Quality Certified Products
                        </p>
                        <p class="text-blue-800 font-medium mt-2">
                            <i class="fas fa-truck text-blue-500 mr-2"></i> Reliable & Timely Delivery
                        </p>
                    </div>
                </div>
                <div class="md:w-1/2">
                    <img src="https://images.unsplash.com/photo-1603380353725-f8a4d39cc41e?q=80&w=2070" alt="Chemical Industry" class="rounded-lg shadow-xl w-full h-auto">
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="py-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">Our Products</h2>
                <div class="w-20 h-1 bg-blue-600 mx-auto"></div>
                <p class="text-lg text-gray-600 max-w-2xl mx-auto mt-4">We provide a wide range of high-quality chemicals and solvents for various industrial applications.</p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Product 1 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden border border-gray-100 hover:shadow-lg transition duration-300">
                    <div class="p-6">
                        <div class="chemical-icon mb-4">
                            <i class="fas fa-flask"></i>
                        </div>
                        <h3 class="text-xl font-bold text-gray-800 mb-2">Industrial Solvents</h3>
                        <p class="text-gray-600">
                            High-purity solvents including acetone, methanol, isopropyl alcohol, toluene, and more for industrial applications.
                        </p>
                    </div>
                </div>
                
                <!-- Product 2 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden border border-gray-100 hover:shadow-lg transition duration-300">
                    <div class="p-6">
                        <div class="chemical-icon mb-4">
                            <i class="fas fa-fire-extinguisher"></i>
                        </div>
                        <h3 class="text-xl font-bold text-gray-800 mb-2">Specialty Chemicals</h3>
                        <p class="text-gray-600">
                            Custom chemical formulations for specific industrial needs with stringent quality specifications.
                        </p>
                    </div>
                </div>
                
                <!-- Product 3 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden border border-gray-100 hover:shadow-lg transition duration-300">
                    <div class="p-6">
                        <div class="chemical-icon mb-4">
                            <i class="fas fa-oil-can"></i>
                        </div>
                        <h3 class="text-xl font-bold text-gray-800 mb-2">Process Chemicals</h3>
                        <p class="text-gray-600">
                            Chemicals for manufacturing processes including acids, alkalis, and other processing agents.
                        </p>
                    </div>
                </div>
                
                <!-- Product 4 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden border border-gray-100 hover:shadow-lg transition duration-300">
                    <div class="p-6">
                        <div class="chemical-icon mb-4">
                            <i class="fas fa-prescription-bottle"></i>
                        </div>
                        <h3 class="text-xl font-bold text-gray-800 mb-2">Laboratory Reagents</h3>
                        <p class="text-gray-600">
                            Analytical and laboratory grade chemicals for research, testing, and quality control applications.
                        </p>
                    </div>
                </div>
                
                <!-- Product 5 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden border border-gray-100 hover:shadow-lg transition duration-300">
                    <div class="p-6">
                        <div class="chemical-icon mb-4">
                            <i class="fas fa-water"></i>
                        </div>
                        <h3 class="text-xl font-bold text-gray-800 mb-2">Water Treatment Chemicals</h3>
                        <p class="text-gray-600">
                            Coagulants, flocculants, biocides, and other chemicals for industrial and municipal water treatment.
                        </p>
                    </div>
                </div>
                
                <!-- Product 6 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden border border-gray-100 hover:shadow-lg transition duration-300">
                    <div class="p-6">
                        <div class="chemical-icon mb-4">
                            <i class="fas fa-industry"></i>
                        </div>
                        <h3 class="text-xl font-bold text-gray-800 mb-2">Bulk Chemicals</h3>
                        <p class="text-gray-600">
                            Cost-effective bulk quantities of standard chemicals for large-scale industrial applications.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">Contact Us</h2>
                <div class="w-20 h-1 bg-blue-600 mx-auto"></div>
                <p class="text-lg text-gray-600 max-w-2xl mx-auto mt-4">Get in touch with us for quality chemical solutions. We're here to help with your requirements.</p>
            </div>
            
            <div class="grid md:grid-cols-2 gap-8">
                <div>
                    <form class="space-y-6">
                        <div>
                            <label for="name" class="block text-sm font-medium text-gray-700 mb-1">Name</label>
                            <input type="text" id="name" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-blue-500" placeholder="Your name">
                        </div>
                        <div>
                            <label for="email" class="block text-sm font-medium text-gray-700 mb-1">Email</label>
                            <input type="email" id="email" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-blue-500" placeholder="Your email">
                        </div>
                        <div>
                            <label for="phone" class="block text-sm font-medium text-gray-700 mb-1">Phone</label>
                            <input type="tel" id="phone" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-blue-500" placeholder="Your phone number">
                        </div>
                        <div>
                            <label for="message" class="block text-sm font-medium text-gray-700 mb-1">Message</label>
                            <textarea id="message" rows="4" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-blue-500" placeholder="Your message"></textarea>
                        </div>
                        <button type="submit" class="bg-blue-600 hover:bg-blue-700 text-white px-6 py-3 rounded-md font-medium transition duration-300 w-full">Send Message</button>
                    </form>
                </div>
                
                <div>
                    <div class="bg-white p-8 rounded-lg shadow-md h-full space-y-6">
                        <div class="contact-card bg-blue-50 p-6 rounded-lg">
                            <div class="flex items-start">
                                <div class="bg-blue-100 p-3 rounded-full mr-4">
                                    <i class="fas fa-phone-alt text-blue-600"></i>
                                </div>
                                <div>
                                    <h3 class="text-lg font-medium text-gray-900 mb-1">Call Us</h3>
                                    <a href="tel:9624238309" class="text-gray-600 hover:text-blue-600">+91 96242 38309</a><br>
                                    <a href="tel:8000046138" class="text-gray-600 hover:text-blue-600">+91 80000 46138</a>
                                </div>
                            </div>
                        </div>
                        
                        <div class="contact-card bg-blue-50 p-6 rounded-lg">
                            <div class="flex items-start">
                                <div class="bg-blue-100 p-3 rounded-full mr-4">
                                    <i class="fas fa-envelope text-blue-600"></i>
                                </div>
                                <div>
                                    <h3 class="text-lg font-medium text-gray-900 mb-1">Email Us</h3>
                                    <a href="mailto:poojaenterprise2166@gmail.com" class="text-gray-600 hover:text-blue-600">poojaenterprise2166@gmail.com</a>
                                </div>
                            </div>
                        </div>
                        
                        <div class="contact-card bg-blue-50 p-6 rounded-lg">
                            <div class="flex items-start">
                                <div class="bg-blue-100 p-3 rounded-full mr-4">
                                    <i class="fas fa-map-marker-alt text-blue-600"></i>
                                </div>
                                <div>
                                    <h3 class="text-lg font-medium text-gray-900 mb-1">Visit Us</h3>
                                    <p class="text-gray-600">b/3 purshottam estate near cozy hotel narol sarkhej highway<br>Narol, Ahmedabad 382405</p>
                                </div>
                            </div>
                        </div>
                        
                        <div class="contact-card bg-blue-50 p-6 rounded-lg">
                            <div class="flex items-start">
                                <div class="bg-blue-100 p-3 rounded-full mr-4">
                                    <i class="fas fa-clock text-blue-600"></i>
                                </div>
                                <div>
                                    <h3 class="text-lg font-medium text-gray-900 mb-1">Business Hours</h3>
                                    <p class="text-gray-600">
                                        Monday - Friday: 9:00 AM - 6:00 PM<br>
                                        Saturday: 9:00 AM - 2:00 PM<br>
                                        Sunday: Closed
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid md:grid-cols-3 gap-10">
                <div>
                    <h3 class="text-xl font-bold text-white mb-4">Pooja Enterprise</h3>
                    <p class="text-gray-400 mb-4">
                        Your trusted partner for premium quality chemicals and solvents for industrial applications.
                    </p>
                    <div class="flex space-x-4">
                        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-twitter"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-linkedin-in"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-instagram"></i></a>
                    </div>
                </div>
                <div>
                    <h3 class="text-lg font-semibold text-white mb-4">Quick Links</h3>
                    <ul class="space-y-2">
                        <li><a href="#home" class="text-gray-400 hover:text-white transition duration-300">Home</a></li>
                        <li><a href="#about" class="text-gray-400 hover:text-white transition duration-300">About Us</a></li>
                        <li><a href="#products" class="text-gray-400 hover:text-white transition duration-300">Products</a></li>
                        <li><a href="#contact" class="text-gray-400 hover:text-white transition duration-300">Contact</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-lg font-semibold text-white mb-4">Newsletter</h3>
                    <p class="text-gray-400 mb-4">Subscribe to our newsletter for the latest updates.</p>
                    <div class="flex">
                        <input type="email" placeholder="Your email" class="px-4 py-2 w-full rounded-l-md focus

