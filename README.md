# timeline-extraction-prompt
O mesmo prompt foi utilizado em todos os modelos, instruíndo-os a analisar o prontuário e extrair uma linha
do tempo de eventos relacionada ao paciente. Apresentamos a composição de um evento
como: i) gatilho: marcação temporal que determina o início do evento (data, hora, etc.);
ii) argumentos: entidades que são parte do evento, sendo classificadas em: sintoma,
procedimento, medicamento, transtorno, doençaa, descoberta, atividade de assistência à
saúde e resultado de laboratório; e iii) extensão: fragmento do texto original que inclui
o gatilho e os argumentos, descrevendo todo o evento. Além disso, buscando manter a
padronização entre as respostas dos modelos, é solicitado um resultado estruturado como
objeto JSON, com instruções exatas sobre a estrutura e campos. Também foi ressaltado
que o texto está escrito de maneira sequencial.
