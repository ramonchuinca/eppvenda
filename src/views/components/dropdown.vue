<template>
  <div class="max-w-4xl mx-auto p-6 text-center text-white">
    <h1 class="text-3xl font-semibold mb-6">Bem-vindo à Tela de Plano de Midia</h1>

    <img 
      src="@/assets/img/planomidia.jpeg" 
      alt="Ilustração do Login" 
      class="w-full h-auto rounded-lg shadow-md mb-8 object-cover"
    />

  <p class="text-gray-700 dark:text-gray-300 mb-8 text-lg leading-relaxed">
  A aba <strong>Planos Mídia</strong> é o espaço dedicado à criação, organização e acompanhamento dos planos de mídia desenvolvidos dentro do sistema Pen6.App.
  <br><br>
  Aqui você pode cadastrar novos planos de mídia contendo todas as informações relevantes para campanhas e veiculações, como veículos, formatos, prazos, valores e observações específicas. Essa área facilita o <strong>planejamento estratégico</strong> e a <strong>visualização centralizada</strong> das ações planejadas.
  <br><br>
  Ao selecionar um plano, você poderá acompanhar os detalhes estruturados por período, tipo de mídia ou cliente, tornando o processo de revisão e aprovação mais ágil e eficiente.
  <br><br>
  Tudo foi pensado para oferecer <strong>clareza, controle e agilidade</strong> no gerenciamento de campanhas, facilitando o trabalho entre equipes de marketing, atendimento e mídia.
</p>


    <router-link
      to="/component/modal"
      class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-medium py-2 px-8 rounded-full transition duration-300"
      title="Ir para a próxima etapa"
    >
      Próximo ➤
    </router-link>
  </div>
</template>