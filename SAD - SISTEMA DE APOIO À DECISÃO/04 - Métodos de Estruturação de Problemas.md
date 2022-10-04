## Métodos de Estruturação de Problemas

### Introdução

- Como um campo novo, muito tem sido escrito sobre o uso de algoritmos de ciência de dados que podem gerar resultados úteis

- Muitos pesquisadores e praticantes têm focado em desenvolver análises avançadas.

- Não surpreendentemente, a pesquisa em ciência de dados normalmente se concentra em melhorar os **modelos de dados** e os **algoritmos** usados em projetos de ciência de dados.

- Mas para usar a ciência de dados em um contexto organizacional existem desafios adicionais que **vão além** dos algoritmos

- Esses desafios incluem itens como:

  - Entender quais dados podem estar disponíveis

  - Quais podem ser os objetivos do esforço;

  - Qual estrutura de gerenciamento de projetos deve ser usada;

  - Como engajar e coordenar os esforços desenvolvidos

  - Como estabelecer cronogramas de projeto realistas

- Kelly e Kaskade (2013) fizeram uma pesquisa com 300 empresas que trabalham com Big Data e certificam que "55% dos projetos de ciência dados não são concluídos e muitos outros ficam aquém de seus objetivos".

- Foi sugerido que uma melhoria no processo de ciência de dados ajudar a melhorar a taxa de sucesso desses projetos (Saltz, 2015).

- No entanto, também foi observado que são necessárias várias metodologias de processo de ciência de dados, com base nos atributos do projeto (Ahangama & Poo, 2015)

- Mas no que consiste um Projeto de Ciência de Dados???

- Ele pode ser descrito como

"um projeto que usa técnicas estatísticas e de aprendizado de máquina em grandes volumes de dados não estruturados e/ou estruturados gerados por sistemas, pessoas, sensores ou rastros digitais de informações de pessoas."

- Este trabalho é feito em um ambiente computacional com o objetivo de identificar correlações e relações causais, classificar e prever eventos, identificar padrões e anomalias e inferir probabilidades, interesse e sentimento.

- Big Data é muitas vezes pensado como um subconjunto da ciência de dados, onde a quantidade de dados requer o uso de ferramentas e algoritmos especiais.

- Projetos de Big Data têm sido frequentemente descritos por meio dos "4 Vs" (Beyer, 2011; IBM, 2013):

  - volume (tamanho dos dados a serem analisados - a equipe precisa usar técnicas de "Big Data")
  
  - variedade (número de fontes e tipo de dados - estruturados, não estruturados ou ambos)
  
  - velocidade (velocidade dos dados coletados/gerados que precisam ser analisados)
  
  - veracidade (a confiabilidade dos dados).
  
- Mas será que esses 4 Vs são suficientes?

- Esses critérios e outros, como fontes de dados, armazenamentos de dados, data staging e processamento de dados, podem ser úteis para descrever os dados usados em um projeto de Big Data.

- Mas muitas vezes é preciso mais para descrever completamente outros atributos sobre o projeto.

- Vamos tomar como exemplo o CRISP-DM (Cross Industry Standard Process for Data Mining), que é um modelo de processo de mineração de dados.

- Ele é um modelo de processo com seis fases que descreve naturalmente o ciclo de vida da ciência de dados.

- É como um conjunto de proteções para ajudar a planejar, organizar e implementar seu projeto de ciência de dados (ou aprendizado de máquina).

- Foi publicado em 1999 para padronizar os processos de mineração de dados em todos os setores.

- Se tornou a metodologia mais comum para projetos de data mining, analytics e data science

- A metodologia pode ser combinada com outras metodologias de gerenciamento de projetos.

- E mesmo sem implementar integralmente, é possível obter benefícios.

<img src=".assets/cicloDC.jpg">

#### compreensão do negócio

- A fase de **compreensão do negócio** concentra-se na compreensão dos objetivos e requisitos do projeto.

  - Apesar de muitas equipes se apressarem nessa fase, ela é absolutamente essencial.

    (gerenciamento de projetos){
   - Determine os objetivos de negócios (o que o cliente deseja realizar?)

   - Avalie a situação (recursos, requisitos, riscos e contingências, analise custo-benefício)

   - Determine as metas de mineração de dados

   - Produza o plano do projeto (seleção de tecnologias e ferrametnas).
  
  }
  
  #### compreensão do negócio
  
  - A fase de **compreensão do negócio** concentra-se na compreensão dos objetivos e requisitos do projeto.

  - Apesar de muitas equipes se apressarem nessa fase, ela é absolutamente essencial.

  gerenciamento de projetos {
    - Determine os objetivos de negócios (o que cliente deseja realizar?)

    - Avalie a situação (recursos, requisitos, riscos e contingências, analise custo-benefício)

    - Determine as metas de mineração de dados

    - Produza o plano do projeto (seleção de tecnologias e ferramentas).
 
  }

  #### compreensão de dados
  
  Em seguida é a fase de **compreensão de dados**.
  
    - Esta fase direciona o foco para identificar, coletar e analisar os conjuntos de dados que podem ajudá-lo a atingir as metas do projeto.

    - Esta fase também tem quatro tarefas:

     - Colete dados iniciais

     - Descreva os dados

     - Explore os dados

     - Verifique a qualidade dos dados

#### preparação dos dados

 - Fase de **preparação dos dados**.
 
  - São preparados o(s) conjunto(s) de dados final(is) para modelagem.

  - Tem cinco tarefas:

    - Selecionar dados (o que será usado?)

    - Limpe os dados

    - Construa dados (derivar de novos atributos que serão úteis)

    - Integre os dados (combinação de várias fontes)

    - Formete os dados conforme necessário


- Na fase de **modelagem**, provavelmente serão construídos e avaliados vários modelos com base em várias técnicas de modelagem diferentes.

  - Deve-se iterar até encontrar um modelo que seja bom o suficiente, rodar o ciclo de vida do CRISP-DM e melhorar o modelo em iterações futuras.
  
- A fase de **modelagem** tem quatro tarefas:

  - Selecione técnicas de modelagem/algoritmos usados
  
  - Gerar design de teste (pode ser necessário dividir os dados em conjuntos de treinamento, teste e validações).
  
  - Construção do modelo
  
  - Avaliação do modelo (análise com base no conhecimento do domínio, nos critérios de sucesso predefinidos e no design do teste)
  
  
- Diferentemente da Avaliação do Modelo da fase de Modelagem, a fase de **Avaliação** foca em verificar de forma mais ampla qual modelo atende melhor aos negócios e o que fazer em seguida.

  - Esta fase tem três tarefas:
  
    - Avalie os resultados (atende ao negócio? Quais atendem?)
    
    - Processo de revisão (checklist de itens, etapas e descobertas)
    
    - Determine as próximas etapas (continuar com a implantação, iterar mais ou iniciar novos projetos?)
    
- Um modelo só é util se traz resultados para o cliente, fazendo com que a fase de **implantação** seja muito importante e com complexidade variável.

  - Esta fase final tem quatro tarefas:
  
    - Planejar a implantação
    
    - Desenvolver o plano de monitoramento e manutenção
    
    - Produzir relatório final
    
    - Revisão do projeto
    
- O trabalho da organização pode não terminar aí.

- Como estrutura de projeto, o CRISP-DM não descreve o que faz apóx o projeto.

- Mas se o modelo for para produção, certifique-se de manter o modelo em produção

- O monitoramento constante e o ajuste ocasional do modelo geralmente são necessários, por isso ele é cíclico.


```
Será que nós sempre sabemos o que o cliente deseja realizar?

Será que nós sempre conseguimos identificar os objetivos de negócios?

Será que nós sempre conseguimos identificar recursos que vamos precisar, requisitos do projeto, os riscos e contingências envolvidas?

Será que nós sempre conseguimos identificar quais são as perguntas que precisamos fazer aos dados?

Por que será que nós não sabemos o que queremos muitas vezes quando vamos tratar de um problema estratégico da organização? Ou quando vamos sugerir um novo produto? Ou um novo serviço?

```

Dinâmica

• Considere que você irá trabalhar de home office, de modo que a
localização em que você vive pode ser completamente independente
da empresa onde você trabalha. 

• Defina em grupo duas personas com perfis diferentes (por exemplo,
jovem solteiro e maduro casado e com filhos) e esboce como seria o
processo destas personas para estruturação da escolha do local onde
elas morariam, para que possam iniciar a coleta de dados para
subsidiar esta escolha. 

• Vocês podem sugerir critérios que considerariam importantes nesta
escolha. Considere adicionalmente a lista de critérios em anexo e
incluam aqueles que vocês acreditam que deveriam ser incluídos na
análise.
