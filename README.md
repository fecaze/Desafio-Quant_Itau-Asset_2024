# Desafio Quant | Itaú Asset - 2024

CRYPO – Estrategista Quantitativo em Criptomoedas

O **CRYPO** é um projeto de estratégia quantitativa aplicada ao mercado de criptomoedas, desenvolvido em **Python**, com foco em **diversificação, rebalanceamento sistemático e uso de indicadores técnicos** para busca de retornos ajustados ao risco superiores ao Bitcoin.

O nome *CRYPO* traduz a essência do universo cripto de forma simples, moderna e direta, representando um robô ágil, orientado a dados e constantemente atento às dinâmicas do mercado.

---

## 📌 Visão Geral da Estratégia

- **Tipo:** Portfolio Strategy  
- **Classe de Ativos:** Criptomoedas  
- **Holding Period:** 1 mês  
- **Média de Trades:** 1 a 3 por mês  
- **Plataforma:** Python  
- **Benchmark:** Total Market Cap (TMC) do Bitcoin  

A estratégia realiza uma **alocação inicial fixa**, com **rebalanceamento mensal**, baseado no desempenho dos últimos 3 meses. A cada 6 meses, a estratégia passa por uma revisão estrutural considerando o TMC do Bitcoin.

---

## 🧠 Motivação

Apesar da dominância do Bitcoin no mercado cripto, essa concentração cria oportunidades relevantes em ativos alternativos com menor correlação e maior potencial de retorno.

O objetivo do CRYPO é:
- Reduzir dependência de ativos dominantes  
- Explorar oportunidades em criptomoedas menos correlacionadas  
- Maximizar retorno ajustado ao risco  
- Oferecer uma alternativa quantitativa ao *buy and hold* de Bitcoin  

---

## 🌐 Universo de Ativos

O universo inicial foi definido com base no relatório **“The Global Crypto Classification Standard” (CoinGecko, 2023)**.

### Processo de Seleção
1. Seleção dos **50 principais criptoativos**
2. Filtro por data de lançamento (até 2017)
3. Análise de **correlação com Bitcoin e Ethereum**
4. Seleção de ativos com **correlação absoluta ≤ 0,3**

### Carteira Final
- USDT  
- DASH  
- XEM  
- EOS  
- BCN  
- STRAX  
- LSK  
- FCT  
- REP  

---

## ⚖️ Alocação de Pesos

Os pesos foram definidos com base na **variação percentual absoluta do preço ajustado** no período de otimização. Após o cálculo, os valores foram **normalizados** para totalizar 100%.

Essa abordagem privilegia ativos com maior volatilidade histórica, buscando maior potencial de ganho da carteira.

---

## 📈 Estratégia de Trading – MACD

A estratégia utiliza o **MACD (Moving Average Convergence/Divergence)** para geração de sinais de compra e venda.

### Regras de Sinal
- **Compra:** EMA curta cruza acima da EMA longa  
- **Venda:** EMA curta cruza abaixo da EMA longa  

### Parâmetros Testados
- **EMA curta:** 10, 20, 30, 40 ou 50 dias  
- **EMA longa:** 50, 100, 150, 200 ou 250 dias  

Os parâmetros foram **otimizados individualmente para cada criptomoeda**, maximizando o retorno histórico no período de otimização.

---

## ⏱️ Períodos de Análise

- **Período de Otimização:** 30/12/2017 → 30/12/2021  
- **Período de Teste (Out-of-Sample):** 30/12/2021 → 30/12/2023  

---

## 📊 Resultados

### Retorno da Carteira
- **Retorno Total (2 anos):** **+14,72%**

### Volatilidade
- **Diária:** 0,34%  
- **Anualizada:** 5,41%  
- **Acumulada (2 anos):** 7,64%  

### Métricas de Risco
- **Índice de Sharpe (Federal Funds Rate):** Positivo  
- **Índice de Sharpe (CMC200):** Elevado  
- **Beta em relação ao CMC200:** **-0,002**  

A estratégia apresentou **baixa correlação com o mercado de criptomoedas**, operando de forma próxima a um perfil *market neutral*.

---

## 🧩 Conclusões

- Superou o *buy and hold* do Bitcoin no período analisado  
- Apresentou excelente eficiência risco-retorno frente ao mercado cripto  
- Funcionou como instrumento de **diversificação de portfólio**  
- Estratégia adequada para perfis com **alta tolerância ao risco**

---

## 🛠️ Tecnologias Utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Dados históricos de criptomoedas  

---

## ⚠️ Aviso Legal

Este projeto possui **finalidade exclusivamente educacional e acadêmica**.  
Não constitui recomendação de investimento.  
Resultados passados não garantem retornos futuros.

---

## 📬 Contato

**Autor:** Seu Nome  
**LinkedIn:** https://www.linkedin.com/in/seu-perfil  

---

