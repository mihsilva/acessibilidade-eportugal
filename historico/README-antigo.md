# ♿ Validação de Acessibilidade - gov.pt

Este repositório documenta os testes automatizados de acessibilidade realizados no site oficial do governo de Portugal ([https://www.gov.pt](https://www.gov.pt)).

---

## 🔧 Ferramentas Utilizadas

- **axe DevTools** – Extensão do Chrome  
- **Versão do axe-core:** 4.10.3  
- **Versão da extensão:** 4.106.1  
- **Padrão avaliado:** WCAG 2.1 AA  
- **Data do teste:** 30/05/2025  
- **Responsável:** michellecarlat@gmail.com

---

## 📊 Resumo do Resultado

| Impacto     | Total de Issues |
|-------------|------------------|
| ⚠️ Crítico   | 2                |
| ❗ Sério     | 1                |
| ⚪ Moderado  | 0                |
| ⚪ Menor     | 0                |
| 🧪 Needs Review | 0            |

---

## ❌ Detalhamento dos Problemas

### 1. Botões sem nome acessível  
- **Regra:** `button-name`  
- **Impacto:** Crítico  
- **Ocorrências:** 2  
- **Descrição:**  
  Os botões identificados não possuem texto discernível por leitores de tela. Isso compromete a acessibilidade para pessoas com deficiência visual.

- **Correções sugeridas:**  
  - Incluir atributo `aria-label` com descrição apropriada.
  - Incluir `title`, `aria-labelledby` ou conteúdo textual visível.

- 🔗 [Mais detalhes sobre a regra](https://dequeuniversity.com/rules/axe/4.10/button-name?application=AxeChrome)

---

### 2. Links sem nome acessível  
- **Regra:** `link-name`  
- **Impacto:** Sério  
- **Ocorrências:** 1  
- **Descrição:**  
  Há um link navegável que não possui texto acessível para leitores de tela ou teclado.

- **Correções sugeridas:**  
  - Adicionar um `aria-label` descritivo ou texto visível que represente o destino da navegação.

- 🔗 [Mais detalhes sobre a regra](https://dequeuniversity.com/rules/axe/4.10/link-name?application=AxeChrome)

---

## 📸 Captura de Tela do Relatório

![Screenshot do axe DevTools](https://axe.deque.com/api/screenshots/5646fac9-161e-4812-a9d4-608b757b312d)

---

## ✅ Próximos Passos

- [ ] Corrigir os elementos apontados no relatório.
- [ ] Executar nova varredura com axe DevTools.
- [ ] Realizar validação cruzada com:
  - [WAVE – Web Accessibility Evaluation Tool](https://wave.webaim.org/)
  - [Validador W3C](https://validator.w3.org/)

---

> Acessibilidade é um direito digital. Garantir acesso a todos é garantir dignidade e inclusão.

