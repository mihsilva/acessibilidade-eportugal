# 📊 Relatório de Acessibilidade - gov.pt

Este relatório apresenta os resultados da análise automatizada de acessibilidade da página [gov.pt](https://www.gov.pt/), realizada com a ferramenta **axe DevTools HTML**.

---

## 🧪 Informações do Teste

- **URL testada:** https://www.gov.pt/
- **Ferramenta:** axe DevTools HTML (Extensão Chrome)
- **Versão da extensão:** 4.106.1  
- **Versão do axe-core:** 4.10.3  
- **Padrão avaliado:** WCAG 2.1 AA  
- **Responsável:** michellecarlat@gmail.com  
- **Data do teste:** 30/05/2025  
- **Início:** 20:37:40 UTC  
- **Término:** 20:37:40 UTC  
- **Boas práticas ativadas:** ❌  
- **Recursos experimentais ativados:** ❌  

---

## ✅ Resumo do Resultado

| Tipo de Problema         | Quantidade |
|--------------------------|------------|
| ❗ Crítico                | 2          |
| ⚠️ Grave (Serious)       | 1          |
| 🔸 Moderado              | 0          |
| 🔹 Leve (Minor)          | 0          |
| 📘 Boas Práticas         | —          |
| ❓ Requer Revisão Manual | 0          |

---

## ❌ Problemas Identificados

### 1. **[button-name] - Botões sem texto discernível**  
> Os seguintes botões não possuem texto ou atributos acessíveis visíveis por leitores de tela.

**Quantidade:** 2  
**Impacto:** Crítico  
**Correção recomendada:**  
Adicionar `aria-label`, `title`, ou conteúdo textual dentro do botão.

#### Elementos afetados:
- `<button aria-haspopup="dialog">`  
  - **Descrição:** Abre painel de busca, mas sem texto visível.  
  - [🔗 Saiba mais](https://dequeuniversity.com/rules/axe/4.10/button-name?application=AxeChrome)

- `<button aria-controls="panel-content-MenuBurger">`  
  - **Descrição:** Botão de menu hamburguer sem texto ou label.  
  - [🔗 Saiba mais](https://dequeuniversity.com/rules/axe/4.10/button-name?application=AxeChrome)

---

### 2. **[link-name] - Link sem texto acessível**  
> Link exibido como ícone apenas, sem texto visível para tecnologias assistivas.

**Quantidade:** 1  
**Impacto:** Grave  
**Correção recomendada:**  
Adicionar texto visível ou `aria-label` descritivo.

#### Elemento afetado:
- `<a href="https://area-reservada.digital.gov.pt/entrar" class="link-with-icon icon-only">`  
  - **Descrição:** Link de acesso à área reservada com ícone, mas sem rótulo acessível.  
  - [🔗 Saiba mais](https://dequeuniversity.com/rules/axe/4.10/link-name?application=AxeChrome)

---

## 📝 Conclusão

O teste identificou **3 barreiras significativas de acessibilidade** no site **gov.pt**, todas relacionadas à **falta de rótulos acessíveis** em botões e links. Recomendamos corrigir os elementos indicados para garantir a conformidade com o padrão **WCAG 2.1 AA** e oferecer uma experiência mais inclusiva para todos os usuários.

---

📸 **[Captura de tela do teste](https://axe.deque.com/api/screenshots/5646fac9-161e-4812-a9d4-608b757b312d)**  
🧪 **Teste executado automaticamente com axe DevTools HTML**
