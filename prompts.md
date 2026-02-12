# 🤖 Prompts Estratégicos – Registro de Uso

Este arquivo documenta os prompts utilizados no NotebookLM, as respostas geradas pela IA e a análise dos resultados obtidos.

---

## Prompt 1: Simplificação de Conceitos - Juros Compostos

**Objetivo:** Compreender juros compostos de forma acessível para iniciantes

**Prompt utilizado:**
```
Explique juros compostos como se estivesse falando com alguém que nunca investiu. 
Use um exemplo prático com R$ 500 investidos por 12 meses.
```

**Resposta gerada:**

Imagine que os juros compostos são como uma bola de neve que você joga do topo de uma montanha: ela começa pequena, mas, conforme desce, vai acumulando mais neve e ficando cada vez maior e mais rápida. No mundo do dinheiro, isso significa que você ganha juros sobre juros.

Em vez de ganhar juros apenas sobre o valor que você tirou do bolso, você ganha também sobre os juros que o banco já te pagou nos meses anteriores. É o dinheiro trabalhando para você, criando o que chamamos de ciclo da prosperidade.

**Exemplo Prático: R$ 500,00 por 12 meses**

Investimento em Renda Fixa (CDB ou conta digital) com rendimento de 1% ao mês:

- **Mês 1:** R$ 500,00 → ganha R$ 5,00 de juros → Total: R$ 505,00
- **Mês 2:** R$ 505,00 → ganha R$ 5,05 de juros → Total: R$ 510,05
- **Mês 3:** R$ 510,05 → ganha R$ 5,10 de juros → Total: R$ 515,15
- **Mês 12:** Aproximadamente **R$ 563,41**

**Por que isso é importante:**
1. Renda Passiva: Com o tempo, os juros podem pagar suas contas
2. Perigo da Dívida: O mesmo efeito trabalha contra você nas dívidas (ex: R$ 10.000 no cartão pode virar quase R$ 9 milhões em 5 anos)

**Referências:** Fontes 1, 3 e 5 do NotebookLM

---

## Prompt 2: Exemplos Práticos de Orçamento

**Objetivo:** Criar modelos de orçamento aplicáveis a diferentes perfis

**Prompt utilizado:**
```
Crie 3 exemplos práticos de orçamento pessoal para diferentes perfis:
1. Profissional CLT com salário de R$ 3.000
2. Autônomo com renda variável de R$ 2.500 a R$ 4.000

Para cada um, crie uma tabela com categorias de gastos e percentuais recomendados.
```

**Resposta gerada:**

Com base na regra dos **50/30/20** (50% essenciais, 30% estilo de vida, 20% futuro):

### 1. Profissional CLT (R$ 3.000,00)

| Categoria | Percentual | Valor | Exemplos |
|-----------|-----------|--------|----------|
| Essenciais | 50% | R$ 1.500 | Aluguel, luz, água, mercado, transporte |
| Estilo de Vida | 30% | R$ 900 | Restaurantes, academia, streaming, lazer |
| Futuro/Reserva | 20% | R$ 600 | Pagamento de dívidas ou Reserva de Emergência |

### 2. Autônomo (Renda Variável R$ 2.500 - R$ 4.000)

**Estratégia:** Basear orçamento no valor **mínimo** (R$ 2.500)

| Categoria | Percentual | Valor* | Estratégia |
|-----------|-----------|--------|------------|
| Essenciais | 50% | R$ 1.250 | Manter custo fixo baixo para caber no pior mês |
| Estilo de Vida | 30% | R$ 750 | Controlado; excedente vai para o futuro |
| Futuro/Reserva | 20% | R$ 500 | Foco em reserva maior (sem FGTS) |

*Baseado na renda mínima

### 3. Iniciante/Salário Mínimo (R$ 1.500)

| Categoria | Percentual | Valor | Observação |
|-----------|-----------|--------|------------|
| Essenciais | 60%* | R$ 900 | Foco em sobrevivência |
| Estilo de Vida | 20%* | R$ 300 | Lazer acessível |
| Futuro/Reserva | 20% | R$ 300 | CDB liquidez diária ou Tesouro Selic |

*Essenciais tomam mais espaço, exigindo cortes no estilo de vida

**Dicas aplicadas:**
- Pague-se primeiro: separe os 20% assim que o dinheiro cair
- Evite passivos: não use aumentos para comprar carro/celular caro
- Reserva prioritária: 6 meses de custo de vida antes de renda variável

**Referências:** Fontes 1, 2 e 4 do NotebookLM

---

## Prompt 3: Comparação Estruturada de Investimentos

**Objetivo:** Diferenciar renda fixa e renda variável de forma clara

**Prompt utilizado:**
```
Compare renda fixa e renda variável em uma tabela com os seguintes critérios:
- Nível de risco
- Liquidez
- Rentabilidade esperada
- Tributação
- Perfil de investidor recomendado
- 2 exemplos de cada tipo
```

**Resposta gerada:**

A principal diferença: **previsibilidade**. Renda fixa tem retorno conhecido; renda variável oscila.

| Critério | Renda Fixa | Renda Variável |
|----------|-----------|----------------|
| **Nível de Risco** | Baixo (protegido pelo FGC) | Alto (sem garantias, pode perder tudo) |
| **Liquidez** | Variável (diária ou com prazo fixo) | Longo prazo (5-10 anos recomendado) |
| **Rentabilidade** | Limitada e previsível (12-15% a.a.) | Potencialmente ilimitada (pode ser 1.000%+ ou negativa) |
| **Tributação** | IOF e IR (alíquotas regressivas) | Taxas e oscilações de mercado |
| **Perfil** | Conservador e Moderado | Arrojado e Moderado (com reserva) |
| **Exemplos** | CDB, Tesouro Direto | Ações, Criptomoedas |

**Pontos de atenção:**
- **Segurança FGC:** CDB e LCI têm garantia de até R$ 250 mil por instituição
- **Regra de Ouro:** Nunca comece pela renda variável sendo iniciante
- **Diversificação:** Nunca coloque todo dinheiro em um único lugar

**Referências:** Fontes 3 e 5 do NotebookLM

---

## Prompt 4: Solução de Problemas - Quitação de Dívidas

**Objetivo:** Estratégia para sair do endividamento de forma organizada

**Prompt utilizado:**
```
Sugira um passo a passo detalhado para sair das dívidas, considerando alguém com:
- R$ 5.000 no cartão de crédito (juros 15% a.m.)
- R$ 3.000 em empréstimo pessoal (juros 5% a.m.)
- R$ 1.000 no cheque especial (juros 12% a.m.)
- Renda mensal de R$ 3.500

Organize por ordem de prioridade e explique o motivo.
```

**Resposta gerada:**

### Ordem de Prioridade (pela taxa de juros)

1. **1º - Cartão de Crédito (15% a.m.)** - Dívida mais perigosa
2. **2º - Cheque Especial (12% a.m.)** - Consome saldo ao cair salário
3. **3º - Empréstimo Pessoal (5% a.m.)** - Taxa 3x menor que cartão

**Motivo:** Sempre focar na dívida com **maior taxa de juros**, independente do valor total.

### Passo a Passo Detalhado

**Passo 1: Estanque o sangramento**
- Pare de usar cartão e cheque especial HOJE
- Regra: se não tem dinheiro agora, não compre

**Passo 2: Orçamento de Guerra**
Adaptação da regra 50/30/20 para crise (R$ 3.500 de renda):
- Essenciais: 50% (R$ 1.750) - aluguel, comida, luz
- Estilo de Vida: Corte para 10-15% temporariamente
- Quitação: 35-40% (R$ 1.200-1.400) só para dívidas

**Passo 3: Troque dívida cara por barata**
- Contrate Empréstimo Consignado (2-3% a.m.)
- Quite cartão e cheque à vista
- Unifica em parcela fixa menor

**Passo 4: Renegocie**
- Procure banco ou Serasa
- Muitos aceitam reduzir juros drasticamente

**Passo 5: Renda Extra**
- Use habilidades para bicos/serviços
- Todo valor extra vai direto para abater principal

**Cenário estimado:**
Com R$ 1.300/mês destinados às dívidas:
- Mês 1: Liquida cheque especial
- Meses seguintes: Foco total no cartão

**Referências:** Fontes 2, 4 e 5 do NotebookLM

---

## Prompt 5: Planejamento de Investimentos

**Objetivo:** Montar carteira diversificada para iniciante

**Prompt utilizado:**
```
Como montar uma carteira diversificada de investimentos para um iniciante com:
- R$ 500 disponíveis por mês para investir
- Perfil conservador/moderado
- Objetivo: reserva de emergência + aposentadoria
- Horizonte: 5 anos

Sugira percentuais de alocação e produtos específicos.
```

**Resposta gerada:**

### Estratégia em 2 Fases

**Fase 1: Construção da Reserva (até 6 meses de gastos)**

Destinar **100% dos R$ 500** para alta liquidez:
- Contas digitais (100% CDI): Nubank, Inter
- CDBs com liquidez diária
- Tesouro Selic

**Motivo:** Garantir que não precise fazer dívidas em imprevistos

---

**Fase 2: Diversificação (após reserva pronta)**

| Alocação | Valor | Produto | Objetivo |
|----------|-------|---------|----------|
| 70% Renda Fixa | R$ 350 | CDBs, Tesouro Direto | Segurança (FGC até R$ 250k) |
| 30% Renda Variável | R$ 150 | Fundos Imobiliários (FIIs) | Aposentadoria (renda passiva mensal) |

**Por que esses produtos:**
- **CDB/Tesouro:** Base do conservador, mais rentável que poupança
- **FIIs:** Pagam dividendos mensais, oscilam menos que ações

**Cuidados fundamentais:**
- Pague-se primeiro: separe R$ 500 ao receber renda
- Não invista no que não entende
- Prefira corretoras sem taxas de manutenção

**Referências:** Fontes 3 e 5 do NotebookLM

---

## Próximos passos:
- Testar prompts para simulações financeiras
- Explorar análise de casos reais de investimento
- Criar roteiro de perguntas para revisão periódica

---


