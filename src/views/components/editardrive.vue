<template>
  <div class="max-w-4xl mx-auto p-6 text-center">
    <h1 class="text-3xl font-semibold mb-6 text-white">Bem Vindo  pagina do Drive</h1>

    <img 
      src="@/assets/img/teladrive2.jpeg" 
      alt="Ilustração do Login" 
      class="w-full h-auto rounded-lg shadow-md mb-8 object-cover"
    />

 <div class="text-gray-700 dark:text-gray-300 mb-8 text-lg leading-relaxed">
  ✏️ <strong>Como editar arquivos no Drive do sistema</strong>
  <ul class="list-none mt-4 space-y-3">
    <li>
      <span class="mr-2">1️⃣</span>
      <strong>Acesse o módulo "Drive":</strong> No menu lateral, clique em <strong>Drive</strong> (ícone de pasta roxa) e localize o arquivo que deseja editar.
    </li>
    <li>
      <span class="mr-2">2️⃣</span>
      <strong>Encontre o arquivo desejado:</strong> Use a barra de pesquisa ou navegue pelas pastas até localizar o arquivo.
    </li>
    <li>
      <span class="mr-2">3️⃣</span>
      <strong>Abra o menu de ações:</strong> Passe o mouse sobre o arquivo ou clique no ícone de opções (⋮ ou ⚙️) ao lado dele.
    </li>
    <li>
      <span class="mr-2">4️⃣</span>
      <strong>Selecione "Editar":</strong> Escolha a opção <em>Editar</em> para modificar o conteúdo ou as informações do arquivo.
    </li>
    <li>
      <span class="mr-2">5️⃣</span>
      <strong>Faça as alterações necessárias:</strong> Dependendo do tipo de arquivo, você poderá alterar o nome, descrição, conteúdo ou mover para outra pasta.
    </li>
    <li>
      <span class="mr-2">6️⃣</span>
      <strong>Salve as alterações:</strong> Após editar, clique em <em>Salvar</em> ou <em>Confirmar</em> para registrar as mudanças.
    </li>
    <li>
      <span class="mr-2">7️⃣</span>
      <strong>Verifique o resultado:</strong> Confira se o arquivo foi atualizado corretamente e está na pasta desejada.
    </li>
  </ul>
</div>


    
        <div class="flex justify-center gap-4">
      <!-- Botão Anterior -->
      <router-link
        to="/component/uploaddrive"
        class="inline-block bg-gray-500 hover:bg-gray-600 text-white font-medium py-2 px-8 rounded-full transition duration-300"
        title="Voltar para a etapa anterior"
      >
         Anterior
      </router-link>

    <router-link
      to="/component/subirarquivo"
      class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-medium py-2 px-8 rounded-full transition duration-300"
      title="Ir para a próxima etapa"
    >
      Próximo 
    </router-link>
    </div>
  </div>
</template>