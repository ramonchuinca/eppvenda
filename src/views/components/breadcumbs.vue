<template>
  <div class="max-w-4xl mx-auto p-6 text-center">
    <h1 class="text-3xl font-semibold mb-6 text-white">Bem Vindo  pagina do Drive</h1>

    <img 
      src="@/assets/img/teladrive2.jpeg" 
      alt="Ilustração do Login" 
      class="w-full h-auto rounded-lg shadow-md mb-8 object-cover"
    />

   <p class="text-gray-700 dark:text-gray-300 mb-8 text-lg leading-relaxed">
  📁 <strong>Aba "Drive" – Como Funciona</strong><br>
  A aba Drive é o local onde você pode <strong>armazenar, visualizar e organizar</strong> seus arquivos e pastas dentro do sistema Pen6.App.
  <br><br>
  ✅ <strong>O que você pode fazer aqui:</strong><br>
  📂 Criar pastas para separar e organizar documentos por tema, projeto ou cliente.<br>
  📄 Visualizar arquivos que foram enviados para o sistema.<br>
  🔍 Pesquisar por arquivos rapidamente.<br>
  📥 Fazer upload de novos arquivos (dependendo das permissões).<br>
  📑 Ver detalhes como nome, tipo de arquivo e quem adicionou.
</p>

    <router-link
      to="/component/uploaddrive"
      class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-medium py-2 px-8 rounded-full transition duration-300"
      title="Ir para a próxima etapa"
    >
      Próximo ➤
    </router-link>
  </div>
</template>