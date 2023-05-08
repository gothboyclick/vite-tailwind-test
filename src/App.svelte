<script>
  import svelteLogo from './assets/svelte.svg'
  import viteLogo from '/vite.svg'
  import Counter from './lib/Counter.svelte'
  import "./app.css";
</script>

<main>
  <nav class="bg-gray-800 shadow">
  <div class="container m-auto flex justify-between items-center text-white-700">
    <span class="pl-8 py-4 text-xl font-bold cursor-pointer">
      <img href="./assets/samurai.png" class="inline object-scale-down h-12 w-12" src="./assets/samurai.png"/>
      Luta do Vale
    </span>
    <ul class="hidden md:flex items-center pr-10 text-base font-semibold cursor-pointer">
      <li class ="hover:bg-green-200 py-4 px-6 rounded duration-300">Home</li>
      <li class ="hover:bg-red-200 py-4 px-6 rounded duration-700">Contato</li>
      <li class ="hover:bg-green-200 py-4 px-6 rounded duration-500">Sobre</li>
    </ul>
    <button class="block md:hidden py-3 px-4 mx-2 rounded focus:outline-none hover:bg-blue-200 group">
    <div class="w-5 h-1 bg-green-600 mb-1"></div>
    <div class="w-5 h-1 bg-red-600 mb-1"></div>
    <div class="w-5 h-1 bg-green-600 mb-1"></div>
    <div class="absolute top-0 -right-full h-screen w-8/12 bg-purple-400 border opacity-0 transform group-focus:right-0 group-focus:opacity-100 transition-all duration-700">
      <ul class="flex flex-col items-center w-full text-base pt-10">
        <li class ="hover:bg-blue-200 py-4 px-6 duration-300 rounded">Home</li>
        <li class ="hover:bg-pink-200 py-4 px-6 duration-300 rounded">Contato</li>
        <li class ="hover:bg-blue-200 py-4 px-6 duration-300 rounded">Sobre</li>
      </ul>
    </div>
    </button>
  </div>
  </nav>
  <section class="m-20 px-4 "></section>
  <div class="max-w-md grid grid-cols-2 grid-flow-col auto-cols-max relative left-32 w-80 p-8 border bg-red-300 columns-2 gap-4">
    <a class="flexabsolute justify-center bg-green-200 col-span-1 border rounded drop-shadow-xl" href="https://vitejs.dev" target="_blank" rel="noreferrer">
      <img src={viteLogo} class="p-3 logo" alt="Vite Logo" />
    </a>
    
    <a class="flexabsolute justify-center bg-blue-200 col-span-2 border rounded drop-shadow-xl" href="https://svelte.dev" target="_blank" rel="noreferrer">
        <img src={svelteLogo} class="p-3 logo drop-shadow-lg svelte" alt="Svelte Logo" />
      </a>
  </div>
  <div class="w-full border">
    <nav class="c"></nav>
  </div>
  <div class="inset-x-0 bottom-0 border">
    <div class="bg-blue-400 border">
      <Counter />
    </div>
  </div>
</main>
  <div class="w-full flex mx-auto  bg-red-400 mb-0 pb-0">
    <navbar class=" rounded-xl">aaaaaa</navbar>
  </div>