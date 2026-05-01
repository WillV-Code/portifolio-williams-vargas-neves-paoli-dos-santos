# 🎨 Desenhando Emojis com Dados

## 📝 Descrição do Projeto
Este projeto explora a manipulação de estruturas de dados multidimensionais para representar e transformar informações visuais e auditivas[cite: 3, 4]. O objetivo central é utilizar **Matrizes (Grades)** e **Dicionários Aninhados** para criar filtros de imagem (como sombreamento de emojis) e inversão de frequências sonoras[cite: 3, 4].

O sistema demonstra que um "Emoji" nada mais é do que uma grade de pixels (tuplas RGB) que pode ser processada logicamente para alterar cores e formas[cite: 4].

## 🚀 Tecnologias e Conceitos
*   **Manipulação de Matrizes:** Uso de listas dentro de listas para representar grades de pixels $5 \times 5$[cite: 4].
*   **Processamento de Cores:** Aplicação de operadores aritméticos em tuplas para criar efeitos de sombra (ex: `pixel // 2`)[cite: 4].
*   **Inversão de Dados:** Uso da função `reversed()` para alterar a ordem de sequências sonoras e sentimentos associados[cite: 3].
*   **Estruturas Multidimensionais:** Loops de 3 níveis para acessar dados profundamente aninhados (Dicionário $\rightarrow$ Lista $\rightarrow$ Tupla)[cite: 3, 5].

## 📊 Funcionalidades e Regras de Negócio

### 1. 🎭 Filtro de Sombreamento em Emojis
O algoritmo percorre uma grade de cores e aplica uma "sombra" lógica:
*   **Identificação:** Localiza pixels de cores específicas (como o amarelo do rosto)[cite: 4].
*   **Transformação:** Divide os valores RGB por 2, reduzindo a luminosidade em 50% enquanto preserva áreas pretas (olhos e boca)[cite: 4].

### 2. 🎵 Inversor de Sentimentos Musicais
Utiliza uma "Biblioteca Musical" para transformar o humor das faixas:
*   **Lógica de Inversão:** Notas de uma música "Alegre" são invertidas e reclassificadas como "Triste", e vice-versa[cite: 3].
*   **Reestruturação:** Reconstrói o dicionário original com as novas sequências de frequências[cite: 3].

### 3. 📖 Organização de Dados Complexos (Receitas)
Gerencia informações com múltiplos níveis de detalhamento:
*   **Hierarquia:** Receita $\rightarrow$ Ingredientes (Tuplas) $\rightarrow$ Passos (Listas de Listas)[cite: 5].
*   **Manipulação Dinâmica:** Uso de métodos como `.insert()`, `.append()` e `.pop()` para editar o conteúdo em tempo de execução[cite: 5].

## 🔧 Estrutura do Algoritmo (Triplo Loop)
Para processar os emojis e receitas, o código segue esta estrutura de profundidade:
1.  **Nível 1 (Dicionário):** Acessa a chave principal (ex: o nome da receita ou o tipo de dado)[cite: 4, 5].
2.  **Nível 2 (Lista/Grade):** Itera sobre as linhas do emoji ou grupos de ingredientes[cite: 4, 5].
3.  **Nível 3 (Tupla/Pixel):** Acessa o dado final (o valor RGB do pixel ou a informação unitária do ingrediente) para aplicar a modificação[cite: 4, 5].

## 🧠 Desafios de Desenvolvimento
O maior desafio neste tema é a **Gestão da Imutabilidade**. Como tuplas são imutáveis em Python, o algoritmo precisa criar novas listas temporárias (`nova_linha`) para reconstruir a estrutura após a modificação dos dados[cite: 3, 4]. O domínio de **Loops Aninhados** é essencial para evitar que dados sejam processados no nível hierárquico errado[cite: 3, 5].

---
[Voltar ao perfil](https://github.com/seu-usuario)
