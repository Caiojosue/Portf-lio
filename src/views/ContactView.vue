<template>
  <div class="max-w-5xl mx-auto px-6 py-10 space-y-16">
    
    <section id="contato" class="space-y-8">
      <h2 class="text-4xl font-extrabold text-rose-600">Contato</h2>
      <form class="space-y-6 bg-white shadow-lg rounded-lg p-6">
        <div>
          <label class="block mb-2 text-lg font-medium text-gray-700" for="name">Nome</label>
          <input id="name" type="text" placeholder="Seu nome"
            class="w-full border border-gray-300 rounded-lg px-4 py-3 focus:outline-none focus:ring-2 focus:ring-rose-500 focus:border-transparent transition"/>
        </div>
        <div>
          <label class="block mb-2 text-lg font-medium text-gray-700" for="email">Email</label>
          <input id="email" type="email" placeholder="seu@email.com"
            class="w-full border border-gray-300 rounded-lg px-4 py-3 focus:outline-none focus:ring-2 focus:ring-rose-500 focus:border-transparent transition"/>
        </div>
        <div>
          <label class="block mb-2 text-lg font-medium text-gray-700" for="message">Mensagem</label>
          <textarea id="message" rows="5" placeholder="Escreva sua mensagem"
            class="w-full border border-gray-300 rounded-lg px-4 py-3 focus:outline-none focus:ring-2 focus:ring-rose-500 focus:border-transparent transition"></textarea>
        </div>
        <button type="submit" disabled
          class="w-full bg-rose-500 text-white px-6 py-3 rounded-lg cursor-not-allowed opacity-50">
          Enviar (não funcional)
        </button>
      </form>

      <div class="pt-6">
        <h3 class="text-2xl font-semibold mb-4 text-rose-600">Redes Sociais</h3>
        <ul class="flex space-x-8">
          <li><a href="https://www.linkedin.com/in/caio-sando-14ba1a2b5/" target="_blank"
            class="hover:text-rose-600 hover:underline transition">LinkedIn</a></li>
          <li><a href="https://github.com/Caiojosue" target="_blank"
            class="hover:text-rose-600 hover:underline transition">GitHub</a></li>
          <li><a href="https://www.instagram.com/caio_sandoo/" target="_blank"
            class="hover:text-rose-600 hover:underline transition">Instagram</a></li>
        </ul>
      </div>
    </section>

    <section id="projetos" class="space-y-6">
      <h2 class="text-4xl font-extrabold text-rose-600">Lista de Projetos</h2>
      <ul class="list-disc list-inside space-y-4 bg-white shadow-lg rounded-lg p-6">
        <li><strong>Projeto Principal:</strong> Agente de Análise de Dados com IA</li>
        <li><strong>Projeto Secundário:</strong> Aplicativo de fechamento da bolsa de valores com IA</li>
        <li><strong>Projeto para praticar:</strong> Sistema de carteira financeira com SQL</li>
      </ul>
    </section>

    <section id="timeline" class="space-y-8">
      <h2 class="text-4xl font-extrabold text-rose-600">Timeline de Carreira e Formação</h2>
      <div class="border-l-4 border-rose-500 pl-10 space-y-10 relative">
        
        <div class="relative">
          <div class="absolute -left-8 top-1 w-6 h-6 rounded-full bg-rose-500 border-4 border-gray-200"></div>
          <p class="text-lg font-semibold">2021 - 2025</p>
          <p class="italic">Técnico de Celulares e Vendedor</p>
          <p>Atuei por 4 anos no camelódromo, realizando manutenção e vendas de celulares</p>
        </div>

        <div class="relative">
          <div class="absolute -left-8 top-1 w-6 h-6 rounded-full bg-rose-500 border-4 border-gray-200"></div>
          <p class="text-lg font-semibold">2025 (Atual)</p>
          <p class="italic">Estagiário em Ciência de Dados - Banco Itaú</p>
          <p>Atualmente trabalho com Python, SQL e projetos envolvendo IA, desenvolvendo minhas habilidades diariamente</p>
        </div>

      </div>
    </section>

  </div>
</template>
