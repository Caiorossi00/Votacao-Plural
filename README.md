
Este código em C implementa um sistema de votação usando o algoritmo de pluralidade. 

O algoritmo de pluralidade é um método de votação projetado para eleições de escolha única, onde cada eleitor tem permissão para votar em apenas um candidato. A implementação básica desse algoritmo envolve várias etapas:

Inicialização:
Cada candidato é representado por uma estrutura de dados que inclui seu nome e uma variável para armazenar a contagem de votos. Inicialmente, a contagem de votos de todos os candidatos é definida como zero.

Recebimento de Votos:
Durante a eleição, cada eleitor é solicitado a escolher um candidato específico. O sistema verifica se o voto é válido, verificando se corresponde ao nome de um candidato existente. Votos inválidos são descartados.

Contagem de Votos:
Quando um voto válido é registrado, a contagem de votos do candidato correspondente é incrementada. Cada candidato acumula votos à medida que os eleitores fazem suas escolhas.

Identificação do Vencedor:
Após o encerramento da votação, o sistema determina qual candidato possui o maior número de votos. Se houver um empate, todos os candidatos com a contagem máxima são considerados vencedores.

Exibição do Resultado:
O nome do candidato vencedor ou vencedores é impresso como o resultado final da eleição. Se houver empate, são apresentados os nomes de todos os candidatos empatados.
