<template>
    <Layout>
        <meta name="color-scheme" content="light dark">
        <meta name="supported-color-schemes" content="light dark">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com">
        <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

        <!-- pre header -->
         <div class="hidden max-h-0 overflow-hidden text-[0px] leading-[0] opacity-0" style="display:none;">
            Here's everything new and updated on Disney Desire
            &#847;&zwnj;&nbsp;&#847;&zwnj;&nbsp;&#847;&zwnj;&nbsp;&#847;&zwnj;&nbsp;&#847;&zwnj;&nbsp;
        </div>

        <!-- banner -->
        <Section class="bg-red-600 dark:bg-neutral-800 text-center font-poppins">
            <Container class="max-w-full">
                <div class="py-5">
                    <img src="https://roxaski.github.io/Email-Changelog/assets/logo/disney_desire/logo.png" width="240" class="mx-auto block w-60" alt="Disney Desire logo">
                    <Text class="-mt-4 text-2xl text-white">Changelog</Text>
                </div>

                <img src="https://roxaski.github.io/Email-Changelog/assets/banner/disney_desire/disney_banner_light_mode.png" width="600" class="block w-full dark:hidden" alt="mickey heads banner">
                <img src="https://roxaski.github.io/Email-Changelog/assets/banner/disney_desire/disney_banner_dark_mode.png" width="600" class="hidden dark:block w-full" alt="">
            </Container>
        </Section>

        <!-- changelog list -->
        <Section class="px-5 py-2 bg-white dark:bg-neutral-900 font-poppins">
            <Container class="max-w-full">
                <Heading class="pt-4 pb-7 text-3xl text-black dark:text-slate-100 text-center">What's New</Heading>
                
                <Heading class="underline underline-offset-1 pb-8 pt-4 text-2xl text-black dark:text-slate-100">Bug Fixes</Heading>
                <ul class="list-none p-0 m-0 text-base text-black dark:text-gray-300">
                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-red-500 dark:bg-rose-800 px-2 py-1 text-xs text-white">bug fix</span>
                        Fixed issues pertaining to portrait images when zooming in within the lightbox ( mobile devices only )
                    </li>

                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-red-500 dark:bg-rose-800 px-2 py-1 text-xs text-white">bug fix</span>
                        Fixed a rare issue that could occur if the gaps between the gallery images were clicked on, it would preload the adjacent images without ever opening the lightbox
                    </li>

                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-red-500 dark:bg-rose-800 px-2 py-1 text-xs text-white">bug fix</span>
                        Fixed a minor issue when mapping out the data for the recommended articles, wherein three unordered list items were being created as opposed to a singular one holding three lists within said element
                    </li>

                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-red-500 dark:bg-rose-800 px-2 py-1 text-xs text-white">bug fix</span>
                        Fixed an issue related to the images of Walter Disney, when opened within the lightbox, which would cause them to zoom in beyond the desired scale ( pc and mobile devices )
                    </li>

                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-red-500 dark:bg-rose-800 px-2 py-1 text-xs text-white">bug fix</span>
                        Fixed a minor issue with variable naming in order to ease confusion for anyone reading the code
                    </li>

                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-red-500 dark:bg-rose-800 px-2 py-1 text-xs text-white">bug fix</span>
                        Fixed the "moving to hollywood" image having the wrong srcset size applied causing it to display at the incorrect height and width for certain screen sizes
                    </li>

                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-red-500 dark:bg-rose-800 px-2 py-1 text-xs text-white">bug fix</span>
                        Fixed the movie contents css file not having a specific css variable attached to it
                    </li>
                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-red-500 dark:bg-rose-800 px-2 py-1 text-xs text-white">bug fix</span>
                        Fixed YouTube thumbnail not having any aspect ratio applied to it, causing chrome to throw errors
                    </li>
                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-red-500 dark:bg-rose-800 px-2 py-1 text-xs text-white">bug fix</span>
                        Fixed an issue where the contents of the movie pages was being pushed down on certain screen sizes
                    </li>

                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-red-500 dark:bg-rose-800 px-2 py-1 text-xs text-white">bug fix</span>
                        Fixed an issue wherein the landscape lightbox images being too large and zoomed in if the browser had other tabs open ( mobile devices only )
                    </li>

                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-red-500 dark:bg-rose-800 px-2 py-1 text-xs text-white">bug fix</span>
                        Fixed an issue that could occur when exiting the lightbox and the focus would shift to another image causing the page to jump ( iOS devices only )
                    </li>

                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-red-500 dark:bg-rose-800 px-2 py-1 text-xs text-white">bug fix</span>
                        Redesigned the lightbox to fix a persistent bug where it would often cause the images to display at the incorrect aspect ratio ( iOS devices only )
                    </li>

                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-red-500 dark:bg-rose-800 px-2 py-1 text-xs text-white">bug fix</span>
                        Fixed a bug with localStorage where if you rated a film and loaded a page that had not been rated before, it would then inherit the prior film's rating
                    </li>
                </ul>

                <Heading class="underline underline-offset-1 pb-8 pt-4 text-2xl text-black dark:text-slate-100">Improvements</Heading>

                <ul class="list-none p-0 m-0 text-base text-black dark:text-gray-300">
                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-blue-500 dark:bg-sky-700 px-2 py-1 text-xs text-white">improvements</span>
                        Improved how the code handled checks when the user was hovered over one of the stars within the star rating section 
                    </li>

                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-blue-500 dark:bg-sky-700 px-2 py-1 text-xs text-white">improvements</span>
                        Improved image preloading, the images now serve the best size and quality for the desired screen size 
                    </li>

                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-blue-500 dark:bg-sky-700 px-2 py-1 text-xs text-white">improvements</span>
                        The lightbox now calculates how much padding is added for each article image in order to dynamically adjust the width of the images in the lightbox ( mobile devices only )
                    </li>

                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-blue-500 dark:bg-sky-700 px-2 py-1 text-xs text-white">improvements</span>
                        Updated certain variables to use const instead of let in order to improve readability to anyone reading the code as the variables never get reassigned
                    </li>

                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-blue-500 dark:bg-sky-700 px-2 py-1 text-xs text-white">improvements</span>
                        Minor reworking of the error message that displays, if the JSON file fails to fetch the recommended articles
                    </li>
                    
                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-blue-500 dark:bg-sky-700 px-2 py-1 text-xs text-white">improvements</span>
                        Moved the lightbox transition outside of the JavaScript code and onto the CSS syntax since Firefox has finally fixed the flashing bug
                    </li>

                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-blue-500 dark:bg-sky-700 px-2 py-1 text-xs text-white">improvements</span>
                        The lightbox now displays the images alt tags on the off chance that the images fail to load
                    </li>

                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-blue-500 dark:bg-sky-700 px-2 py-1 text-xs text-white">improvements</span>
                        Other minor improvements and adjustments were made
                    </li>
                </ul>

                <Heading class="underline underline-offset-1 pb-8 pt-4 text-2xl text-black dark:text-slate-100">Accessibility</Heading>

                <ul class="list-none p-0 m-0 text-base text-black dark:text-gray-300">
                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-green-500 dark:bg-emerald-800 px-2 py-1 text-xs text-white">accessibility</span>
                        Improved focus accessibility, you can now tab through and open any image within the lightbox, in doing so the focus will now remain on the last image that was focused on when exiting the lightbox ( pc only )
                    </li>
                    
                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-green-500 dark:bg-emerald-800 px-2 py-1 text-xs text-white">accessibility</span>
                        Improved accessibility options while reduced motion is enabled 
                    </li>
                </ul>

                <Heading class="underline underline-offset-1 pb-8 pt-4 text-2xl text-black dark:text-slate-100">New Features</Heading>
                
                <ul class="list-none p-0 m-0 text-base text-black dark:text-gray-300">
                    <li class="mb-5">
                        <span class="mr-1 font-medium capitalize rounded bg-orange-500 dark:bg-amber-700 px-2 py-1 text-xs text-white">new feature</span>
                        Added a new star rating feature, where the stars themselves now display when hovering on the user ratings and their color scheme now matches the respective movie page ( pc only )
                    </li>
                </ul>
            </Container>
        </Section>

        <!-- site button link -->
        <Section class="bg-gray-100 dark:bg-neutral-800 px-6 py-8 font-poppins">
            <img src="https://roxaski.github.io/Email-Changelog/assets/other/mickey_minnie.png" width="120" class="mx-auto block w-30 -my-2" alt="icons"/>

            <Heading class="capitalize text-2xl text-black dark:text-slate-100 text-center font-normal pb-3">check out what's new</Heading>

            <div class="text-4xl pt-2 px-5 pb-5 text-center font-medium">
                <a href="https://roxaski.github.io/Disney-Desire/" class="px-8 py-3 inline-block rounded-lg bg-black text-white dark:bg-slate-200 dark:text-black text-base font-normal no-underline shadow-md">
                    Disney Desire
                </a>
            </div>
        </Section>

        <!-- footer -->
        <Section class="px-5 py-8 text-center bg-white dark:bg-black font-poppins">
            <Text class="m-0 mb-2 text-xs text-gray-500 dark:text-gray-400">
                Disney Desire is an unofficial, non-commercial fan project. All Disney characters, names and artwork are the property of The Walt Disney Company. This project is not affiliated with or endorsed by Disney.
            </Text>
            
            <Text class="m-0 text-xs text-gray-500 dark:text-gray-400">
                &copy; 2026 Disney Desire
            </Text>
        </Section>
    </Layout>
</template>