## **Sistema de apoio à decisão (SAD)** (também conhecido por Decision Support System (DSS))

### Definição de SAD:

Um sistema de informação consistindo de hardware/software e do elemento humano designado para assistir um tomador de decisão de qualquer nível, com ênfase em tarefas estruturadas e não-estruturadas (desestruturadas).

```
O SAD serve para decisões não estruturadas. QUE não é simplesmente programar um sistema, é preciso entender qual a utilidade, designação e estruturar a aplicação. O problema muitas vezes não está formulado ou dado o cliente muitas vezes não sabe o que quer.
 
Cabe a você compatibilizar os aspectos humanos, decisórios, modelos, base de dados… tudo que vai ser necessário para esse problema de decisão.
```

pode resultar em várias telas em resposta a mudanças hipotéticas introduziadas por um gerente. É um sistema usado para explorar alternativas possíveis. 

O SAD envolve quatro tipos básicos de modelagem analítica.
<ul>
    <li>Análise tipo what if "o que-se".
    
     O usuário introduz mudanças nas variáveis ou relações e verifica as mudanças resultantes nos valores das outras variáveis
     
     Ex: Se o orçamento com marketing aumentar em 2%, qual será o impacto total nas vendas?
</li>

<li>Análise de busca de metas (busca de objetivo).

 Alterando os valores das variáveis finais (metas) é observada a mudança das outras variávies
 
Ex: Quanto se deve gastar com marketing para se gerar R$50.000,00 de vendas totais.
 </li>


<li>Análise de sensibilidade.

 É um caso especial da análise what if, onde a mudança repetida de um única variável faz com que sejam observadas as mudanças nas outras variáveis. Permite desenvolver análises aplicando diferentes variáveis.

 Ex: Qual o preço máximo que se deve pagar pela matéria-prima e ainda obter lucro?
 </li>

 
<li>Análise de Otimização.

 É uma extensão da análise busca de metas, onde ao invés de fixar uma meta, a meta é encontrar a solução ótima para uma ou mais variáveis alvo do problema. Geralmente a otimização é alcançadas através de programação matemática, sendo que às vezes, devido à complexidade do sistema, são adotados modelos heurísticos que usam métodos de inteligência artificial. Os métodos de inteligência arificial muitas vezes não encontram a solução ótima, mas encontram uma solução próxima da ótima </li>
</ul>


#### Etapas para um SAD

De uma forma geral os gestores tormam decisões seguindo um processo de 4 etapas conforme proposto por Simon:

- Definição / Estruturação do problema de decisão (oportunidade de decisão)

- Construção de um modelo que descreve o problema do mundo real

- Identificação de possíveis soluções para o problema e avaliação de soluções

- Comparação, escolha e recomendação de uma solução potencial para o problema

#### Características da tomada de decisão

- Pensamento de grupo: Membros do grupo aceitam soluções sem refletir, o que pode levar a decisões ruins

- Avaliação de cenários what-if

- Experimentação de um sistema real é muito custoso (deveria testar num modelo antes?!?)

- Mudanças no ambiente de tomada de decisão podem ocorrer constantemente: - Isso altera as premissas do modelo! (deve verificar o que é dinâmico e o que não é dinâmico)(por exemplo,(em um sistema tipo ifood) as entregas em dias de
feriado podem aumentar, exigindo uma visão diferente do problema).

- Impondo pressão de tempo sobre o decisor.

- A análise de um problema custa tempo/dinheiro: - É difícil fazer o trade-off e decidir o escopo para tomar uma decisão (É difícil
determinar quando parar e tomar uma decisão - dependendo do problema você não vai perder tempo com o problema)

- Informação insuficiente ou em abundância isso atrapalha. Informação demais atrapalha porque você não consegue enchergar o que é relevante.

- A construção de um SAD bem-sucedido requer um conhecimento profundo destes conceitos:
    - Support: métodos de apoio a decisão
    - Decision Making: aspectos cognitivos que estão envolvidos no aspecto decisório
    - System: O que o sistema pode contribuir
    - Models and data: Como elaborar modelos e enriquecer através de dados.


#### Eficácia de um SAD

O Fator crítico para obter a eficácia do sistema é uma combinação das características abaixo:

- Poder - grau em que o sistema pode responder a importantes decisões (O problema deve ser relevante)

- Acessibilidade - o grau em que o sistema pode fornecer respostas oportunas e consistentes (não adianta nada você ter um sistema maravilhoso que só fica pronto depois que a decisão precisa ser tomada)

- Flexibilidade - o grau no qual sistema pode se adaptar às necessidades e situações que o problema vai apresentar ao longo do processo que você está usando para resolver. (Você aprende mais sobre o problema o quando mais você pensa sobre o problema)

(são vários aspectos que mundam quando está considerando a individualidade de cada um. Cada pessoa pode se preocupar e foca em algum aspecto diferente do problema, não existe um padrão para tomar uma decisão não estruturada. Ex: escolher a carreira - cada pessoa segue uma trilha diferente de pensamento para tomar a sua decisão)

- idéia é melhorar a qualidade de tomar uma decisão não estruturada para minimisar a insatisfação que pode ter ou as perdas que pode ter no futuro por que não usou uma metodologia não adequada. 

```
Implementação de um SAD

- O projetista, o sistema e o usuário devem está integrados a fim de alcançar um desenvolvimento unificado.

Devem conhecer

- Tarefas particulares ou decisões a serem apoiadas
- Os objetivos do sistema
- O processo de decisão atual do tomador de decisão.
```

Benefícios esperados de um SAD

Benefícios esperados:

- Aumentar o número de alternativas examinadas
- Melhorar o entendimento dos negócios
- Respostas rápidas para situações inesperadas
- Habilidade para lidar com tarefas descontínuas
- Poupar custos e tempo (psois o processamento agora está sendo feito pelo computador)
- Fazer melhor uso dos recursos de dados


As capacidade do sistema de apoio a tomada de decisão vem aumentando cada vez mais.

<img src="">


Classificação do sistema de apoio à decisão

-- Classificação fornecida pela Association for Information Systems Special Interest Group on Decision Support Systems (AIS SIGDSS).

- SAD orientado a comunicação e SAD para grupos
- SAD orientado a dados
- SAD orientado a documentos
- SAD orientado a conhecimento
- SAD orientado a modelos

- (Frequentemente o SAD é um híbrido de muitas classes)

-- Outras categorias SAD

- SAD institucional e ad-hoc

-- Sistemas personalizados versus sistemas prontos

-- Suporte pessoal, em grupo e organizacional

-- Sistema de suporte individual versus sistema de suporte em grupo (GSS)...

Componentes de um SAD

<img src="">


OBS: Acessibilidade: Verificar se o usuário tem algum problema visual na hora de desenvolver a interface. Ex: Alguns usuários daltônicos não conseguiam diferenciar as cores no gráfico.



```
O sistema deve se adequar a organização e não a organização se adequar ao sistema

```
