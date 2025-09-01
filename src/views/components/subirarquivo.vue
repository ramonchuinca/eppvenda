<template>
  <div class="max-w-4xl mx-auto p-6 text-center">
    <h1 class="text-3xl font-semibold mb-6 text-gray-700">Bem Vindo a Como Subir Arquivo no Drive</h1>

    <img 
      src="@/assets/img/teladrive2.jpeg" 
      alt="Ilustração do Login" 
      class="w-full h-auto rounded-lg shadow-md mb-8 object-cover"
    />

<div class="text-gray-700 dark:text-gray-300 mb-8 text-lg leading-relaxed">
  📂 <strong>Como subir (fazer upload) de um arquivo no Drive do sistema</strong>
  <ul class="list-none mt-4 space-y-3">
    <li>
      <span class="mr-2">1️⃣</span>
      <strong>Acesse o módulo "Drive":</strong> No menu lateral, clique em <strong>Drive</strong> (ícone de pasta roxa).
    </li>
    <li>
      <span class="mr-2">2️⃣</span>
      <strong>Escolha a pasta de destino:</strong> Clique na pasta onde deseja guardar o arquivo (ex.: <em>teste-teste</em>).
    </li>
    <li>
      <span class="mr-2">3️⃣</span>
      <strong>Localize o botão de upload:</strong> Na parte superior direita da tela, procure o botão ou ícone de <em>Upload</em> (geralmente uma seta para cima ou opção “Enviar arquivo”).
    </li>
    <li>
      <span class="mr-2">4️⃣</span>
      <strong>Selecione o arquivo:</strong> Ao clicar no botão de upload, escolha no seu computador o arquivo que deseja enviar e clique em <em>Abrir</em>.
    </li>
    <li>
      <span class="mr-2">5️⃣</span>
      <strong>Acompanhe o envio:</strong> Pode aparecer uma barra de progresso ou mensagem de confirmação. Aguarde até o processo terminar.
    </li>
    <li>
      <span class="mr-2">6️⃣</span>
      <strong>Verifique o resultado:</strong> O arquivo enviado deve aparecer na lista de arquivos da pasta escolhida. Teste abrindo ou baixando para confirmar.
    </li>
  </ul>
</div>


       <div class="flex justify-center gap-4">
      <!-- Botão Anterior -->
      <router-link
        to="/component/editardrive"
        class="inline-block bg-gray-500 hover:bg-gray-600 text-white font-medium py-2 px-8 rounded-full transition duration-300"
        title="Voltar para a etapa anterior"
      >
         Anterior
      </router-link>
    <router-link
      to="/component/badge"
      class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-medium py-2 px-8 rounded-full transition duration-300"
      title="Ir para a próxima etapa"
    >
      Próximo 
    </router-link>
    </div>
  </div>
</template>