# 🩺 Estudo Preditivo de Diabetes: Árvores de Decisão

[![Python](https://shields.io)](https://python.org)
[![Scikit-Learn](https://shields.io)](https://scikit-learn.org)
[![Jupyter](https://shields.io)](https://jupyter.org)
[![License: MIT](https://shields.io)](https://opensource.org)

Este repositório contém um estudo técnico avançado sobre a aplicação de **Árvores de Decisão** para o diagnóstico de diabetes, utilizando o dataset *Pima Indians Diabetes*. O projeto confronta duas abordagens de modelagem: uma focada em padrões profissionais de estabilidade e outra em exploração acadêmica de dados.

## 🚀 Estrutura do Projeto

O projeto foi desenhado seguindo as melhores práticas de engenharia de software e ciência de dados:

*   **`Analise_Preditiva_Diabetes.ipynb`**: Relatório dinâmico com a narrativa, dashboards e vereditos.
*   **`modelagem_diabetes.py`**: Motor do projeto que centraliza a lógica de treinamento, métricas e visualizações customizadas.
*   **`diabetes.csv`**: Base de dados com indicadores de saúde (Glicose, IMC, Idade, etc.).
*   **`Referencial_Teorico.ipynb`**: Documentação técnica detalhada sobre Hiperparâmetros (Gini, Entropia, Depth) e Métricas.

## 💻 Pré-requisitos e Instalação

O projeto foi desenvolvido utilizando o **Visual Studio Code (VS Code)**. Para reproduzir os resultados em sua máquina, você precisará de:

1.  **Python 3.8+** instalado.
2.  **Extensões do VS Code**: [Python Extension](https://visualstudio.com) e [Jupyter Extension](https://visualstudio.com).

### Bibliotecas Utilizadas e Aplicações
As bibliotecas essenciais e o motivo de sua utilização no projeto são:
*   **[Pandas](https://pydata.org)**: Utilizada para a ingestão do arquivo CSV, tradução de colunas e manipulação das tabelas de resultados e rankings.
*   **[Scikit-Learn](https://scikit-learn.org)**: Motor principal de Machine Learning. Usada para instanciar o algoritmo `DecisionTreeClassifier`, realizar o `train_test_split` e calcular todas as métricas de performance.
*   **[Matplotlib](https://matplotlib.org)**: Responsável por toda a camada visual, incluindo gráficos de barras customizados, curvas ROC sobrepostas e estilização.
*   **[Ipywidgets](https://readthedocs.io)**: Utilizada para criar a interface interativa (menus suspensos).
*   **[IPython.display](https://readthedocs.io)**: Essencial para a renderização de tabelas formatadas e componentes de interface no Notebook.

> **Observação sobre Instalação:** O projeto possui gestão automática de dependências. Ao executar o **Bloco 2 do Tópico 4** no arquivo `Analise_Preditiva_Diabetes.ipynb`, o sistema verificará o ambiente e realizará a instalação das bibliotecas necessárias automaticamente caso não sejam encontradas.

## 📊 Metodologia de Experimentos

Foram desenvolvidas duas baterias de testes independentes:

1.  **Experimento Profissional:** Focado no controle de **Profundidade (Max Depth)**. Utiliza um split fixo de 25% para teste, visando criar modelos estáveis.
2.  **Experimento Acadêmico:** Focado no **Crescimento Livre** e variações de proporção de dados (**Split**).

## 🛠️ Recursos e Dashboards

O notebook oferece ferramentas interativas para análise granular:

*   **Comparativo de Importância:** Identifica quais fatores de saúde são mais determinantes.
*   **Matrizes de Confusão:** Avaliação detalhada de Falsos Negativos e Falsos Positivos.
*   **Duelo ROC Sobreposto:** Confronto direto de até 4 modelos simultâneos.

## 🍴 Como Usar, Clonar ou Contribuir

Se você deseja explorar este código, realizar seus próprios testes ou sugerir melhorias, siga os passos abaixo:

### 1. Criando sua própria cópia (Fork)
Se você pretende modificar o código e salvar as alterações no seu perfil do GitHub, clique no botão **Fork** (localizado no canto superior direito desta página). Isso criará uma cópia idêntica deste repositório na sua conta.

### 2. Clonando para sua máquina local
Para baixar os arquivos e rodar o projeto, clique no botão verde **"<> Code"** (acima da lista de arquivos) e copie o link exibido. Em seu terminal, digite:
```bash
git clone https://github.com
```
*(Nota: Se você fez um Fork, substitua o link acima pelo link do seu próprio repositório).*

## ⚠️ Observações Gerais
*   **Ambiente Virtual**: Recomenda-se o uso de um `.venv` para evitar conflitos de bibliotecas.
*   **Hardware**: Código leve, compatível com computadores básicos.
*   **Dados**: O dataset `diabetes.csv` deve estar na mesma pasta do código.

## 🏁 Veredito Final

O projeto conclui com um **Ranking Global de Desempenho** ordenado por relevância clínica, priorizando o **AUC** e o **Recall**.

---

## 📜 Licença
Este projeto está sob a licença **MIT** - consulte o arquivo [LICENSE](LICENSE) para detalhes.

---
**Disciplina:** Mineração de Dados  
**Instituição:** UFPA - Campus de Tucuruí  
**Grupo 07:** Pamella Roberta Ferreira da Silva & Fabricio Baia Vasconcelos
