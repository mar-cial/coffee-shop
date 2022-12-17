<script>
    import FaHome from 'svelte-icons/fa/FaHome.svelte'
</script>

<header class="flex px-12 pt-12">
    <div class="text-sm w-10 h-10">
        <a href="/" ><FaHome /></a>
    </div>
</header>

<main class="p-12 break-words font-mono">
    <h1 class="text-7xl flex-wrap">Zarmondwond Cafe</h1>
</main>

<section class="p-12 flex flex-col gap-4">
    <header>
        <h2 class="font-mono">No hay tiempo pa cotorrear. Solo cafe.</h2>
    </header>

    <div class="grid gap-4 lg:grid-cols-3">
        <div class="border rounded-md">
            <a href="/products" class="w-full h-full flex flex-col p-6 gap-2 justify-center items-center">
                Products
            </a>
        </div>
        <div class="border rounded-md ">
            <a href="/orders" class="w-full h-full flex flex-col p-6 gap-2 justify-center items-center">
                Orders
            </a>
        </div>
        <div class="border rounded-md ">
            <a href="/you" class="w-full h-full flex flex-col p-6 gap-2 justify-center items-center">
                You
            </a>
        </div>
    </div>
</section>