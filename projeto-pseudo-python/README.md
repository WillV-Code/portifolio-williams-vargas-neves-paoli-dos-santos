# 🐍 Traduzindo Lógica para Python

## 📝 Descrição do Projeto
Este projeto demonstra a transição de algoritmos conceituais para implementações reais em **Python**. O foco é mostrar como estruturas de repetição (`for`), decisões condicionais (`if/elif/else`) e funções tratam dados do mundo real, como finanças, clima e educação.

O objetivo é garantir que a lógica estruturada em fluxogramas ou pseudocódigos seja traduzida de forma limpa, eficiente e legível.

## 🚀 Tecnologias e Conceitos
*   **Lógica de Programação:** Uso intenso de laços de repetição (`range`) e acumuladores de valores.
*   **Tipagem Dinâmica:** Conversão de entradas de texto (`input`) para números reais (`float`) ou inteiros (`int`).
*   **Interatividade:** Captura de dados em tempo real para processamento imediato.
*   **Saída Formatada:** Uso de *f-strings* para exibição de valores monetários e resultados precisos.

## 📊 Módulos e Regras de Negócio

### 1. 🛒 Processamento de Vendas
O algoritmo automatiza o cálculo de carrinhos de compra com descontos progressivos:
*   **Regra:** Aplica 10% de desconto para compras acima de R$ 500 e 5% para compras acima de R$ 200.
*   **Validação:** Impede o processamento de produtos com preços ou quantidades negativas.

### 2. 🌡️ Análise Climática Semanal
Monitora a variação de temperatura ao longo de uma semana (7 dias):
*   **Alerta:** Identifica condições extremas.
*   **Estatística:** Calcula a média térmica semanal e contabiliza dias de calor intenso (acima de 35°C).

### 3. 🎓 Gestão Acadêmica de Notas
Avalia o desempenho de uma turma de alunos:
*   **Classificação:** 
    *   Média $\ge 7.0$: Aprovado.
    *   Média entre $5.0$ e $6.9$: Recuperação.
    *   Média $< 5.0$: Reprovado.

### 4. 💰 Simulador de Investimentos (Poupança)
Calcula a evolução do patrimônio com aportes mensais e juros compostos:
*   **Lógica:** O saldo é atualizado mensalmente somando o aporte e aplicando a taxa de juros sobre o montante acumulado.
*   **Meta:** Notifica o usuário assim que o saldo ultrapassa a marca de R$ 10.000.

## 🔧 Estrutura do Código Python
Diferente do pseudocódigo estático, em Python utilizamos:
1.  **`input()`**: Para capturar dados do usuário.
2.  **`float()` / `int()`**: Para garantir que os cálculos matemáticos sejam realizados corretamente.
3.  **`range()`**: Para controlar o número exato de iterações (dias, meses ou alunos).
4.  **`print(f"{valor:.2f}")`**: Para limitar as casas decimais em resultados financeiros.

## 🧠 Desafios de Tradução
O maior desafio nesta transição é o **Tratamento de Erros**. Enquanto no papel a lógica aceita "qualquer dado", em Python o desenvolvedor deve prever entradas inválidas (como letras onde deveriam estar números). Para versões futuras, planeja-se a implementação de blocos `try/except` para tornar o sistema à prova de falhas.

---
[Voltar ao perfil](https://github.com/WillV-Code)
