Aplicativo de Calculadora
Este projeto é um aplicativo de calculadora simples desenvolvido como parte de uma tarefa de Programação Orientada a Objetos (POO) para o curso de Análise e Projeto de Software.

Estrutura do Projeto
O projeto é estruturado em várias classes TypeScript, cada uma representando um componente diferente da calculadora.

Calculadora
A classe Calculadora é a classe principal que une todos os componentes. Ela possui um objeto Teclado, Tela e Cpu, e usa esses para realizar cálculos com base nos pressionamentos de botões.

Teclado
A classe Teclado representa o teclado da calculadora. Ela mantém uma lista de objetos Botao e fornece um método para simular o pressionamento de um botão.

Tela
A classe Tela representa a tela da calculadora. Ela fornece métodos para exibir o resultado de um cálculo e para limpar a tela.

Cpu
A classe Cpu realiza os cálculos reais. Ela recebe uma expressão como entrada e retorna o resultado do cálculo.

Botao
A classe Botao representa um botão no teclado da calculadora. Cada botão tem um valor, que pode ser recuperado usando o método obterValor.

Uso
Para usar a calculadora, crie uma nova instância da classe Calculadora e use o método pressionarBotao para simular pressionamentos de botões. Por exemplo:

const calculadora = new Calculadora();
calculadora.pressionarBotao("2");
calculadora.pressionarBotao("+");
calculadora.pressionarBotao("2");
calculadora.pressionarBotao("=");
Copiar
Isso realizará o cálculo 2 + 2 e exibirá o resultado na tela.

Dependências
Este projeto usa TypeScript e requer Node.js para funcionar. As dependências necessárias estão listadas no arquivo package.json.

Compilação e Execução
Para compilar e executar o projeto, use os seguintes scripts npm:

npm run build: Compila o código TypeScript em JavaScript.
npm run start: Executa o código JavaScript compilado.
