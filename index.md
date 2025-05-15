<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BazokaBeauty - Distribución de Cosméticos</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100">

    <!-- Hero Section -->
    <header class="relative bg-cover bg-center h-screen text-white flex items-center justify-center" style="background-image: url('https://img.freepik.com/foto-gratis/producto-cosmetico-estetico-ensueno-fondo-fresco_23-2151382880.jpg');">
        <div class="text-center p-6 bg-black bg-opacity-50 rounded-lg">
            <h1 class="text-4xl font-bold">BazokaBeauty</h1>
            <p class="text-lg mt-4">Distribución inteligente y sostenible de productos de belleza</p>
            <a href="#contacto" class="mt-6 inline-block bg-pink-500 text-white px-6 py-3 rounded-full text-lg font-semibold hover:bg-pink-600">Contáctanos</a>
        </div>
    </header>

    <!-- Sobre Nosotros -->
    <section class="py-12 px-6 text-center">
        <h2 class="text-3xl font-bold">¿Por qué BazokaBeauty?</h2>
        <p class="mt-4 text-gray-700">Somos líderes en distribución de productos de belleza en España, con presencia en farmacia, parafarmacia, grandes superficies y perfumería online y offline.</p>
    </section>

    <!-- Imágenes -->
    <section class="grid grid-cols-1 md:grid-cols-2 gap-4 px-6">
        <img src="https://img.freepik.com/foto-gratis/surtido-productos-belleza-exhibidos-estante_23-2150717989.jpg" class="rounded-lg shadow-md">
        <img src="https://img.freepik.com/foto-gratis/retrato-hombre-que-sale-comprar-varios-bienes-consumo_23-2151669822.jpg" class="rounded-lg shadow-md">
        <img src="https://img.freepik.com/foto-gratis/retrato-mujer-que-trabaja-industria-farmaceutica_23-2151684904.jpg" class="rounded-lg shadow-md">
    </section>

    <!-- Formulario de contacto -->
    <section id="contacto" class="py-12 bg-white px-6">
        <h2 class="text-3xl font-bold text-center">Contáctanos</h2>
        <form action="ENDPOINT_DEL_FORMULARIO" method="POST" class="max-w-md mx-auto mt-6">
            <label class="block text-gray-700">Nombre</label>
            <input type="text" name="nombre" class="w-full p-3 border rounded-lg" required>

            <label class="block text-gray-700 mt-4">Correo Electrónico</label>
            <input type="email" name="email" class="w-full p-3 border rounded-lg" required>

            <label class="block text-gray-700 mt-4">Mensaje</label>
            <textarea name="mensaje" class="w-full p-3 border rounded-lg" required></textarea>

            <button type="submit" class="mt-6 bg-pink-500 text-white px-6 py-3 rounded-full text-lg font-semibold hover:bg-pink-600 w-full">Enviar</button>
        </form>
    </section>

    <!-- Footer -->
    <footer class="py-6 bg-gray-800 text-white text-center">
        <p>Contacto: <a href="mailto:bazokabeauty@gmail.com" class="underline">bazokabeauty@gmail.com</a></p>
    </footer>

</body>
</html>
---
title: Welcome to my blog
---

