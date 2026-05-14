<h1>📍 Consulta de CEP com Fetch API</h1>

Este projeto é uma aplicação web simples e funcional desenvolvida para realizar a busca de endereços completos a partir de um CEP informado pelo usuário. A aplicação consome dados em tempo real da API pública ViaCEP.

<h3>🚀 Tecnologias Utilizadas</h3>

<b>HTML5:</b> Estruturação semântica da interface.

<b>CSS3:</b> Estilização baseada em Flexbox para garantir um layout centralizado e limpo.

<b>JavaScript (ES6+):</b> Manipulação de eventos, tratamento de strings com Regex e consumo de API assíncrona via `fetch`.

<h3>⚙️ Funcionalidades</h3>

- <b>Busca Automática:</b> Ao digitar os 8 dígitos do CEP, a aplicação busca logradouro, bairro e localidade.

- <b>Tratamento de Entrada:</b> O sistema remove automaticamente caracteres não numéricos antes de processar a requisição.

- <b>Feedback ao Usuário:</b> Mensagens de erro dinâmicas para CEPs inválidos (menos de 8 dígitos) ou não encontrados.

- <b>Interface Reativa:</b> Os campos de resultado só aparecem na tela quando uma consulta é realizada com sucesso.

<h3>📂 Estrutura de Arquivos</h3>

`index.html:` Estrutura principal da página.

`style.css:` Definições visuais, incluindo estados de visibilidade e responsividade básica.

`script.js:` Lógica de integração com o serviço ViaCEP e manipulação do DOM.

<h1>🛠️ Como Executar</h1>

<b>1. Clone este repositório.</b>

```bash
git clone https://github.com/Yasmin-Fiusa/Buscar-Endereco.git
```

<b>2. Abra o arquivo `index.html` em qualquer navegador moderno.</b>

<b>3. Insira um CEP válido e clique em Consultar.</b>
