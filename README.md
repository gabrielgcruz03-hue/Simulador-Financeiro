
# Simulador Financeiro 💰

Este projeto foi criado para ajudar no controle e planejamento de investimentos mensais, permitindo visualizar o crescimento do patrimônio ao longo do tempo com base em parâmetros configuráveis.

---

## 🧩 Estrutura da Planilha

A planilha contém três seções principais:

### 1. CONFIGURAÇÕES
- **Salário:** valor base mensal.
- **Rendimento da Carteira:** taxa de retorno estimada (%).
- **Sugestão de Investimento:** percentual do salário destinado a investimentos.

### 2. INVESTIMENTO MENSAL
- **Quanto investir por mês:** valor calculado a partir da sugestão.
- **Por quantos anos:** período de investimento.
- **Taxa de rendimento mensal:** taxa aplicada sobre o capital.
- **Patrimônio acumulado:** total estimado ao final do período.
- **Dividendos mensais:** retorno mensal esperado.

### 3. CENÁRIOS
Simulações automáticas para diferentes horizontes de tempo:
| Período | Patrimônio | Dividendos |
|----------|-------------|------------|
| 2 anos | R$ 34.306,81 | R$ 205,84 |
| 5 anos | R$ 105.558,91 | R$ 633,35 |
| 10 anos | R$ 306.538,11 | R$ 1.839,23 |
| 20 anos | R$ 1.417.749,98 | R$ 8.506,50 |
| 30 anos | R$ 5.445.933,77 | R$ 32.675,60 |

---

## 📊 Perfil de Investidor
A planilha também sugere uma distribuição de investimentos conforme o perfil (exemplo: **Conservador**):

| Tipo de FII | Percentual | Valor |
|--------------|-------------|-------|
| Papel | 30% | R$ 378,00 |
| Tijolo | 50% | R$ 630,00 |
| Híbridos | 10% | R$ 126,00 |
| FoFs | 10% | R$ 126,00 |

---

## 🛠️ Como foi criada
1. **Base de cálculo:** fórmulas de juros compostos para projeção de crescimento.
2. **Automação:** uso de funções do Excel como `FV`, `PMT` e `SE`.
3. **Design:** cores e seções organizadas para facilitar leitura e simulação.
4. **Validação:** testes com diferentes taxas e períodos para garantir precisão.

---

## 🚀 Como usar
1. Abra o arquivo `Simulador-Financeiro.xlsx`.
2. Ajuste os valores de salário, taxa e anos conforme sua realidade.
3. Observe os resultados automáticos nos cenários e gráficos.

---

## 📈 Exemplo visual
![Captura da Planilha](<img width="675" height="750" alt="Capturar" src="https://github.com/user-attachments/assets/8b182bf7-b949-49c9-9ccc-f3b70c9be824" />
)

---

## 🧠 Créditos
Projeto inspirado no curso da [DIO - Criando uma Ferramenta de Controle de Investimentos com Excel](https://web.dio.me/lab/criando-uma-ferramenta-de-controle-de-investimentos-com-excel/learning/14151e92-a01d-42fe-befb-9f45c77062f2?back=/track/santander-excel-2026).

Autor: **Gabriel G. Cruz**
