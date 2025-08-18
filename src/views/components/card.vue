<template>
  <div class="max-w-4xl mx-auto p-6 text-center text-white">
    <h1 class="text-3xl font-semibold mb-6">Bem-vindo à Tela de Tarefas</h1>

    <img 
      src="@/assets/img/teladetarefa.jpeg" 
      alt="Ilustração do Login" 
      class="w-full h-auto rounded-lg shadow-md mb-8 object-cover"
    />

  <p class="text-gray-700 dark:text-gray-300 mb-8 text-lg leading-relaxed">
  A tela de <strong>Tarefas - Visão Geral</strong> apresenta um panorama completo das suas atividades dentro do sistema Pen6.App. Aqui, você pode visualizar rapidamente a quantidade de tarefas <strong>em aberto</strong>, <strong>atrasadas</strong>, <strong>atribuídas a você</strong> e também as <strong>que estão próximas do vencimento</strong>.
  <br><br>
  Utilize os filtros para organizar as tarefas por status, como <strong>“A vencer”</strong>, <strong>“Atrasadas”</strong>, <strong>“Com prazo”</strong>, <strong>“Sem prazo”</strong> ou <strong>“Todas”</strong>. Também é possível filtrar por período: <strong>Dia</strong>, <strong>Semana</strong> ou uma visão <strong>Geral</strong>.
  <br><br>
  A barra de pesquisa permite que você encontre rapidamente uma tarefa específica dentro dos quadros, facilitando sua navegação e produtividade.
  <br><br>
  Essa seção foi desenvolvida para garantir <strong>agilidade, clareza e controle</strong> total das suas responsabilidades no dia a dia.
</p>


   <div class="flex justify-center gap-4">
      <!-- Botão Anterior -->
      <router-link
        to="/component/button"
        class="inline-block bg-gray-500 hover:bg-gray-600 text-white font-medium py-2 px-8 rounded-full transition duration-300"
        title="Voltar para a etapa anterior"
      >
         Anterior
      </router-link>
    <router-link
      to="/component/dropdown"
      class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-medium py-2 px-8 rounded-full transition duration-300"
      title="Ir para a próxima etapa"
    >
      Próximo 
    </router-link>
    </div>
  </div>
</template>