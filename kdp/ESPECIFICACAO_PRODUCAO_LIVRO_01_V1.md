# Especificação de produção — Livro 01

**Versão:** 1.0  
**Data de aprovação do formato:** 2026-11-12  
**Estado:** FORMATO EDITORIAL DEFINIDO; ARTES FINAIS EM PRODUÇÃO.

## 1. Especificação física

| Parâmetro | Definição |
|---|---|
| Produto | Livro de colorir infantil, brochura |
| Formato de corte | 8,5 × 11 pol. (215,9 × 279,4 mm) |
| Interior | Tinta preta, papel branco |
| Sangria do interior | Não |
| Orientação | Retrato, todas as páginas |
| Encadernação | Paperback / brochura |
| Idioma | Português |
| Ilustrações | 30 páginas de atividade |
| Impressão frente e verso | Arte somente na frente; verso correspondente em branco |

## 2. Arquitetura preliminar de paginação

A paginação de trabalho será de **64 páginas**:

| Páginas | Conteúdo |
|---|---|
| 1 | Página de título |
| 2 | Direitos autorais e créditos |
| 3 | Apresentação e instruções simples |
| 4 | Página “Este livro pertence a” |
| 5, 7, 9 … 63 | 30 ilustrações, uma por página ímpar |
| 6, 8, 10 … 64 | Versos em branco |

A sequência coloca cada desenho numa página ímpar (lado direito) e deixa o verso em branco. A paginação final deve ser conferida no PDF exportado; páginas em branco intencionais devem ser preservadas.

## 3. Template raster de referência

- Página final: **2550 × 3300 px**, equivalente a 8,5 × 11 pol. a 300 DPI.
- Modo de cor de produção: preto e branco; preferir line art monocromática sem cinzentos.
- Fundo: branco puro.
- Área de segurança editorial adotada: **0,5 pol. em cada lado** (150 px a 300 DPI).
- Área útil máxima resultante: **2250 × 3000 px**.
- Nenhuma parte essencial da ilustração pode ultrapassar a área útil.
- Linha: nunca abaixo do mínimo KDP de 0,75 pt; alvo visual recomendado de 2–3 pt, validado em prova física.
- Não ampliar por interpolação um protótipo pequeno e tratá-lo como master. Regerar/recompor na composição final e validar a qualidade da linha.

A área de segurança de 0,5 pol. é uma regra interna conservadora do projeto, superior aos mínimos de impressão aplicáveis ao livro de 64 páginas.

## 4. Critérios técnicos de aceitação

1. Página individual, não spread ou dupla página.
2. Proporção retrato 8,5:11.
3. Resolução efetiva de 300 DPI no tamanho final.
4. Contornos pretos, limpos, fechados quando necessário e sem cinzentos, sombras ou texturas.
5. Personagem integralmente visível, sem cortes e com espaço em torno da silhueta.
6. Áreas internas grandes e claramente delimitadas para colorir.
7. Sem texto, logotipos, marcas d'água ou elementos de terceiros na arte.
8. Verificação visual em 100% e inspeção de PDF em escala real.
9. Teste de prova física antes da publicação.

## 5. Implicações para as artes-piloto

Os PNGs-piloto existentes permanecem referências de estilo. Não são masters finais. As novas composições de ART-001 (gato), ART-006 (borboleta) e ART-008 (elefante) deverão ser produzidas individualmente, em retrato, respeitando o template de 2550 × 3300 px e a área útil de 2250 × 3000 px.

## 6. Verificação KDP

A documentação oficial consultada confirma:
- 8,5 × 11 pol. é um formato de corte disponível para brochura.
- Para interior sem sangria, o arquivo deve usar exatamente o formato de corte.
- O mínimo de páginas para brochura é 24; 64 páginas está dentro do intervalo permitido para preto e branco em papel branco.
- Para 24–150 páginas, a margem interna mínima é 0,375 pol. e as margens externas mínimas sem sangria são 0,25 pol.
- A resolução mínima de imagens é 300 DPI.
- A espessura mínima de linhas indicada é 0,75 pt.

Fonte oficial: https://kdp.amazon.com/en_US/help/topic/G201857950

**Atenção:** confirmar novamente as opções disponíveis no marketplace de publicação e no KDP Print Previewer no momento do upload. A aprovação final depende da validação do arquivo completo pelo KDP e de prova física.
