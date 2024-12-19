
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>laravel from scratch blog</title>
    <link href="https://unpkg.com/tailwindcss@^2/dist/tailwind.min.css" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap" rel="stylesheet">

<body style="font-family: open sans , sans-serif ,Arial, Helvetica;">

    <section class="px-6 py-8">
        <nav class="md:flex md:justify-between md:items-center">
            <div>
                <a href="#">
                    <img src="images/logo.svg" alt="image logo" height="16" width="165">
                </a>
            </div>
            <div class="mt-8 md:mt-0">
                <a href="/" class="text-xs font-bold uppercase">Home Page</a>
                <a href="#"
                    class="bg-blue-500 ml-3 rounded-full text-xs font-semibold text-white uppercase py-3 px-5">Subscribe
                    for
                    updates</a>
            </div>
        </nav>
        <header class="mt-10">
            <div class="max-w-4xl mx-auto text-center">
                <h1 class="text-4xl">
                    Latest <span class="text-blue-500">Laravel From Scratch </span> News
                </h1>
                <h2 class="inline-flex mt-4">By lary laracore <img src="/images/lary-head.svg" alt="laray head"></h2>

                <p class="text-sm mt-14">
                    Another year. Another update. We're refreshing the popular Laravel series with new content.
                    I'm going to keep you guys up to speed with what's going on!
                </p>

                <div class="tw-flex tw-justify-center space-y-2 lg:space-y-0 lg:space-x-4 mt-8">

                    <!--Category-->
                    <span class="relative flex lg:inline-flex items-center bg-gray-100  rounded-xl">
                        <select name="" id=""
                            class="flex-1 appearance-none bg-transparent py-2 pl-3 pr-9 text-sm font-semibold">
                            <option value="category" disabled selected>Category</option>
                            <option value="personal">Personal </option>
                            <option value="business">Business</option>
                        </select>
                        <svg class="transform -rotate-90 absolute pointer-events-none" style="right: 12px;" width="22"
                            height="22" viewBox="0 0 22 22">
                            <g fill="none" fill-rule="evenodd">
                                <path stroke="#000" stroke-opacity=".012" stroke-width=".5" d="M21 1v20.16H.84V1z">
                                </path>
                                <path fill="#222"
                                    d="M13.854 7.224l-3.847 3.856 3.847 3.856-1.184 1.184-5.04-5.04 5.04-5.04z"></path>
                            </g>
                        </svg>
                    </span>


                    <!--oother filters-->
                    <span class="relative flex lg:inline-flex items-center bg-gray-100  rounded-xl">
                        <select name="" id=""
                            class="flex-1 appearance-none bg-transparent py-2 pl-3 pr-9 text-sm font-semibold">
                            <option value="category" disabled selected>Other filters</option>
                            <option value="bar">bar </option>
                            <option value="foo">foo</option>
                        </select>
                        <svg class="transform -rotate-90 absolute pointer-events-none" style="right: 12px;" width="22"
                            height="22" viewBox="0 0 22 22">
                            <g fill="none" fill-rule="evenodd">
                                <path stroke="#000" stroke-opacity=".012" stroke-width=".5" d="M21 1v20.16H.84V1z">
                                </path>
                                <path fill="#222"
                                    d="M13.854 7.224l-3.847 3.856 3.847 3.856-1.184 1.184-5.04-5.04 5.04-5.04z"></path>
                            </g>
                        </svg>
                    </span>

                    <!--Search -->
                    <div class="relative flex lg:inline-flex items-center bg-gray-100  rounded-xl px-3 py-2">
                        <form action="#" method="get">
                            <input type="text" name="" id="" placeholder="find something"
                                class="bg-transparent placeholder-black font-semibold text-sm">
                        </form>
                    </div>
                </div>

            </div>
        </header>
        <main class="max-w-6xl mx-auto mt-16 space-y-8">
            <article
                class="transition-colors duration-300 hover:bg-gray-100 border border-black border-opacity-0 hover:border-opacity-5 rounded-xl">
                <div class="py-6 px-5 lg:flex">
                    <div class="flex-1 lg:mr-8">
                        <img src="images/illustration-1.png" alt="Blog post illustration">
                    </div>
                    <div class="flex-1 flex flex-col justify-between">
                        <header class="mt-8 lg:mt-0">
                            <div class="space-x-2">
                                <a href="#"
                                    class="px-3 py-1 border border-blue-300 rounded-full text-blue-300 text-xs uppercase font-semibold"
                                    style="font-size: 10px;">Techniques</a>
                                <a href="#"
                                    class="px-3 py-1 border border-red-300 rounded-full text-red-300 text-xs uppercase font-semibold"
                                    style="font-size: 10px;">updates</a>
                            </div>
                            <div class="mt-2">
                                <h1 class="text-3xl">This is a big title and it will look great on two or even three
                                    lines. Wooohoo!</h1>
                                <span class="mt-2 block text-gray-400 text-xs">
                                    Published
                                    <time>1 day ago </time></span>
                            </div>
                        </header>
                        <div class="text-sm mt-2">
                            <p>
                                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                                incididunt
                                ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
                                ullamco laboris nisi ut aliquip ex ea commodo consequat.
                            </p>

                            <p class="mt-4">
                                Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat
                                nulla pariatur.
                            </p>
                        </div>
                        <footer class="flex justify-between items-center mt-8">
                            <div class="flex items-center text-sm">
                                <img src="images/lary-avatar.svg" alt="Lary Avatar">
                                <div class="ml-3">
                                    <h5 class="font-bold">lary laracore</h5>
                                    <h6>Mascote at laracast</h6>
                                </div>
                            </div>
                            <div class="hidden md:block">
                                <a href="post.html"
                                    class="text-xs font-semibold bg-gray-200 py-2 px-6 rounded-full">Read
                                    More</a>
                            </div>

                        </footer>
                    </div>
                </div>
            </article>
            <div class="lg:grid lg:grid-cols-2">
                <article
                    class="transition-colors duration-300 hover:bg-gray-100 border border-black border-opacity-0 hover:border-opacity-5 rounded-xl">
                    <div class="py-6 px-5">
                        <div>
                            <img src="images/illustration-1.png" alt="Blog post illustration">
                        </div>
                        <div class="mt-6 flex-1 flex flex-col justify-between">
                            <header>
                                <div class="space-x-2">
                                    <a href="#"
                                        class="px-3 py-1 border border-blue-300 rounded-full text-blue-300 text-xs uppercase font-semibold"
                                        style="font-size: 10px;">Techniques</a>
                                    <a href="#"
                                        class="px-3 py-1 border border-red-300 rounded-full text-red-300 text-xs uppercase font-semibold"
                                        style="font-size: 10px;">updates</a>
                                </div>
                                <div class="mt-2">
                                    <h1 class="text-3xl">This is a big title and it will look great on two or even three
                                        lines. Wooohoo!</h1>
                                    <span class="mt-2 block text-gray-400 text-xs">
                                        Published
                                        <time>1 day ago </time></span>
                                </div>
                            </header>
                            <div class="text-sm mt-4">
                                <p>
                                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                                    incididunt
                                    ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
                                    ullamco laboris nisi ut aliquip ex ea commodo consequat.
                                </p>

                                <p class="mt-4">
                                    Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu
                                    fugiat
                                    nulla pariatur.
                                </p>
                            </div>
                            <footer class="flex justify-between items-center mt-8">
                                <div class="flex items-center text-sm">
                                    <img src="images/lary-avatar.svg" alt="Lary Avatar">
                                    <div class="ml-3">
                                        <h5 class="font-bold">lary laracore</h5>
                                        <h6>Mascote at laracast</h6>
                                    </div>
                                </div>
                                <div class="hidden md:block">
                                    <a href="post.html"
                                        class="text-xs font-semibold bg-gray-200 py-2 px-6 rounded-full">Read
                                        More</a>
                                </div>

                            </footer>
                        </div>
                    </div>
                </article>
                <article
                    class="transition-colors duration-300 hover:bg-gray-100 border border-black border-opacity-0 hover:border-opacity-5 rounded-xl">
                    <div class="py-6 px-5">
                        <div>
                            <img src="images/illustration-2.png" alt="Blog post illustration">
                        </div>
                        <div class="mt-6 flex-1 flex flex-col justify-between">
                            <header>
                                <div class="space-x-2">
                                    <a href="#"
                                        class="px-3 py-1 border border-blue-300 rounded-full text-blue-300 text-xs uppercase font-semibold"
                                        style="font-size: 10px;">Techniques</a>
                                    <a href="#"
                                        class="px-3 py-1 border border-red-300 rounded-full text-red-300 text-xs uppercase font-semibold"
                                        style="font-size: 10px;">updates</a>
                                </div>
                                <div class="mt-2">
                                    <h1 class="text-3xl">This is a big title and it will look great on two or even three
                                        lines. Wooohoo!</h1>
                                    <span class="mt-2 block text-gray-400 text-xs">
                                        Published
                                        <time>1 day ago </time></span>
                                </div>
                            </header>
                            <div class="text-sm mt-4">
                                <p>
                                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                                    incididunt
                                    ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
                                    ullamco laboris nisi ut aliquip ex ea commodo consequat.
                                </p>

                                <p class="mt-4">
                                    Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu
                                    fugiat
                                    nulla pariatur.
                                </p>
                            </div>
                            <footer class="flex justify-between items-center mt-8">
                                <div class="flex items-center text-sm">
                                    <img src="images/lary-avatar.svg" alt="Lary Avatar">
                                    <div class="ml-3">
                                        <h5 class="font-bold">lary laracore</h5>
                                        <h6>Mascote at laracast</h6>
                                    </div>
                                </div>
                                <div class="hidden md:block">
                                    <a href="post.html"
                                        class="text-xs font-semibold bg-gray-200 py-2 px-6 rounded-full">Read
                                        More</a>
                                </div>

                            </footer>
                        </div>
                    </div>
                </article>
            </div>

            <div class="lg:grid lg:grid-cols-3">
                <article
                    class="transition-colors duration-300 hover:bg-gray-100 border border-black border-opacity-0 hover:border-opacity-5 rounded-xl">
                    <div class="py-6 px-5">
                        <div>
                            <img src="images/illustration-3.png" alt="Blog post illustration">
                        </div>
                        <div class="mt-6 flex-1 flex flex-col justify-between">
                            <header>
                                <div class="space-x-2">
                                    <a href="#"
                                        class="px-3 py-1 border border-blue-300 rounded-full text-blue-300 text-xs uppercase font-semibold"
                                        style="font-size: 10px;">Techniques</a>
                                    <a href="#"
                                        class="px-3 py-1 border border-red-300 rounded-full text-red-300 text-xs uppercase font-semibold"
                                        style="font-size: 10px;">updates</a>
                                </div>
                                <div class="mt-2">
                                    <h1 class="text-3xl">This is a big title and it will look great on two or even three
                                        lines. Wooohoo!</h1>
                                    <span class="mt-2 block text-gray-400 text-xs">
                                        Published
                                        <time>1 day ago </time></span>
                                </div>
                            </header>
                            <div class="text-sm mt-4">
                                <p>
                                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                                    incididunt
                                    ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
                                    ullamco laboris nisi ut aliquip ex ea commodo consequat.
                                </p>

                                <p class="mt-4">
                                    Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu
                                    fugiat
                                    nulla pariatur.
                                </p>
                            </div>
                            <footer class="flex justify-between items-center mt-8">
                                <div class="flex items-center text-sm">
                                    <img src="images/lary-avatar.svg" alt="Lary Avatar">
                                    <div class="ml-3">
                                        <h5 class="font-bold">lary laracore</h5>
                                        <h6>Mascote at laracast</h6>
                                    </div>
                                </div>
                                <div class="hidden md:block">
                                    <a href="post.html"
                                        class="text-xs font-semibold bg-gray-200 py-2 px-6 rounded-full">Read
                                        More</a>
                                </div>

                            </footer>
                        </div>
                    </div>
                </article>
                <article
                    class="transition-colors duration-300 hover:bg-gray-100 border border-black border-opacity-0 hover:border-opacity-5 rounded-xl">
                    <div class="py-6 px-5">
                        <div>
                            <img src="images/illustration-4.png" alt="Blog post illustration">
                        </div>
                        <div class="mt-6 flex-1 flex flex-col justify-between">
                            <header>
                                <div class="space-x-2">
                                    <a href="#"
                                        class="px-3 py-1 border border-blue-300 rounded-full text-blue-300 text-xs uppercase font-semibold"
                                        style="font-size: 10px;">Techniques</a>
                                    <a href="#"
                                        class="px-3 py-1 border border-red-300 rounded-full text-red-300 text-xs uppercase font-semibold"
                                        style="font-size: 10px;">updates</a>
                                </div>
                                <div class="mt-2">
                                    <h1 class="text-3xl">This is a big title and it will look great on two or even three
                                        lines. Wooohoo!</h1>
                                    <span class="mt-2 block text-gray-400 text-xs">
                                        Published
                                        <time>1 day ago </time></span>
                                </div>
                            </header>
                            <div class="text-sm mt-4">
                                <p>
                                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                                    incididunt
                                    ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
                                    ullamco laboris nisi ut aliquip ex ea commodo consequat.
                                </p>

                                <p class="mt-4">
                                    Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu
                                    fugiat
                                    nulla pariatur.
                                </p>
                            </div>
                            <footer class="flex justify-between items-center mt-8">
                                <div class="flex items-center text-sm">
                                    <img src="images/lary-avatar.svg" alt="Lary Avatar">
                                    <div class="ml-3">
                                        <h5 class="font-bold">lary laracore</h5>
                                        <h6>Mascote at laracast</h6>
                                    </div>
                                </div>
                                <div class="hidden md:block">
                                    <a href="post.html"
                                        class="text-xs font-semibold bg-gray-200 py-2 px-6 rounded-full">Read
                                        More</a>
                                </div>

                            </footer>
                        </div>
                    </div>
                </article>
                <article
                    class="transition-colors duration-300 hover:bg-gray-100 border border-black border-opacity-0 hover:border-opacity-5 rounded-xl">
                    <div class="py-6 px-5">
                        <div>
                            <img src="images/illustration-5.png" alt="Blog post illustration">
                        </div>
                        <div class="mt-6 flex-1 flex flex-col justify-between">
                            <header>
                                <div class="space-x-2">
                                    <a href="#"
                                        class="px-3 py-1 border border-blue-300 rounded-full text-blue-300 text-xs uppercase font-semibold"
                                        style="font-size: 10px;">Techniques</a>
                                    <a href="#"
                                        class="px-3 py-1 border border-red-300 rounded-full text-red-300 text-xs uppercase font-semibold"
                                        style="font-size: 10px;">updates</a>
                                </div>
                                <div class="mt-2">
                                    <h1 class="text-3xl">This is a big title and it will look great on two or even three
                                        lines. Wooohoo!</h1>
                                    <span class="mt-2 block text-gray-400 text-xs">
                                        Published
                                        <time>1 day ago </time></span>
                                </div>
                            </header>
                            <div class="text-sm mt-4">
                                <p>
                                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                                    incididunt
                                    ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
                                    ullamco laboris nisi ut aliquip ex ea commodo consequat.
                                </p>

                                <p class="mt-4">
                                    Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu
                                    fugiat
                                    nulla pariatur.
                                </p>
                            </div>
                            <footer class="flex justify-between items-center mt-8">
                                <div class="flex items-center text-sm">
                                    <img src="images/lary-avatar.svg" alt="Lary Avatar">
                                    <div class="ml-3">
                                        <h5 class="font-bold">lary laracore</h5>
                                        <h6>Mascote at laracast</h6>
                                    </div>
                                </div>
                                <div class="hidden md:block">
                                    <a href="post.html"
                                        class="text-xs font-semibold bg-gray-200 py-2 px-6 rounded-full">Read
                                        More</a>
                                </div>

                            </footer>
                        </div>
                    </div>
                </article>
            </div>
        </main>
        <footer class="bg-gray-100 border border-black border-opacity-5 rounded-xl text-center py-16 px-10 mt-10 ">
            <img src="images/lary-newsletter-icon.png" alt="laray svg" class="mx-auto" style="width: 140px;">
            <h5 class="text-3xl">Stay in touch with the latest posts</h5>
            <p class="text-sm mt-3">Promise to keep the inbox clean. No bugs.</p>

            <div class="mt-10">
                <div class="relative inline-block mx-auto lg:bg-gray-200 rounded-full">
                    <form action="#" method="post" class="lg:flex text-sm items-center">
                        <div class="lg:py-3 lg:px-5 items-center">
                            <label for="email" class="hidden lg:tw-inline">
                                <img src="images/mailbox-icon.svg" alt="mail box email here ">
                            </label>
                            <input type="text" name="" id="email" placeholder="Your email address here "
                                class="lg:bg-transparent pl-4 focus-within:outline-none">
                        </div>
                        <button type="submit"
                            class="bg-blue-500 hover:bg-blue-600 mt-4 lg:mt-0 lg:ml-3 rounded-full text-xs font-semibold text-white uppercase py-3 px-6">Subscribe
                        </button>
                    </form>
                </div>
            </div>
        </footer>
    </section>
</body>

</html>
