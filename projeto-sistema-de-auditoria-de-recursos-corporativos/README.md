# 🏢 Auditoria de Orçamentos Corporativos (Python)
 
[![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)
[![Status](https://img.shields.io/badge/status-concluído-brightgreen.svg)]()
 
## 📖 Sobre o Projeto
Este projeto foi desenvolvido como parte da disciplina de **Progamação de Computadores** do curso de **Ciência da Computação**.  
O objetivo do script é processar e calcular o orçamento total de uma estrutura organizacional complexa, representada por dicionários aninhados, simulando o ambiente corporativo de uma multinacional.

A solução foi arquitetada utilizando conceitos avançados da linguagem Python para garantir **flexibilidade**, **escalabilidade**, **performance** e **rastreabilidade**, características comuns em sistemas backend de médio e grande porte.
 
## 🚀 Funcionalidades
- **Cálculo Hierárquico:** Varredura completa da estrutura corporativa, independentemente do nível de profundidade da hierarquia.
- **Filtros Dinâmicos:** Capacidade de ignorar setores específicos e todos os seus subsetores durante o cálculo financeiro.
- **Conversão de Câmbio:** Suporte a parâmetros opcionais para conversão de moedas em tempo de execução.
- **Sistema de Auditoria:** Monitoramento automatizado do tempo de execução e registro dos parâmetros utilizados na operação financeira.
 
## 🛠️ Tecnologias e Conceitos Aplicados
Este projeto foi construído utilizando **Python puro (Standard Library)**, com foco nos seguintes paradigmas e recursos:

- **Funções Recursivas (Recursion):**  
  Utilizadas para navegar pela árvore de dados (dicionários aninhados), permitindo que o cálculo funcione corretamente independentemente da profundidade da estrutura organizacional.

- **Decorators:**  
  Implementação do decorator `@auditor`, responsável por adicionar auditoria de execução (logging e tempo) sem modificar a lógica principal da aplicação.

- **Empacotamento de Argumentos (`*args` e `**kwargs`):**  
  Uso de `*args` para passagem dinâmica de departamentos ignorados e `**kwargs` para parâmetros opcionais como taxa de câmbio e moeda de destino.
 
## ⚙️ Como Executar
 
### ✅ Pré-requisitos
- Python **3.8 ou superior** instalado.
 
### ▶️ Passo a Passo
1. Clone este repositório:
   ```bash
   git clone (https://github.com/WillV-Code/portfolio-williams-vargas-neves-paoli-dos-santos.git)

   ```
2. Acesse a pasta do projeto:
   ```bash
   cd seu-repositorio
   ```
3. Execute o script principal:
   ```bash
   python main.py
   ```
 
## 🧠 Lógica e Estrutura do Código
Breve explicação de como o código foi organizado:
* A lógica do projeto foi construída a partir da necessidade de percorrer uma estrutura organizacional hierárquica de profundidade desconhecida, tornando a recursão a abordagem mais adequada.
A função principal percorre cada nível da árvore de dados, somando apenas os valores finais (folhas), enquanto ignora dinamicamente departamentos informados pelo usuário.
O decorator de auditoria foi acoplado à função de cálculo para registrar dados da execução, como argumentos recebidos e tempo total de processamento, seguindo o princípio de separação de responsabilidades, muito utilizado em projetos backend profissionais.
* **Dados:** Os dados da empresa foram estruturados como um dicionário aninhado, onde cada chave representa um departamento ou subdepartamento, e os nós finais contêm os valores numéricos de orçamento.
 
## 👤 Autor
 
* **Williams Vargas Neves Paoli dos Santos** * LinkedIn: <https://www.linkedin.com/in/williams-paoli-98315b407>
* E-mail: williamspaoli1@gmail.com
 
---
*Projeto acadêmico com foco na aplicação prática de conceitos avançados da linguagem Python.*
