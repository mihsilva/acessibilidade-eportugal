# Estudo de Caso: Avaliação de Acessibilidade no Portal www.gov.pt – Etapa 1

**Autora:** Michelle Silva  
**Ferramentas utilizadas:**  
- WAVE (Web Accessibility Evaluation Tool)  
- axe DevTools (versão 4.10.3)

**Data da análise:** [21/05/2025]  
**Seção analisada:** Aba *"Serviços e Informações"* do portal [www.gov.pt](https://www.gov.pt)

---

## Objetivo

Realizar uma avaliação de acessibilidade em uma página pública de Portugal, utilizando ferramentas automáticas, com o intuito de identificar barreiras que possam impactar negativamente a experiência de pessoas com deficiência. Esta é a primeira etapa do estudo, focada na aba *"Serviços e Informações"*.  

Este estudo faz parte de um projeto pessoal com fins educacionais, publicado no GitHub, com o propósito de demonstrar minhas habilidades como QA com foco em acessibilidade.

---

## Resultados Resumidos

### 1. WAVE – WebAIM
- **Erros:** 0  
- **Erros de contraste:** 9  
- **Alertas:** 9  
- **Funcionalidades detectadas:** 19  
- **Elementos estruturais:** 67  
- **Elementos ARIA:** 663

**Observações:**  
A ausência de erros críticos é um ponto positivo, porém os erros de contraste e alertas indicam que ainda há espaço para melhorias no design e na hierarquia de conteúdos da página.

### 2. axe DevTools
- **Total de problemas detectados:** 3  
  - **Críticos:** 2  
  - **Graves:** 1  
- **Principais problemas encontrados:**
  - Botões sem texto identificável (2 ocorrências)
  - Links sem texto discernível (1 ocorrência)

**Observações:**  
Esses problemas podem impactar diretamente usuários que utilizam leitores de tela, pois os elementos interativos não estão devidamente identificados.

---

## Conclusão (Etapa 1)

A análise inicial da aba *"Serviços e Informações"* do portal [www.gov.pt](https://www.gov.pt) demonstra um bom nível de acessibilidade estrutural, especialmente pela ausência de erros críticos no WAVE. No entanto, foram identificadas falhas no axe DevTools, principalmente relacionadas à acessibilidade de botões e links.  

**As próximas etapas** deste estudo envolverão as abas *"Locais de Atendimento"* e *"Contactos"*, com o objetivo de ampliar a cobertura da análise de acessibilidade do portal.

---

## Repositório GitHub

Este estudo está sendo publicado neste repositório:  
👉 [https://github.com/mihsilva/acessibilidade-eportugal](https://github.com/mihsilva/acessibilidade-eportugal)
