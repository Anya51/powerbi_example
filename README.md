# powerbi_example

## Sobre o projeto

Esse projeto possui um exemplo, construído através do Power BI, de dashboard. A pasta models é utilizado para armazenar as dashboards. A pasta samples é utilizada para armazenar os arquivos, onde os dados são importados.

## Como visualizar o exemplo

Execute o arquivo da pasta models

ou

Inicie o Power BI. Iniciando o Power BI, no menu, selecione: File => Open. Vá na pasta do projeto e em models selecione o arquivo de exemplo.

## Power BI Tutorial

Tutorial de como utilizar o Power BI

### Importanto dados

no menu "Home", clique em "Get Data"

![import1](./imagens/import1.png)

Selecione o extensão do arquivo a ser trabalhado, por exemplo, csv, xls(Excel), json, pdf ...

![import2](./imagens/import2.png)

Selecione a sample ou arquivo, onde os dados serão importados.

![import3](./imagens/import3.png)

Aparecerá uma tela com a pré-visualização dos dados. Confirme clicando em "Load".

![import4](./imagens/import4.png)

No canto direito em Fields aparecerá a tabela com as chaves dos dados importados.

![import5](./imagens/import5.png)

### Entendendo os Dados

No canto inferior esquerdo existe um botão com nome "Data". Esse menu mostra todos os dados importados em forma de tabela. É útil para entender as relações que os dados possuem antes de inserir algum gráfico.

![dados](./imagens/dados.png)

### Gráficos

No menu Vizualizations clique no gráfico de sua escolha.

![vizualizations](./imagens/vizualizations.png)

Depois de selecionar, será possível escalonar o gráfico na tela a vontade.

![escalonar](./imagens/escalonar.png)

### Inserindo os dados importados nos Gráficos

Em sua dashboard, selecione um dos gráficos. Depois de selecionar, no campo Fields marque os atributos que você deseja representar no gráfico selecionado.

![insert](./imagens/insert.png)

OBS: Ao marcar atributos sem selecionar nenhum gráfico resultará em uma criação de gráfica automática pelo Power BI.

![insert](./imagens/insert.png)

No campo "Legends" é possível definir quais atributos vão nas linhas, colunas e legendas
do gráfico, por exemplo, se arrastamos o atributo "Atividades" até legenda, temos:

![graph1](./imagens/graph1.png)
![graph2](./imagens/graph2.png)

Agora, o nosso gráfico, o da direita. aparece com a legenda de Atividades, indicando as atividades de cada estado e seu valor de orçamento.

### Formatando o Gráfico

É possível mudar algumas informações do gráfico a partir do menu "Format" em Vizualizations.

![format1](./imagens/format1.png)

Aqui, alteramos a cor da legenda do mapa a direita, mas existem um número grande de opções como: remoção de título, legenda, adição de controles de zoom, etc ...;

![format2](./imagens/format2.png)

### Interagindo com o Dashboard

O dashboard possui interações entre o gráficos. Neste exemplo, Selecionando uma região diretamente no gráfico da esquerda, resulta, no gráfico da direita, o realce do orçamento dos estados daquela região.

![interaction1](./imagens/interaction1.png)
![interaction2](./imagens/interaction2.png)

### Aplicação de Filtros

No campo "Filters" fazer algumas pesquisa nos atributos para mostrar no dashboard.
![Filter1](./imagens/Filter1.png)

Em Filters clique no atributo escolhido para aplicação do filtro. Depois, construa a lógica do Filtro

![Filter2](./imagens/Filter2.png)

Aplique e veja o resultado.
![Filter3](./imagens/Filter3.png)
