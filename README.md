📱 Calculadora de IMC

📝 Desenvolvido por:

👤 Isabela Nunes🎓 RA: 24026460

📌 Descrição Geral do Projeto

Este projeto consiste em um aplicativo Android desenvolvido em Java que permite calcular o Índice de Massa Corporal (IMC) do usuário. Com base no resultado do cálculo, o aplicativo exibe um feedback positivo e personalizado para cada categoria de IMC.

🚀 Funcionalidades Principais:

✅ Tela principal com logo e botão para acessar a calculadora de IMC.✅ Tela de cálculo com campos de entrada para peso e altura, botões para calcular, limpar e fechar.✅ Navegação entre múltiplas telas (Activities) de feedback.✅ Uso de Intent e Bundle para passagem de dados entre Activities.✅ Layouts responsivos criados com XML, seguindo a paleta de cores definida.

🛠️ Processo de Desenvolvimento

🎨 Decisões Tomadas:

📌 Paleta de Cores:

🟢 Verde Escuro: #006341 (Cabeçalhos e destaques).

🟢 Verde Claro: #00A859 (Botões e links).

⚫ Cinza Escuro: #4D4D4D (Textos secundários).

⚪ Branco: #FFFFFF (Fundo principal).

📌 Estrutura do Aplicativo:📂 Múltiplas Activities para uma navegação intuitiva.📂 Passagem de dados entre Activities via Intent e Bundle.📂 Armazenamento de strings e valores fixos no values.xml.

📌 Lógica do Cálculo:📊 Fórmula utilizada: IMC = peso / (altura * altura)📊 Classificação do IMC:

🔴 Abaixo do peso: IMC < 18.5

🟢 Peso normal: 18.5 ≤ IMC < 25

🟠 Sobrepeso: 25 ≤ IMC < 30

🟡 Obesidade grau 1: 30 ≤ IMC < 35

🔴 Obesidade grau 2: 35 ≤ IMC < 40

🚨 Obesidade grau 3: IMC ≥ 40

⚠️ Desafios Enfrentados:

1️⃣ Passagem de Dados entre Activities → Resolvido com Intent e Bundle.2️⃣ Manipulação de Imagens → Uso de ImageView com scaleType="fitCenter".3️⃣ Interface do Usuário → Ajuste da paleta de cores e espaçamento.

🔥 Melhorias Futuras:
