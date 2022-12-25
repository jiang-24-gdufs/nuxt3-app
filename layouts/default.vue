<template>
    <!-- nuxt docs flex layout -->
    <div class="flex flex-col h-screen w-screen">
        <header class="h-16 sticky">
            <div class="mx-auto">
                <Header></Header>
            </div>

        </header>
        <main class="flex flex-1">
            <aside class="w-12">
                <Nav></Nav>
            </aside>
            <section class="flex-1">
                <slot />
            </section>
            <aside class="w-12">aside</aside>
        </main>
        <footer class="h-16">
            <div class="mx-auto">
                <Footer></Footer>
            </div>
        </footer>

    </div>
</template>
  
<script setup lang="ts">
</script>

<style>
header {}

footer {}
</style>
