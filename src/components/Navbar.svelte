


    <!-- Navbar -->
    <nav class="  bg-white hover:bg-gray-100 p-5">
        <div class="container mx-auto flex items-center justify-between">

            <!-- Logo and Text -->
            <div class="flex items-center md:mx-20 ">
                <!-- Logo (replace 'logo.png' with your actual logo file) -->
                <img src="/Logo.png" alt="Logo" class="h-12 w-12 mr-3">

                <!-- Text (replace 'Your Company' with your actual company name) -->
                <span class=" text-black sm:text-3xl  font-poppins font-normal">Inflection Zone Lab</span>
            </div>

           <!-- Hamburger Menu for Small Screens -->
           <div class="  md:hidden transition-transform duration-300 ease-in-out">
            <button id="menu-toggle" class="text-black focus:outline-none">
                <svg class="h-6 w-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
                </svg>
            </button>
        </div>
        <div class="hidden md:flex space-x-4 mx-20 text-lg">
            <a href="home" class="text-black font-poppins transition duration-200 pr-4 relative group p-1 ">
                Home 
                <span class="absolute bottom-0 left-1/2 transform -translate-x-1/2 w-0 h-0.5 bg-orange-500 origin-center transition-all duration-500 group-hover:w-full"></span>
            </a>
            <a href="solutions" class="text-black font-poppins hover:text-orange-500 transition duration-200 pr-3 relative group p-1">
                Solutions
                <span class="absolute bottom-0 left-1/2 transform -translate-x-1/2 w-0 h-0.5 bg-orange-500 origin-center transition-all duration-500 group-hover:w-full"></span>
            </a>
            <a href="aboutus" class="text-black font-poppins hover:text-orange-500 transition duration-200 pr-3 relative group p-1">
                About us
                <span class="absolute bottom-0 left-1/2 transform -translate-x-1/2 w-0 h-0.5 bg-orange-500 origin-center transition-all duration-500 group-hover:w-full"></span>
            </a>
            <a href="contactus" class="text-black font-poppins hover:text-orange-500 transition duration-200 pr-3 relative group p-1">
                Contact us
                <span class="absolute bottom-0 left-1/2 transform -translate-x-1/2 w-0 h-0.5 bg-orange-500 origin-center transition-all duration-500 group-hover:w-full"></span>
            </a>
        </div>
        
        
        </div>
    </nav>

    <!-- Responsive Navigation Menu (Initially Hidden) -->
    <div id="mobile-menu" class="  animate__animated animate__fadeInUp md:hidden hidden bg-black p-4 ">
        <a href="home" class="block text-white mb-2 transition duration-300 pr-3 relative font-poppins">Home</a>
        <span class="absolute bottom-0 left-1/2 transform -translate-x-1/2 h-0.5 bg-orange-500 w-0 transition-transform duration-200 group-hover:w-full"></span>
        <a href="solutions" class="block text-white mb-2 transition duration-300 hover:text-orange-500 pr-3 font-poppins">Solutions</a>
        <a href="aboutus" class="block text-white mb-2 transition duration-300 hover:text-orange-500 pr-3 font-poppins">About us</a>
        <a href="contactus" class="block text-white      transition duration-300 hover:text-orange-500 pr-3 font-poppins">Contact us</a>
    </div>

    <!-- Your Content Goes Here -->
    <script>
        import { onMount } from 'svelte';
    
        onMount(() => {
            if (typeof document !== 'undefined') {
                // @ts-ignore
                document.getElementById('menu-toggle').addEventListener('click', function () {
                    // @ts-ignore
                    document.getElementById('mobile-menu').classList.toggle('hidden');
                });
            }
        });
    </script>


