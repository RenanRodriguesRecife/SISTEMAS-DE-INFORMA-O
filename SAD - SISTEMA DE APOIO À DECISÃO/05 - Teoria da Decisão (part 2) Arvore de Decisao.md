# Teoria da Decisão: Árvore de Decisão

## Diagrama de Fluxo de Decisões

• Árvore de Decisões

  – Análise qualitativa

    - Avaliação cronológica das escolhas:

      – Controladas pelo decisor;

      – Determinadas pelo “acaso”
  
  – No exemplo da urna, tem-se logo de início: participar ou não do jogo.
  
  <img src=".assets/arv1.jpg">
  
  
- Árvore de Decisões

  – No exemplo da urna, tem-se logo de início: participar ou não do jogo.
  
    - Se você não se recusar a participar do jogo, então deve decidir se colhe mais informação.
    
    - O decisor pode fazer:
    
      – Nenhuma observação (e0)
      
      – Uma única observação (e1)
      
      – Um par de observações (e2)
      
      – Ou experimentar sequencialmente (es)
      
  <img src=".assets/arv2.jpg">
      
      
 - Árvore de Decisões

  – E se o decisor decidir pelo caminho e1.
  
   <img src=".assets/arv3.jpg"> 

- Depois de pagar $8,00 (taxa de amostragem – experimentação), o decisor encontraria uma encruzilhada, com o ramo marcado V (vermelho) e P (preto).

  – Neste ponto, o decisor não tem mais poder sobre o próprio destino
  
• Suponha então que, por acaso, o decisor retire uma bola vermelha da urna não identificada, e portanto se dirija pelo caminho V
  
      
 <img src=".assets/arv4.jpg"> 

 <img src=".assets/arv5.jpg"> 


• Existem situações onde o risco não é apenas discreto, como também assume caráter sequencial

• Nessas situações depende-se de decisões sequenciais e processos estocásticos encadeados

• Para este tipo de situação pode ser utilizada a técnica de Árvores de Decisão

• As árvores de decisão permitem considerar o risco em diversos estágios e prover respostas para os resultados obtidos em cada um destes


### Componentes da análise com árvores de decisão

- **Nó raiz**: representa o início da árvore de decisão, onde o decisor está diante de uma decisão ou de um resultado incerto. A ideia é obter o valor do investimento de risco neste nó

- **Nós de evento**: representam os possíveis resultados de uma aposta ou processo estocástico

- **Nós de decisão**: representam escolhas que o decisor pode tomar, exemplo seguir com um investimento após pesquisa de mercado

- **Nós de fim**: são os desfechos das decisões tomadas em reação aos desfechos prévios

<img src=".assets/arv6.jpg"> 

### Etapas para análise de uma árvore de decisão

1. Dividir a análise em fases de risco (geração de cenários)

2. Estimar as probabilidades dos resultados em cada fase

3. Definir os pontos de decisão

4. Calcular os fluxos de caixa e os valores nos nós de fim

5. Executar o caminho inverso da árvore (Fold Back)

### A árvore de decisão permite encontrar dois dados chave:

• Valor esperado para hoje obtido ao se percorrer a árvore de decisão, considerando potenciais perdas e oportunidades de risco e as ações a serem tomadas

• A faixa de variação de valores nos nós de fim que contém o risco em potencial de um investimento
