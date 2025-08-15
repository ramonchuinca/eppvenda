<template>
<div class="max-w-4xl mx-auto p-6 text-center">
    <h1 class="text-3xl font-semibold mb-6 text-white">Bem Vindo página do Drive</h1>

    <div class="space-y-10 text-gray-700 dark:text-gray-300 text-lg leading-relaxed">

        <!-- Slide 1 -->
        <div>
            <img src="@/assets/img/primeiro-12.png" alt="Tela de abertura com título Google Authenticator" class="rounded-xl shadow-lg mb-4">
            <p>🎥 <strong>Slide 1 – Abertura:</strong> "Como baixar e instalar o Google Authenticator no celular".<br>
            <em>Sugestão de narração:</em> Hoje você vai aprender a instalar o Google Authenticator no seu celular de forma rápida e segura.</p>
        </div>

        <!-- Slide 2 -->
        <div>
            <img src="/" alt="Abrindo a Google Play Store ou App Store" class="rounded-xl shadow-lg mb-4">
            <p><strong>Slide 2 – Abrir a loja de aplicativos:</strong> Passo 1: Abra a loja de aplicativos do seu celular (Google Play Store no Android ou App Store no iPhone).<br>
            <em>Sugestão de narração:</em> O primeiro passo é abrir a loja de aplicativos. No Android é a Google Play Store, e no iPhone é a App Store.</p>
        </div>

        <!-- Slide 3 -->
        <div>
            <img src="link-da-imagem-slide3.png" alt="Pesquisando Google Authenticator na loja" class="rounded-xl shadow-lg mb-4">
            <p><strong>Slide 3 – Pesquisar pelo app:</strong> Passo 2: Pesquise por "Google Authenticator".<br>
            <em>Sugestão de narração:</em> Digite Google Authenticator na busca e localize o aplicativo oficial do Google.</p>
        </div>

        <!-- Slide 4 -->
        <div>
            <img src="link-da-imagem-slide4.png" alt="Botão Instalar ou Obter do Google Authenticator" class="rounded-xl shadow-lg mb-4">
            <p><strong>Slide 4 – Instalar:</strong> Passo 3: Toque em Instalar (Android) ou Obter (iPhone) e aguarde o download.<br>
            <em>Sugestão de narração:</em> Clique no botão Instalar e aguarde até o aplicativo ser baixado e instalado.</p>
        </div>

        <!-- Slide 5 -->
        <div>
            <img src="link-da-imagem-slide5.png" alt="Tela inicial do Google Authenticator" class="rounded-xl shadow-lg mb-4">
            <p><strong>Slide 5 – Abrir o app:</strong> Passo 4: Abra o aplicativo e siga as instruções para configurar.<br>
            <em>Sugestão de narração:</em> Depois que a instalação terminar, abra o aplicativo e siga as orientações para adicionar suas contas.</p>
        </div>

        <!-- Slide 6 -->
        <div>
            <img src="link-da-imagem-slide6.png" alt="Ícone de segurança e alerta" class="rounded-xl shadow-lg mb-4">
            <p><strong>Slide 6 – Dica de segurança:</strong> ⚠ Baixe apenas da loja oficial para evitar riscos.<br>
            <em>Sugestão de narração:</em> Lembre-se: baixe sempre o aplicativo da loja oficial para evitar apps falsos.</p>
        </div>

    </div>








    <div class="flex justify-center gap-4">
      <!-- Botão Anterior -->
      <router-link
        to="/component/alert"
        class="inline-block bg-gray-500 hover:bg-gray-600 text-white font-medium py-2 px-8 rounded-full transition duration-300"
        title="Voltar para a etapa anterior"
      >
         Anterior
      </router-link>

      <!-- Botão Próximo -->
      <router-link
        to="/component/accordion"
        class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-medium py-2 px-8 rounded-full transition duration-300"
        title="Ir para a próxima etapa"
      >
        Próximo 
      </router-link>
    </div>
  </div>
</template>
