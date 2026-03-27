# Lassi-Castle
Welcome to **Lassi Castle**, the ultimate spot for bold flavors! Dive into our signature **crispy chicken**, seasoned for a golden, irresistible crunch. Pair it with our thick, velvety **milkshakes** for the perfect treat. Quality comfort food and royal snacks await—stop by and feast like a king!
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lassi Castle | Premium Crispy Chicken & Shakes</title>
    
    <!-- Scripts & Styles -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

    <style>
        .glass {
            background: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.3);
        }
        .hero-gradient {
            background: linear-gradient(135deg, #fffcf0 0%, #ffffff 100%);
        }
    </style>
</head>
<body class="bg-white text-gray-900 font-sans selection:bg-red-100">

    <!-- Navigation -->
    <nav class="fixed top-0 w-full z-50 glass px-6 py-4 flex justify-between items-center shadow-sm">
        <div class="animate__animated animate__fadeInLeft">
            <span class="text-2xl font-black text-red-600 tracking-tighter uppercase">Lassi Castle</span>
        </div>
        <div class="hidden md:block animate__animated animate__fadeInRight text-sm font-bold uppercase tracking-widest text-gray-500">
            Kurusady • Nagercoil
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="min-h-screen flex flex-col justify-center items-center text-center px-6 pt-20 hero-gradient">
        <div class="animate__animated animate__zoomIn bg-yellow-400 text-yellow-900 px-4 py-1 rounded-full text-xs font-black uppercase tracking-widest mb-6">
            Top Rated in Nagercoil
        </div>
        <h1 class="animate__animated animate__fadeInUp text-5xl md:text-7xl font-black text-gray-900 mb-6 leading-tight">
            Crunchy <span class="text-red-600">Chicken.</span><br>Velvety <span class="text-orange-500">Shakes.</span>
        </h1>
        <p class="animate__animated animate__fadeInUp animate__delay-1s text-gray-600 max-w-lg text-lg mb-10">
            Experience the royal standard of snacks. We serve the crispest golden chicken and thickest milkshakes in the Mission Complex area.
        </p>
        <div class="animate__animated animate__fadeInUp animate__delay-1s flex flex-col sm:flex-row gap-4 w-full justify-center">
            <a href="tel:08124582756" class="bg-red-600 text-white px-8 py-4 rounded-2xl font-bold shadow-xl shadow-red-200 hover:scale-105 transition-transform text-lg">
                Order Now
            </a>
            <a href="https://www.google.com/maps/dir//Lassi+Castle+Mission+Complex,+155Z%2F1,+St+Antony+St,+Kurusady,+North+Konam,+Nagercoil,+Tamil+Nadu+629004" target="_blank" class="bg-gray-900 text-white px-8 py-4 rounded-2xl font-bold hover:scale-105 transition-transform text-lg">
                Get Directions
            </a>
        </div>
    </section>

    <!-- Features Section -->
    <section class="py-24 px-6 max-w-6xl mx-auto">
        <div class="grid md:grid-cols-2 gap-12">
            <div data-aos="fade-up" class="group relative overflow-hidden rounded-[2rem] bg-yellow-50 p-10">
                <span class="text-6xl">🍗</span>
                <h3 class="text-3xl font-black mt-6 mb-4 text-gray-900">The Signature Crunch</h3>
                <p class="text-gray-600 text-lg">Our crispy chicken is marinated for 12 hours and fried to a perfect golden hue. Every bite is a royal celebration of flavor.</p>
            </div>
            <div data-aos="fade-up" data-aos-delay="200" class="group relative overflow-hidden rounded-[2rem] bg-orange-50 p-10">
                <span class="text-6xl">🥤</span>
                <h3 class="text-3xl font-black mt-6 mb-4 text-gray-900">Thick & Velvety</h3>
                <p class="text-gray-600 text-lg">Crafted with premium dairy and fresh ingredients, our milkshakes set the gold standard for sweetness in Kurusady.</p>
            </div>
        </div>
    </section>

    <!-- Reviews Section -->
    <section class="py-24 bg-gray-900 text-white overflow-hidden">
        <div class="px-6 max-w-6xl mx-auto">
            <div class="mb-16" data-aos="fade-right">
                <h2 class="text-4xl font-black mb-4">Loved by Locals</h2>
                <div class="flex items-center gap-2">
                    <div class="flex text-yellow-400">
                        <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star text-gray-600"></i>
                    </div>
                    <span class="font-bold">4.8 (5 Google Reviews)</span>
                </div>
            </div>

            <div class="grid md:grid-cols-2 gap-8">
                <!-- Review 1 -->
                <div data-aos="zoom-in" class="bg-gray-800/50 p-8 rounded-3xl border border-gray-700">
                    <p class="text-xl italic text-gray-300 mb-6">"The chicken is so crunchy and the shakes are thick! Best spot in town."</p>
                    <div class="flex items-center gap-4">
                        <div class="w-10 h-10 rounded-full bg-red-600 flex items-center justify-center font-bold">G</div>
                        <span class="font-bold tracking-wide">Verified Google Review</span>
                    </div>
                </div>
                <!-- Review 2 -->
                <div data-aos="zoom-in" data-aos-delay="200" class="bg-gray-800/50 p-8 rounded-3xl border border-gray-700">
                    <p class="text-xl italic text-gray-300 mb-6">"Amazing quality and fast service. A must-visit in Kurusady!"</p>
                    <div class="flex items-center gap-4">
                        <div class="w-10 h-10 rounded-full bg-yellow-500 flex items-center justify-center font-bold">L</div>
                        <span class="font-bold tracking-wide">Local Guide Review</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-20 px-6 text-center">
        <div data-aos="fade-up">
            <h2 class="text-2xl font-black mb-4 uppercase tracking-tighter">Lassi Castle</h2>
            <p class="text-gray-500 mb-8">
                Mission Complex, 155Z/1, St Antony St, Kurusady,<br>
                North Konam, Nagercoil, Tamil Nadu 629004
            </p>
            <div class="flex justify-center gap-6 text-2xl text-gray-400">
                <i class="fab fa-instagram hover:text-red-600 transition-colors"></i>
                <i class="fab fa-whatsapp hover:text-green-500 transition-colors"></i>
            </div>
        </div>
        <div class="mt-20 text-[10px] text-gray-300 uppercase tracking-[0.3em]">
            Digital Experience by [Your Name]
        </div>
    </footer>

    <!-- Floating Action Bar (Mobile Only) -->
    <div class="fixed bottom-6 left-1/2 -translate-x-1/2 w-[90%] max-w-md glass rounded-2xl shadow-2xl p-2 flex gap-2 z-50 md:hidden animate__animated animate__fadeInUp">
        <a href="tel:08124582756" class="flex-1 bg-red-600 text-white text-center py-3 rounded-xl font-bold text-sm">
            <i class="fa-solid fa-phone mr-2"></i>Call
        </a>
        <a href="https://www.google.com/maps/dir//Lassi+Castle+Mission+Complex,+155Z%2F1,+St+Antony+St,+Kurusady,+North+Konam,+Nagercoil,+Tamil+Nadu+629004" target="_blank" class="flex-1 bg-gray-900 text-white text-center py-3 rounded-xl font-bold text-sm">
            <i class="fa-solid fa-location-dot mr-2"></i>Map
        </a>
    </div>

    <!-- Scripts for Animations -->
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        AOS.init({
            duration: 800,
            once: true,
        });
    </script>
</body>
</html>
