# imcApp
Calculadora de IMC

Desenvolvido por:

Isabela NunesRA: 24026460

Descrição Geral do Projeto

Este projeto consiste em um aplicativo Android desenvolvido em Java que permite calcular o Índice de Massa Corporal (IMC) do usuário. Com base no resultado do cálculo, o aplicativo exibe um feedback positivo e personalizado para cada categoria de IMC.

Funcionalidades Principais:

Tela principal com logo e botão para acessar a calculadora de IMC.

Tela de cálculo com campos de entrada para peso e altura, botões para calcular, limpar e fechar.

Navegação entre múltiplas telas (Activities) de feedback, exibindo o resultado do IMC com mensagens motivacionais e imagens personalizadas.

Uso de Intent e Bundle para passagem de dados entre Activities.

Layouts responsivos criados com XML, seguindo a paleta de cores definida.

Processo de Desenvolvimento

Decisões Tomadas:

Paleta de Cores: Para garantir um design coeso, utilizei as seguintes cores:

Verde Escuro (#006341) para cabeçalhos e destaques.

Verde Claro (#00A859) para botões e links.

Cinza Escuro (#4D4D4D) para textos secundários.

Cinza Claro (#B3B3B3) para bordas e divisores.

Branco (#FFFFFF) para o fundo principal.

Estrutura do Aplicativo:

Utiliza múltiplas Activities para uma navegação intuitiva.

Passagem de dados entre Activities via Intent e Bundle.

Armazenei strings e valores fixos no arquivo values.xml para melhor organização.

Lógica do Cálculo:

Utilizei a fórmula: IMC = peso / (altura * altura).

Defini as categorias do IMC conforme padrões internacionais:

Abaixo do peso: IMC < 18.5

Peso normal: 18.5 ≤ IMC < 25

Sobrepeso: 25 ≤ IMC < 30

Obesidade grau 1: 30 ≤ IMC < 35

Obesidade grau 2: 35 ≤ IMC < 40

Obesidade grau 3: IMC ≥ 40

Exibe mensagens motivacionais para cada categoria.

Desafios Enfrentados:

Passagem de Dados entre Activities:

Inicialmente, tive dificuldades ao transferir valores de uma Activity para outra.

Resolvi utilizando Intent e Bundle, garantindo que peso, altura, IMC e categoria fossem corretamente passados.

Manipulação de Imagens:

Ajustar imagens para diferentes tamanhos de tela sem comprometer a qualidade foi um desafio.

Utilizei ImageView com scaleType="fitCenter" para um melhor resultado.

Interface do Usuário:

Ajustar cores e espaçamento para garantir uma boa experiência foi essencial.

Testei diferentes combinações da paleta de cores para manter a harmonia visual.

Melhorias Futuras:

Implementar animações para melhorar a interatividade.

Adicionar um gráfico para visualizar a evolução do IMC ao longo do tempo.

Suporte a diferentes idiomas.
