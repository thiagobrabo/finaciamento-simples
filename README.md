# Simulador de Financiamento

## Descrição

Esta é uma calculadora e simulador de financiamento de página única que ajuda os usuários a entender os detalhes de seus empréstimos. A ferramenta permite calcular a taxa de juros, comparar os sistemas de amortização PRICE e SAC, e visualizar o impacto de pagamentos extras na quitação do financiamento.

## Funcionalidades

- **Calculadora de Taxa de Juros:** Calcule a taxa de juros mensal com base no valor financiado, no valor da parcela e no prazo em meses.
- **Simulador de Financiamento:**
    - Simule financiamentos usando os sistemas de amortização **PRICE** (parcelas fixas) e **SAC** (amortização constante).
    - Compare lado a lado os resultados dos dois sistemas.
- **Amortização Inteligente:**
    - Receba sugestões de pagamentos extras mensais com base em diferentes perfis de investimento (Conservador, Moderado, Agressivo, Ultra Agressivo).
    - Visualize a economia de juros e a redução no prazo do financiamento ao aplicar os cenários de amortização.
- **Exportação de Dados (Funcionalidade Futura):**
    - Botões para download da tabela de amortização em formatos **CSV** e **PDF**.

## Tecnologias Utilizadas

- **HTML5:** Estrutura da página.
- **CSS3:** Estilização moderna e responsiva, utilizando Flexbox e variáveis CSS para um tema consistente.
- **JavaScript (ES6+):** Lógica para os cálculos de juros, simulações de amortização e interatividade da página.
- **Google Fonts:** Fonte [Roboto](https://fonts.google.com/specimen/Roboto) para uma melhor legibilidade.
- **jsPDF & jsPDF-AutoTable:** Bibliotecas para a futura implementação da funcionalidade de exportação para PDF.

## Como Usar

1.  Abra o arquivo `index.html` em seu navegador de preferência.
2.  **Para calcular a taxa de juros:**
    - Preencha os campos "Valor Financiado", "Valor da Parcela" e "Prazo (em meses)" na seção "Calculadora de Taxa de Juros".
    - Clique em "Calcular Taxa". A taxa calculada será preenchida automaticamente no simulador.
3.  **Para simular um financiamento:**
    - Preencha os campos "Valor Financiado", "Taxa de Juros Mensal (%)" e "Prazo (em meses)".
    - Opcionalmente, adicione um valor em "Pagamento Extra Fixo Mensal".
    - Clique em "Simular PRICE", "Simular SAC" ou "Comparar PRICE e SAC" para ver as tabelas de amortização.
4.  **Para sugestões de amortização:**
    - Com os dados do financiamento preenchidos, clique em "Sugerir Amortização Inteligente".
    - Analise os cenários e clique em "Aplicar Cenário" para ver a simulação com o pagamento extra sugerido.

## Melhorias Futuras

- [ ] Implementar a funcionalidade de download da tabela de amortização em formato **CSV**.
- [ ] Implementar a funcionalidade de download da tabela de amortização em formato **PDF**.
- [ ] Adicionar gráficos para visualizar a evolução do saldo devedor e a composição das parcelas (juros vs. amortização).
- [ ] Permitir a inclusão de pagamentos extras esporádicos (não apenas fixos mensais).
- [ ] Criar um back-end para salvar e carregar simulações.
