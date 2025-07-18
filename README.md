<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pickleball Factory - Custom Solutions & Partnerships</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#2563eb',
                        secondary: '#f97316',
                        custom: '#10b981', // 定制服务专用绿色
                        dark: '#1e293b',
                        light: '#f8fafc'
                    },
                    fontFamily: {
                        sans: ['Inter', 'system-ui', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    <style type="text/tailwindcss">
        @layer utilities {
            .text-shadow {
                text-shadow: 0 2px 4px rgba(0,0,0,0.1);
            }
            .card-hover {
                transition: transform 0.3s ease, box-shadow 0.3s ease;
            }
            .card-hover:hover {
                transform: translateY(-5px);
                box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
            }
            .highlight-badge {
                animation: pulse 2s infinite;
            }
            @keyframes pulse {
                0% {
                    box-shadow: 0 0 0 0 rgba(16, 185, 129, 0.4);
                }
                70% {
                    box-shadow: 0 0 0 10px rgba(16, 185, 129, 0);
                }
                100% {
                    box-shadow: 0 0 0 0 rgba(16, 185, 129, 0);
                }
            }
        }
    </style>
</head>
<body class="bg-gray-50 font-sans text-gray-800">
    <!-- Hero Section with Dual Focus -->
    <header class="relative bg-gradient-to-r from-primary to-blue-700 text-white py-20 md:py-32 overflow-hidden">
        <div class="absolute inset-0 opacity-10">
            <div class="absolute inset-0 bg-[url('https://picsum.photos/id/1058/1200/800')] bg-cover bg-center"></div>
        </div>
        <div class="container mx-auto px-6 relative z-10">
            <div class="max-w-3xl">
                <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold mb-6 text-shadow">
                    Pickleball Factory
                </h1>
                <p class="text-xl md:text-2xl opacity-90 mb-8">Custom solutions for brands & clubs, with opportunities for retailers, agents & distributors worldwide</p>
                
                <!-- Dual Focus Badge -->
                <div class="inline-block bg-secondary text-white px-4 py-2 rounded-full text-sm font-semibold mb-6 highlight-badge">
                    <i class="fa fa-cogs mr-2"></i> Custom Services & <i class="fa fa-handshake-o ml-2"></i> Partnership Opportunities
                </div>
                
                <div class="flex flex-wrap gap-4">
                    <a href="#customization" class="inline-block bg-custom hover:bg-custom/90 text-white font-semibold px-6 py-3 rounded-lg transition-all duration-300 shadow-lg hover:shadow-xl">
                        Explore Custom Solutions <i class="fa fa-arrow-right ml-2"></i>
                    </a>
                    <a href="#partnership" class="inline-block bg-white hover:bg-gray-100 text-primary font-semibold px-6 py-3 rounded-lg transition-all duration-300 shadow-lg hover:shadow-xl">
                        Partnership Opportunities <i class="fa fa-users ml-2"></i>
                    </a>
                </div>
            </div>
        </div>
    </header>

    <!-- Story Background Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-8 text-dark">Our Story</h2>
            
            <div class="max-w-4xl mx-auto bg-light rounded-2xl p-8 md:p-10 shadow-md border border-gray-100">
                <div class="flex flex-col md:flex-row items-center gap-8">
                    <div class="md:w-2/5">
                        <img src="https://picsum.photos/id/1040/600/800" alt="Our factory workshop with workers crafting pickleball paddles" class="rounded-xl shadow-md w-full h-auto">
                    </div>
                    <div class="md:w-3/5">
                        <p class="text-gray-700 mb-4 leading-relaxed">
                            We have been deeply involved in Pickleball Paddle customization and contract manufacturing, offering professional services to numerous renowned global brands.
                        </p>
                        <p class="text-gray-700 mb-4 leading-relaxed">
                            Our team comprises both seasoned master craftsmen and innovative young talents. We are dedicated to delivering the highest quality service.
                        </p>
                        <p class="text-gray-700 leading-relaxed">
                            From material selection to process refinement, every detail is meticulously controlled in accordance with international standards—whether it involves performance customization for professional competitions or mass production contract manufacturing for the broader market, we can precisely meet brand requirements.
                        </p>
                        <p class="text-gray-700 font-semibold mt-6">
                            With our robust production capabilities and customization expertise, we empower global brands to excel in competition and thrive in the marketplace.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section with Custom Options -->
    <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-4 text-dark">Our Pickleball Paddles</h2>
            <p class="text-center text-gray-600 max-w-2xl mx-auto mb-12">
                A wide range of high-quality paddles available for customization, distribution and retail
            </p>

            <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Product 1 -->
                <div class="bg-white rounded-xl shadow-sm overflow-hidden card-hover">
                    <div class="h-48 bg-blue-50 flex items-center justify-center">
                        <img src="https://picsum.photos/id/106/600/400" alt="Fiberglass pickleball paddle with smooth surface" class="h-36 object-contain">
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-2">
                            <h3 class="font-bold text-lg">Fiberglass Paddle</h3>
                            <span class="bg-custom/10 text-custom px-2 py-1 rounded text-xs">Customizable</span>
                        </div>
                        <p class="text-gray-600 text-sm mb-3">Durable and lightweight with excellent ball control</p>
                        <div class="text-xs text-gray-500">
                            <i class="fa fa-paint-brush mr-1"></i> Custom colors, logos & designs available
                        </div>
                    </div>
                </div>

                <!-- Product 2 -->
                <div class="bg-white rounded-xl shadow-sm overflow-hidden card-hover">
                    <div class="h-48 bg-blue-50 flex items-center justify-center">
                        <img src="https://picsum.photos/id/107/600/400" alt="Carbon Fiber pickleball paddle with textured surface" class="h-36 object-contain">
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-2">
                            <h3 class="font-bold text-lg">T300/T700/T800 Carbon Fiber</h3>
                            <span class="bg-custom/10 text-custom px-2 py-1 rounded text-xs">Customizable</span>
                        </div>
                        <p class="text-gray-600 text-sm mb-3">Cold & Thermoformed press options</p>
                        <div class="text-xs text-gray-500">
                            <i class="fa fa-paint-brush mr-1"></i> Custom colors, logos & designs available
                        </div>
                    </div>
                </div>

                <!-- Product 3 -->
                <div class="bg-white rounded-xl shadow-sm overflow-hidden card-hover">
                    <div class="h-48 bg-blue-50 flex items-center justify-center">
                        <img src="https://picsum.photos/id/108/600/400" alt="Carbon Fiber 3K/12K/18K paddle with woven pattern" class="h-36 object-contain">
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-2">
                            <h3 class="font-bold text-lg">3K 12k 18kCarbon Fiber</h3>
                            <span class="bg-custom/10 text-custom px-2 py-1 rounded text-xs">Customizable</span>
                        </div>
                        <p class="text-gray-600 text-sm mb-3">Available in cold and thermoformed varieties</p>
                        <div class="text-xs text-gray-500">
                            <i class="fa fa-paint-brush mr-1"></i> Custom colors, logos & designs available
                        </div>
                    </div>
                </div>

                <!-- Product 4 -->
                <div class="bg-white rounded-xl shadow-sm overflow-hidden card-hover">
                    <div class="h-48 bg-blue-50 flex items-center justify-center">
                        <img src="https://picsum.photos/id/109/600/400" alt="3D Carbon Fiber paddle with advanced structure" class="h-36 object-contain">
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-2">
                            <h3 class="font-bold text-lg">3D 12K/18K Carbon Fiber</h3>
                            <span class="bg-custom/10 text-custom px-2 py-1 rounded text-xs">Customizable</span>
                        </div>
                        <p class="text-gray-600 text-sm mb-3">Advanced 3D construction for optimal performance</p>
                        <div class="text-xs text-gray-500">
                            <i class="fa fa-paint-brush mr-1"></i> Custom colors, logos & designs available
                        </div>
                    </div>
                </div>

                <!-- Product 5 -->
                <div class="bg-white rounded-xl shadow-sm overflow-hidden card-hover">
                    <div class="h-48 bg-blue-50 flex items-center justify-center">
                        <img src="https://picsum.photos/id/110/600/400" alt="KEVLAR pickleball paddle with distinctive finish" class="h-36 object-contain">
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-2">
                            <h3 class="font-bold text-lg">KEVLAR Paddle</h3>
                            <span class="bg-custom/10 text-custom px-2 py-1 rounded text-xs">Customizable</span>
                        </div>
                        <p class="text-gray-600 text-sm mb-3">Cold and thermoformed press options</p>
                        <div class="text-xs text-gray-500">
                            <i class="fa fa-paint-brush mr-1"></i> Custom colors, logos & designs available
                        </div>
                    </div>
                </div>

                <!-- Product 6 -->
                <div class="bg-white rounded-xl shadow-sm overflow-hidden card-hover">
                    <div class="h-48 bg-blue-50 flex items-center justify-center">
                        <img src="https://picsum.photos/id/111/600/400" alt="Titanium pickleball paddle with premium finish" class="h-36 object-contain">
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-2">
                            <h3 class="font-bold text-lg">Titanium</h3>
                            <span class="bg-custom/10 text-custom px-2 py-1 rounded text-xs">Customizable</span>
                        </div>
                        <p class="text-gray-600 text-sm mb-3">Premium materials for professional performance</p>
                        <div class="text-xs text-gray-500">
                            <i class="fa fa-paint-brush mr-1"></i> Custom colors, logos & designs available
                        </div>
                    </div>
                </div>
            </div>

            <!-- New Inner Cores Section -->
            <div class="mt-16 bg-primary/5 rounded-xl p-8 border border-primary/10">
                <h3 class="text-2xl font-bold mb-4 text-primary">New Inner Core Options</h3>
                <p class="text-gray-600 mb-6">All core materials can be paired with custom outer designs and branding</p>
                <div class="grid md:grid-cols-2 gap-6">
                    <div class="flex items-start">
                        <div class="bg-primary/10 p-3 rounded-lg mr-4">
                            <i class="fa fa-cube text-primary"></i>
                        </div>
                        <div>
                            <h4 class="font-semibold text-lg mb-1">Foam</h4>
                            <p class="text-gray-600">Advanced foam core technology for improved feel and control</p>
                        </div>
                    </div>
                    <div class="flex items-start">
                        <div class="bg-primary/10 p-3 rounded-lg mr-4">
                            <i class="fa fa-cubes text-primary"></i>
                        </div>
                        <div>
                            <h4 class="font-semibold text-lg mb-1">Eva foam wall+pp(+PU)</h4>
                            <p class="text-gray-600">Multi-layer composite core for optimal power and durability</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Customization Section -->
    <section id="customization" class="py-20 bg-gradient-to-br from-custom/5 to-primary/5">
        <div class="container mx-auto px-6">
            <div class="max-w-3xl mx-auto text-center mb-16">
                <span class="inline-block bg-custom text-white px-4 py-1 rounded-full text-sm font-semibold mb-4">Our Specialty</span>
                <h2 class="text-3xl md:text-5xl font-bold mb-6 text-dark">Custom Solutions for Brands & Clubs</h2>
                <p class="text-xl text-gray-600">
                    Tailored pickleball paddles designed to match your brand identity or club requirements
                </p>
            </div>

            <div class="grid md:grid-cols-3 gap-8 max-w-5xl mx-auto">
                <!-- Customization Option 1 -->
                <div class="bg-white rounded-xl shadow-md p-8 card-hover border border-gray-100">
                    <div class="w-16 h-16 rounded-full bg-custom/10 flex items-center justify-center mx-auto mb-6">
                        <i class="fa fa-paint-brush text-2xl text-custom"></i>
                    </div>
                    <h3 class="text-xl font-bold text-center mb-4">Design Customization</h3>
                    <ul class="text-gray-600 space-y-2">
                        <li class="flex items-start">
                            <i class="fa fa-check text-custom mt-1 mr-2"></i>
                            <span>Custom graphics & color schemes</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa fa-check text-custom mt-1 mr-2"></i>
                            <span>Brand logo placement</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa fa-check text-custom mt-1 mr-2"></i>
                            <span>Custom handle designs</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa fa-check text-custom mt-1 mr-2"></i>
                            <span>Unique surface patterns</span>
                        </li>
                    </ul>
                </div>

                <!-- Customization Option 2 -->
                <div class="bg-white rounded-xl shadow-md p-8 card-hover border border-gray-100">
                    <div class="w-16 h-16 rounded-full bg-custom/10 flex items-center justify-center mx-auto mb-6">
                        <i class="fa fa-cogs text-2xl text-custom"></i>
                    </div>
                    <h3 class="text-xl font-bold text-center mb-4">Material Customization</h3>
                    <ul class="text-gray-600 space-y-2">
                        <li class="flex items-start">
                            <i class="fa fa-check text-custom mt-1 mr-2"></i>
                            <span>Material selection</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa fa-check text-custom mt-1 mr-2"></i>
                            <span>Core technology options</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa fa-check text-custom mt-1 mr-2"></i>
                            <span>Weight specifications</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa fa-check text-custom mt-1 mr-2"></i>
                            <span>Performance tuning</span>
                        </li>
                    </ul>
                </div>

                <!-- Customization Option 3 -->
                <div class="bg-white rounded-xl shadow-md p-8 card-hover border border-gray-100">
                    <div class="w-16 h-16 rounded-full bg-custom/10 flex items-center justify-center mx-auto mb-6">
                        <i class="fa fa-box text-2xl text-custom"></i>
                    </div>
                    <h3 class="text-xl font-bold text-center mb-4">Brand & Packaging</h3>
                    <ul class="text-gray-600 space-y-2">
                        <li class="flex items-start">
                            <i class="fa fa-check text-custom mt-1 mr-2"></i>
                            <span>Complete OEM branding</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa fa-check text-custom mt-1 mr-2"></i>
                            <span>Custom packaging design</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa fa-check text-custom mt-1 mr-2"></i>
                            <span>Private label options</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa fa-check text-custom mt-1 mr-2"></i>
                            <span>Custom labeling</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Partnership & Recruitment Section -->
    <section id="partnership" class="py-20 bg-white">
        <div class="container mx-auto px-6">
            <div class="max-w-3xl mx-auto text-center mb-16">
                <span class="inline-block bg-secondary text-white px-4 py-1 rounded-full text-sm font-semibold mb-4">Join Our Network</span>
                <h2 class="text-3xl md:text-5xl font-bold mb-6 text-dark">We Welcome Retailers, Agents & Distributors</h2>
                <p class="text-xl text-gray-600">
                    Expand your business with our high-quality pickleball products and comprehensive support
                </p>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6 max-w-6xl mx-auto">
                <!-- Partner Type 1 -->
                <div class="bg-light rounded-xl shadow-md p-8 card-hover border border-gray-100">
                    <div class="w-16 h-16 rounded-full bg-primary/10 flex items-center justify-center mx-auto mb-6">
                        <i class="fa fa-shopping-bag text-2xl text-primary"></i>
                    </div>
                    <h3 class="text-xl font-bold text-center mb-4">Retail Stores</h3>
                    <p class="text-gray-600 mb-4 text-center">
                        Stock our premium paddles to enhance your sports equipment offerings
                    </p>
                    <ul class="text-gray-600 space-y-2">
                        <li class="flex items-start">
                            <i class="fa fa-check text-primary mt-1 mr-2"></i>
                            <span>Attractive retail margins</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa fa-check text-primary mt-1 mr-2"></i>
                            <span>Point-of-sale materials</span>
                        </li>
                    </ul>
                </div>

                <!-- Partner Type 2 -->
                <div class="bg-light rounded-xl shadow-md p-8 card-hover border border-gray-100">
                    <div class="w-16 h-16 rounded-full bg-primary/10 flex items-center justify-center mx-auto mb-6">
                        <i class="fa fa-handshake-o text-2xl text-primary"></i>
                    </div>
                    <h3 class="text-xl font-bold text-center mb-4">Agents</h3>
                    <p class="text-gray-600 mb-4 text-center">
                        Represent our brand with attractive commission opportunities
                    </p>
                    <ul class="text-gray-600 space-y-2">
                        <li class="flex items-start">
                            <i class="fa fa-check text-primary mt-1 mr-2"></i>
                            <span>Lucrative commission structure</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa fa-check text-primary mt-1 mr-2"></i>
                            <span>Sales training & support</span>
                        </li>
                    </ul>
                </div>

                <!-- Partner Type 3 -->
                <div class="bg-light rounded-xl shadow-md p-8 card-hover border border-gray-100">
                    <div class="w-16 h-16 rounded-full bg-primary/10 flex items-center justify-center mx-auto mb-6">
                        <i class="fa fa-truck text-2xl text-primary"></i>
                    </div>
                    <h3 class="text-xl font-bold text-center mb-4">Distributors</h3>
                    <p class="text-gray-600 mb-4 text-center">
                        Distribute our products across your region with exclusive rights
                    </p>
                    <ul class="text-gray-600 space-y-2">
                        <li class="flex items-start">
                            <i class="fa fa-check text-primary mt-1 mr-2"></i>
                            <span>Competitive wholesale pricing</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa fa-check text-primary mt-1 mr-2"></i>
                            <span>Regional exclusivity options</span>
                        </li>
                    </ul>
                </div>

                <!-- Partner Type 4 -->
                <div class="bg-light rounded-xl shadow-md p-8 card-hover border border-gray-100">
                    <div class="w-16 h-16 rounded-full bg-primary/10 flex items-center justify-center mx-auto mb-6">
                        <i class="fa fa-cubes text-2xl text-primary"></i>
                    </div>
                    <h3 class="text-xl font-bold text-center mb-4">Wholesalers</h3>
                    <p class="text-gray-600 mb-4 text-center">
                        Purchase in bulk for redistribution to retailers in your network
                    </p>
                    <ul class="text-gray-600 space-y-2">
                        <li class="flex items-start">
                            <i class="fa fa-check text-primary mt-1 mr-2"></i>
                            <span>Bulk pricing discounts</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa fa-check text-primary mt-1 mr-2"></i>
                            <span>Flexible order quantities</span>
                        </li>
                    </ul>
                </div>
            </div>

            <div class="mt-16 text-center">
                <a href="#contact" class="inline-block bg-secondary hover:bg-secondary/90 text-white font-semibold px-8 py-3 rounded-lg transition-all duration-300 shadow-lg hover:shadow-xl">
                    Apply for Partnership <i class="fa fa-arrow-right ml-2"></i>
                </a>
            </div>
        </div>
    </section>

    <!-- Factory Advantages Section -->
    <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-4 text-dark">Why Work With Us</h2>
            <p class="text-center text-gray-600 max-w-2xl mx-auto mb-12">
                Our capabilities benefit both custom clients and distribution partners
            </p>

            <div class="grid md:grid-cols-3 gap-8">
                <!-- Advantage 1 -->
                <div class="text-center p-6 card-hover bg-white rounded-xl shadow-sm">
                    <div class="w-16 h-16 bg-primary/10 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fa fa-paint-brush text-2xl text-primary"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Custom Design Expertise</h3>
                    <p class="text-gray-600">
                        From brand identity to club colors, we create paddles that stand out in the market.
                    </p>
                </div>

                <!-- Advantage 2 -->
                <div class="text-center p-6 card-hover bg-white rounded-xl shadow-sm">
                    <div class="w-16 h-16 bg-primary/10 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fa fa-industry text-2xl text-primary"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Reliable Production</h3>
                    <p class="text-gray-600">
                        Consistent quality and on-time delivery for both custom orders and wholesale partners.
                    </p>
                </div>

                <!-- Advantage 3 -->
                <div class="text-center p-6 card-hover bg-white rounded-xl shadow-sm">
                    <div class="w-16 h-16 bg-primary/10 rounded-full flex items-center justify-center mx-auto mb-6">
                        <i class="fa fa-users text-2xl text-primary"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Partner Support</h3>
                    <p class="text-gray-600">
                        Comprehensive assistance for our partners with marketing and product knowledge.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Brands Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-12 text-dark">Our Own Brands</h2>
            
            <div class="grid md:grid-cols-2 gap-8 max-w-4xl mx-auto">
                <!-- JFPICK Brand -->
                <div class="bg-light rounded-xl shadow-md p-8 card-hover border border-gray-100">
                    <div class="flex items-center mb-6">
                        <div class="w-16 h-16 rounded-full bg-blue-100 flex items-center justify-center mr-4">
                            <i class="fa fa-table-tennis text-2xl text-primary"></i>
                        </div>
                        <h3 class="text-2xl font-bold text-primary">JFPICK</h3>
                    </div>
                    <p class="text-gray-600 mb-4">
                        Our middle and low-end brand offering quality pickleball paddles at affordable prices, perfect for beginners and recreational players.
                    </p>
                    <div class="flex flex-wrap gap-2 mb-2">
                        <span class="bg-blue-50 px-3 py-1 rounded-full text-sm">Middle & Low-end</span>
                        <span class="bg-custom/10 text-custom px-3 py-1 rounded-full text-sm"><i class="fa fa-paint-brush mr-1"></i> Customizable</span>
                    </div>
                </div>

                <!-- JOYCSPS Brand -->
                <div class="bg-light rounded-xl shadow-md p-8 card-hover border border-gray-100">
                    <div class="flex items-center mb-6">
                        <div class="w-16 h-16 rounded-full bg-orange-100 flex items-center justify-center mr-4">
                            <i class="fa fa-trophy text-2xl text-secondary"></i>
                        </div>
                        <h3 class="text-2xl font-bold text-secondary">JOYCSPS</h3>
                    </div>
                    <p class="text-gray-600 mb-4">
                        Our premium high-end brand featuring top-of-the-line materials and craftsmanship, designed for serious players and professionals.
                    </p>
                    <div class="flex flex-wrap gap-2 mb-2">
                        <span class="bg-orange-50 px-3 py-1 rounded-full text-sm">High-end</span>
                        <span class="bg-custom/10 text-custom px-3 py-1 rounded-full text-sm"><i class="fa fa-paint-brush mr-1"></i> Customizable</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section with Dual Focus -->
    <section id="contact" class="py-16 bg-gray-50">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-4 text-dark">Get In Touch</h2>
            <p class="text-center text-gray-600 max-w-2xl mx-auto mb-12">
                Whether you need custom solutions or partnership information, we're ready to help
            </p>

            <div class="max-w-4xl mx-auto bg-white rounded-2xl shadow-lg overflow-hidden">
                <div class="md:flex">
                    <div class="md:w-1/2 bg-primary p-8 text-white">
                        <h3 class="text-2xl font-bold mb-6">Contact Information</h3>
                        <p class="mb-8 opacity-90">
                            Reach out through any of these channels for custom inquiries or partnership opportunities
                        </p>
                        
                        <div class="space-y-6">
                            <div class="flex items-start">
                                <i class="fa fa-whatsapp text-xl mt-1 mr-4"></i>
                                <div>
                                    <h4 class="font-semibold mb-1">WhatsApp</h4>
                                    <p class="opacity-90">+86 19137644243</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <i class="fa fa-weixin text-xl mt-1 mr-4"></i>
                                <div>
                                    <h4 class="font-semibold mb-1">WeChat</h4>
                                    <p class="opacity-90">1913764424</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <i class="fa fa-envelope text-xl mt-1 mr-4"></i>
                                <div>
                                    <h4 class="font-semibold mb-1">Email</h4>
                                    <p class="opacity-90">ivanadengchina@gmail.com</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="md:w-1/2 p-8">
                        <h3 class="text-2xl font-bold mb-6 text-dark">Inquiry Form</h3>
                        <form>
                            <div class="mb-4">
                                <label for="name" class="block text-gray-700 mb-2">Your Name</label>
                                <input type="text" id="name" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent" placeholder="John Doe">
                            </div>
                            
                            <div class="mb-4">
                                <label for="organization" class="block text-gray-700 mb-2">Organization/Company</label>
                                <input type="text" id="organization" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent" placeholder="Your company name">
                            </div>
                            
                            <div class="mb-4">
                                <label for="inquiry-type" class="block text-gray-700 mb-2">Inquiry Type</label>
                                <select id="inquiry-type" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent">
                                    <option value="">Select inquiry type</option>
                                    <option value="custom-brand">Brand Customization</option>
                                    <option value="custom-club">Club Customization</option>
                                    <option value="retail">Retail Partnership</option>
                                    <option value="agent">Agent Opportunity</option>
                                    <option value="distributor">Distribution Partnership</option>
                                    <option value="wholesale">Wholesale Inquiry</option>
                                </select>
                            </div>
                            
                            <div class="mb-6">
                                <label for="message" class="block text-gray-700 mb-2">Your Message</label>
                                <textarea id="message" rows="4" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary focus:border-transparent" placeholder="Tell us about your requirements or partnership interests..."></textarea>
                            </div>
                            
                            <button type="submit" class="w-full bg-secondary hover:bg-secondary/90 text-white font-semibold py-3 px-6 rounded-lg transition duration-300">
                                Send Inquiry <i class="fa fa-paper-plane ml-2"></i>
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white py-12">
        <div class="container mx-auto px-6">
            <div class="md:flex justify-between items-center">
                <div class="mb-6 md:mb-0">
                    <h3 class="text-2xl font-bold mb-2">Pickleball Factory</h3>
                    <p class="text-gray-400">Custom Solutions & Trusted Partnerships</p>
                </div>
                
                <div class="flex space-x-4">
                    <a href="#" class="w-10 h-10 rounded-full bg-white/10 flex items-center justify-center hover:bg-primary transition duration-300">
                        <i class="fa fa-facebook"></i>
                    </a>
                    <a href="#" class="w-10 h-10 rounded-full bg-white/10 flex items-center justify-center hover:bg-primary transition duration-300">
                        <i class="fa fa-instagram"></i>
                    </a>
                    <a href="#" class="w-10 h-10 rounded-full bg-white/10 flex items-center justify-center hover:bg-primary transition duration-300">
                        <i class="fa fa-twitter"></i>
                    </a>
                    <a href="#" class="w-10 h-10 rounded-full bg-white/10 flex items-center justify-center hover:bg-primary transition duration-300">
                        <i class="fa fa-linkedin"></i>
                    </a>
                </div>
            </div>
            
            <hr class="border-gray-700 my-8">
            
            <div class="text-center text-gray-400 text-sm">
                <p>© 2023 Pickleball Factory. Custom manufacturing and distribution partners.</p>
            </div>
        </div>
    </footer>

    <!-- Back to Top Button -->
    <button onclick="window.scrollTo({top: 0, behavior: 'smooth'})" class="fixed bottom-6 right-6 bg-primary text-white w-12 h-12 rounded-full flex items-center justify-center shadow-lg hover:bg-primary/90 transition duration-300">
        <i class="fa fa-arrow-up"></i>
    </button>

    <script>
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Add animation on scroll
        window.addEventListener('scroll', function() {
            const elements = document.querySelectorAll('.card-hover');
            elements.forEach(element => {
                const position = element.getBoundingClientRect();
                // If element is in viewport
                if(position.top < window.innerHeight && position.bottom >= 0) {
                    element.style.opacity = '1';
                    element.style.transform = 'translateY(0)';
                }
            });
        });

        // Initialize animations
        window.dispatchEvent(new Event('scroll'));
    </script>
</body>
</html>
