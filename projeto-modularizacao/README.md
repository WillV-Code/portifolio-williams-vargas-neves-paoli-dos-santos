## 🚀 Tecnologias e Conceitos
* **Lógica de Programação:** Estruturas de decisão bivalentes (`SE / SENÃO`) e modularização por funções.
* **Pseudocódigo:** Representação estruturada com funções específicas para validação, cálculo e decomposição.
* **Modelagem de Processos:** Fluxogramas detalhados que separam a lógica principal (Main) dos módulos de apoio.
* **Aritmética Computacional:** Uso de operadores de divisão inteira e resto (`%`) para contagem de cédulas.

## 📊 Funcionalidades e Regras de Negócio
O algoritmo avalia as seguintes condições para processar a venda:

* **✅ Validação de Pagamento:** O sistema verifica se o valor pago ($V\_PAG$) é maior ou igual ao valor total ($V\_TOT$). Caso seja inferior, o sistema retorna erro.
* **💵 Cálculo de Troco:** Se o pagamento for válido, o sistema calcula a diferença exata a ser devolvida ao cliente.
* **📉 Decomposição de Notas:** O valor do troco é processado para identificar a quantidade de notas de **100, 50, 10, 5 e 1**.
* **🖥️ Saída de Dados:** Exibição clara do valor total do troco e a discriminação quantitativa de cada cédula.

## 🔧 Estrutura do Algoritmo
O fluxo segue a seguinte hierarquia de módulos conforme as imagens:
1.  **Entrada:** Leitura das variáveis `V_TOT` (Valor Total) e `V_PAG` (Valor Pago).
2.  **Módulo Validar_Pagamento:** Retorna um valor booleano (Verdadeiro/Falso).
3.  **Módulo Calcular_Troco:** Realiza a operação aritmética de subtração.
4.  **Módulo Calc_Nota:** Função auxiliar que utiliza `Troco / Nota` para a quantidade e `Troco % Nota` para o saldo remanescente.
5.  **Módulo Decompor_Notas:** Orquestra as chamadas sucessivas para as diferentes denominações de papel-moeda.

## 🧠 Desafios de Desenvolvimento
Durante a concepção, o maior desafio foi a implementação da modularidade, garantindo que a função de decomposição atualizasse o saldo do troco corretamente a cada passo (reutilização de variáveis de retorno). Para futuras versões, planeja-se a inclusão de moedas (centavos) e a integração com métodos de pagamento digital.

---
[Voltar ao perfil](https://github.com/seu-usuario)
