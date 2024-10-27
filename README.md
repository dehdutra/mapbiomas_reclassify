Este script permite uma visualização interativa e reclassificação das classes de uso da terra do MapBiomas usando Google Earth Engine (GEE) e a biblioteca Geemap. 
Ele facilita a análise de mudanças de uso da terra no Brasil de 1985 até 2023, utilizando a coleção de dados MapBiomas, e adiciona funcionalidades como legenda personalizada e reclassificação de classes.

Credito dos dados: https://brasil.mapbiomas.org

Recursos Principais

Visualização Interativa:

- Cria um mapa interativo que adiciona camadas de uso da terra para cada ano (1985-2023) da coleção MapBiomas.
- Inclui uma paleta de cores detalhada e uma legenda para identificar facilmente cada classe de uso da terra.
- Reclassificação das Classes de Uso da Terra:

As classes de uso da terra originais são mapeadas para novas categorias simplificadas, como "Áreas Florestais" e "Água", entre outras.
As classes reclassificadas são exibidas no mapa com uma paleta de cores simplificada, destacando as principais categorias.

Legendas Customizadas e Controle de Camadas:

- Adiciona uma legenda para as classes originais e reclassificadas, permitindo uma navegação mais intuitiva.
- Inclui controles de camada para alternar entre visualizações.
- Instruções para Utilização

Autenticação e Inicialização:

- Inicie a sessão com o GEE autenticando sua conta e especificando o projeto Google Earth Engine.

Adicionando Camadas:

- Use a função add_layer_by_year para adicionar as camadas de uso da terra para cada ano.

Reclassificação:

- A função reclassify_mapbiomas mapeia as classes de uso da terra para novas categorias.
- As imagens reclassificadas são coletadas em uma ImageCollection e exibidas em camadas no mapa.

Dependências

- Google Earth Engine: Para acessar e processar dados de uso da terra.
- Geemap: Para visualização e interação com o mapa no ambiente Python.
