# Aula 08-11 - App Conversão de moeda

## Avaliação

* Implemente para que o usuário possa fazer conversão de outras moedas (mínimo + 3 moedas);
* Descreva abaixo o seu entendimento acerca desta atividade, explorando as funcionalidades das classes que contruímos e os principais pontos da aplicação;

## Entrega

* Clone este repositório e faça o que se pede;
* Realize um commit das suas alterações no seu repositório;
* Envie o link do repositório na avaliação gerada no classroom;

## Descritivo do Aluno:

   A atividade avaliativa engloba aspectos importantes e primordiais, principalmente para adentrar ao conteúdo de API. Foi visto a maneira em que o código e os arquivos passam a ser organizados, para que possam comunicar corretamente com a API e o retorno de dados com base na moeda escolhida. 
* onCreate() -> Inicializa, configura a interface e busca a seleção do usuário;
* converter() -> Valida se alguma opção foi selecionada e se foi digitado algum valor, após isso busca na API (com base na seleção do usuário) a conversão correta para ser exibida em tela, com base nas cláusulas if e else. Há também validação com try/catch para captar erros quando a aplicação não estiver funcionando devidamente;
* AwesomeClient() -> Realiza as requisições para obter os dados da API de converão de moedas (utilizando a biblioteca Retrofit);
* buscarDados() -> Faz uma requisição passando o parâmetro opcaoSelecionada e faz a validação de possíveis erros.

   A classe AwesomeClient é usada dentro da MainActivity, onde o método buscarDados é chamado com a opção de conversão selecionada. Após coletar os dados da API o resultado é mostrado em tela.

 
