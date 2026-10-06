# Exercício 9-1 — O guia ganha histórico

Projeto preparado a partir do exercício 8-3 para a atividade de Git/GitHub.

## Alteração realizada

Foi reorganizado o cabeçalho usando apenas HTML e CSS já utilizados no projeto:

- identidade e menu foram agrupados em `.cabecalho-conteudo`;
- o cabeçalho mantém o conteúdo e os links existentes;
- o alinhamento e o espaçamento entre identidade e menu foram organizados;
- o comportamento responsivo do menu foi preservado;
- a barra lateral, cards e demais conteúdos não foram alterados.

## Histórico sugerido

O histórico do exercício deve conter pelo menos 3 commits semânticos:

1. `feat: inicializar guia e arquivos do projeto`
2. `docs: adicionar gitignore e documentação do exercício`
3. `refactor: reorganizar cabeçalho do guia`

## Branch da atividade

`refactor/reorganizar-cabecalho`

## Repositório remoto

`https://github.com/Cavalcanti75/AULA-TER-0910-GIT.git`

## Como publicar

Se o Git já estiver configurado, entre nesta pasta e execute:

```bash
git remote add origin https://github.com/Cavalcanti75/AULA-TER-0910-GIT.git
git branch -M main
git checkout -b refactor/reorganizar-cabecalho
git push -u origin refactor/reorganizar-cabecalho
```

Depois, no GitHub, abra um Pull Request da branch `refactor/reorganizar-cabecalho` para `main`.

Título sugerido:

`refactor: reorganizar cabeçalho do guia`

Descrição sugerida:

> Reorganiza o cabeçalho do guia mantendo o conteúdo e os links existentes. A alteração melhora o agrupamento, alinhamento e espaçamento entre a identidade do site e o menu, preservando o comportamento responsivo.
