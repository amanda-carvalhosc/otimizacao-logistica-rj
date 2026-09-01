# 🚚 Estudo de Caso Prático: Engenharia de Dados e Otimização Logística (Cenário Fictício)

![Dashboard de Logística](painel.png)


## 📌 Visão Geral do Projeto
Este repositório apresenta o desenvolvimento de um projeto focado em **aperfeiçoamento profissional e desenvolvimento de portfólio**, abordando desafios práticos de **Engenharia de Dados e Business Intelligence** na área de Cadeia de Suprimentos (Supply Chain) e Logística. O objetivo principal deste estudo de caso foi simular o recebimento de uma base de dados operacional bruta e inconsistente de uma filial de transportes no Rio de Janeiro, aplicar técnicas rigorosas de higienização via código Python (Pandas) e estruturar um painel executivo moderno para tomadas de decisão.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas
- **Python 3** (Desenvolvimento da lógica de automação e tratamento)
- **Pandas & NumPy** (Manipulação de matrizes, tratamento de dados e higienização)
- **Google Colab** (Ambiente de desenvolvimento integrado em nuvem)
- **Power BI** (Modelagem de dados, Storytelling visual e Dashboard Executivo)

---

## 📐 O Desafio Operacional Simulado e Regras de Negócio
A base de dados utilizada neste estudo de caso simulou falhas críticas de integridade que costumam inviabilizar análises gerenciais no dia a dia do mercado corporativo. Através do desenvolvimento deste script em Python, foram implementadas as seguintes soluções para resolução de problemas reais de negócios:

1. **Higienização de Textos:** Correção de inconsistências de digitação e falhas de codificação de caracteres (*encoding*) nas variáveis de destino (ex: "São Gonçalo") e status operacionais (ex: "Em trânsito").
2. **Tratamento de Registros Ausentes (NaN):** Desenvolvimento de uma metodologia de inputação baseada na média ponderada do custo de combustível por quilômetro rodado, preenchendo os valores vazios com base na distância real de cada rota.
3. **Auditoria de Capacidade de Frota (Otimização):** Implementação de regras de validação cruzando o peso real da carga transportada com a capacidade máxima de carga do veículo alocado, simulando disparos automáticos de inconformidades operacionais (sobrecarga).

---

## 📊 Resultados e Indicadores Consolidados (Dados Simulados)
Após o processamento e higienização da base pelo algoritmo Python, os seguintes indicadores gerenciais foram consolidados:
- **Custo Total de Transporte (Combustível):** R$ 1.300,90
- **Auditoria de Conformidade:** Identificação de riscos operacionais críticos envolvendo veículos operando acima da capacidade máxima de carga permitida.
- **Centro de Custo por Região:** Identificação automatizada da localidade do Rio de Janeiro como o maior polo de despesas logísticas (R$ 635,40).

---

## 🎨 Modelagem Visual no Power BI
Com a base de dados higienizada e padronizada pelo script Python, o arquivo final `.xlsx` foi modelado no Power BI. 
Foi desenvolvido um dashboard gerencial utilizando o conceito de **Dark Mode (Tema Escuro)** com alto contraste visual (laranja e branco), focado em fornecer uma leitura executiva rápida, limpa e eficiente para gestores e diretores de operações.

---

### 📂 Estrutura de Arquivos do Repositório
- `analise_e_limpeza_logistica.ipynb`: Notebook Python contendo o script de engenharia e tratamento de dados.
- `entregas_limpas_operacao.xlsx`: Base de dados higienizada exportada pelo Python e conectada ao painel visual.


# otimizacao-logistica-rj
Estudo de caso de engenharia de dados e otimização logística utilizando Python (Pandas) no Google Colab e Dashboard Executivo em Dark Mode no Power BI.
