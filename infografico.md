# Especificação Técnica e Visual do Infográfico

**Projeto de Extensão CESUTech 2026/2 — Conectando Gerações e Impulsionando o Futuro e o Protagonismo Digital**  
**Equipe:** Mateus Suman Carpenter

---

## 1. Configuração do Frame Principal (Canvas)

| Propriedade | Valor Recomendado | Observações |
| :--- | :--- | :--- |
| **Dimensão do Frame** | **`1200 px` × `2200 px`** | Proporção ideal para pôster vertical / alta definição; comporta a ilustração de `992 px` com folga lateral adequada. |
| **Opção A4 (Impressão)** | **`1240 px` × `1754 px`** | Padrão A4 a 150 DPI. Caso utilize este, reduza os espaçamentos verticais entre blocos em ~15%. |
| **Cor de Fundo (Fill)** | `#F5F2EB` *(Warm Paper / Bege Editorial)* | Tom suave e quente, fiel à referência estética. |
| **Margens Laterais (Padding)** | **`60 px`** (esquerda e direita) | Margem de segurança para os elementos visuais. |
| **Layout Grid (Colunas)** | **12 colunas** \| Gutter: `16 px` \| Margin: `60 px` | Alinhamento preciso para as 2 colunas da metade inferior. |

---

## 2. Paleta de Cores (Color Styles)

| Nome do Estilo | Código Hex | Aplicação Recomendada |
| :--- | :---: | :--- |
| **`Dark/Title`** | `#14171A` | Título principal, perguntas e ênfases de grande porte. |
| **`Dark/Body`** | `#33373D` | Textos explicativos, legendas e citações normativas. |
| **`Primary/Blue`** | `#2A405A` | Pilar Ensino, nó esquerdo do infinito e card Extensão. |
| **`Accent/Terracotta`** | `#D05A3F` | Pilar Pesquisa, nó direito do infinito e destaque da Síntese. |
| **`Accent/Sage Green`** | `#52735B` | Pilar Extensão, centro do infinito e ícone Avaliar. |
| **`Neutral/Sand`** | `#DED7CB` | Linhas divisórias horizontais e verticais (*stroke* de 1.5px a 2px). |
| **`Surface/White`** | `#FFFFFF` | Fundo dos cards e da caixa de síntese (*Drop Shadow* suave: X: 0, Y: 4, Blur: 12, Opacidade: 6%). |

---

## 3. Guia Tipográfico (Text Styles)

> **Família Tipográfica:** Plus Jakarta Sans (primária) ou Inter (secundária para corpo).

| Estilo de Texto | Família | Peso (Weight) | Tamanho | Line Height | Tracking | Transform |
| :--- | :--- | :--- | :---: | :---: | :---: | :---: |
| **H1 - Título Principal** | Plus Jakarta Sans | **Black (900)** | `44 px` | `105%` | `-0.02em` | UPPERCASE |
| **H2 - Subtítulo Obrigatório** | Plus Jakarta Sans | **Bold (700)** | `18 px` | `120%` | `+0.04em` | UPPERCASE |
| **H3 - Título de Seção** | Plus Jakarta Sans | **ExtraBold (800)** | `20 px` | `115%` | `+0.02em` | UPPERCASE |
| **H4 - Subtítulo de Eixo** | Plus Jakarta Sans | **Bold (700)** | `15 px` | `120%` | `0` | UPPERCASE |
| **Card Title / Destaque** | Plus Jakarta Sans | **ExtraBold (800)** | `13 px` | `120%` | `+0.01em` | UPPERCASE |
| **Body / Descritivo** | Plus Jakarta Sans | **Medium (500)** | `12 px` | `135%` | `0` | Normal |
| **Tag / Badge / Micro** | Plus Jakarta Sans | **Bold (700)** | `10 px` | `110%` | `+0.05em` | UPPERCASE |
| **Rodapé / Referências** | Plus Jakarta Sans | **Regular (400)** | `9.5 px` | `130%` | `0` | Normal |

---

## 4. Diagramação Espacial do Infográfico

```text
+-------------------------------------------------------------------+
|  [H1] EXTENSÃO UNIVERSITÁRIA:                                     |
|  [H2] DA UNIVERSIDADE PARA A COMUNIDADE E DA COMUNIDADE PARA...   |
+-------------------------------------------------------------------+
|  [H3] O TRIPÉ ACADÊMICO (ART. 207 CF/88)                          |
|                                                                   |
|          [ilustracao-universidade-comunidade.png (W: 780px)]      |
|  (Rótulos flutuantes: ENSINO, PESQUISA, EXTENSÃO)                |
|  [Legenda central: RETROALIMENTAÇÃO PERMANENTE...]                |
+-------------------------------------------------------------------+
|  [H3] DINÂMICA DIALÓGICA: UNIVERSIDADE E COMUNIDADE               |
|                                                                   |
|          [ilustracao-ensino-pesquisa-extensao.png (W: 720px)]     |
|  (3 Caixas de texto: Esquerda, Centro e Direita)                  |
+-------------------------------------------------------------------+
|  GRID DE 2 COLUNAS (Separadas por Stroke vertical #DED7CB):      |
|                                 |                                 |
|  [COLUNA 1: PROTAGONISMO]       |  [COLUNA 2: COMPARATIVO]        |
|  • O Aluno como Agente Ativo    |  • Extensão vs. Voluntariado... |
|  • Composição:                  |  • Superação do Elitismo        |
|    - Anel hexagonal (fundo)     |  • 3 Cards em Pilha:            |
|    - Corredor (centro)          |    [ Card Extensão Curricular ] |
|    - 6 Fases ao redor           |    [ Card Voluntariado ]        |
|                                 |    [ Card Assistencialismo ]    |
+-------------------------------------------------------------------+
|  [BOX DESTACADO BRANCO] SÍNTESE FINAL                             |
|  [H3] POR QUE UMA UNIVERSIDADE DEVE ATUAR NA SOCIEDADE?           |
|  [Texto em 4 linhas com barra lateral Terracotta]                 |
+-------------------------------------------------------------------+
|  [FOOTER] Fontes Consultadas (ABNT) + Nomes da Equipe             |
+-------------------------------------------------------------------+
```

---

## 5. Conteúdo Textual (Copywriting Final)

### Bloco 1: Topo / Cabeçalho
* **Caixa 1 (H1):**  
  `EXTENSÃO UNIVERSITÁRIA:`
* **Caixa 2 (H2):**  
  `DA UNIVERSIDADE PARA A COMUNIDADE E DA COMUNIDADE PARA A UNIVERSIDADE`

### Bloco 2: O Tripé Acadêmico
* **Título de Seção (H3):**  
  `O TRIPÉ ACADÊMICO (ART. 207 CF/88)`
* **Label Pilar Esquerdo (Azul):**  
  **`ENSINO`**  
  `Organiza, contextualiza e sistematiza o saber acadêmico.`
* **Label Pilar Central (Terracotta):**  
  **`PESQUISA`**  
  `Investiga a realidade e produz novos conhecimentos científicos.`
* **Label Pilar Direito (Verde):**  
  **`EXTENSÃO`**  
  `Conecta essas esferas à sociedade em processo transformador.`
* **Legenda Base (Centralizada):**  
  `RETROALIMENTAÇÃO PERMANENTE: A extensão oxigena o ensino e a pesquisa, trazendo as demandas complexas da sociedade para o centro da produção universitária.`

### Bloco 3: Dinâmica Dialógica
* **Título de Seção (H3):**  
  `DINÂMICA DIALÓGICA: UNIVERSIDADE E COMUNIDADE`
* **Caixa Esquerda (sobre o nó azul):**  
  **`INTERAÇÃO HORIZONTAL E TRANSFORMADORA`**  
  `Problemas sociais reais reorientam os processos de investigação científica.`
* **Caixa Central (sobre a junção do nó):**  
  **`DIÁLOGO ENTRE CIÊNCIA E SABER POPULAR`**  
  `Integra sujeitos sociais como legítimos coautores, unindo conhecimento técnico e saberes tradicionais.`
* **Caixa Direita (sobre o nó laranja):**  
  **`VIA DE MÃO DUPLA`**  
  `Conhecimento acadêmico e saber comunitário se enriquecem mutuamente.`

### Bloco 4 (Esquerda): Protagonismo do Estudante
* **Título (H3):**  
  `PROTAGONISMO DO ESTUDANTE`
* **Subtítulo (H4):**  
  `O ALUNO COMO AGENTE ATIVO`
* **Rótulo Central do Anel:**  
  `CICLO DE ATUAÇÃO DO ESTUDANTE`
* **Os 6 Passos ao Redor do Hexágono:**
  1. `1. ESCUTAR` — *Acolher as demandas da comunidade*
  2. `2. INVESTIGAR` — *Diagnóstico técnico do contexto*
  3. `3. PLANEJAR` — *Co-criação com os parceiros*
  4. `4. AGIR` — *Execução aplicada (PBL)*
  5. `5. AVALIAR` — *Medição conjunta dos impactos*
  6. `6. REFLETIR` — *Impacto ético-social e ciclo duplo*

### Bloco 4 (Direita): Comparativo de Extensão
* **Título (H3):**  
  `EXTENSÃO VS. VOLUNTARIADO VS. ASSISTENCIALISMO`
* **Texto de Apoio (Superação do Elitismo):**  
  `SUPERAÇÃO DO ELITISMO ACADÊMICO: A extensão rompe a ideia da universidade como única produtora de saber, reconhecendo a legitimidade da comunidade.`
* **Card 1 (Extensão Universitária):**  
  * **Título:** `EXTENSÃO UNIVERSITÁRIA (CURRICULAR 10%)`  
  * **Descrição:** `Intencionalidade pedagógica articulada a ensino e pesquisa. Foco na emancipação duradoura e aprendizagem reflexiva de ciclo duplo.`  
  * **Destaque Caso Real:** `Exemplo Real: Consultorias de Marketing (PBL) para mulheres microempreendedoras (Prêmio Sebrae 2024 / Oliveira, 2024).`
* **Card 2 (Voluntariado):**  
  * **Título:** `VOLUNTARIADO (AÇÃO OPCIONAL)`  
  * **Descrição:** `Ação solidária espontânea. Relevante civicamente, porém sem vinculação curricular obrigatória ou método de pesquisa científica.`
* **Card 3 (Ação Assistencial):**  
  * **Título:** `AÇÃO ASSISTENCIAL (EMERGENCIAL)`  
  * **Descrição:** `Atendimento paliativo a necessidades imediatas, sem transformar as causas estruturais nem promover a autonomia comunitária.`

### Bloco 5: Síntese Final (Questão Norteadora)
* **Tag Superior:**  
  `SÍNTESE FINAL COLETIVA`
* **Pergunta de Destaque:**  
  `POR QUE UMA UNIVERSIDADE DEVE ATUAR DIRETAMENTE NA SOCIEDADE?`
* **Resposta (Exatamente 4 Linhas Argumentadas):**  
  > *“Para cumprir sua função social constitucional e transformar conhecimento acadêmico em emancipação humana. Essa atuação direta oxigena a academia pela troca dialógica de saberes, consolida a formação de cidadãos conscientes, qualifica a práxis profissional dos estudantes e co-constrói soluções sustentáveis com a comunidade.”*

### Bloco 6: Rodapé Institucional
* **Referências ABNT:**  
  `Fontes Consultadas: BRASIL. Resolução CNE/CES nº 7/2018; Parecer CNE/CES nº 608/2018; FONTENELE, I. C. (Rev. Katálysis, 2024); MIGUEL, J. C. (Práxis Educativa, 2023); OLIVEIRA, P. H. P. (Regae, 2024); ARGYRIS & SCHÖN (1997); AYAS & ZENIUK (2001).`
* **Identificação:**  
  `Projeto de Extensão CESUTech 2026/2 – Conectando Gerações | Equipe: Mateus Suman Carpenter`

---

## 6. Diretrizes Técnicas para Diagramação

1. **Auto Layout:** Recomenda-se a utilização de Auto Layout com espaçamento de `24px` no frame principal para garantir alinhamento e fluxo vertical consistente.
2. **Escala de Ativos Gráficos:** Ao redimensionar arquivos PNG (diretório `componentes`), deve-se preservar a proporção original para evitar distorções.
3. **Profundidade e Sombreamento:** Para hierarquização visual de cards e elementos centrais, aplicar sombreamento sutil: `X: 0, Y: 4, Blur: 16, Spread: 0, Color: #1A1A1A a 5%`.
4. **Exportação:** Exportar o frame principal em formato **PDF** ou **PNG @2x / @3x** para manter a integridade e nitidez tipográfica durante a apresentação.
