# Conversor de moedas
Este conversor de moedas é um programa escrito em Python que permite converter valores entre diferentes moedas. Ele utiliza interfaces gráficas e dados de APIs online para fornecer uma experiência amigável e atualizada.

Funcionalidades:

Conversão de Moedas: Converta valores entre diversas moedas, como Real, Dólar, Euro, Libra Esterlina e muito mais.
Interface Gráfica: Utilize um menu intuitivo para selecionar as moedas de origem e destino, digitar o valor a ser convertido e visualizar o resultado.
Atualizações Automáticas: As taxas de conversão são atualizadas em tempo real através de APIs online, garantindo a precisão dos resultados.
Múltiplas Moedas Disponíveis: O conversor suporta uma ampla variedade de moedas, abrangendo diversas regiões do mundo.
Dados Confiáveis: As taxas de conversão são obtidas de fontes confiáveis e atualizadas frequentemente.
Interface Personalizável: Personalize a aparência da interface com diferentes temas e configurações.
Como Funciona:

Importação de Bibliotecas: O programa importa as bibliotecas necessárias para funcionar, incluindo customtkinter para a interface gráfica, requests para acessar APIs online e xmltodict para ler arquivos XML.
Configuração da Interface: A interface gráfica é configurada com o tema "dark-blue" e a janela principal é dimensionada para 500x500 pixels.

Carregamento de Dados:
Dicionário de Conversões Disponíveis: Um dicionário é carregado a partir de um arquivo XML ("Conversoes.xml") contendo todas as conversões de moedas disponíveis.
Lista de Nomes de Moedas: Uma lista de nomes de moedas é carregada a partir de outro arquivo XML ("moedas.xml").

Criação de Elementos da Interface:

Título: Um título "Conversor de Moedas" é criado e exibido na parte superior da tela.

Textos Explicativos: Textos explicativos são criados para orientar o usuário na seleção das moedas de origem e destino.
Menus Drop-down: Menus drop-down ("OptionMenu") são criados para que o usuário possa selecionar as moedas de origem e destino.

Botão de Conversão: Um botão "Converter" é criado para iniciar o processo de conversão.

Campo de Resultado: Um campo de texto é criado para exibir o resultado da conversão.

Lista de Moedas Disponíveis: Uma lista scrollable é criada para mostrar todas as moedas disponíveis para conversão.

Funções:
carregar_moedas_destino: Carrega as moedas de destino disponíveis para a moeda de origem selecionada no menu drop-down.
converter_moeda: Obtém as taxas de conversão da API online, realiza a conversão e exibe o resultado no campo de texto.
pegar_cotacao_moeda: Faz a requisição para a API online para obter a taxa de conversão entre as moedas especificadas.
nomes_moedas: Lê o arquivo XML "moedas.xml" e retorna um dicionário com os nomes das moedas.
conversoes_disponiveis: Lê o arquivo XML "Conversoes.xml" e retorna um dicionário com as conversões de moedas disponíveis.

Execução da Interface: A interface gráfica é executada em um loop principal ("mainloop") para que o usuário possa interagir com os elementos e realizar as conversões.


