# 🏥 Sistema de Triagem de Saúde Pública (SUS)

## 📝 Descrição do Projeto
Este projeto consiste em um algoritmo de automação para a triagem de pacientes em unidades de saúde pública. O objetivo principal é otimizar o fluxo de atendimento, classificando a urgência dos casos com base em sinais vitais (temperatura, frequência cardíaca), idade e risco imediato de morte.

O sistema foi desenhado para traduzir problemas do mundo real em estruturas de decisão binária, garantindo que casos críticos recebam socorro imediato enquanto organiza a fila de espera prioritária e comum.

## 🚀 Tecnologias e Conceitos
*   **Lógica de Programação:** Estruturas de decisão encadeadas (`SE / SENÃO`).
*   **Pseudocódigo:** Representação estruturada da lógica de entrada, processamento e saída.
*   **Modelagem de Processos:** Fluxograma detalhado do fluxo do paciente desde a entrada até o encaminhamento médico.

## 📊 Funcionalidades e Regras de Negócio
O algoritmo avalia as seguintes condições para determinar o tipo de atendimento:

*   **🚨 Socorro Imediato:** Identificado quando há risco de morte iminente confirmado no input.
*   **🔥 Atendimento Prioritário (Clínico):** Ativado se a frequência cardíaca for $\ge 150$ bpm ou a temperatura for $\ge 39°C$ (febre alta).
*   **👵 Atendimento Prioritário (Idade):** Pacientes com idade $\ge 60$ anos são automaticamente classificados como prioridade.
*   **🩺 Atendimento Comum:** Destinado a casos que não apresentam alterações nos sinais vitais acima ou critérios de idade/risco.

## 🔧 Estrutura do Algoritmo
O fluxo segue a seguinte ordem de captura de dados:
1.  **Identificação:** Nome, CPF/Passaporte e Data de Nascimento.
2.  **Triagem Técnica:** Coleta de Temperatura, Frequência Cardíaca e Idade.
3.  **Avaliação de Risco:** Verificação subjetiva de risco de morte.



## 🧠 Desafios de Desenvolvimento
Durante a concepção, o maior desafio foi a tradução das nuances do atendimento médico para uma estrutura lógica binária. Para futuras versões, planeja-se a implementação de *failsafes* para aumentar a resiliência contra falhas humanas ou de sensores, permitindo múltiplas verificações antes do diagnóstico final.

---
[Voltar ao perfil](https://github.com/seu-usuario)
