<template>
  <div class="max-w-4xl mx-auto p-6 text-center text-gray-700">
    <h1 class="text-3xl font-semibold mb-6">Bem-vindo à Tela de Dashboard Externo</h1>

    <img 
      src="@/assets/img/prestador.png" 
      alt="Ilustração do Login" 
      class="w-full h-auto rounded-lg shadow-md mb-8 object-cover"
    />

    <p class="text-gray-700 dark:text-gray-300 mb-8 text-lg leading-relaxed">
  Esta é a <strong>Tela de Acesso Exclusiva para Prestadores de Serviço</strong> da plataforma Pen6. Aqui, você poderá acompanhar arquivos, orçamentos e conteúdos disponibilizados diretamente pela nossa equipe.
  <br /><br />
  Para continuar, informe seu <strong>e-mail</strong> e <strong>senha</strong> cadastrados. Em seguida, você passará por uma <strong>etapa de verificação de segurança</strong> para confirmar sua identidade, garantindo a proteção das informações acessadas.
  <br /><br />
  Nosso objetivo é oferecer uma interface simples, intuitiva e segura — facilitando sua navegação e interação com os recursos disponíveis no sistema.
</p>


     <div class="flex justify-center gap-4">
      <!-- Botão Anterior -->
      <router-link
        to="/component/modal"
        class="inline-block bg-gray-500 hover:bg-gray-600 text-white font-medium py-2 px-8 rounded-full transition duration-300"
        title="Voltar para a etapa anterior"
      >
         Anterior
      </router-link>
    <router-link
      to="/component/Dashbord-externo"
      class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-medium py-2 px-8 rounded-full transition duration-300"
      title="Ir para a próxima etapa"
    >
      Próximo 
    </router-link>
    </div>
  </div>
</template>
