# Nano Banana Pro v6.2 — Campanha de Marca Completa

Curso aberto e gratuito: seis módulos, 18 aulas de aproximadamente 15 minutos.
Caso autoral Brisa: produto, personagem fictícia, paleta, texto, infográfico e sequência visual.

[Abra o curso](https://inematds.github.io/curso-nano-banana-pro/).

As ilustrações didáticas foram geradas exclusivamente com Codex image_gen. Não são resultados do Nano Banana.
As práticas orientam o aluno a registrar o modelo realmente utilizado. Geração pode exigir conta e créditos;
atividades não executadas permanecem pendentes. O formato é inspirado no OSWork v6.2.

## Arquivos

`context/conteudo-base.json` e `context/aulas-editoriais.json` são as fontes autorais.
`montar.py` gera as aulas e invoca o montador oficial INEMA v6 para `curso.html` e a lista da landing.
`assets/aula.css` e `assets/curso.js` são cópias sem alterações do motor oficial.
`context/fontes.md` registra documentação oficial consultada; `context/leitor-*.md` registra revisões simuladas.
Não há vídeos, transcrições ou imagens copiados do acervo privado de terceiros.

## Montagem

Com Python 3 e a skill `formato-curso-v6` instalada, ajuste `SKILL` em `montar.py` se necessário e rode:

```sh
python3 montar.py
node /caminho/formato-curso-v6/scripts/auditar-curso.cjs curso.html --json context/auditoria.json
node /caminho/formato-curso-v6/scripts/testar-motor.cjs curso.html
```

Os verificadores usam Playwright; `PLAYWRIGHT_PATH` pode indicar sua instalação.
O formato educacional é v6.2; a versão inicial do conteúdo é 1.0.0.

## Mais no INEMA.CLUB

- [Ficha do curso](https://www.inema.club/cursos/284-nano-banana-pro-v6-2-campanha-de-marca-completa/)
- [Guia para aprender IA](https://www.inema.club/aprender-inteligencia-artificial/)
- [Catálogo](https://www.inema.club/cursos/)
