<template>
    <aside class="2xl:w-[280px] xl:w-[280px] lg:w-[80px] sm:w-[80px] overflow-y-auto fixed flex flex-col overflow-x-hidden flex-start justify-between border-r-[1px] border-r-lowWhite h-screen">
        <div class="flex flex-col items-start justify-center">
            <nuxt-link to="/" class="relative leading-none fill-normalWhite cursor-pointer p-3 text-normalWhite rounded-full hover:bg-lowWhite flex gap-4 items-center text-md transition duration-300">
  <div class="w-12 h-12 rounded-full overflow-hidden flex items-center justify-center">
    <img src="/images/logo.png" class="h-full object-scale-down" alt="profile image">
  </div>
  <span class="2xl:block xl:block lg:hidden sm:hidden">Inforum</span>
</nuxt-link>
<br>
            <nuxt-link to="/explore"
                       class="leading-none fill-normalWhite cursor-pointer p-3 text-normalWhite  rounded-full hover:bg-lowWhite flex gap-4 items-center text-md transition duration-300">
                <svg viewBox="0 0 24 24" class="w-[23px]" aria-hidden="true">
                    <g>
                        <path d="M10.09 3.098L9.72 7h5.99l.39-4.089 1.99.187L17.72 7h3.78v2h-3.97l-.56 6h3.53v2h-3.72l-.38 4.089-1.99-.187.36-3.902H8.78l-.38 4.089-1.99-.187L6.77 17H2.5v-2h4.46l.56-6H3.5V7h4.21l.39-4.089 1.99.187zM14.96 15l.56-6H9.53l-.56 6h5.99z"></path>
                    </g>
                </svg>
                <span class="2xl:block xl:block lg:hidden sm:hidden">Explora</span>
            </nuxt-link>
            <nuxt-link to="/notifications"
                       class="leading-none fill-normalWhite cursor-pointer p-3 text-normalWhite  rounded-full hover:bg-lowWhite px-4 flex gap-4 items-center text-md transition duration-300">
                <svg viewBox="0 0 24 24" class="w-[23px]" aria-hidden="true">
                    <g>
                        <path d="M19.993 9.042C19.48 5.017 16.054 2 11.996 2s-7.49 3.021-7.999 7.051L2.866 18H7.1c.463 2.282 2.481 4 4.9 4s4.437-1.718 4.9-4h4.236l-1.143-8.958zM12 20c-1.306 0-2.417-.835-2.829-2h5.658c-.412 1.165-1.523 2-2.829 2zm-6.866-4l.847-6.698C6.364 6.272 8.941 4 11.996 4s5.627 2.268 6.013 5.295L18.864 16H5.134z"></path>
                    </g>
                </svg>
                <span class="2xl:block xl:block lg:hidden sm:hidden">Notificaciones</span>
            </nuxt-link>
            <nuxt-link to="/"
                       class="leading-none fill-normalWhite cursor-pointer p-3 text-normalWhite  rounded-full hover:bg-lowWhite px-4 flex gap-4 items-center text-md transition duration-300">
                <svg viewBox="0 0 24 24" class="w-[23px]" aria-hidden="true">
                    <g>
                        <path d="M15.704 8.99c.457-.05.891-.17 1.296-.35-.302.45-.685.84-1.125 1.15.004.1.006.19.006.29 0 2.94-2.269 6.32-6.421 6.32-1.274 0-2.46-.37-3.459-1 .177.02.357.03.539.03 1.057 0 2.03-.35 2.803-.95-.988-.02-1.821-.66-2.109-1.54.138.03.28.04.425.04.206 0 .405-.03.595-.08-1.033-.2-1.811-1.1-1.811-2.18v-.03c.305.17.652.27 1.023.28-.606-.4-1.004-1.08-1.004-1.85 0-.4.111-.78.305-1.11 1.113 1.34 2.775 2.22 4.652 2.32-.038-.17-.058-.33-.058-.51 0-1.23 1.01-2.22 2.256-2.22.649 0 1.235.27 1.647.7.514-.1.997-.28 1.433-.54-.168.52-.526.96-.992 1.23zM2 21h15c3.038 0 5.5-2.46 5.5-5.5 0-1.4-.524-2.68-1.385-3.65-.08-.09-.089-.22-.023-.32.574-.87.908-1.91.908-3.03C22 5.46 19.538 3 16.5 3H2v18zM16.5 5C18.433 5 20 6.57 20 8.5c0 1.01-.43 1.93-1.12 2.57-.468.43-.414 1.19.111 1.55.914.63 1.509 1.69 1.509 2.88 0 1.93-1.567 3.5-3.5 3.5H4V5h12.5z"></path>
                    </g>
                </svg>
                <span class="2xl:block xl:block lg:hidden sm:hidden">Plan premium</span>
            </nuxt-link>
            <nuxt-link to="/profile"
                       class="leading-none fill-normalWhite cursor-pointer p-3 text-normalWhite  rounded-full hover:bg-lowWhite px-4 flex gap-4 items-center text-md transition duration-300">
                <svg viewBox="0 0 24 24" class="w-[23px]" aria-hidden="true">
                    <g>
                        <path d="M5.651 19h12.698c-.337-1.8-1.023-3.21-1.945-4.19C15.318 13.65 13.838 13 12 13s-3.317.65-4.404 1.81c-.922.98-1.608 2.39-1.945 4.19zm.486-5.56C7.627 11.85 9.648 11 12 11s4.373.85 5.863 2.44c1.477 1.58 2.366 3.8 2.632 6.46l.11 1.1H3.395l.11-1.1c.266-2.66 1.155-4.88 2.632-6.46zM12 4c-1.105 0-2 .9-2 2s.895 2 2 2 2-.9 2-2-.895-2-2-2zM8 6c0-2.21 1.791-4 4-4s4 1.79 4 4-1.791 4-4 4-4-1.79-4-4z"></path>
                    </g>
                </svg>
                <span class="2xl:block xl:block lg:hidden sm:hidden">Perfil</span>
            </nuxt-link>
            <nuxt-link to="/"
                       class="leading-none fill-normalWhite cursor-pointer p-3 text-normalWhite  rounded-full hover:bg-lowWhite px-4 flex gap-4 items-center text-md transition duration-300">
                <svg viewBox="0 0 24 24" class="w-[23px]" aria-hidden="true">
                    <g>
                        <path d="M3.75 12c0-4.56 3.69-8.25 8.25-8.25s8.25 3.69 8.25 8.25-3.69 8.25-8.25 8.25S3.75 16.56 3.75 12zM12 1.75C6.34 1.75 1.75 6.34 1.75 12S6.34 22.25 12 22.25 22.25 17.66 22.25 12 17.66 1.75 12 1.75zm-4.75 11.5c.69 0 1.25-.56 1.25-1.25s-.56-1.25-1.25-1.25S6 11.31 6 12s.56 1.25 1.25 1.25zm9.5 0c.69 0 1.25-.56 1.25-1.25s-.56-1.25-1.25-1.25-1.25.56-1.25 1.25.56 1.25 1.25 1.25zM13.25 12c0 .69-.56 1.25-1.25 1.25s-1.25-.56-1.25-1.25.56-1.25 1.25-1.25 1.25.56 1.25 1.25z"></path>
                    </g>
                </svg>
                <span class="2xl:block xl:block lg:hidden sm:hidden">Mas</span>
            </nuxt-link>
            <div class="2xl:w-60 xl:w-60 lg:w-auto md:w-auto sm:w-auto mt-2">
                <button class="flex items-center justify-center transition duration-200  bright hover:brightness-90	 leading-none bg-useGreen text-normalWhite font-bold rounded-full 2xl:w-full xl:w-full text-sm  py-[16px] lg:w-12 lg:h-12">
                    <span class="2xl:block xl:block lg:hidden md:hidden sm:hidden">Informa</span>
                    <svg viewBox="0 0 24 24" class="w-[25px] fill-normalWhite 2xl:hidden xl:hidden lg:block md:block sm:block" aria-hidden="true">
                        <g>
                            <path d="M23 3c-6.62-.1-10.38 2.421-13.05 6.03C7.29 12.61 6 17.331 6 22h2c0-1.007.07-2.012.19-3H12c4.1 0 7.48-3.082 7.94-7.054C22.79 10.147 23.17 6.359 23 3zm-7 8h-1.5v2H16c.63-.016 1.2-.08 1.72-.188C16.95 15.24 14.68 17 12 17H8.55c.57-2.512 1.57-4.851 3-6.78 2.16-2.912 5.29-4.911 9.45-5.187C20.95 8.079 19.9 11 16 11zM4 9V6H1V4h3V1h2v3h3v2H6v3H4z"></path>
                        </g>
                    </svg>
                </button>
            </div>
        </div>
        <div tabindex="0"
             class="relative flex items-center group px-3 transition duration-200 cursor-pointer hover:bg-lowWhite rounded-full bottom-2 2xl:left-4 xl:left-4 py-2 2xl:w-11/12 xl:w-11/12 lg:w-16 lg:h-16 sm:h-16 sm:w-16 focus:pointer-events-none ">
            <div class="flex items-center gap-3 w-full">
                <div class="flex items-center justify-center">
                <img class="rounded-full w-9 object-cover " src="/images/gc.jpg"
                     alt="profile image">
                </div>
                <div class="flex flex-col flex-grow items-center 2xl:block xl:block lg:hidden sm:hidden">
                    <span class="text-normalWhite text-sm font-semibold block">Persona promedio</span>
                    <span class="text-lowsWhite font-light text-sm block">@personapromedio</span>
                </div>
                <div class="mr-1 2xl:block xl:block lg:hidden sm:hidden">
                    <svg viewBox="0 0 24 24" class="w-[15px] fill-normalWhite" aria-hidden="true">
                        <g>
                            <path d="M3 12c0-1.1.9-2 2-2s2 .9 2 2-.9 2-2 2-2-.9-2-2zm9 2c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2zm7 0c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2z"></path>
                        </g>
                    </svg>
                </div>
                <div class="absolute right-2 opacity-0 shadow-[rgba(222,222,222,0.6)] shadow-[0_0_7px_0] text-normalWhite py-3 rounded-xl text-sm w-56 bg-black z-100 pointer-events-none group-focus:opacity-100 group-focus:pointer-events-auto bottom-16 ">
                    <div class="relative  flex flex-col py-2 border-t-[0.5px] border-[rgba(222,222,222,0.4)]">
                        <a class="py-2 px-2 cursor-pointer w-full hover:bg-useGray transition duration-200">Agrega una cuenta</a>
                        <a class="py-2 px-2 w-full hover:bg-useGray cursor-pointer transition duration-200">Cerrar sesion</a>
                    </div>
                </div>
            </div>
        </div>
    </aside>
</template>

<script setup>

</script>
