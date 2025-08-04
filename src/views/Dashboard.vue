<template>
  <div class="dashboard p-4">
    <!-- end nav -->
    <div class="mt-2 w-full">
      <div
        class="lg:flex grid-cols-1 lg:space-y-0 space-y-3 gap-5 justify-between"
      >
        <div>
          <p class="uppercase text-xs text-gray-700 font-semibold">
            visualizações
          </p>
          <h1 class="text-2xl text-gray-900 dark:text-gray-200 font-medium">
            Bem Vindo ao App
          </h1>
        </div>
        <div class="flex gap-2">
          <button
            class="bg-primary border flex gap-2 text-white hover:bg-primary/80 dark:border-gray-700 rounded py-3 px-5"
          >
            <span class="icon text-2xl"><Icon icon="ic:twotone-plus" /></span>
          </button>
        </div>
      </div>
    </div>

    <!-- grid wrapper card -->
    <div
      class="wrapper-card grid lg:grid-cols-4 grid-cols-1 md:grid-cols-2 gap-2 mt-5"
    >
      <!-- card  -->
      <div
        class="card bg-white dark:bg-gray-800 rounded-md p-5 border dark:border-gray-700 flex w-full max-w-3xl"
      >
        <div class="flex-1 p-0">
          <img
            src="../assets/img/teste-1.jpeg"
            alt="Descrição da imagem"
            class="mb-4 w-full h-auto object-contain rounded"
          />

          <div class="p-2 max-w-sm text-white flex items-center gap-2">
            <router-link
              to="/component/alert"
              class="text-sm bg-gray-200 hover:bg-gray-300 dark:bg-gray-700 dark:hover:bg-gray-600 text-black dark:text-white rounded-full p-2 transition"
              title="Ir para Alert.vue"
            >
              ➤
            </router-link>
            Tela de Login
          </div>
        </div>
      </div>

      <!-- end card -->
      <div
        class="card bg-white dark:bg-gray-800 rounded-md p-5 border dark:border-gray-700 flex w-full max-w-3xl"
      >
        <div class="flex-1 p-0">
          <img
            src="../assets/img/fator-2.jpeg"
            alt="Descrição da imagem"
            class="mb-4 w-full h-auto object-contain rounded"
          />

          <div class="p-2 max-w-sm text-white flex items-center gap-2">
            <router-link
              to="/component/accordion"
              class="text-sm bg-gray-200 hover:bg-gray-300 dark:bg-gray-700 dark:hover:bg-gray-600 text-black dark:text-white rounded-full p-2 transition"
              title="Ir para Alert.vue"
            >
              ➤
            </router-link>
            Tela Segundo Fator
          </div>
        </div>
      </div>

      <!-- end card -->
      <div
        class="card bg-white dark:bg-gray-800 rounded-md p-5 border dark:border-gray-700 flex w-full max-w-3xl"
      >
        <div class="flex-1 p-0">
          <img
            src="../assets/img/teladashbord.jpeg"
            alt="Descrição da imagem"
            class="mb-4 w-full h-auto object-contain rounded"
          />

          <div class="p-2 max-w-sm text-white flex items-center gap-2">
            <router-link
              to="/component/badge"
              class="text-sm bg-gray-200 hover:bg-gray-300 dark:bg-gray-700 dark:hover:bg-gray-600 text-black dark:text-white rounded-full p-2 transition"
              title="Ir para Alert.vue"
            >
              ➤
            </router-link>
            DashBord Cliente
          </div>
        </div>
      </div>
      <!-- end card -->
      <div
        class="card bg-white dark:bg-gray-800 rounded-md p-5 border dark:border-gray-700 flex w-full max-w-3xl"
      >
        <div class="flex-1 p-0">
          <img
            src="../assets/img/teladrive2.jpeg"
            alt="Descrição da imagem"
            class="mb-4 w-full h-auto object-contain rounded"
          />

          <div class="p-2 max-w-sm text-white flex items-center gap-2">
            <router-link
              to="/component/breadcumb"
              class="text-sm bg-gray-200 hover:bg-gray-300 dark:bg-gray-700 dark:hover:bg-gray-600 text-black dark:text-white rounded-full p-2 transition"
              title="Ir para Alert.vue"
            >
              ➤
            </router-link>
            Drive
          </div>
        </div>
      </div>
      <!-- end card -->
    </div>
    <!-- end wrapper card -->
    <div class="mt-2 lg:flex block lg:gap-2 relative">
      <div
        class="bg-white dark:bg-gray-800 p-0 lg:w-3/4 w-full rounded-md box-border border dark:border-gray-700"
      >
        <div class="p-5 flex justify-between">
          <div>
            <h2 class="font-medium text-sm text-gray-800 dark:text-gray-200">
              DashBord
            </h2>
            <!-- <h1 class="font-semibold text-4xl text-gray-800 dark:text-gray-200">
              72%
            </h1> -->

            <p class="text-gray-400 font-lexend font-normal">
              DashBord Externo
            </p>
          </div>

          <!-- <div class="flex gap-5">
            <span class="">
              <h2 class="text-red-500 flex">
                <span class="mr-2"> 15.9% </span
                ><span>
                  <Icon icon="akar-icons:arrow-down" />
                </span>
              </h2>
            </span>
            <span class="">
              <h2 class="text-green-500 flex">
                <span class="mr-2"> 87.9% </span
                ><span>
                  <Icon icon="akar-icons:arrow-up" />
                </span>
              </h2>
            </span>
          </div> -->
        </div>

     <img
  src="../assets/img/prestador.png"
  alt="Descrição da imagem"
  class="mb-4 w-full h-auto object-contain rounded"
/>

<div class="text-gray-800 dark:text-gray-200 text-sm leading-relaxed space-y-3">
  <h2 class="text-lg font-semibold flex items-center gap-2">
    👋 Bem-vindo ao Painel de Prestador
  </h2>
  <p>Este é o seu espaço para acessar e organizar tudo de forma prática.</p>

  <div>
    <h3 class="font-medium">📂 Drive de Arquivos</h3>
    <p>Aqui você encontra e envia arquivos relacionados aos seus serviços.</p>
    <p>Clique sobre as pastas ou documentos para abrir ou baixar.</p>
  </div>

  <div>
    <h3 class="font-medium">📊 Orçamentos e Mídias</h3>
    <p>Acompanhe orçamentos, propostas e materiais enviados para você.</p>
    <p>Tudo fica organizado para facilitar seu trabalho.</p>
  </div>

  <div>
    <h3 class="font-medium">🔒 Perfil e Segurança</h3>
    <p>No menu lateral, você pode acessar seu perfil e sair com segurança quando terminar.</p>
  </div>

  <div>
    <h3 class="font-medium">💡 Dica</h3>
    <p>Use os botões e ícones do painel para navegar facilmente. Tudo foi feito para ser rápido e intuitivo!</p>
  </div>
</div>

<br />
<hr />


        <div class="wrapper-button p-5 flex justify-between mt-3">
        <router-link
  to="error/blank"
  class="flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white text-sm font-medium rounded-full px-4 py-2 transition duration-300 shadow-md hover:shadow-lg"
  title="Ir para Alert.vue"
>
  <span>Saiba mais</span>
  <span class="text-lg">➤</span>
</router-link>

          <!-- <select
            name=""
            id=""
            class="dark:bg-gray-800 dark:hover:bg-gray-700 dark:border-gray-700 border max-w-lg px-4 py-3 block rounded-md text-gray-500 dark:text-gray-400"
          >
            <option value=""></option>
          </select> -->
          <!-- <button class="uppercase border-b border-red-600 text-red-600">
            
          </button> -->
        </div>
      </div>

      <div
        class="bg-white dark:bg-gray-800 p-5 lg:mt-0 mt-4 lg:w-2/4 border dark:border-gray-700 rounded-md w-full"
      >
        <div class="">
          <h2 class="text-lg font-semibold dark:text-gray-200">
            Funcionalidades Do App
          </h2>
          <p class="text-gray-400">Funcionalidades Principais.</p>
        </div>
        <perfect-scrollbar class="divide-y h-96 mt-5 dark:divide-gray-700">
          <div class="p-3 w-full">
            <div class="flex gap-5">
              <div>
                <img
                  class="w-14 rounded-md"
                  src="../assets/img/user1.png"
                  alt=""
                />
              </div>
              <div class="mt-1">
                <h2 class="dark:text-gray-200">💬 Chat</h2>
                <p class="text-sm dark:text-gray-500 text-gray-400">
                  Converse diretamente com a equipe responsável pelos seus
                  projetos. O chat integrado permite comunicação rápida,
                  centralizada e segura, eliminando a necessidade de múltiplos
                  canais externos.
                </p>
              </div>
            </div>
          </div>
          <div class="p-3 w-full">
            <div class="flex gap-5">
              <div>
                <img
                  class="w-14 rounded-md"
                  src="../assets/img/user2.png"
                  alt=""
                />
              </div>
              <div class="mt-1">
                <h2 class="dark:text-gray-200">📌 Tarefas</h2>
                <p class="text-sm dark:text-gray-500 text-gray-400">
                  Gerencie suas atividades de forma prática e organizada.
                  Acompanhe tarefas pendentes, atrasadas ou concluídas, utilize
                  filtros para visualizar apenas o que é relevante e mantenha
                  total controle do que precisa ser feito no dia a dia.
                </p>
              </div>
            </div>
          </div>
          <div class="p-3 w-full">
            <div class="flex gap-5">
              <div>
                <img
                  class="w-14 rounded-md"
                  src="../assets/img/user3.png"
                  alt=""
                />
              </div>
              <div class="mt-1">
                <h2 class="dark:text-gray-200">✅ Aprovação de Mídia</h2>
                <p class="text-sm dark:text-gray-500 text-gray-400">
                  Receba, visualize e aprove materiais de mídia com agilidade.
                  Essa funcionalidade garante mais transparência e rapidez no
                  fluxo de aprovação, facilitando a comunicação entre clientes e
                  a equipe de marketing.
                </p>
              </div>
            </div>
          </div>
          <div class="p-3 w-full">
            <div class="flex gap-5">
              <div>
                <img
                  class="w-14 rounded-md"
                  src="../assets/img/user4.png"
                  alt=""
                />
              </div>
              <div class="mt-1">
                <h2 class="dark:text-gray-200">📂 Drive</h2>
                <p class="text-sm dark:text-gray-500 text-gray-400">
                  Armazene, organize e acesse todos os arquivos relacionados aos
                  seus projetos em um só lugar. Com o Drive integrado, você tem
                  acesso rápido a documentos, imagens e pastas de forma simples
                  e segura.
                </p>
              </div>
            </div>
          </div>
          <div class="p-3 w-full">
            <div class="flex gap-5">
              <div>
                <img
                  class="w-14 rounded-md"
                  src="../assets/img/user5.png"
                  alt=""
                />
              </div>
              <div class="mt-1">
                <h2 class="dark:text-gray-200">💰 Faturamento</h2>
                <p class="text-sm dark:text-gray-500 text-gray-400">
                  Tenha controle completo sobre a parte financeira dos seus
                  projetos. Visualize relatórios de faturamento, acompanhe
                  faturas emitidas e consulte faturas canceladas de forma
                  simples e transparente.
                </p>
              </div>
            </div>
          </div>
        </perfect-scrollbar>
      </div>
    </div>
    <div class="mt-2 lg:flex block lg:gap-2">
      <div
        class="mt-2 bg-white dark:bg-gray-800 p-0 w-full rounded-md box-border border dark:border-gray-700"
      >
        <div class="head p-5">
          <h2 class="font-bold text-lg text-gray-800 dark:text-gray-200">
            Dashboard
          </h2>
          <p class="text-gray-400 font-lexend font-normal">
           Externo
          </p>
          <span class="float-right">
            <h2 class="text-green-500 -mt-12 flex">
           
            </h2>
          </span>
        </div>
        <div class="wrapper-chart mt-5 pr-2 pl-2">
          <img
            src="@/assets/img/prestador.png"
            alt="Descrição da imagem"
            class="mb-4 w-full h-auto object-contain rounded"
          />

          <p style="color: aliceblue; font-weight: bold">
            DashBord acesso Externo
          </p>

          <br />
          <hr />

          <div class="footer p-5">
            <div class="wrapper-button flex justify-between mt-3">
              <router-link
                to="/component/breadcumb"
                class="text-sm bg-gray-200 hover:bg-gray-300 dark:bg-gray-700 dark:hover:bg-gray-600 text-black dark:text-white rounded-full p-2 transition"
                title="Ir para Alert.vue"
              >
                ➤
              </router-link>
            </div>
          </div>
        </div>
      </div>
      <div
        class="mt-2 bg-white dark:bg-gray-800 p-0 w-full rounded-md box-border border dark:border-gray-700"
      >
        <div class="head p-5">
          <h2 class="font-bold text-lg text-gray-800 dark:text-gray-200">
            Perfil Externo
          </h2>
          <p class="text-gray-400 font-lexend font-normal">Externo</p>

          <span class="float-right">
            <h2 class="text-green-500 -mt-12 flex">
              <span> </span>
            </h2>
          </span>
        </div>
        <div class="wrapper-chart mt-5">
          <img
            src="../assets/img/prestador-2.png"
            alt="Descrição da imagem"
            class="mb-4 w-full h-auto object-contain rounded"
          />
          <p style="color: aliceblue; font-weight: bold">Perfil de Acesso Externo</p>
          <br />
          <hr />

          <div class="footer p-5">
            <div class="wrapper-button flex justify-between mt-3">
              <router-link
                to="/component/breadcumb"
                class="text-sm bg-gray-200 hover:bg-gray-300 dark:bg-gray-700 dark:hover:bg-gray-600 text-black dark:text-white rounded-full p-2 transition"
                title="Ir para Alert.vue"
              >
                ➤
              </router-link>
            </div>
          </div>
        </div>
      </div>
      <div
        class="mt-2 bg-white dark:bg-gray-800 p-0 w-full rounded-md box-border border dark:border-gray-700"
      >
        <div class="head p-5">
          <h2 class="font-bold text-lg text-gray-800 dark:text-gray-200">
            Drive 
          </h2>
          <p class="text-gray-400 font-lexend font-normal">Externo</p>
        </div>

        <div class="wrapper-chart mt-5">
          <img
            src="../assets/img/teladrive2.jpeg"
            alt="Descrição da imagem"
            class="mb-4 w-full h-auto object-contain rounded"
          />
          <p style="color: aliceblue; font-weight: bold">Drive de Acesso Externo</p>
          <br />
          <hr />

          <div class="footer p-5">
            <div class="wrapper-button flex justify-between mt-3">
              <router-link
                to="/component/breadcumb"
                class="text-sm bg-gray-200 hover:bg-gray-300 dark:bg-gray-700 dark:hover:bg-gray-600 text-black dark:text-white rounded-full p-2 transition"
                title="Ir para Alert.vue"
              >
                ➤
              </router-link>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- <div
      class="mt-2 bg-white dark:bg-gray-800 p-5 w-full rounded-md box-border border dark:border-gray-700"
    >
      <h2 class="font-bold text-lg text-gray-800 dark:text-gray-200">
        Latest Transactions
      </h2>
      <p class="text-gray-400 font-lexend font-normal">
        This is a list of latest transactions
      </p>
      <div class="wrapping-table mt-10">
        <table
          class="w-full text-sm text-left text-gray-500 dark:text-gray-400 lg:overflow-auto overflow-x-scroll"
        >
          <thead
            class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400"
          >
            <tr>
              <th scope="col" class="uppercase px-6 py-3">Transaction</th>
              <th scope="col" class="uppercase px-6 py-3">Date & Time</th>
              <th scope="col" class="uppercase px-6 py-3">Amount</th>
              <th scope="col" class="uppercase px-6 py-3">Status</th>
            </tr>
          </thead>
          <tbody>
            <tr
              class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 odd:bg-white even:bg-gray-50"
              v-for="items in tableTransaction"
              :key="items.transaction"
            >
              <td class="px-6 py-4">
                {{ items.transaction }}
              </td>
              <td class="px-6 py-4">
                {{ items.datetime }}
              </td>
              <td class="px-6 py-4">
                {{ items.amount }}
              </td>
              <td class="px-6 py-4">
                <span
                  class="text-green-800 bg-green-300 px-3 py-1 rounded-md"
                  v-if="items.statusTransaction == 'completed'"
                >
                  {{ items.statusTransaction }}
                </span>
                <span
                  class="text-purple-800 bg-purple-300 px-3 py-1 rounded-md"
                  v-else-if="items.statusTransaction == 'progress'"
                >
                  {{ items.statusTransaction }}
                </span>
                <span
                  class="text-red-800 bg-red-300 px-3 py-1 rounded-md"
                  v-else
                >
                  {{ items.statusTransaction }}
                </span>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
      <div class="wrapper-button flex justify-between mt-3">
        <select
          name=""
          id=""
          class="dark:bg-gray-800 dark:hover:bg-gray-700 border dark:border-gray-700 max-w-lg px-4 py-3 block rounded-md text-gray-500 dark:text-gray-400"
        >
          <option value="">Last 7 years</option>
        </select>
        <button class="uppercase border-b border-red-600 text-red-600">
          Transaction Report
        </button>
      </div>
    </div> -->
  </div>
</template>

<script>
// @ is an alias to /src
import { Icon } from "@iconify/vue";

export default {
  name: "Dashboard",
  data() {
    return {
      // for more guide apexchart.js
      // https://apexcharts.com/docs/chart-types/line-chart/

      // chart data area
      optionsArea: {
        xaxis: {
          categories: [2015, 2016, 2017, 2018, 2019, 2020, 2021, 2022],
        },
        fontFamily: "Segoe UI, sans-serif",
        stroke: {
          curve: "straight",
        },
        chart: {
          toolbar: {
            show: true,
          },
          zoom: {
            enabled: false,
          },
          sparkline: {
            enabled: true,
          },
        },
        markers: {
          size: 0,
        },
        yaxis: {
          show: false,
        },
        fill: {
          type: "gradient",
          gradient: {
            shadeIntensity: 0,
            opacityFrom: 0.2,
            opacityTo: 0.5,
            stops: [0, 90, 100],
          },
        },
      },

      chart: {
        fontFamily: "lexend, sans-serif",
      },

      seriesArea: [
        {
          name: "Revenue",
          data: [30, 40, 45, 50, 49, 60, 70, 91],
        },
        {
          name: "Revenue (Previous period)",
          data: [20, 34, 45, 55, 79, 87, 90, 98],
        },
      ],
      optionsBar: {
        chart: {
          toolbar: {
            show: false,
          },
          zoom: {
            enabled: false,
          },
          sparkline: {
            enabled: true,
          },
        },
        legend: {
          show: false,
        },
        xaxis: {
          show: false,
        },
        yaxis: {
          show: false,
        },
        colors: ["#4f46e5", "#DC2626"],
        dataLabels: {
          enabled: false,
        },
        stroke: {
          curve: "straight",
        },
      },

      seriesBar: [
        {
          name: "Product 1",
          data: [30, 40, 45, 50, 49, 60, 70, 91],
        },
        {
          name: "Product 2",
          data: [20, 34, 45, 55, 79, 87, 90, 98],
        },
      ],
      optionsVisitor: {
        chart: {
          toolbar: {
            show: false,
          },
          zoom: {
            enabled: false,
          },
          sparkline: {
            enabled: true,
          },
        },
        legend: {
          show: false,
        },
        xaxis: {
          show: false,
        },
        yaxis: {
          show: false,
        },
        colors: ["#4f46e5"],
        dataLabels: {
          enabled: false,
        },
        fill: {
          type: "gradient",
          gradient: {
            shadeIntensity: 0,
            opacityFrom: 0,
            opacityTo: 0.3,
            stops: [0, 90, 100],
          },
        },
        stroke: {
          curve: "smooth",
        },
      },

      seriesVisitor: [
        {
          name: "Visitor ",
          data: [30, 40, 45, 50, 49, 60, 70, 91],
        },
      ],
      optionsDonut: {
        chart: {
          type: "donut",
        },
        legend: false,
        dataLabels: {
          enabled: false,
        },
        labels: ["admin", "SuperAdmin", "User", "Costumer"],
      },

      seriesDonut: [20, 15, 63, 83],
      tableTransaction: [
        {
          transaction: "Payment from Ethan Roger",
          datetime: "Apr 22, 2022",
          amount: "Rp.450.000",
          statusTransaction: "completed",
        },
        {
          transaction: "Payment from Taylor neal",
          datetime: "May 2, 2022",
          amount: "Rp.250.000",
          statusTransaction: "completed",
        },
        {
          transaction: "Payment from Tobi Ferreira",
          datetime: "May 5, 2022",
          amount: "Rp.150.000",
          statusTransaction: "progress",
        },
        {
          transaction: "Payment failed from #046577",
          datetime: "May 5, 2022",
          amount: "Rp.180.000",
          statusTransaction: "cancelled",
        },
      ],
    };
    // end chart data line
  },
  components: {
    Icon,
  },
  mounted() {},
};
</script>
