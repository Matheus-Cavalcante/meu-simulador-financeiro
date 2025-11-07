# Meu Simulador Financeiro

Este projeto consiste em uma planilha desenvolvida para simular investimentos ao longo do tempo.  
Ela permite calcular o crescimento do patrimônio com base em aportes mensais e juros compostos, ajudando o usuário a visualizar o efeito do tempo e da taxa de rendimento sobre o valor investido.

## Objetivo

Criar uma ferramenta prática e intuitiva para o controle e planejamento financeiro pessoal, facilitando o entendimento dos conceitos de juros compostos e de crescimento de investimentos.

## Funcionalidades

- Cálculo automático de juros compostos com e sem aportes mensais.  
- Campos configuráveis para valor inicial, aporte mensal, taxa de juros e tempo de investimento.  
- Exibição do total acumulado, total investido e total de juros ganhos.  
- Interface simples e fácil de usar, podendo ser aberta no Excel ou Google Sheets.  

## Como usar

1. Baixe o arquivo **Projeto_Matheus.xlsx**.  
2. Abra a planilha no **Microsoft Excel** ou **Google Sheets**.  
3. Insira os valores desejados nos campos de entrada:  
   - Valor inicial do investimento  
   - Aporte mensal  
   - Taxa de juros (% ao mês)  
   - Número de meses  
4. A planilha mostrará automaticamente o valor total acumulado e o rendimento obtido ao longo do tempo.

## Fórmula utilizada

O cálculo de juros compostos utilizado na planilha segue a fórmula:

Valor Futuro = Valor Inicial × (1 + Juros)^Tempo + Aporte × [(1 + Juros)^Tempo - 1] / Juros

Onde:
- Valor Inicial é o montante aplicado no início;
- Juros é a taxa de rendimento por período (geralmente mensal);
- Tempo é o número de períodos (meses);
- Aporte é o valor investido periodicamente.

## Estrutura do projeto

- Projeto_Matheus.xlsx → planilha principal com as fórmulas e cálculos  
- README.md → documentação explicando o funcionamento  

## Aplicações possíveis

- Planejar objetivos financeiros pessoais;  
- Simular cenários com diferentes taxas e prazos;  
- Entender como aportes regulares aceleram o crescimento do investimento;  
- Apoiar decisões sobre poupança e metas financeiras.  

## Licença

Este projeto é de uso livre para fins pessoais e educacionais.  
Desenvolvido por **Matheus Cavalcante**.
