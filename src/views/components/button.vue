<template>
  <div class="max-w-4xl mx-auto p-6 text-center text-white">
    <h1 class="text-3xl font-semibold mb-6">Bem-vindo à Tela de perfil</h1>

    <img 
      src="@/assets/img/teladeperfil.jpeg" 
      alt="Ilustração do Login" 
      class="w-full h-auto rounded-lg shadow-md mb-8 object-cover"
    />

   <p class="text-gray-700 dark:text-gray-300 mb-8 text-lg leading-relaxed">
  A aba <strong>Meu Perfil</strong> permite que você personalize e mantenha suas informações sempre atualizadas dentro do sistema Pen6.App.
  Aqui você pode <strong>editar seus dados pessoais</strong>, como nome, telefone, data de nascimento e CPF, além de incluir uma imagem de perfil para melhor identificação dentro da plataforma.
  <br><br>
  Também é possível preencher sua <strong>bio profissional</strong>, destacando suas habilidades ou função, utilizando uma área de texto com opções de formatação.
  <br><br>
  Se desejar mais segurança, você pode <strong>alterar sua senha</strong> diretamente nesta tela, garantindo total controle sobre o seu acesso ao sistema.
  <br><br>
  Tudo foi pensado para oferecer uma experiência intuitiva, rápida e segura, permitindo que você gerencie seus dados com facilidade.
</p>


    <router-link
      to="/component/card"
      class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-medium py-2 px-8 rounded-full transition duration-300"
      title="Ir para a próxima etapa"
    >
      Próximo ➤
    </router-link>
  </div>
</template>