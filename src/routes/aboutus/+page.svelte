<script>
import Footer from "../../components/Footer.svelte";
import Navbar from "../../components/Navbar.svelte";

</script>

<Navbar/>

<div class="bg-black">
    <h1 class="text-xl sm:text-lg md:text-4xl lg:text-5xl text-white   md:pt-10 xl:pt-16  font-medium font-poppins  pt-6 flex justify-center">About us</h1>
    
    <div class="flex flex-col md:flex-row p-4 md:p-8  lg:p-24 mx-auto xl:ml-28">
        <!-- Image -->
        <img src="/about.jpg" alt="" class=" animate__animated animate__fadeInLeft w-[50%] md:w-[400%] lg:w-[40%] object-cover mb-4 md:mb-0  mx-auto">

        <!-- Text Content -->
        <div class="md:ml-8 lg:ml-16 ">
            <!-- Heading -->
            <h1 class="animate__animated animate__fadeInUp text-yellow-400 font-poppins font-medium text-2xl md:text-4xl lg:text-5xl mb-6">
                Who we are ?</h1>
            
            <!-- Paragraph -->
            <p class=" animate__animated animate__fadeInUp animate__delay-1s text-white  md:text-xl lg:text-lg  xl:w-[80%] mb-6  font-poppins">We are passionate engineers always looking for patterns around us. We believe that any mundane task which one has to repeat more than twice can be and needs to be automated!

            </p>
            <p class=" animate__animated animate__fadeInUp animate__delay-1s text-white  md:text-xl lg:text-lg  xl:w-[80%] mb-6  font-poppins">Apart from providing software development services, we are also working on our products which are currently in stealth mode. We soon hope to bring them out in the sun!</p>
            
        </div>
    </div>
    
    </div>

<Footer/>

