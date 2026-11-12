# Regra de paginação das ilustrações

**Projeto:** Meu Mundo em Cores — Livro 01  
**Data:** 2026-11-12  
**Estado:** REGRA EDITORIAL OBRIGATÓRIA

## Regra principal

Cada ilustração ocupa uma página inteira e exclusiva do livro. É proibido:
- colocar duas ou mais ilustrações na mesma página;
- criar tripticos, colagens, mosaicos ou painéis múltiplos;
- dividir uma ilustração entre páginas;
- usar uma montagem de pré-visualização como página final.

## Especificação de página

- Formato: 8,5 × 11 pol. (21,59 × 27,94 cm).
- Orientação: retrato.
- Interior: preto e branco em papel branco.
- Sem sangria para as ilustrações.
- Arquivo de página: 2550 × 3300 px a 300 DPI, ou master vetorial equivalente.
- Área de segurança interna do projeto: 0,5 pol. em todos os lados.
- Uma única composição temática por página.
- Verso da página de atividade intencionalmente em branco.

## Identificação e organização

Cada arquivo recebe um identificador permanente:
- ART-001-gato
- ART-002-cachorro
- ART-003-coelho
- …
- ART-030-minha-criacao

Estrutura esperada:
- `illustrations/source/`: originais editáveis.
- `illustrations/final/`: artes finais individuais.
- `illustrations/review/`: provas e versões em revisão.

O nome do arquivo deve conter o identificador e a versão. Exemplo: `ART-001-gato_V1.0.png`.

## Critério de bloqueio

Nenhuma página é aprovada se contiver mais de uma ilustração principal, se estiver em baixa resolução efetiva, se apresentar corte de elementos essenciais ou se não tiver sido inspecionada em tamanho real.
