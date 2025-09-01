<template>
  <div class="max-w-4xl mx-auto p-6 text-center">
    <h1 class="text-3xl font-semibold mb-6 text-gray-700">Bem-vindo ao Perfil Acesso Externo</h1>

    <img 
      src="@/assets/img/teladeperfil.jpeg" 
      alt="Ilustração do Login" 
      class="w-full h-auto rounded-lg shadow-md mb-8 object-cover"
    />

<p class="text-gray-700 dark:text-gray-300 mb-8 text-lg leading-relaxed">
  Nesta tela você pode <strong>gerenciar seu perfil de usuário</strong> dentro do <strong>Pen6.App</strong>.  
  Aqui estão as principais funções disponíveis:
  <br><br>
  <ul class="list-disc ml-6 space-y-2 text-gray-700 dark:text-gray-300">
    <li>
      <strong>Adicionar ou alterar foto de perfil:</strong> Clique no botão <em>“Adicionar imagem”</em> para enviar uma foto que será exibida no seu perfil.
    </li>
    <li>
      <strong>Editar informações pessoais:</strong> À direita, você encontra seus dados como <em>nome</em>, <em>email</em>, <em>telefone</em>, <em>data de nascimento</em> e <em>CPF</em>.  
      Atualize os campos quando necessário e clique em <strong>Salvar</strong>.
    </li>
    <li>
      <strong>Minha Bio:</strong> Use o editor de texto para escrever uma breve descrição sobre você, suas funções ou habilidades. É possível aplicar formatações (negrito, itálico, alinhamento, etc.).
    </li>
    <li>
      <strong>Alterar senha:</strong> No final da tela, insira uma nova senha no campo indicado e clique em <strong>Confirmar</strong> para atualizar sua senha de acesso ao sistema.
    </li>
    Utilize essa tela sempre que precisar <strong>manter seus dados atualizados</strong> e garantir uma melhor personalização dentro do sistema.
  </ul>
  <br>
</p>



<div class="flex justify-center gap-4">
      <!-- Botão Anterior -->
      <router-link
        to="/component/Dashbord-externo"
        class="inline-block bg-gray-500 hover:bg-gray-600 text-white font-medium py-2 px-8 rounded-full transition duration-300"
        title="Voltar para a etapa anterior"
      >
         Anterior
      </router-link>
    <router-link
      to="/component/Drive-externo"
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
