<template>
  <div class="max-w-4xl mx-auto p-6 text-center text-gray-700">
    <h1 class="text-3xl font-semibold mb-6">Bem-vindo à Tela de Planos de Conta</h1>

    <img 
      src="@/assets/img/planocontas.jpeg" 
      alt="Ilustração do Login" 
      class="w-full h-auto rounded-lg shadow-md mb-8 object-cover"
    />

   <p class="text-gray-700 dark:text-gray-300 mb-8 text-lg leading-relaxed">
  A aba <strong>Plano de Contas</strong> permite organizar e estruturar todas as contas financeiras utilizadas no sistema Pen6.App, de forma categorizada e padronizada.
  <br><br>
  Aqui você pode cadastrar, editar ou excluir contas contábeis, agrupadas nas seguintes categorias principais:
  <strong>Ativo</strong>, <strong>Passivo</strong> e <strong>Contas de Resultados</strong>. 
  <br><br>
  Cada grupo representa uma parte fundamental da estrutura financeira da empresa:
  <ul class="list-disc list-inside mt-2">
    <li><strong>Ativo:</strong> tudo o que a empresa possui.</li>
    <li><strong>Passivo:</strong> tudo o que a empresa deve.</li>
    <li><strong>Contas de Resultados:</strong> receitas e despesas que impactam o resultado do período.</li>
  </ul>
  <br>
  Use o botão <strong>“+ Adicionar”</strong> para criar novas contas e personalize conforme as necessidades do seu negócio. Utilize a busca para localizar contas rapidamente.
  <br><br>
  Essa estrutura é essencial para gerar relatórios financeiros organizados e facilitar o controle e análise da saúde financeira da empresa.
</p>
  <div class="flex justify-center gap-4">
      <!-- Botão Anterior -->
      <router-link
        to="/component/dropdown"
        class="inline-block bg-gray-500 hover:bg-gray-600 text-white font-medium py-2 px-8 rounded-full transition duration-300"
        title="Voltar para a etapa anterior"
      >
         Anterior
      </router-link>
    <router-link
      to="/blank"
      class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-medium py-2 px-8 rounded-full transition duration-300"
      title="Ir para a próxima etapa"
    >
      Próximo 
    </router-link>
    </div>
  </div>
</template>