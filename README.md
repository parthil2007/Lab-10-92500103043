<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">

    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">

    <title>Mehta's Store - Product Page</title>

    <script src="https://cdn.tailwindcss.com"></script>
</head>

<body class="bg-gray-100 min-h-screen flex flex-col">

    <!-- Header -->
    <header class="bg-orange-500 text-white p-3">
        <h1 class="text-xl font-medium">Mehta's Store</h1>
    </header>

    <!-- Main Content -->
    <main class="flex-grow px-4 py-4">

        <h2 class="text-xl text-center mb-4">
            Our Products
        </h2>

        <!-- Product Cards -->
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3 max-w-4xl mx-auto">

            <!-- Product 1 -->
            <div class="bg-white p-3 flex flex-col">

                <img src="laptop.jpeg"
                     alt="Laptop"
                     class="w-full h-48 object-contain">

                <h3 class="text-base mt-2">Laptop</h3>
                <p class="text-sm">Price: ₹1,45,999</p>

                <button class="bg-orange-500 hover:bg-orange-700 text-white text-sm p-2 mt-2 w-full rounded-full transition">
                    Buy Now
                </button>

            </div>

            <!-- Product 2 -->
            <div class="bg-white p-3 flex flex-col">

                <img src="phones.jpeg"
                     alt="Phone"
                     class="w-full h-48 object-contain">

                <h3 class="text-base mt-2">Phone</h3>
                <p class="text-sm">Price: ₹1,99,999</p>

                <button class="bg-orange-500 hover:bg-orange-700 text-white text-sm p-2 mt-2 w-full rounded-full transition">
                    Buy Now
                </button>

            </div>

            <!-- Product 3 -->
            <div class="bg-white p-3 flex flex-col">

                <img src="shoes.jpeg"
                     alt="Shoes"
                     class="w-full h-48 object-contain">

                <h3 class="text-base mt-2">Shoes</h3>
                <p class="text-sm">Price: ₹50,499</p>

                <button class="bg-orange-500 hover:bg-orange-700 text-white text-sm p-2 mt-2 w-full rounded-full transition">
                    Buy Now
                </button>

            </div>

            <!-- Product 4 -->
            <div class="bg-white p-3 flex flex-col">

                <img src="watch.jpeg"
                     alt="Apple Watch"
                     class="w-full h-48 object-contain">

                <h3 class="text-base mt-2">Apple watch</h3>
                <p class="text-sm">Price: ₹30,499</p>

                <button class="bg-orange-500 hover:bg-orange-700 text-white text-sm p-2 mt-2 w-full rounded-full transition">
                    Buy Now
                </button>

            </div>

        </div>

    </main>

    <!-- Footer -->
    <footer class="bg-orange-950 text-white text-center p-3 mt-auto">
        Mehta's Store © 2026
    </footer>

</body>
</html>
