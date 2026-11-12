# Fluxo de montagem contínua do Livro 01

**Projeto:** Meu Mundo em Cores  
**Versão:** 1.0  
**Data:** 2026-11-12

## Objetivo

Manter um PDF de acompanhamento atualizado durante a produção, para que a apresentação do livro possa ser avaliada a cada nova ilustração aprovada.

## Estrutura do miolo

- 64 páginas de trabalho.
- Páginas 1–4: abertura editorial.
- Páginas 5, 7, 9 ... 63: 30 páginas individuais de ilustração.
- Páginas 6, 8, 10 ... 64: versos em branco.
- Cada ilustração ocupa uma página exclusiva.
- Nenhuma montagem, colagem, painel múltiplo ou triptico será usado no miolo.

## Fluxo por ilustração

1. Gerar a ilustração identificada (ART-001 a ART-030).
2. Verificar se é uma única composição, adequada ao tema e à faixa etária.
3. Preparar master editável e exportação no padrão de página.
4. Conferir proporção, margens, traços, resolução efetiva e ausência de cortes.
5. Aprovar formalmente a arte.
6. Inserir a arte na página reservada correspondente.
7. Exportar uma nova versão integral do PDF de acompanhamento.
8. Registrar a versão, páginas alteradas e estado da arte.

## Dois arquivos distintos

### PDF de acompanhamento
- Mostra páginas ainda não preenchidas com identificadores de produção.
- Serve para revisar sequência, ritmo visual, abertura e evolução do livro.
- Não é arquivo para venda ou impressão comercial.

### PDF final de impressão
- Não contém placeholders, etiquetas técnicas ou marcas de revisão.
- Mantém apenas o conteúdo editorial aprovado e as ilustrações finais.
- Só será exportado após fechamento editorial e validação no KDP Print Previewer.

## Controle de versões

Convenção:
- `MEU_MUNDO_EM_CORES_PROVA_V0.1.pdf`
- `MEU_MUNDO_EM_CORES_PROVA_V0.2.pdf`
- `MEU_MUNDO_EM_CORES_PROVA_V0.3.pdf`

Cada nova inclusão de arte aprovada gera uma nova versão integral. Não sobrescrever versões anteriores.

## Estado inicial

A versão inicial contém 64 páginas, com 30 páginas de ilustração reservadas e versos em branco. Os espaços reservados são elementos de revisão e serão removidos no PDF final de impressão.


## Diretriz de habitat/contexto

Cada ilustração adicionada ao PDF deve trazer, além do personagem principal, um pequeno contexto ambiental coerente (habitat natural, ambiente doméstico ou cenário de uso). O contexto será composto por poucos elementos grandes e simples, sem competir com o personagem. A referência completa por ART-001 a ART-030 está em [Briefing das 30 ilustrações](BRIEFING_30_ILUSTRACOES_V1.md#6-diretriz-complementar--habitat-e-contexto-das-30-páginas).


## Registro de montagem — V0.3 — 2026-11-12

- PDF integral de acompanhamento gerado: `MEU_MUNDO_EM_CORES_PROVA_DE_TRABALHO_V0.3.pdf`.
- Total: 64 páginas; tamanho de página verificado em 8,5 × 11 pol. (612 × 792 pt).
- ART-001 (gato) foi inserida na página 5, com cenário de jardim/quintal doméstico.
- Página 6 permanece em branco, conforme a regra de impressão somente na frente.
- As páginas ART-002 a ART-030 continuam como espaços reservados com habitat/contexto descrito.
- A imagem de ART-001 foi extraída de uma geração em dupla página e recortada para compor a página individual. O recorte mede 709 × 926 px a aproximadamente 96 DPI; portanto, é **somente uma prévia visual de baixa resolução**, não master nem arquivo pronto para impressão.
- A arte ainda apresenta moldura externa gerada, que deverá ser removida na revisão do master para cumprir o padrão oficial sem borda pesada.
- Nenhum arquivo de arte foi aprovado para publicação. A página 5 está em estado **PROTÓTIPO INSERIDO — REVISÃO PENDENTE**.

Próxima ação: gerar ou redesenhar ART-001 em fonte vetorial ou raster nativo de alta resolução, sem moldura, mantendo o gato e o habitat coerente; atualizar o PDF integral após a aprovação. Depois avançar para ART-002.


## Registro de montagem — V0.5 (2026-11-12)

- Capa frontal colorida: incluída como estudo provisório no PDF de acompanhamento.
- ART-001 — Gato: página 5 permanece preenchida com estudo visual de baixa resolução; não aprovado como master de impressão.
- ART-002 — Cachorro: estudo visual individual extraído de composição gerada, inserido na página 7; não aprovado como master de impressão.
- Versos das páginas de atividade permanecem em branco.
- Total do PDF de acompanhamento: 64 páginas, incluindo capa frontal de estudo e 30 posições de atividade.
- A capa ainda não é o wrap completo KDP (contracapa + lombada + frente). A paginação do miolo e o papel deverão ser confirmados antes de calcular a lombada.
- Os arquivos de imagem utilizados nesta versão são estudos provisórios e não têm resolução efetiva suficiente para impressão em página inteira. Não classificar ART-001, ART-002 ou capa como finais.

**Arquivo de acompanhamento:** `MEU_MUNDO_EM_CORES_PROVA_DE_TRABALHO_V0.5.pdf` (artefato da sessão; o PDF e os PNGs não foram incorporados ao GitHub nesta etapa).


## Registro de produção — V0.6 (2026-11-12)

- Foi gerada uma nova prova integral do interior: `MEU_MUNDO_EM_CORES_INTERIOR_PROVA_V0.6.pdf`.
- O interior mantém 64 páginas: 4 páginas iniciais, 30 páginas de ilustração e 30 versos em branco.
- ART-001 (Gato) foi substituída por um arquivo individual em retrato, com elementos de jardim (flores, vegetação e céu). O arquivo foi inserido na página 5 para avaliação visual.
- ART-002 a ART-030 permanecem como páginas reservadas; cada página inclui a indicação do tema e contexto/habitat planejado.
- A capa colorida foi separada do interior em `MEU_MUNDO_EM_CORES_CAPA_COLORIDA_ESTUDO_V0.6.pdf`, respeitando a distinção entre arquivo de interior e arquivo de capa no fluxo KDP.

**Limitação técnica:** a arte ART-001 gerada tem 1102 × 1427 px. Está inserida apenas como protótipo de acompanhamento; não satisfaz 300 DPI efetivos quando ampliada para o formato de corte 8,5 × 11 pol. Não está aprovada como master final. A capa também é estudo frontal, não é ainda o arquivo de capa completa (contracapa + lombada + frente) exigido para impressão.

**Estado:** prova V0.6 criada; produção continua. Não declarar livro pronto para publicação.


## Registro de montagem — V0.7 (2026-11-12)

- Interior de acompanhamento: 64 páginas, formato 8,5 × 11 pol.
- ART-001 — Gato: permanece na página 5 como protótipo de revisão.
- ART-002 — Cachorro: inserido na página 7 com contexto de quintal (árvore, casinha, gramado, bola, comedouro e flores).
- Páginas 6 e 8: versos em branco.
- ART-003 a ART-030: páginas reservadas com habitats/contextos especificados.
- Capa colorida frontal: mantida como arquivo separado de estudo, conforme fluxo KDP.
- PDF gerado localmente: `MEU_MUNDO_EM_CORES_INTERIOR_PROVA_V0.7.pdf` (64 páginas).

**Limitação técnica:** ART-001 e ART-002 são protótipos raster de 1102 × 1427 px, insuficientes para 300 DPI efetivos em página 8,5 × 11 pol. Não estão aprovados para impressão. A capa frontal também é estudo; falta desenvolver a capa completa (contracapa + lombada) após fechamento definitivo da paginação e validação KDP. O PDF V0.7 é prova de acompanhamento, não arquivo final de publicação.


## Registro de produção — V0.8 (2026-11-12)

- ART-003 — Coelho na pradaria — inserido na página 9 do interior.
- Habitat representado: pradaria/jardim campestre com toca, vegetação, flores, árvore e céu.
- Página 10 permanece intencionalmente em branco.
- Interior preservado em 64 páginas.
- Capa frontal colorida exportada em arquivo independente, ocupando a página inteira, sem margens brancas.
- Prova combinada de leitura contém capa frontal + 64 páginas do interior (65 páginas no PDF de acompanhamento).

**Controle de qualidade:** a arte ART-003 está inserida como protótipo visual, não como master final. O arquivo gerado mede 1102 × 1427 px, abaixo dos 2550 × 3300 px previstos para raster a 300 DPI no formato 8,5 × 11 pol. A capa também é um estudo frontal, não o arquivo completo de capa KDP com lombada e contracapa. Os PDFs V0.8 são provas de acompanhamento e não estão aprovados para upload/publicação.


## Aditivo V0.9 — paginação sequencial

**Decisão editorial do usuário (2026-11-12):** não deixar páginas em branco entre as ilustrações ART. Cada arte ocupa uma página própria e as artes são apresentadas em sequência contínua.

- Páginas 1–4: abertura editorial.
- Páginas 5–34: ART-001 a ART-030, uma ilustração por página, sem páginas vazias intercaladas.
- Capa frontal colorida: arquivo separado, em página inteira (full bleed), para prova visual.
- V0.9: ART-001 gato na página 5; ART-002 cachorro na página 6; ART-003 coelho na página 7; ART-004 tartaruga na página 8.
- Total do interior de trabalho: 34 páginas. Prova combinada de visualização: 1 página de capa + 34 páginas de interior.

**Nota de qualidade:** as quatro imagens inseridas são protótipos raster de 1102 × 1427 px; não atingem 300 DPI efetivos no formato 8,5 × 11 pol. e não estão aprovadas como masters de impressão. As páginas ART-005 a ART-030 permanecem reservadas para inserção posterior.
