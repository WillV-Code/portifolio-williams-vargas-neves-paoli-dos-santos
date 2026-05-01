# 🏗️ Engenharia de Contexto e Lógica Física

## 📝 Descrição do Projeto
Este projeto demonstra como a programação pode ser utilizada para mapear e resolver desafios físicos do cotidiano. Através de algoritmos de **Simulação de Fuga** e **Análise de Microclima Urbano**, o sistema transforma variáveis do ambiente — como portas trancadas, temperatura e qualidade do ar — em dados processáveis para tomada de decisão eficiente[cite: 6, 7].

O objetivo é mostrar que problemas grandes tornam-se menos complexos quando divididos em pequenas partes lógicas, transformando eventos caóticos em projetos organizados e testáveis[cite: 8].

## 🚀 Tecnologias e Conceitos
*   **Simulação de Estado:** Uso de variáveis para monitorar a posição do agente, inventário (chaves) e níveis de energia[cite: 6].
*   **Lógica de Condicional Crítica:** Aplicação de estruturas `if/else` para definir rotas alternativas caso um caminho esteja bloqueado[cite: 6, 8].
*   **Análise de Dados Ambientais:** Integração de métricas de temperatura, umidade e Índice de Qualidade do Ar (IQAr) para calcular o conforto urbano[cite: 7].
*   **Modularização e Funções Auxiliares:** Uso de funções específicas para converter valores brutos em categorias compreensíveis (ex: IQAr para "Bom", "Moderado" ou "Ruim")[cite: 7].

## 📊 Funcionalidades e Regras de Negócio

### 1. 🏃 Simulador de Saída de Fuga
O algoritmo gerencia a evacuação de um ambiente através de uma lista de locais e estados físicos[cite: 6]:
*   **Gestão de Recursos:** O agente consome energia a cada movimento e deve encontrar chaves para abrir portas trancadas[cite: 6].
*   **Lógica de Persistência:** Implementação de "voltas" obrigatórias em áreas específicas (ex: escadas) antes de progredir para a saída final[cite: 6].
*   **Resultado Binário:** O sistema valida o sucesso (fuga concluída) ou falha (exaustão de energia)[cite: 6].

### 2. 🌡️ Algoritmo de Microclima Local
Analisa o bem-estar em diferentes pontos da cidade (Praças, Estações de Metrô) em períodos distintos (Manhã/Noite)[cite: 7]:
*   **Pontuação de Conforto:** Atribui notas de 0 a 10 para temperatura, umidade e ar, gerando uma média final de "Conforto Urbano"[cite: 7].
*   **Categorização por Match/Case:** Utiliza a estrutura `match/case` para fornecer feedbacks detalhados sobre a salubridade do ar e alertas de saúde[cite: 7].

## 🔧 Estrutura do Pensamento Algorítmico
A transição da observação comum para a lógica física segue três pilares[cite: 8]:
1.  **Decomposição:** Ver um local não como um todo, mas como um conjunto de dados (número de pessoas, obstáculos, metros até a saída)[cite: 8].
2.  **Clareza de Passos:** O computador não adivinha; ele exige comandos exatos. Isso reflete na organização pessoal de tarefas e na explicação clara de processos[cite: 8].
3.  **Previsibilidade:** Estar sempre "um passo à frente" ao definir condições: "Se o corredor A estiver bloqueado, vá pelo corredor B"[cite: 8].

## 🧠 Reflexão de Desenvolvimento
A maior lição desta engenharia é que a vida deixa de ser um evento caótico e passa a parecer um projeto que pode ser organizado, testado e melhorado[cite: 8]. O desafio não está na complexidade do problema em si, mas em como simplificá-lo em partes menores para que a lógica possa encontrar o caminho mais eficiente para a "saída"[cite: 8].

---
[Voltar ao perfil](https://github.com/WillV-Code)
