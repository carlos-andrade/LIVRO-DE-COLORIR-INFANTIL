# Auditoria técnica dos protótipos de ilustração — V1

**Data:** 2026-11-12  
**Escopo:** avaliação visual e metadados dos três protótipos ART-001, ART-006 e ART-008.  
**Status geral:** REFERÊNCIA VISUAL — NÃO APROVADO PARA IMPRESSÃO.

## 1. Inventário técnico

| ID | Tema | Dimensões em pixels | Orientação | DPI declarado |
|---|---|---:|---|---|
| ART-001 | Gato | 1199 × 1312 | Retrato | Não informado |
| ART-006 | Borboleta | 1536 × 1024 | Paisagem | Não informado |
| ART-008 | Elefante | 1312 × 1199 | Paisagem | Não informado |

Os três arquivos são RGB e não apresentam metadados DPI incorporados. As proporções são diferentes entre si.

## 2. Avaliação visual

### ART-001 — Gato
- Personagem imediatamente reconhecível, expressão amigável e contorno forte.
- Boa distribuição de áreas internas para colorir.
- Orelhas e patas ficam relativamente próximas dos limites da composição.
- **Decisão:** manter como referência de estilo; recompor com margem de segurança maior.

### ART-006 — Borboleta
- Simetria clara, asas amplas e áreas grandes para preenchimento.
- Elementos decorativos internos são simples e adequados ao conceito.
- Composição horizontal; não corresponde ao padrão de página vertical proposto.
- **Decisão:** manter como referência; gerar nova composição vertical sem cortes.

### ART-008 — Elefante
- Silhueta reconhecível, expressão amigável e áreas amplas.
- Orelha esquerda e tromba aproximam-se dos limites laterais/superior.
- Composição horizontal; não corresponde ao padrão de página vertical proposto.
- **Decisão:** manter como referência; gerar nova composição vertical com margem de segurança.

## 3. Não conformidades para impressão

1. Dimensões e proporções inconsistentes.
2. Ausência de resolução física/DPI declarada.
3. Ausência de página-mestre e margens de segurança padronizadas.
4. Arquivos ainda não comprovados em escala real de impressão.
5. Arquivos de protótipo não devem ser tratados como masters finais.

**Nota:** aumentar o DPI por interpolação não cria detalhe real. A solução preferencial é gerar/recompor cada arte na proporção final e na resolução necessária, preservando linhas limpas.

## 4. Critérios para aprovação final

- Definir formato de corte KDP e especificação de interior antes da finalização.
- Padronizar todas as artes na mesma proporção e área útil.
- Garantir margem de segurança e ausência de elementos cortados.
- Validar preto puro nas linhas e fundo branco, sem cinzentos ou artefatos.
- Inspecionar cada página em escala real e em prova PDF.
- Arquivar original gerado, master editável quando disponível e arquivo final de impressão.
- Registrar autoria/licença e cadeia de proveniência dos elementos.

## 5. Decisão e próximos passos

Os três protótipos ficam **APROVADOS COMO REFERÊNCIA DE DIREÇÃO ARTÍSTICA**, mas **REPROVADOS COMO ARQUIVOS FINAIS DE IMPRESSÃO**.

Ordem de execução:
1. Definir formato físico do livro.
2. Fixar template de página, margens e resolução.
3. Regerar ART-001, ART-006 e ART-008 nesse padrão.
4. Aprovar os três masters antes de produzir as outras 27 artes.

## 6. Proveniência e armazenamento

Na data desta auditoria, os PNGs foram inspecionados no ambiente de trabalho da sessão, mas ainda não foram incorporados ao repositório. Este documento registra os resultados técnicos; não representa o armazenamento dos binários nem a aprovação de arquivos finais.


## 7. Aditivo de execução — 2026-11-12

Foram realizadas novas tentativas de geração para reconstruir as artes em formato individual. O processo continuou retornando composições com três painéis (gato, borboleta e elefante) em um único arquivo, apesar da solicitação de arquivos independentes. Essas composições não serão aceitas como páginas finais nem recortadas e ampliadas para simular resolução efetiva de 300 DPI.

**Decisão:** manter os painéis compostos somente como referência de direção artística. ART-006 (borboleta) e ART-008 (elefante) continuam sem masters individuais aprovados. ART-001 (gato) possui protótipos individuais, mas também permanece pendente de master final com dimensões e qualidade de impressão verificadas.

Nenhum binário novo foi incorporado ao repositório nesta etapa. A produção deve retomar com fluxo de geração/ilustração que garanta um único assunto por arquivo e resolução nativa adequada, seguida de inspeção e prova.
