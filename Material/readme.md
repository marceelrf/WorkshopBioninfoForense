# Material

## Dia 1 - Sequenciamento

- Para que sequenciar? Potenciais de uso da técnica.
- O que é um sequenciamento de DNA?
- Abordar as diferentes tecnologias de sequenciamento existentes, custos, velocidade de processamento, vantagens e desvantagens.
- Explicar a estrutura de dados fastq.

## Dia 2 - Alinhamento

- O que é um genoma de referência? Quais estão disponíveis.
- Alinhamento denovo e alinhamento com base em uma referência.
- Alinhamento de sequencias usando BWA.
- Dificuldades na montagem.
- Apresentar arquivos SAM e BAM.

## Dia 3 - Genotipagem

- Mapeamento de sequências utilizando BWA e minimap2.
- Criar BAMs indexados para as montagens.
- Visualizar a montagem utilizando IGV. 
- Visualizar genes específicos e variantes importantes para a genética forense.
- Comparar cobertura de short e long reads.


## Dia 4 - Long Reads (ONT)

## Dia 5 - STRs

## Detalhamento:
O curso terá suas atividades divididas em aulas teóricas pelas manhã e atividades práticas nos períodos da tarde.
No primeiro dia (segunda-feira), após realizada a abertura do evento, o foco será nas diferentes tecnologias de alinhamento existentes. Discutiremos o que é um sequenciamento de DNA, o porquê de se realizar um sequenciamento, abordando as diferentes tecnologias de sequenciamento (custos, velocidade de processamento, vantagens e desvantagens). Explicaremos os diferentes tipos de dados gerados e suas estruturas, com destaque para o formato fastq. No período da tarde serão realizadas atividades para explorar arquivos fastq, realizando controle de qualidade com o software FastQC. Serão utilizados arquivos de sequenciamento produzidos por tecnologias distintas, como Illumina e Oxford nanopore. Estes arquivos serão acessados de uma base de dados pública chamada 1000 genomes.
No segundo dia (terça-feira), o tema será alinhamento de sequências. Neste momento, o enfoque será a tecnologia da Illumina. Pela manhã, abordaremos a questão de tipos de alinhamento, utilizando genomas de referência ou por abordagens de novo, e detalharemos dificuldades comuns ao montar o genoma. Apresentaremos softwares mais utilizados para realizar o alinhamento, como BWA e minimap2, e por fim os arquivos gerados, de formato SAM e BAM, serão apresentados. Pela tarde, as atividades práticas serão a realização do mapeamento das sequências, utilizando os softwares apresentados pela manhã, a construção de BAMs indexados e sua visualização no software IGV. O enfoque será na visualização de genes específicos e variantes importantes para a genética forense.
A identificação de variantes será o tema do terceiro dia (quarta-feira). Na aula teórica serão abordados as questões sobre a origem da diversidade e quais são os marcadores genéticos mais frequentes. Apresentaremos o programa de chamada de variantes freebayes e de faseamento e montagem de haplótipos WhatsHap. Será discutido o formato de dados VCF, resultado destes tipos de análise. No período da tarde, as atividades práticas envolvem genotipagem de marcadores e/ou genes importantes para genética forense, utilizando-se os programas freebayes e WhatsHap.
No quarto dia (quinta-feira), serão apresentados os dados de Oxford nanopore. Repetiremos as análises do segundo e terceiro dia, utilizando dados específicos desta tecnologia, e comparando os resultados anteriormente nas análises de dados Illumina.
No quinto dia (sexta-feira), apresentaremos uma estratégia para genotipagem de STRs a partir de dados de NGS utilizando o software Strait Razor. Adicionalmente, realizaremos discussão sobre aspectos populacionais (equilíbrio de Hardy-Weinberg, diversidade genética, desequilíbrio de ligação, diferenciação populacional, etc.) e parâmetros forenses de informatividade, de modo a contribuir para a avaliação da qualidade das genotipagens realizadas e para seleção de marcadores para aplicação na área de identificação humana e análise de ancestralidade. No período da tarde, as atividades práticas envolvem genotipagem de STRs utilizando-se o programa STRait Razor e utilizaremos os genótipos gerados nas etapas anteriores para avaliação dos parâmetros populacionais e forenses, utilizando-se os programas Arlequin e STRAF. Ao término das atividades, será realizado o encerramento do curso.

