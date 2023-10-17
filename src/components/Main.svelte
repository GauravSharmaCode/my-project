<script>
    import Step from "./Step.svelte";

    let steps = [
        {
            name: "Live Chat App",
            icon: "fa-solid fa-comments",
            description:
                "Smoljames Store is a a merchanising store created with Next.js, Commerce.js & Stripe! Commerce.js is a CMS for managing project and Stripe is used for all transaction handling.",
        },
        {
            name: "SKS ENTERPRISES PORTFOLIO",
            icon: "fa-solid fa-folder",
            description:
                "Experience the dynamic online presence of SKS Enterprises through our sleek and responsive website, meticulously crafted using Tailwind CSS. Dive into our world of services and offerings, presented with a user-friendly interface and engaging design. Discover the essence of our business, mission, and the value we bring to the market.",
        },
        {
            name: "Tic Tac Toe Game",
            icon: "fa-brands fa-react",
            description:
                "Experience the classic strategy game brought to life in this interactive React project. Compete with a friend and claim victory in the ultimate Tic-Tac-Toe challenge.",
        },
    ];

    let benefits = [
        {
            metric: "10x",
            name: "a self taught developer",
            description:
                "I taught myself to code using free online resources and absolutely fell in love with the creativity and problem solving that is involved in developing and engineering innovative new online experiences. Starting of with JavaScript, HTML & CSS and evolving my knowledge base to include JavaScript frameworks, backend programmingand much much more.",
        },
        {
            name: "a tech enthusiast and problem solver",
            description:
                "With a deep fascination for technology and a knack for creative problem-solving, I thrive in the world of web development. I enjoy tackling complex technical challenges, especially in areas like JavaScript (NEXT.JS or SvelteKit), TailwindCSS, Node.js + Express.js, and database systems like PostgreSQL and MongoDB. I'm dedicated to crafting robust online experiences and am constantly eager to learn and evolve in this ever-changing landscape.",
        },
        {
            name: "an excellent communicator",
            description:
                "Communication is key and it's a paramount value of mine. I believe in transparency and constructive communication above all else. This helps me develop deep relationships and ensures my effectiveness and productivity in any work space with any team.",
        },
    ];
</script>

<main class="flex flex-col flex-1 p-4">
    <section
        id="introPage"
        class="grid grid-cols-1 lg:grid-cols-2 gap-10 py-8 sm:py-14"
    >
        <div
            class="flex flex-col lg:justify-center text-center lg:text-left gap-6 md:gap-8 lg:gap-10"
        >
            <h2 class="font-semibold text-4xl sm:text-5xl md:text-6xl">
                Hi! I'm <span class="poppins text-violet-400">Gaurav</span> Sharma
                <br />Full Stack
                <span class="poppins text-violet-400">Developer</span>
            </h2>
            <p class="text-base sm:text-lg md:text-xl">
                My <span class="text-violet-400"> favorite tech</span> includes JavaScript
                (NEXT.JS or SvelteKit), TailwindCSS, Node.js + Express.js & PostgreSQL
                or MongoDB!
            </p>
            <p class="text-base sm:text-lg md:text-xl">
                Have an <span class="text-violet-400"> interesting project</span> ?  I would love to hear about it!
            </p>
            <button
                class="blueShadow mx-auto lg:mr-auto lg:ml-0 text-base sm:text-lg md:text-xl poppins relative overflow-hidden px-6 py-3 group rounded-full bg-white text-slate-950"
            >
            <a href="#contact" target="_blank"> <div
                class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200"
            />
            <h4 class="relative z-9">Get in touch &rarr;</h4></a>
               
            </button>
        </div>
        <div class="relative shadow-2xl grid place-items-center">
            <img
                src={"images/profile.png"}
                alt="Zetane Engine"
                class="object-cover z-[2] max-h-[70vh]"
            />
        </div>
        <!-- <div  class="flex p-0.5 relative max-w-[700px] w-full mx-auto">
            <div
                class="absolute inset-0 overflow-hidden rounded-md flex items-center justify-center"
            >
                <div
                    class="bg-gradient-to-r absolute inset-[-20px]  from-violet-800 to-indigo-800 specialSpin"
                />
            </div>

            <img
                src={"images/zetane-engine.jpeg"}
                alt="Zetane Engine"
                class="w-full h-full object-cover z-[2]"
            />
        </div> -->
    </section>
    <div class="flex mt-4 space-x-5 sm:justify-center sm:mt-0">
        <a href="#" class="text-white hover:text-gray-900 dark:hover:text-white">
            <i class="fa-brands fa-react"></i>
            <span class="sr-only">React</span>
        </a>
        <a href="#" class="text-white hover:text-gray-900 dark:hover:text-white">
            <i class="fa-brands fa-node-js"></i>
            <span class="sr-only">Node JS</span>
        </a>
        <a href="#" class="text-white hover:text-gray-900 dark:hover:text-white">
            <i class="fa-brands fa-github"></i>
            <span class="sr-only">GitHub</span>
        </a>
        <a href="#" class="text-white hover:text-gray-900 dark:hover:text-white">
            <svg class="w-4 h-4 text-white dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 14">
                <path d="M9.782.72a4.773 4.773 0 0 0-4.8 4.173 3.43 3.43 0 0 1 2.741-1.687c1.689 0 2.974 1.972 3.758 2.587a5.733 5.733 0 0 0 5.382.935c2-.638 2.934-2.865 3.137-3.921-.969 1.379-2.44 2.207-4.259 1.231C14.488 3.365 13.551.6 9.782.72ZM4.8 6.979A4.772 4.772 0 0 0 0 11.151a3.43 3.43 0 0 1 2.745-1.687c1.689 0 2.974 1.972 3.758 2.587a5.733 5.733 0 0 0 5.382.935c2-.638 2.933-2.865 3.137-3.921-.97 1.379-2.44 2.208-4.259 1.231C9.51 9.623 8.573 6.853 4.8 6.979Z"/>
              </svg>
            <span class="sr-only">Tailwind CSS</span>
        </a>
        <a href="#" class="text-white hover:text-gray-900 dark:hover:text-white">
            <svg class="w-4 h-4 text-white dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 16 20">
                <path d="M8 5.625c4.418 0 8-1.063 8-2.375S12.418.875 8 .875 0 1.938 0 3.25s3.582 2.375 8 2.375Zm0 13.5c4.963 0 8-1.538 8-2.375v-4.019c-.052.029-.112.054-.165.082a8.08 8.08 0 0 1-.745.353c-.193.081-.394.158-.6.231l-.189.067c-2.04.628-4.165.936-6.3.911a20.601 20.601 0 0 1-6.3-.911l-.189-.067a10.719 10.719 0 0 1-.852-.34 8.08 8.08 0 0 1-.493-.244c-.053-.028-.113-.053-.165-.082v4.019C0 17.587 3.037 19.125 8 19.125Zm7.09-12.709c-.193.081-.394.158-.6.231l-.189.067a20.6 20.6 0 0 1-6.3.911 20.6 20.6 0 0 1-6.3-.911l-.189-.067a10.719 10.719 0 0 1-.852-.34 8.08 8.08 0 0 1-.493-.244C.112 6.035.052 6.01 0 5.981V10c0 .837 3.037 2.375 8 2.375s8-1.538 8-2.375V5.981c-.052.029-.112.054-.165.082a8.08 8.08 0 0 1-.745.353Z"/>
              </svg>
            <span class="sr-only">Mongo DB</span>
        </a>
    </div>
    <section class="py-20 lg:py-32 flex flex-col gap-24" id="projects">
        <div class="flex flex-col gap-2 text-center">
            <h6 class="text-large sm:text-xl md:text-2xl">
                A few of my creative endeavors.
            </h6>
            <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
                Curious to <span class="poppins text-violet-400">see</span> my work?
            </h3>
        </div>
        <div class="grid grid-cols-1 lg:grid-cols-3 gap-12 lg:gap-10">
            <a target="_blank" href="https://github.com/GauravSharmaCode/LiveChatApp-main"><Step step={steps[0]}>
                <p>
                    Experience real-time communication with our live chat app, built with the power of the <strong
                    class="text-violet-400"
                    >MERN Stack</strong
                >  and <strong
                class="text-violet-400"
                >Socket.io</strong
            >. Engage in instant conversations and stay connected with friends, colleagues, or clients. Enjoy seamless and responsive messaging on a platform that brings people together.
         </p>
            </Step> </a>

            <a target="_blank" href="https://sksenterprises.in/"><Step step={steps[1]}>
                <p>
                    Explore SKS Enterprises' online presence, meticulously crafted with <strong class="text-violet-400">Tailwind CSS</strong> for an engaging and user-friendly experience. Powered by <strong class="text-violet-400">Netlify Forms</strong>, our website allows seamless communication and interaction. Discover our business essence, mission, and market value.
                </p>
            </Step></a>
            <a target="_blank" href="https://github.com/GauravSharmaCode/tic-tac-toe"><Step step={steps[2]}>
                <p>
                    Enjoy the classic strategy game reimagined in React. This interactive project, developed with <strong class="text-violet-400"
                        >JavaScript</strong
                    >
                    and
                    <strong class="text-violet-400">React</strong>, that
                    consumes and caches the
                    , lets you compete with a friend for Tic-Tac-Toe victory!!!
                </p>
            </Step></a>
        </div>
    </section>

    <section
    id="about"
    class="py-20 pt-10 lg:pt-16 lg:py-32 flex flex-col gap-16 sm:gap-20 md:gap-24 relative"
>
    <!-- <div class="z-[-1] bg-violet-950 w-screen left-1/2 -translate-x-1/2 top-0 h-full absolute"> </div> -->
    <div
        class="flex flex-col gap-2 text-center relative before:absolute before:top-0 before:left-0 before:w-2/3 before:h-1.5 before:bg-violet-700 after:absolute after:bottom-0 after:right-0 after:w-2/3 after:h-1.5 after:bg-violet-700 py-4"
    >
        <h6 class="text-large sm:text-xl md:text-2xl">
            Want to know more?
        </h6>
        <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
            A bit <span class="poppins text-violet-400">about</span> me.
        </h3>
    </div>
    <p class="mx-auto poppins font-semibold text-lg sm:text-xl md:text-2xl">
        I am . . .
    </p>
    <div class="flex flex-col gap-20 w-full mx-auto max-w-[800px]">
        {#each benefits as benefit, index}
            <!-- <div class="flex flex-col gap-2 mx-auto">
                <div class="flex items-end gap-4">
                    <p
                        class="poppins text-6xl sm:text-7xl md:text-8xl text-slate-500 font-medium"
                    >
                        {benefit.metric}
                    </p>
                    <p
                        class="text-xl sm:text-2xl md:text-3xl capitalize pb-2"
                    >
                        {benefit.name}
                    </p>
                </div>
                <p class="text-center italic">- {benefit.description}</p>
            </div> -->
            <div class="flex gap-6 sm:gap-8">
                <p
                    class="poppins text-4xl sm:text-5xl md:text-6xl text-slate-500 font-semibold"
                >
                    0{index + 1}
                </p>
                <div class="flex flex-col gap-6 sm:gap-8">
                    <h3 class="text-2xl sm:text-3xl md:text-5xl">
                        {benefit.name}
                    </h3>
                    <p>{benefit.description}</p>
                </div>
            </div>
        {/each}
    </div>
    <h5 class={" text-2xl sm:text-3xl font-semibold text-center poppins "}>
        The <span class="text-violet-400">Complete</span> Package
    </h5>
    <div
        class="flex flex-col overflow-x-scroll gap-10 max-w-[800px] mx-auto w-full"
    >
        <table class="bg-white text-slate-700 rounded text-center">
            <thead class={"border-b border-solid border-slate-200  "}>
                <tr class="">
                    <th />
                    <th class="whitespace-nowrap p-2 px-4">Candidate #1</th>
                    <th class="whitespace-nowrap p-2 px-4">Candidate #2</th>
                    <th class="whitespace-nowrap p-2 px-4">Candidate #3</th>
                    <th
                        class="bg-violet-700 text-white whitespace-nowrap p-4 px-8"
                        >Me</th
                    >
                </tr>
            </thead>
            <tbody>
                <tr class="border-b border-solid border-slate-200">
                    <td
                        class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                        >Dedication</td
                    >
                    <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                    <td><i class="fa-solid fa-check text-slate-500" /></td>
                    <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                    <td><i class="fa-solid fa-check text-green-500" /></td>
                </tr>
                <tr class="border-b border-solid border-slate-200">
                    <td
                        class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                        >Critical Thought</td
                    >
                    <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                    <td><i class="fa-solid fa-check text-slate-500" /></td>
                    <td><i class="fa-solid fa-check text-slate-500" /></td>
                    <td><i class="fa-solid fa-check text-green-500" /></td>
                </tr>
                <tr>
                    <td
                        class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                        >Interpersonal Skills</td
                    >
                    <td><i class="fa-solid fa-check text-slate-500" /></td>
                    <td><i class="fa-solid fa-check text-slate-500" /></td>
                    <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                    <td><i class="fa-solid fa-check text-green-500" /></td>
                </tr>
                <tr class="border-t border-solid border-slate-200">
                    <td
                        class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                        >Progamming Ability</td
                    >
                    <td><i class="fa-solid fa-check text-slate-500" /></td>
                    <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                    <td><i class="fa-solid fa-check text-slate-500" /></td>
                    <td><i class="fa-solid fa-check text-green-500" /></td>
                </tr>
            </tbody>
        </table>
    </div>
    <div class="mx-auto -mt-12 italic sm:hidden opacity-50">
        <p>Scroll to see more &rarr;</p>
    </div>
    <p class="mx-auto">So why not invest?</p>
</section>
</main>