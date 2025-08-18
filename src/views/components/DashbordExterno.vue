<template>
  <div class="max-w-4xl mx-auto p-6 text-center">
    <h1 class="text-3xl font-semibold mb-6 text-white">Bem-vindo ao DashBord</h1>

    <img 
      src="@/assets/img/prestador.png" 
      alt="Ilustração do Login" 
      class="w-full h-auto rounded-lg shadow-md mb-8 object-cover"
    />

   <p class="text-gray-700 dark:text-gray-300 mb-8 text-lg leading-relaxed">
  Seja bem-vindo ao <strong>Pen6.App</strong>, um sistema completo desenvolvido para facilitar a gestão da sua empresa.  
  Aqui, você encontra funcionalidades essenciais como controle de <strong>empresas</strong>, <strong>usuários</strong>, <strong>orçamentos</strong>, <strong>faturas</strong>, além de ferramentas para 
  <strong>tarefas</strong>, <strong>scrum diário</strong>, <strong>chat interno</strong>, <strong>drive de arquivos</strong> e muito mais.
  <br><br>
  Navegue pelo menu lateral para acessar os módulos disponíveis e otimize sua rotina com agilidade e segurança.  
  O sistema foi pensado para ser intuitivo, com uma interface simples e moderna, garantindo uma ótima experiência desde o primeiro acesso.
</p>


 <div class="flex justify-center gap-4">
      <!-- Botão Anterior -->
      <router-link
        to="/blank"
        class="inline-block bg-gray-500 hover:bg-gray-600 text-white font-medium py-2 px-8 rounded-full transition duration-300"
        title="Voltar para a etapa anterior"
      >
         Anterior
      </router-link>
    <router-link
      to="/component/Perfil-externo"
      class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-medium py-2 px-8 rounded-full transition duration-300"
      title="Ir para a próxima etapa"
    >
      Próximo 
    </router-link>
    </div>
  </div>
</template>

<script>
  export default {};
</script>
