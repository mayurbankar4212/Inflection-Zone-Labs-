<script>
	import Footer from '../../components/Footer.svelte';
	import Navbar from '../../components/Navbar.svelte';
</script>

<Navbar />



<section class="bg-whit dark:bg-slate-800" id="contact">
    <div class="mx-auto max-w-7xl px-4 py-16 sm:px-6 lg:px-8 lg:py-20">
     
        <div class="flex items-stretch justify-center">
            <div class="grid md:grid-cols-2">
                <div class="h-full pr-6 lg:mt-16 mt-2 md:mt-32 xl:mt-32 animate__animated animate__fadeInLeft">
                   
                    <ul class="mb-6 md:mb-0">
                        <li class="flex">
                            <div class="flex h-10 w-10 md:w-16 md:h-16 items-center justify-center rounded  bg-orange-500 text-gray-50">
                                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
                                    fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                    stroke-linejoin="round" class="h-6 w-6 md:h-8 md:w-8" >
                                    <path d="M9 11a3 3 0 1 0 6 0a3 3 0 0 0 -6 0"></path>
                                    <path
                                        d="M17.657 16.657l-4.243 4.243a2 2 0 0 1 -2.827 0l-4.244 -4.243a8 8 0 1 1 11.314 0z">
                                    </path>
                                </svg>
                            </div>
                            <div class="ml-5 mb-4">
                                <h3 class="mb-2 text-lg font-medium leading-6 text-gray-900 dark:text-white font-poppins xl:text-2xl">Offices
                                </h3>
                                <p class="text-gray-600 dark:text-slate-400 font-poppins xl:text-base">Manjari Greens, Pune-Solapur Road, Pune</p>
                               
                            </div>
                        </li>
                        <li class="flex xl:mt-4">
                            <div class="flex h-10 w-10  md:w-16 md:h-16  items-center justify-center rounded   bg-orange-500 text-gray-50">
                                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
                                    fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                    stroke-linejoin="round" class="h-6 w-6 md:h-8 md:w-8">
                                    <path
                                        d="M5 4h4l2 5l-2.5 1.5a11 11 0 0 0 5 5l1.5 -2.5l5 2v4a2 2 0 0 1 -2 2a16 16 0 0 1 -15 -15a2 2 0 0 1 2 -2">
                                    </path>
                                    <path d="M15 7a2 2 0 0 1 2 2"></path>
                                    <path d="M15 3a6 6 0 0 1 6 6"></path>
                                </svg>
                            </div>
                            <div class="ml-4 mb-4">
                                <h3 class="mb-2  font-poppins text-lg font-medium leading-6 text-gray-900 dark:text-white xl:text-2xl">Call us
                                </h3>
                                <p class="text-gray-600 font-poppins dark:text-slate-400 xl:text-base">+91-20-79612519 | Monday – Friday</p>
                              
                            </div>
                        </li>
                        <li class="flex xl:mt-4">
                            <div class="flex h-10 w-10  md:w-16 md:h-16  items-center justify-center rounded bg-orange-500 text-gray-50">
                                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
                                    fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                    stroke-linejoin="round" class="h-6 w-6 md:h-8 md:w-8">
                                    <path
                                    d="M21 4H3a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h18a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2zm0 0l-9 6-9-6M3 6l9 6 9-6">
                                </path>
                                </svg>
                            </div>
                            <div class="ml-4 mb-4">
                                <h3 class="mb-2 text-lg font-medium leading-6 text-gray-900 dark:text-white font-poppins xl:text-2xl">Email</h3>
                                <p class="text-gray-600 dark:text-slate-400 font-poppins xl:text-base">contact@inflectionzone.com</p>
                              
                            </div>
                        </li>
                    </ul>
                </div>


                <div class="animate__animated animate__fadeInRight card h-fit max-w-6xl p-5 md:p-12" id="form">
                    
                    <form id="contactForm">
                        <div class="mb-6">
                            <div class="mx-0 mb-1 sm:mb-4">
                                <div class="mx-0 mb-1 sm:mb-4">
                                    <label for="name" class="pb-1 text-sm  tracking-wider font-poppins">First Name</label><input type="text" id="name" autocomplete="given-name" placeholder="First Name" class=" font-poppins mb-2 w-full rounded-md border border-gray-400 py-2 pl-2 pr-4 shadow-md dark:text-gray-300 sm:mb-0" name="name">
                                </div>

                                <div class="mx-0 mb-1 sm:mb-4">
                                    <label for="name" class="pb-1 text-sm  tracking-wider font-poppins">Last Name</label><input type="text" id="name" autocomplete="given-name" placeholder="Last Name" class=" font-poppins mb-2 w-full rounded-md border border-gray-400 py-2 pl-2 pr-4 shadow-md dark:text-gray-300 sm:mb-0" name="name">
                                </div>

                                <div class="mx-0 mb-1 sm:mb-4">
                                    <label for="email" class="pb-1 text-sm  tracking-wider font-poppins"></label>Email<input type="email" id="email" autocomplete="email" placeholder="Your email address" class=" font-poppins mb-2 w-full rounded-md border border-gray-400 py-2 pl-2 pr-4 shadow-md dark:text-gray-300 sm:mb-0" name="email">
                                </div>
                            </div>
                            <div class="mx-0 mb-1 sm:mb-4">
                                <label for="textarea" class="pb-1 text-sm  tracking-wider font-poppins"></label> Message or Comments<textarea id="textarea" name="textarea" cols="30" rows="5" placeholder="Write your message..." class=" font-poppins mb-2 w-full rounded-md border border-gray-400 py-2 pl-2 pr-4 shadow-md dark:text-gray-300 sm:mb-0"></textarea>
                            </div>

                        </div>

                        <div class="text-center">
                            <button type="submit" class="w-full bg-orange-500  hover:bg-orange-600 font-poppins text-white px-6 py-3  xl:text-xl rounded-md sm:mb-0">Submit</button>
                        </div>

                    </form>
                </div>
            </div>
        </div>
    </div>
</section>


<Footer />
