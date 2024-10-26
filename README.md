# associacao-futebol
Repositório dedicado ao tratamento e disponibilização de dados coletados após a disputa de jogos de futebol.

Utilização
Deve ser preenchido completamente cada arquivo com nome:
"Sumula" + "_" + "T" + "_xx_" + "B" + "_yy_" + ".xlsx"

"_xx_" representa o número da temporada, que deve ir de 01 a 99 (00 também, pois não foi feita restrição).
"_yy_" representa o número do baba, ou dia de partida, que deve ir de 01 a 99 (ou 00 também, mesma situação).

De modo que nomes de arquivos válidos seriam:
Sumula_T01B01.xlsx
Sumula_T16B98.xlsx
sUmUlA_t99b02.xlsx

E nomes de arquivos inválidos seriam:
Sumulas_T01B01.xlsx
Sumula_T1B1.xlsx
Sumula_T001B001.xlsx
Sumula_TXXBYY.xlsx
Sumula_T01B01(1).xlsx
OutrosNomes_T01B01.xlsx
Sumula_T01B01.csv

Obs: Um arquivo com nome duplicado é salvo com "(1)", "(2)", "(3)" ao final do nome, que deve ser removido para que o arquivo seja processado normalmente.

Remover dados com código específico:
Para remover dados, deve ser gerado um arquivo com nome:
"REMOVER" + "_" + "T" + "_xx_" + "B" + "_yy_" + ".xlsx"

"_xx_" e "_yy_" representam, respectivamente, os números da temporada e do baba, como visto anteriormente.

Nomes válidos:
REMOVER_T01B01.xlsx
remover_T10B09.xlsx
rEmOvEr_T21B22.xlsx

É utilizado somente o nome desse arquivo para remover os dados dos outros arquivos, portanto, o conteúdo dentro desse arquivo não tem relevância.