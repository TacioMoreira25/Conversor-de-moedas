# Conversor de Moedas 
### Descrição
Este conversor de moedas em Python permite converter valores entre diversas moedas com facilidade e precisão. Utilize uma interface gráfica intuitiva para selecionar moedas, digitar valores e visualizar resultados atualizados em tempo real.

### Funcionalidades
**Conversão Abrangente:** Converta entre diversas moedas, como Real, Dólar, Euro, Libra Esterlina e muito mais.
**Interface Intuitiva:** Navegue facilmente com menus drop-down, campos de texto e botões para uma experiência amigável.
**Atualizações em Tempo Real:** Obtenha taxas de conversão precisas e atualizadas diretamente de APIs online confiáveis.
**Suporte Multimoeda:** Acesse uma ampla variedade de moedas de diferentes regiões do mundo.
**Dados Confiáveis:** Confie em fontes confiáveis e atualizadas para taxas de conversão precisas.
**Personalização:** Personalize a interface com temas e configurações para atender às suas preferências.

### Como Funciona

#### Importação de Bibliotecas

**customtkinter:** Cria a interface gráfica amigável.
**requests:** Acessa APIs online para obter taxas de conversão.
**xmltodict:** Interpreta arquivos XML com dados de conversão.

#### Configuração da Interface

**Tema:** Define um tema visual atraente ("dark-blue").
**Dimensão:** Ajusta o tamanho da janela principal para melhor visualização (500x500 pixels).

#### Carregamento de Dados

**Dicionário de Conversões:** Carrega conversões disponíveis de um arquivo XML ("Conversoes.xml").
**Lista de Nomes de Moedas:** Obtém nomes de moedas de outro arquivo XML ("moedas.xml").

#### Criação de Elementos da Interface

**Título:** Apresenta o título "Conversor de Moedas" na parte superior.
**Textos Explicativos:** Orienta o usuário na seleção de moedas.
**Menus Drop-down:** Permite escolher moedas de origem e destino.
**Botão de Conversão:** Inicia o processo de conversão.
**Campo de Resultado:** Exibe o valor convertido.
**Lista de Moedas Disponíveis:** Mostra todas as moedas para consulta.

### Funções

**carregar_moedas_destino:** Atualiza as moedas de destino com base na moeda de origem selecionada.
**converter_moeda:** Obtém taxas de conversão, realiza a conversão e exibe o resultado.
**pegar_cotacao_moeda:** Faz a requisição à API para obter taxas de conversão específicas.
**nomes_moedas:** Retorna um dicionário com nomes de moedas do arquivo XML.
**conversoes_disponiveis:** Retorna um dicionário com conversões de moedas do arquivo XML.

### Execução da Interface

**Loop Principal:** Mantém a interface ativa para interação do usuário e realização de conversões.