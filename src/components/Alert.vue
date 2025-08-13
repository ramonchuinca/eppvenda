<template>
  <div class="max-w-4xl mx-auto p-6 text-center">
    <h1 class="text-3xl font-semibold mb-6">Bem-vindo à Tela de Login</h1>

    <img 
      src="../assets/img/teste.jpeg" 
      alt="Ilustração do Login" 
      class="w-full h-auto rounded-lg shadow-md mb-8 object-cover"
    />

   <!-- <p class="text-gray-700 dark:text-gray-300 mb-8 text-lg leading-relaxed">
  Para acessar o sistema, informe seu <strong>e-mail</strong> e <strong>senha</strong> cadastrados. 
  Esta tela foi criada para ser simples, segura e fácil de usar, garantindo uma experiência tranquila para todos os usuários.
  Após o login, você será direcionado para uma <strong>segunda etapa de autenticação</strong>, onde confirmaremos que está tudo certo com suas informações antes de liberar o acesso completo ao sistema.
</p> -->

<ul class="text-gray-700 dark:text-gray-300 space-y-4 text-base leading-relaxed">
  <li>📨 <strong>Informe suas credenciais:</strong> Digite o e-mail que você cadastrou no sistema e insira sua senha de acesso.</li>
  <li>🔒 <strong>Faça login com segurança:</strong> Após confirmar seus dados, clique no botão <em>"Entrar"</em>.</li>
  <li>🔑 <strong>Autenticação em duas etapas (2FA):</strong> Assim que o login for realizado com sucesso, você será direcionado para a segunda etapa de autenticação.</li>
 <li>
  📲 <strong>Confirme o código no Authenticator:</strong> 
  Abra seu aplicativo Authenticator 
  (<a href="https://support.google.com/accounts/answer/1066447?hl=pt-BR" target="_blank" class="text-blue-600 hover:underline dark:text-blue-400">
    veja como baixar o Google Authenticator
  </a> ou 
  <a href="https://support.microsoft.com/pt-br/account-billing/baixar-e-instalar-o-aplicativo-microsoft-authenticator-351498fc-850a-45da-b7b6-27e523b8702a" target="_blank" class="text-blue-600 hover:underline dark:text-blue-400">
    Microsoft Authenticator
  </a>), localize o código de 6 dígitos e digite-o no campo solicitado.
</li>

  <li>🚀 <strong>Acesso liberado:</strong> Após a validação do código, o sistema verificará que tudo está correto e você terá acesso completo às funcionalidades disponíveis.</li>
</ul>


    <router-link
      to="/component/autenticator"
      class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-medium py-2 px-8 rounded-full transition duration-300"
      title="Ir para a próxima etapa"
    >
      Próximo ➤
    </router-link>
  </div>
</template>



<script>


</script>

<style scoped>
/* Personalize como quiser */
</style>
