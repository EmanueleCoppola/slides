---
layout: center
class: text-left
title: "Ma cosa c'è dietro a tutto questo?"
---

## 💻 Cosa c'è dietro a un sito web?

<div class="grid grid-cols-3 gap-8 mt-10 text-center">

<!-- Colonna 1: HTML -->
<div v-click>
  <h3 class="text-2xl font-bold text-blue-500 mb-3">HTML</h3>
  <p class="text-lg">
    È il linguaggio di struttura di un sito web.<br>
    Definisce cosa compare nella pagina: testi, immagini, titoli, link, sezioni...
  </p>
  <div class="mt-4 bg-gray-800 text-gray-100 text-left p-3 rounded-lg text-sm font-mono">
    <code>&lt;h1&gt;Ciao mondo!&lt;/h1&gt;<br>&lt;p&gt;Benvenuto nel mio sito.&lt;/p&gt;</code>
  </div>
</div>

<!-- Colonna 2: CSS -->
<div v-click>
  <h3 class="text-2xl font-bold text-pink-500 mb-3">CSS</h3>
  <p class="text-lg">
    È il linguaggio di stile.<br>
    Decide come la pagina appare: colori, spazi, font e disposizione degli elementi.
  </p>
  <div class="mt-4 bg-gray-800 text-gray-100 text-left p-3 rounded-lg text-sm font-mono">
    <code>h1 { color: coral; }<br>p { font-size: 18px; }</code>
  </div>
</div>

<!-- Colonna 3: JavaScript -->
<div v-click>
  <h3 class="text-2xl font-bold text-yellow-400 mb-3">JavaScript</h3>
  <p class="text-lg">
    È il linguaggio di comportamento.<br>
    Rende la pagina interattiva: pulsanti che reagiscono, animazioni, moduli dinamici.
  </p>
  <div class="mt-4 bg-gray-800 text-gray-100 text-left p-3 rounded-lg text-sm font-mono">
    <code>document.querySelector('h1')<br>  .addEventListener('click', () =&gt; alert('Ciao!'));</code>
  </div>
</div>

</div>

<div v-click class="mt-10 text-gray-400 italic text-lg text-center">
💡 Insieme, HTML, CSS e JavaScript sono le tre fondamenta del web.<br>
L’HTML dà la struttura, il CSS lo stile, e JavaScript la vita.
</div>
