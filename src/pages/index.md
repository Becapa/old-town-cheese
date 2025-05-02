---
layout: ../layouts/BaseLayout.astro
title: "Home"
---

<!-- Hero Section -->
<section class="bg-ironRust text-wheat px-20 py-10 shadow text-center">
  <h2 class="text-4xl text-white font-bold mb-2">The Old Town Cheese Cart is Rolling Out</h2>
  <p class="text-lg mb-4">Find us at local farmers markets and events starting this summer.</p>
  <a href="/contact" class="bg-wheat text-ironRust px-4 py-2 rounded hover:bg-wheat hover:text-forestGreen hover:outline-2 hover:outline-offset-2 hover:outline-forestGreen transition">
    Where to Find Us
  </a>
</section>

<!-- Mobile Cart Feature -->
<section class="px-20 py-10 shadow flex">
  <div class="flex-1/2">
    <h2 class="text-2xl font-semibold text-stone-800 mb-2">Fresh Charcuterie, Served from Our Cart</h3>
    <p class="mb-4 text-stone-700">
      Grab a delicious, ready-to-go charcuterie cup made with seasonal and local ingredients. Perfect for snacking while you shop.
    </p>
    <ul class="list-disc list-inside text-stone-700">
      <li>Saturdays – Riverfront Market</li>
      <li>Sundays – Main Street Market</li>
      <li>Special Events – Follow us on Instagram</li>
    </ul>
  </div>
  <img src="placeholder.jpg" alt="The Old Town Cheese Cart set up under a canopy." class="rounded shadow float-right flex-1/2">
</section>

<!-- Storefront Teaser -->
<section class="bg-wheat p-6 px-50 text-center">
  <h3 class="text-xl text-stone-700 font-semibold mb-2">🏠 Storefront Coming Soon</h3>
  <p class="text-stone-700">We’re working on something special — stay tuned for more news on our future home base.</p>
</section>

<!-- Social Feed Placeholder -->
<section class="mt-12 text-center">
  <h3 class="text-xl text-stone-700 font-semibold mb-4">📸 See What We're Serving</h3>
  <p class="text-stone-700 mb-4">Follow us on Instagram <a href="https://instagram.com/oldtowncheese" class="text-blue-600 underline">@oldtowncheese</a></p>
  <!-- You could embed a feed here or use static preview images -->
  <div class="grid grid-cols-2 md:grid-cols-4 gap-4 px-20">
    <img src="/placeholder1.jpg" alt="Charcuterie" class="rounded shadow" />
    <img src="/placeholder2.jpg" alt="Event" class="rounded shadow" />
    <img src="/placeholder3.jpg" alt="Cup Detail" class="rounded shadow" />
    <img src="/placeholder4.jpg" alt="Cart at Market" class="rounded shadow" />
  </div>
</section>