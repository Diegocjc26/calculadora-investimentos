﻿# 📈 Calculadora de Investimentos Web

Um projeto interativo e responsivo desenvolvido para simular o crescimento de investimentos ao longo do tempo, considerando aportes iniciais, contribuições adicionais, taxas de retorno e impostos. A ferramenta oferece visualizações claras através de gráficos e uma tabela detalhada.

## ✨ Funcionalidades

- **Cálculo Detalhado:** Simula o valor final do investimento com base em:
  - Capital Inicial.
  - Aportes Adicionais Regulares.
  - Prazo (em meses ou anos).
  - Taxa de Retorno (mensal ou anual).
  - Taxa de Imposto sobre o Lucro.
- **Visualização Clara de Dados:**
  - **Gráfico de Pizza (Doughnut Chart):** Exibe a distribuição final do dinheiro entre o "Total Investido", "Rendimento" e "Imposto".
  - **Gráfico de Barras (Bar Chart):** Mostra a progressão mensal do "Total Investido" e do "Retorno do Investimento".
- **Tabela de Resultados Mensais:** Uma tabela dinâmica que detalha a evolução mês a mês do investimento, incluindo: Mês, Total Investido, Rendimento Mensal, Rendimento Total e Quantia Total.
- **Design Responsivo (Mobile-First):** Layout adaptável para diferentes tamanhos de tela, garantindo uma ótima experiência em dispositivos móveis e desktops.
- **Validação de Entrada:** Mensagens de erro claras para campos numéricos inválidos ou valores menores ou iguais a zero.
- **Navegação por Carrossel:** Transição suave entre a seção de gráficos e a tabela de resultados.
- **Botões de Navegação Inteligentes:** Os botões de avançar/voltar do carrossel aparecem e desaparecem dinamicamente conforme a posição atual da visualização (gráficos ou tabela), melhorando a usabilidade.
- **Limpeza de Dados:** Botão "Limpar" para resetar o formulário, os gráficos e a tabela, permitindo novas simulações.
- **Recálculo Eficiente:** Ao clicar em "Calcular" novamente, os gráficos e a tabela são completamente atualizados sem duplicar informações.

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estrutura semântica da aplicação.
- **CSS (Tailwind CSS):** Framework de CSS utility-first para estilização rápida e responsiva.
- **JavaScript:** Lógica de cálculo, manipulação do DOM e interatividade.
- **Chart.js:** Biblioteca JavaScript para criação de gráficos.

## 🚀 Como Usar

1.  **Acesse a Aplicação:** Se a aplicação estiver hospedada online, basta abrir o link em seu navegador. Caso contrário, siga as instruções em "Como Executar Localmente".
2.  **Preencha os Campos:** Insira os valores desejados para o seu investimento nos campos do formulário (Investimento Inicial, Aportes Adicionais, Prazo, Rentabilidade e Impostos sobre Lucro).
3.  **Calcular:** Clique no botão "Calcular" para ver os resultados e os gráficos gerados.
4.  **Navegue pelos Resultados:** Use as setas laterais do carrossel para alternar entre os gráficos e a tabela de resultados mensais.
5.  **Limpar:** Clique no botão "Limpar" para resetar todos os campos e visualizações e fazer uma nova simulação.

## �� Como Executar Localmente

Para rodar este projeto em sua máquina:

1.  **Clone o Repositório:**

    ```bash
    git clone https://github.com/Diegocjc26/calculadora-investimentos.git
    cd calculadora-investimentos # Navegue até a pasta do projeto
    ```

    _(Se você não está usando Git, pode simplesmente baixar o arquivo ZIP do projeto e descompactá-lo.)_

2.  **Abra no Navegador:**
    Abra o arquivo `index.html` diretamente em seu navegador web preferido (Google Chrome, Firefox, Edge, etc.). Não é necessário configurar um servidor local, pois é uma aplicação estática.

## 🙏 Agradecimentos

Este projeto foi desenvolvido com base nos conhecimentos e didática da **Hashtag Treinamentos**, que forneceu a fundação para a construção desta aplicação web.

## 💡 Melhorias Futuras Possíveis

- Adicionar opções para diferentes tipos de impostos ou alíquotas progressivas.
- Funcionalidade para salvar e carregar simulações.
- Otimização de performance para um grande número de meses na simulação.
- Opção de exportar os resultados da tabela (CSV, PDF).
- Implementar um "Dark Mode" para o layout.
- Melhorias na acessibilidade (ARIA attributes).

## 🧑‍💻 Autor

Diego (Estudante de programação e IAs)

Com o apoio e guidance do modelo de IA One, desenvolvido pela Adapta.

---
