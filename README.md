# eloapfe-AvaliacaoIMC-react
## Calculadora de IMC - avaliacao_imc
Descrição
App simples em React Native + Expo que calcula o IMC com base no peso e altura informados. Exibe o valor e a classificação do IMC.

Tecnologias
React Native
Expo

TypeScript

Como executar
Clone o projeto:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/avaliacao_imc.git
cd avaliacao_imc
Instale as dependências:

bash
Copiar
Editar
npm install
Inicie o app:

bash
Copiar
Editar
npx expo start
Abra no celular com Expo Go ou emulador.

Lógica do IMC
ts
Copiar
Editar
imc = peso / (altura * altura);

if (imc < 18.5) classificacao = "Abaixo do peso";
else if (imc < 24.9) classificacao = "Peso normal";
else if (imc < 29.9) classificacao = "Sobrepeso";
else if (imc < 34.9) classificacao = "Obesidade grau I";
else if (imc < 39.9) classificacao = "Obesidade grau II";
else classificacao = "Obesidade grau III";