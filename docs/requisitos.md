# 📋 Requisitos do Sistema — CasaCerta

## 1. Visão Geral
O sistema CasaCerta tem como objetivo auxiliar usuários na tomada de decisão entre financiamento imobiliário e consórcio, através de simulações e análises comparativas.

---

## 2. Requisitos Funcionais

### RF01 — Simulação de Financiamento
O sistema deve permitir simular financiamento imobiliário com base em:
- Valor do imóvel
- Valor de entrada
- Taxa de juros
- Prazo

---

### RF02 — Simulação de Consórcio
O sistema deve permitir simular consórcio com:
- Valor da carta de crédito
- Taxa administrativa
- Prazo

---

### RF03 — Comparação
O sistema deve comparar:
- Custo total
- Valor das parcelas
- Tempo de aquisição

---

### RF04 — Exibição de Resultados
O sistema deve exibir:
- Parcelas mensais
- Custo total
- Tempo estimado

---

### RF05 — Recomendações
O sistema deve gerar recomendações com base no perfil do usuário:
- Renda
- Urgência
- Objetivo

---

### RF06 — Autenticação
O sistema deve permitir:
- Cadastro de usuário
- Login
- Autenticação via JWT

---

### RF07 — Simulação de Lance
O sistema deve permitir:
- Inserir valor de lance
- Simular impacto na contemplação

---

### RF08 — Estimativa de Contemplação
O sistema deve estimar o prazo de contemplação com base em:
- Histórico médio
- Lance informado

---

### RF09 — Relatórios
O sistema deve gerar:
- Relatórios personalizados
- Comparações detalhadas

---

## 3. Requisitos Não Funcionais

### RNF01 — Usabilidade
Interface simples e intuitiva.

### RNF02 — Performance
Tempo de resposta inferior a 2 segundos.

### RNF03 — Compatibilidade
Compatível com navegadores desktop modernos.

### RNF04 — Segurança
- Uso de JWT
- Proteção de dados sensíveis

### RNF05 — Escalabilidade
Arquitetura modular e organizada.

---

## 4. Público-Alvo
- Pessoas interessadas em imóveis
- Jovens planejando finanças
- Usuários leigos em finanças
