# api-dio
Api de Consulta ao Diário Oficial

## Funcionalidades

- Busca as últimas edições do DIO ES
- Executa uma pesquisa no DIO ES
  - query: texto a ser pesquisado
  - dateMin: data inicial
  - dateMax: data final
  - pageNumber: número da página
  - sort: ordenação
  
 ## Rotas
 - **GET /search/{palavrachave}**: retorna o DIO atual basedo em uma palavra chave
