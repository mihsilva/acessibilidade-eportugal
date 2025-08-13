# 📊 Relatório de Acessibilidade – WAVE

**Ferramenta utilizada:** WAVE – Web Accessibility Evaluation Tool  
**Página testada:** [https://www.gov.pt/](https://www.gov.pt/)  
**Data do teste:** 13/08/2025  
**Responsável:** Michelle Silva

---

## 🧾 Resumo

A ferramenta WAVE foi utilizada para identificar barreiras de acessibilidade na página inicial do portal ePortugal. O teste foi realizado diretamente pela extensão do navegador, com análise visual dos elementos destacados.

---

## 🔍 Detalhes dos achados

### ⚠️ Alertas

| Tipo de alerta | Quantidade | Descrição |
|----------------|------------|-----------|
| Estrutura de títulos ausente | 1 | A página não possui uma hierarquia clara de `<h1>`, `<h2>`, etc. |
| Elemento `<noscript>` | 1 | Pode afetar usuários com JavaScript desativado. |

### ✅ Funcionalidades detectadas

| Elemento | Quantidade | Observação |
|----------|------------|------------|
| Definição de idioma (`lang`) | 1 | Presente e corretamente definido como `pt`. |
| Elemento `<main>` | 1 | Indica corretamente o conteúdo principal da página. |

### 🔧 ARIA

| Atributo ARIA | Quantidade | Observação |
|---------------|------------|------------|
| Elementos com ARIA | 11 | Uso de `aria-label`, `aria-hidden`, entre outros. |
| Regiões vivas (live region) | 1 | Pode ser útil para notificações dinâmicas. |
| `aria-hidden` | 6 | Deve ser validado para garantir que não esconda conteúdo relevante. |

---

## 🖼 Captura de tela

![Captura WAVE – Detalhes](../imagens/wave-erros.png)

---

## 📚 Referências

- [WAVE Tool – Site oficial](https://wave.webaim.org/)
- Critérios relacionados da WCAG:
  - **1.3.1** – Informação e relacionamentos
  - **2.4.6** – Cabeçalhos e rótulos
  - **4.1.2** – Nome, função, valor

---

## 📌 Conclusão

A análise com WAVE revelou **problemas estruturais leves**, como ausência de hierarquia de títulos e presença de elementos que podem afetar a experiência de usuários com configurações específicas. O uso de ARIA é positivo, mas requer validação manual para garantir conformidade.

**Próximos passos recomendados:**
- Reorganizar os títulos da página para refletir a estrutura semântica correta
- Validar manualmente os atributos ARIA com leitor de tela
- Avaliar o impacto do `<noscript>` na experiência de navegação

---
