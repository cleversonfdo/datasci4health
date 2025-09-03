# Projeto `Clusters de coexpressão gênica em pacientes com câncer de próstata com e sem obesidade: impactos na progressão tumoral`
# Project `Gene Expression Clusters in Prostate Cancer Patients With and Without Obesity: Impacts on Tumor Progression`

# Descrição Resumida do Projeto

A obesidade é uma condição metabólica caracterizada pelo acúmulo excessivo de gordura corporal, especialmente a visceral, e está associada a inflamação crônica, alterações hormonais e disfunções metabólicas. Essa condição tem se tornado um dos maiores problemas de saúde pública no mundo, com projeções de crescimento alarmantes nas próximas décadas.

O câncer de próstata, por sua vez, é o tumor maligno mais frequente em homens no Brasil depois do câncer de pele não melanoma e apresenta elevada taxa de mortalidade. O desenvolvimento e a progressão da doença envolvem múltiplos fatores de risco, incluindo idade, hereditariedade, dieta e estilo de vida.

Diversos estudos indicam que a obesidade influencia negativamente a biologia tumoral da próstata, promovendo maior agressividade, risco de recidiva e mortalidade específica. Esse efeito ocorre por meio da liberação de adipocinas inflamatórias, alterações na sinalização hormonal (como o aumento da aromatização da testosterona em estradiol) e modificações no microambiente tumoral.

A proposta deste projeto é analisar dados de expressão gênica de pacientes com câncer de próstata obesos e não obesos, construindo redes de coexpressão para identificar clusters de genes, hubs e vias biológicas associadas à progressão tumoral. Essa abordagem permitirá compreender como a obesidade reprograma o transcriptoma prostático.

# Slides

> Coloque aqui o link para o PDF da apresentação da parte 1.

# Fundamentação Teórica

> Fundamentação teórica resumida do problema em saúde/biologia. Apenas cite artigos que tomará como base e, em uma frase, em que problema.

# Perguntas de Pesquisa

Quais genes são diferencialmente expressos entre tumores de pacientes com câncer de próstata obesos/sobrepeso e tumores de pacientes normopeso, e como os perfis de expressão destes genes se associam a parâmetros clínicos de progressão tumoral?

__Hipóteses__
- A obesidade altera o padrão de expressão gênica em tumores de pacientes com câncer de próstata, resultando em um conjunto distinto de genes diferencialmente expressos entre obesos/sobrepeso e normopeso.


- Os genes diferencialmente expressos em tumores de pacientes obesos/sobrepeso estarão enriquecidos em vias relacionadas à inflamação, ao metabolismo e ao remodelamento do microambiente tumoral.


- Um score de assinatura derivado dos genes diferencialmente expressos estará associado a pior prognóstico clínico (p. ex. maiores escores de Gleason, estádios mais avançados e menor sobrevida livre de progressão).

# Bases de Dados


Base de Dados | Endereço na Web | Resumo descritivo
----- | ----- | -----
Gene Expression Omnibus (GEO) | https://www.ncbi.nlm.nih.gov/gds | Base pública do NCBI que armazena dados de expressão gênica e outros experimentos de alto rendimento, permitindo acesso a estudos de transcriptômica em diversas condições biológicas e doenças.
The Cancer Genome Atlas Program (TCGA) | https://portal.gdc.cancer.gov/ | Consórcio internacional que reúne dados multi-ômicos de diferentes tipos de câncer, incluindo genômica, transcriptômica, epigenética e clínica, para apoiar a pesquisa em oncologia e medicina de precisão.

# Modelo Lógico

> ![Modelo Lógico de Grafos](assets/images/modelo_logico.png)

# Metodologia
1. Busca em bases de dados por coexpressão de transcritos coletados de indivíduos obesos com e sem câncer de próstata.


2. Identificação de coexpressões relevantes entre os transcritos.


3. Construção de uma rede de interação entre esses transcritos para pacientes com câncer de próstata com e sem obesidade.


4. Análise da topologia da rede para determinar a centralidade dos nós e a presença de hubs e comunidades.


5. Comparação das redes e identificação de transcritos candidatos a biomarcadores.


6. Análise de enriquecimento de vias para identificar quais transcritos candidatos apresentam expressão significativa em vias de interesse.


7. Correlação desses biomarcadores no contexto do desenvolvimento do câncer de próstata.


# Ferramentas
- Cytoscape
- RStudio
- STRING
# Referências Bibliográficas

> Lista de artigos, links e referências bibliográficas.
>
> Fiquem à vontade para escolher o padrão de referenciamento preferido pelo grupo.
