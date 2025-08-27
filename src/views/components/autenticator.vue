<template>
  <div class="max-w-3xl mx-auto p-6 text-center">
    <h1 class="text-3xl font-semibold mb-6 text-gray-600">
      Bem Vindo página do Authenticator
    </h1>

    <div class="space-y-8">
      <!-- Slide 1 -->
      <div>
        <img
          src="@/assets/img/primeiro-12.png"
          alt="Tela de abertura Google Authenticator"
          class="rounded-xl shadow-lg mx-auto mb-4"
        />
        <p class="text-gray-500">
          🎥 <strong>Passo 1 – Abertura:</strong> "Como baixar e instalar o
          Google Authenticator no celular".<br />
          <em>Sugestão:</em> Hoje você vai aprender a instalar o Google
          Authenticator de forma rápida e segura.
        </p>
      </div>

      <!-- Slide 2 -->
      <div>
        <img
          src="@/assets/img/passo-2.png"
          alt="Abrindo a Google Play Store ou App Store"
          class="rounded-xl shadow-lg mx-auto mb-4"
        />
        <p class="text-gray-500">
          <strong>Passo 2 – Abrir a loja:</strong> Abra a loja de aplicativos do
          seu celular (Google Play Store ou App Store).<br />
          <em>Sugestão:</em> No Android é a Play Store, no iPhone é a App Store.
        </p>
      </div>

      <!-- Slide 3 -->
      <div>
        <img
          src="@/assets/img/passo-3.png"
          alt="Pesquisando Google Authenticator"
          class="rounded-xl shadow-lg mx-auto mb-4"
        />
        <p class="text-gray-500">
          <strong>Passo 3 – Pesquisar:</strong> Procure por "Google
          Authenticator".<br />
          <em>Sugestão:</em> Digite o nome na busca e escolha o app oficial do
          Google.
        </p>
      </div>

      <!-- Slide 4 -->
      <div>
        <img
          src="@/assets/img/passo-4.png"
          alt="Botão Instalar ou Obter"
          class="rounded-xl shadow-lg mx-auto mb-4"
        />
        <p class="text-gray-500">
          <strong>Passo 4 – Instalar:</strong> Toque em Instalar (Android) ou
          Obter (iPhone).<br />
          <em>Sugestão:</em> Aguarde até o aplicativo ser baixado e instalado.
        </p>
      </div>

      <!-- Slide 5 -->
      <div>
        <img
          src="@/assets/img/passo-5.jpg"
          alt="Tela inicial do Google Authenticator"
          class="rounded-xl shadow-lg mx-auto mb-4"
        />
        <p class="text-gray-500">
          <strong>Passo 5 – Abrir o app:</strong> Abra o aplicativo e siga as
          instruções.<br />
          <em>Sugestão:</em> Configure suas contas no app.
        </p>
      </div>

      <!-- Slide 6 -->
      <div>
        <img
          src="@/assets/img/passo-6.png"
          alt="Ícone de segurança"
          class="rounded-xl shadow-lg mx-auto mb-4"
        />
        <p class="text-gray-500">
          <strong>Passo 6 – Segurança:</strong> ⚠ Baixe apenas da loja oficial.<br />
          <em>Sugestão:</em> Evite apps falsos baixando sempre das lojas
          oficiais.
        </p>
      </div>
    </div>

    <!-- Botões de navegação -->
    <div class="flex justify-center gap-4 mt-8">
      <router-link
        to="/component/alert"
        class="inline-block bg-gray-500 hover:bg-gray-600 text-white font-medium py-2 px-8 rounded-full transition duration-300"
      >
        Anterior
      </router-link>

      <router-link
        to="/component/accordion"
        class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-medium py-2 px-8 rounded-full transition duration-300"
      >
        Próximo
      </router-link>
    </div>
  </div>
</template>

<style scoped>

/* Todas as imagens do tutorial (uma abaixo da outra) */
.space-y-8 img {
  width: 100%;
  max-width: 420px;   /* diminui a largura máxima */
  max-height: 350px;  /* limita a altura para não ficar gigante */
  height: auto;       /* mantém proporção */
  object-fit: contain;
  display: block;
  margin: 0 auto;     /* centraliza */
  border-radius: 10px;
}

/* Opcional: em telas menores, ainda mais compacto */
@media (max-width: 420px) {
  .space-y-8 img {
    max-width: 320px;
    max-height: 280px;
  }
}
</style>


