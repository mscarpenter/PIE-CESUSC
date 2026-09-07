# PIE — Projeto Integrador Extensionista

> **Projeto de Extensão CESUTech 2026/2 — Conectando Gerações e Impulsionando o Futuro e o Protagonismo Digital**  
> *Faculdade UNICESUSC | Florianópolis, SC*  
> **Autor:** Mateus Suman Carpenter  

## Visão Geral do Projeto

Este repositório documenta o desenvolvimento analítico, visual e técnico da **Atividade 01: Compreendendo a Extensão Universitária**, cujo objetivo é responder de forma fundamentada e gráfica à questão norteadora:

> ### *"Por que uma universidade deve atuar diretamente na sociedade?"*

O resultado final é um **Infográfico Editorial em página única**, estruturado no Figma e acompanhado de um **Mini-App Web Interativo** para consulta detalhada das evidências acadêmicas, leis e pareceres normativos que sustentam cada decisão visual.

![Infográfico Final](assets/infografico-final-v2.jpg)

---

## Navegação Rápida

* **[Mini-App Interativo (GitHub Pages)](https://mscarpenter.github.io/PIE-CESUSC/):** Versão web com hotspots clicáveis e consulta direta às fontes bibliográficas.
* **[Projeto no Figma](https://www.figma.com/design/Jjd1Sn0VJ38R0LKLBwQmc2/Infografico?node-id=0-1):** Artboard, Design System, componentes vetoriais e Auto Layouts.
* **[Declaração de Uso de IA & Processo](processo.md):** Relatório transparente sobre o uso de Gemini, Copilot, Claude e Antigravity via MCP.
* **[Dossiê de Pesquisa dos 9 Eixos](desenvolvimento.md):** Tabela de fichamento, justificativa epistemológica e roteiro de oratória (pitch de 5 min).
* **[Especificação Visual](infografico.md):** Guia tipográfico, paleta de cores e parâmetros de diagramação.
* **[Checklist de Conformidade](todo.md):** Controle de requisitos acadêmicos da atividade.

---

## Os Cinco Pilares Estruturais do Infográfico

O infográfico articula visualmente as diretrizes da **Resolução CNE/CES nº 7/2018** e da **Constituição Federal de 1988 (Art. 207)** através de cinco blocos integrados:

```text
+-----------------------------------------------------------------------------------------------+
|  1. O TRIPÉ ACADÊMICO (ART. 207 CF/88)                                                        |
|     Articulação indissociável: Ensino (sistematiza), Pesquisa (investiga) e Extensão (conecta)|
+-----------------------------------------------------------------------------------------------+
|  2. DINÂMICA DIALÓGICA: UNIVERSIDADE E COMUNIDADE                                             |
|     Relação horizontal de mão dupla e superação da transmissão vertical de conhecimento.      |
+-----------------------------------------------+-----------------------------------------------+
|  3. PROTAGONISMO DO ESTUDANTE                 |  4. O GRANDE COMPARATIVO CONCEITUAL           |
|     Ciclo ativo em 6 etapas: Escutar,          |     • Extensão: Vínculo curricular e método.  |
|     Investigar, Planejar, Agir, Avaliar,       |     • Voluntariado: Ação altruísta pontual.   |
|     Refletir (Donald Schön / PBL).            |     • Assistencialismo: Alívio paliativo.     |
+-----------------------------------------------+-----------------------------------------------+
|  5. SÍNTESE FINAL: TRANSFORMAÇÃO SOCIAL E FORMAÇÃO PROFISSIONAL                               |
|     Resposta argumentada em 4 linhas demonstrando que a função social da universidade é       |
|     construir soluções "com as pessoas, e não apenas para elas".                              |
+-----------------------------------------------------------------------------------------------+
```

---

## Matriz Resumida dos Nove Eixos de Pesquisa

| Eixo Teórico / Normativo | Base Legal / Fonte Acadêmica | Síntese do Conceito Aplicado |
| :--- | :--- | :--- |
| **1. Definição de Extensão** | Resolução CNE/CES nº 7/2018 (Art. 3º e 4º) | Processo formativo e curricular obrigatório (mín. 10%) de interação transformadora. |
| **2. Indissociabilidade** | Art. 207 da CF/88; Miguel (2023) | O ensino fundamenta, a pesquisa aprofunda e a extensão retroalimenta ambos na prática. |
| **3. Objetivos e Diretrizes** | Parecer CNE/CES nº 608/2018 (Art. 5º) | Diálogo social, formação cidadã, interdisciplinaridade e impacto regional duradouro. |
| **4. Relação de Mão Dupla** | Fontenele (2024); Parecer 608/2018 | Substituição da postura professoral pela escuta ativa e coautoria com a comunidade. |
| **5. Comparativo Rigoroso** | Miguel (2023); Parecer 608/2018 | Diferenciação categórica entre Extensão Curricular, Voluntariado e Assistencialismo. |
| **6. Protagonismo Discente** | Resolução 7/2018 (Art. 6º); Oliveira (2024) | Estudante como condutor central e tomador de decisões em problemas sociais reais. |
| **7. Formação Integral** | Resolução 7/2018; Fontenele (2024) | Integração entre técnica profissional e sensibilidade humana, ética e cidadã. |
| **8. Troca de Saberes** | Fontenele (2024); Parecer 608/2018 | Reconhecimento epistemológico de que o saber popular e o acadêmico se completam. |
| **9. Caso Real Aplicado** | Oliveira (2024) - Regae/UFSM | Projeto com metodologia PBL em Marketing para microempreendedoras (Prêmio Sebrae 2024). |

---

## Tecnologias e Metodologia Empregada

O projeto combinou rigor científico, design visual e automação com agentes inteligentes:

* **Design e UI:** [Figma](https://figma.com) (componentes vetoriais, grid de 12 colunas, tokens de cores e Auto Layouts responsivos).
* **Protocolo MCP (Model Context Protocol):** Conexão direta entre IDE e a API do Figma para inspeção estrutural de camadas, refatoração de layout e validação de parâmetros.
* **Inteligência Artificial Generativa:** Uso declarado e ético de **Google Gemini / NotebookLM**, **GitHub Copilot**, **Claude** e **Google Antigravity** via MCP.
* **Tratamento Gráfico:** NanoBanana para vetorização e equilíbrio tonal de ilustrações.
* **Web:** HTML5 semântico, Tailwind CSS e Vanilla JavaScript para o mini-app interativo.

---

## Estrutura de Arquivos

```text
PIE/
├── README.md                      # Apresentação do projeto para GitHub/Portfólio
├── index.html                     # Mini-App interativo para GitHub Pages
├── infografico.md                 # Especificação técnica visual e copywriting
├── processo.md                    # Relatório metodológico e declaração formal de IA
├── desenvolvimento.md             # Tabela de pesquisa detalhada e roteiro do pitch
├── todo.md                        # Checklist acadêmico de controle da entrega
├── assets/
│   ├── infografico-final-v2.jpg   # Imagem em altíssima resolução (4x/2x)
│   └── componentes/               # Ícones e ilustrações originais exportados
├── material-apoio/                # Documentos oficiais da disciplina (PDFs e DOCXs)
└── referencias-basicas/           # Artigos acadêmicos e pareceres do CNE/MEC
```

---

## Autoria e Identificação Acadêmica

* **Aluno:** Mateus Suman Carpenter
* **Matrícula / E-mail Institucional:** 2521660@unicesusc.edu.br
* **Disciplina:** Projeto de Extensão CESUTech 2026/2
* **Docente Responsável:** Coordenação de Extensão UNICESUSC
* **Florianópolis, Setembro de 2026**
