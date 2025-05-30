# Relatório de Acessibilidade – gov.pt  
📅 **Data do teste:** 30/05/2025  
🔍 **Ferramenta utilizada:** axe DevTools (Versão 4.106.1)  
📖 **Padrão avaliado:** WCAG 2.1 AA  

---

## 🔗 URL Avaliada

https://www.gov.pt/

## ⏱️ Período de Teste

- Início: 30/05/2025 – 20:37:40
- Fim: 30/05/2025 – 20:37:40

## 🧪 Resumo da Avaliação

| Severidade     | Quantidade de Erros |
|----------------|---------------------|
| 🔴 Crítico      | 2                   |
| 🟠 Sério        | 1                   |
| 🟡 Moderado     | 0                   |
| 🔵 Menor        | 0                   |

---

## ❌ Falhas Detectadas

### 1. [button-name](https://dequeuniversity.com/rules/axe/4.10/button-name?application=AxeChrome) – **Criticidade: Crítica**

> **Descrição:** Botões devem ter texto discernível.

**Ocorrências: 2**

**Elementos afetados:**

- `<button aria-haspopup="dialog">` (botão sem texto visível nem rótulo acessível)
- `<button aria-controls="panel-content-MenuBurger" aria-label="">` (botão com atributo `aria-label` vazio)

---

### 2. [link-name](https://dequeuniversity.com/rules/axe/4.10/link-name?application=AxeChrome) – **Criticidade: Séria**

> **Descrição:** Links devem ter texto discernível.

**Ocorrência: 1**

**Elemento afetado:**

- `<a class="link-with-icon icon-only" href="https://area-reservada.digital.gov.pt/entrar">` (link somente com ícone, sem texto acessível)

---

## 📎 Fonte do Teste

- **Produto:** axe DevTools HTML
- **Versão do axe-core:** 4.10.3
- **Criado por:** michellecarlat@gmail.com

## 🖼️ Captura de Tela

[screenshot](https://axe.deque.com/api/screenshots/5646fac9-161e-4812-a9d4-608b757b312d)

---

## ✅ Conformidades (sem erros)

Nenhuma regra foi marcada como manual ou como "precisa de revisão" nesta análise.

---

## 📌 Notas Finais

Este relatório documenta a avaliação automatizada inicial. Recomenda-se realizar validações manuais complementares para uma análise completa de acessibilidade.

---

**Relatório gerado automaticamente com axe DevTools**  
🔧 Criado por Michelle Silva
