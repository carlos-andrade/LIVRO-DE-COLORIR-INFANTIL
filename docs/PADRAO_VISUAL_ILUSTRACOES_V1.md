# Padrão visual oficial das ilustrações — V1.0

**Projeto:** Meu Mundo em Cores — Livro 01  
**Identificador:** LCI-LIVRO-001  
**Aprovado como padrão de produção:** 2026-11-12  
**Estado:** PADRÃO EDITORIAL OBRIGATÓRIO PARA AS 30 ARTES

## 1. Regra estrutural inegociável

**Uma ilustração individual ocupa uma página inteira e exclusiva.**

- Um arquivo de arte corresponde a uma única página do livro.
- Uma página contém uma única composição temática principal.
- Não criar tripticos, colagens, mosaicos, folhas de contato ou painéis múltiplos.
- Não dividir uma arte entre páginas.
- Não usar montagens de pré-visualização como páginas finais.
- A página pode conter elementos secundários que componham a mesma cena, desde que não concorram com o tema principal.
- Cada página de atividade será impressa somente na frente; o verso ficará intencionalmente em branco.

“Página inteira” significa que a página do livro é dedicada exclusivamente àquela ilustração; não significa que o desenho deva tocar as bordas ou ultrapassar as margens.

## 2. Formato físico e arquivo

| Item | Padrão |
|---|---|
| Formato de corte | 8,5 × 11 pol. (215,9 × 279,4 mm) |
| Orientação | Retrato |
| Interior | Preto e branco, papel branco |
| Sangria | Não |
| Raster final | 2550 × 3300 px a 300 DPI efetivos |
| Master preferencial | SVG ou PDF vetorial editável |
| Fundo | Branco puro |
| Traço | Preto puro |
| Área de segurança interna | 0,5 pol. (150 px a 300 DPI), em todos os lados |
| Área útil de referência | 2250 × 3000 px |

Não se deve aumentar artificialmente um PNG pequeno para alegar resolução efetiva de 300 DPI. Se a fonte for raster, a arte precisa ter detalhe nativo suficiente no tamanho final. Se for vetorial, exportar no tamanho final e inspecionar a renderização.

## 3. Linguagem visual

### 3.1 Personagens
- Estilo cartoon infantil original, acolhedor e facilmente reconhecível.
- Formas arredondadas e silhuetas claras.
- Expressões positivas, tranquilas e não ameaçadoras.
- Anatomia estilizada, mas coerente: patas, asas, orelhas, caudas e demais partes devem ser legíveis.
- Personagem principal mostrado inteiro, salvo quando o briefing específico justificar outra composição.
- Evitar olhos, bocas ou acessórios tão grandes que deformem a identidade do animal.

### 3.2 Contornos
- Linhas pretas, limpas, contínuas e de espessura consistente.
- Alvo de espessura visual: 2 a 3 pt no tamanho final; nunca inferior a 0,75 pt.
- Contornos principais ligeiramente mais fortes que detalhes internos, sem variação brusca.
- Preferir formas fechadas para criar áreas fáceis de colorir.
- Não usar hachuras, pontilhismo, retículas, degradês, sombras, cinza ou textura.
- Evitar cruzamentos, tangências e linhas muito próximas que possam confundir a criança.
- Pequenos preenchimentos pretos podem existir apenas em detalhes essenciais (por exemplo, pupilas); não usar grandes massas pretas.

### 3.3 Complexidade e áreas de colorir
- Baixa complexidade, compatível com a faixa de trabalho de 3 a 5 anos.
- Áreas internas amplas, claramente delimitadas e sem microdetalhes.
- Poucos detalhes decorativos, grandes e espaçados.
- Não usar padrões repetitivos pequenos (escamas, pelos, manchas, sementes ou texturas em excesso).
- O tema deve ser identificável sem texto, cor ou explicação.
- Não impor cores corretas ou respostas únicas.

## 4. Composição da página

- Uma figura principal por página, centralizada opticamente.
- O tema principal deve ocupar aproximadamente 60% a 75% da altura útil, ajustando a escala conforme a silhueta.
- Manter espaço branco respirável em torno da figura.
- Elementos secundários: preferencialmente de 0 a 3, grandes e subordinados ao tema.
- Fundo simples; não criar cenário carregado.
- Não cortar orelhas, antenas, patas, caudas, asas, trombas ou outros elementos essenciais.
- Não adicionar moldura retangular pesada. A área de segurança é invisível e não deve ser desenhada como borda.
- Evitar objetos tocando tangencialmente o contorno do personagem.

## 5. Consistência entre as 30 páginas

Todas as artes devem parecer pertencer ao mesmo livro:
- mesmo vocabulário de formas e expressões;
- mesma família de espessura de linha;
- densidade de detalhes equivalente;
- escala de personagem coerente;
- quantidade semelhante de espaço em branco;
- mesmo tratamento de fundo e ausência de molduras.

Variações de pose e enquadramento são permitidas quando necessárias para tornar cada tema reconhecível. Consistência não significa repetir o mesmo personagem ou a mesma composição.

## 6. Conteúdo e direitos

- Produzir desenhos originais; não reproduzir páginas de outros livros.
- Não utilizar personagens famosos, marcas, logotipos ou elementos protegidos sem autorização.
- Não imitar deliberadamente a identidade visual de artista vivo.
- Não incluir texto dentro da ilustração, salvo aprovação editorial expressa.
- Registrar origem, autoria, ferramenta/processo e versões de cada arte.

## 7. Convenção de arquivos

Cada arte terá identificador permanente e versão:

`ART-001-gato_V1.0.svg`  
`ART-001-gato_V1.0.png`

Estrutura:
- `illustrations/source/`: arquivo-fonte editável.
- `illustrations/final/`: exportação individual pronta para diagramação.
- `illustrations/review/`: provas e versões em revisão.

Não sobrescrever masters aprovados. Incrementar versão e registrar a alteração.

## 8. Checklist de aprovação por página

Uma arte só pode receber status **APROVADA PARA DIAGRAMAÇÃO** quando todos os itens forem verdadeiros:

1. [ ] Contém uma única ilustração temática principal.
2. [ ] Ocupa uma página individual em retrato, sem montagem ou painel.
3. [ ] Respeita o formato 8,5 × 11 pol. e a área de segurança de 0,5 pol.
4. [ ] Personagem/objeto está inteiro e não toca acidentalmente as margens.
5. [ ] Preto puro sobre branco, sem cinza, sombras ou texturas.
6. [ ] Linhas limpas, consistentes e com espessura suficiente para impressão.
7. [ ] Áreas de colorir são amplas e adequadas à idade-alvo.
8. [ ] Não há excesso de detalhes, sobreposições ou tangências confusas.
9. [ ] Original editável e exportação final estão arquivados.
10. [ ] Resolução efetiva e dimensões foram verificadas.
11. [ ] Prova em tamanho real foi inspecionada.
12. [ ] Direitos e proveniência estão documentados.

**Qualquer falha bloqueia a aprovação.** “Visualmente bonito na tela” não é critério suficiente de qualidade editorial.

## 9. Aplicação inicial

O padrão será aplicado primeiro às três artes-piloto:
- ART-001 — Gato
- ART-006 — Borboleta
- ART-008 — Elefante

As 27 artes restantes só entram em produção depois da aprovação das três páginas-piloto, garantindo que o padrão seja estável e reproduzível.


## 10. Habitat e contexto ambiental — requisito obrigatório

Cada página deve incluir elementos de habitat ou contexto que ajudem a criança a compreender onde o personagem vive, aparece ou é utilizado. O ambiente faz parte da composição da mesma página e não constitui uma segunda ilustração.

### Regras de composição do habitat
- O personagem/objeto principal permanece como foco visual e ocupa aproximadamente 60% a 75% da altura útil, quando a forma permitir.
- Incluir preferencialmente 2 a 4 elementos ambientais grandes e simples; reduzir quando o tema já tiver muitos detalhes.
- Usar elementos reconhecíveis: solo, água, plantas, árvores, flores, rochas, céu, ninho ou objetos cotidianos, conforme o tema.
- Não desenhar cenários completos com excesso de perspectiva, texturas, folhas, grama ou pequenos elementos.
- O habitat não pode encobrir, cruzar confusamente ou tocar tangencialmente o contorno do personagem.
- Preservar áreas brancas amplas e fechadas para colorir.
- Respeitar a ecologia básica do animal representado. Não colocar espécies em ambientes incompatíveis nem misturar biomas sem justificativa.
- Para animais domésticos, mostrar contexto de convivência humana (casa, quintal ou parque), sem chamar isso de habitat selvagem.
- Para objetos e temas não vivos, usar um contexto de uso ou ambiente temático, não um habitat biológico.
- Elementos ambientais devem ser tão simples quanto o personagem, com o mesmo traço e espessura.

### Critério de aprovação adicional
A página deve permitir reconhecer tanto o personagem quanto pelo menos um aspecto do seu ambiente/contexto, sem exigir texto explicativo. O cenário deve permanecer secundário e não transformar a página numa paisagem carregada.
