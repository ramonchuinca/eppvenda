<template>
  <div class="max-w-4xl mx-auto p-6 text-center">
    <h1 class="text-3xl font-semibold mb-6 text-gray-600">Bem Vindo  a Como Fazer Upload do Drive</h1>

    <img 
      src="@/assets/img/teladrive2.jpeg" 
      alt="Ilustração do Login" 
      class="w-full h-auto rounded-lg shadow-md mb-8 object-cover"
    />

 <div class="text-gray-700 dark:text-gray-300 mb-8 text-lg leading-relaxed">
  📂 <strong>Como fazer upload de arquivo no Drive do sistema</strong>
  <ul class="list-none mt-4 space-y-3">
    <li>
      <span class="mr-2">1️⃣</span>
      <strong>Acesse o módulo "Drive":</strong> No menu lateral, clique em <strong>Drive</strong> (ícone de pasta roxa). Você já está nessa tela, então pode continuar.
    </li>
    <li>
      <span class="mr-2">2️⃣</span>
      <strong>Localize o botão ou ícone de upload:</strong> Pode estar na parte superior direita da área do Drive ou dentro da pasta onde deseja subir o arquivo. Geralmente tem o texto <em>"Enviar arquivo"</em>, <em>"Upload"</em> ou um ícone de seta para cima.
    </li>
    <li>
      <span class="mr-2">3️⃣</span>
      <strong>Escolha o local antes de enviar:</strong> Clique na pasta de destino antes de fazer o upload para que o arquivo seja armazenado no local correto.
    </li>
    <li>
      <span class="mr-2">4️⃣</span>
      <strong>Selecione o arquivo:</strong> Ao clicar no botão de upload, selecione o arquivo no seu computador e clique em <em>Abrir</em>.
    </li>
    <li>
      <span class="mr-2">5️⃣</span>
      <strong>Aguarde o envio:</strong> Pode aparecer uma barra de progresso ou uma mensagem de sucesso. Assim que terminar, o arquivo aparecerá na lista.
    </li>
    <li>
      <span class="mr-2">6️⃣</span>
      <strong>Confirme se o arquivo está visível:</strong> Verifique se ele aparece no local certo e se consegue abrir ou baixar.
    </li>
  </ul>
</div>

        <div class="flex justify-center gap-4">
      <!-- Botão Anterior -->
      <router-link
        to="/component/breadcumb"
        class="inline-block bg-gray-500 hover:bg-gray-600 text-white font-medium py-2 px-8 rounded-full transition duration-300"
        title="Voltar para a etapa anterior"
      >
         Anterior
      </router-link>
    <router-link
      to="/component/editardrive"
      class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-medium py-2 px-8 rounded-full transition duration-300"
      title="Ir para a próxima etapa"
    >
      Próximo 
    </router-link>
    </div>
  </div>
</template>