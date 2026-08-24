# 🧪 Testes de Prompts

Este documento registra os principais prompts utilizados durante o desenvolvimento do Caderno Temático no NotebookLM.

O objetivo é demonstrar a evolução das perguntas utilizadas e os ajustes realizados para melhorar a qualidade das respostas.

---

## Prompt 1 — Pergunta inicial

> Explique como criar uma ficha de D&D.

### Problema identificado

A pergunta é muito ampla e pode produzir uma resposta genérica.

---

## Prompt 2 — Direcionamento para iniciantes

> Explique passo a passo como criar uma ficha de personagem de D&D para uma pessoa que nunca jogou RPG. Explique cada conceito utilizando linguagem simples e apresente exemplos práticos.

### Resultado

A resposta apresentou uma estrutura mais adequada para iniciantes, porém ainda faltavam explicações específicas sobre cada campo da ficha.

---

## Prompt 3 — Preenchimento campo a campo

> Atue como um instrutor de D&D para jogadores iniciantes. Explique o preenchimento da ficha de personagem campo por campo, seguindo uma ordem lógica.
>
> Para cada campo:
>
> 1. Explique o que ele significa;
> 2. Explique o que deve ser colocado nele;
> 3. Explique como obter essa informação;
> 4. Apresente um exemplo;
> 5. Explique erros comuns que um iniciante pode cometer.
>
> Baseie as respostas prioritariamente nas fontes disponíveis no notebook e indique as fontes utilizadas.

### Resultado

A resposta passou a apresentar maior detalhamento e organização.

---

# 🩹 Cicatrizes / Troubleshooting

## Problema 1 — Respostas genéricas

**Problema:** a pergunta inicial não especificava o nível de conhecimento do usuário.

**Solução:** definir o público como iniciante e solicitar explicações passo a passo.

---

## Problema 2 — Excesso de termos técnicos

**Problema:** alguns conceitos poderiam ser difíceis para alguém que nunca jogou D&D.

**Solução:** solicitar linguagem simples, exemplos e explicação dos termos antes de utilizá-los.

---

## Problema 3 — Diferenças entre versões das regras

**Problema:** materiais de diferentes versões de D&D podem apresentar regras ou processos diferentes.

**Solução:** definir explicitamente qual versão das regras será utilizada no projeto e priorizar fontes compatíveis.

---

## 📌 Aprendizado

Os testes demonstraram que prompts mais específicos, contextualizados e estruturados produzem respostas mais úteis para o objetivo do projeto.
