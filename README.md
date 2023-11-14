# Segundo Projeto de Ciência dos Dados

Este projeto foi desenvolvido na disciplina de Ciência dos Dados do Insper pelos alunos:

- [Henrique Leite dos Santos][henrique]
- [Pedro Henrique Viegas Ribeiro][pedro]
- [Vitor Hideki Pereira Katakura][vitor]

Utilizamos a base de microdados do ENEM 2022 para realizar a análise.

- [Base de Microdados do ENEM 2022][microdados]

## Objetivo

Prever uma variável principal (**Nota de matemática**) em função de demais outras variáveis (**Cor/Raça**, **Renda**, **Sexo**, ser **Treineiro** e **Nota de Ciências Humanas**) que podem influenciar em seu comportamento.

## Instalação

Como a base de microdados que estamos utilizando é muito pesada, é necessário utilizar o Git LFS para baixar os arquivos.

Primero, instale o Git LFS no site oficial: <https://git-lfs.github.com/>

Depois, clone o repositório da forma que preferir:

Utilizando https:

```bash
git clone https://github.com/Phvr06/Proj2-Cdados.git
```

Utilizando ssh-key:

```bash
git clone git@github.com:Phvr06/Proj2-Cdados.git
```

Utilizando GitHub CLI:

```bash
gh repo clone Phvr06/Proj2-Cdados
```

Após isso, entre na pasta do repositório e execute os seguintes comandos:

```bash
git lfs fetch
```

```bash
git lfs checkout
```

Agora será possível acessar os arquivos da base de microdados e executar o jupyter notebook.

[henrique]: https://github.com/Rkzzin
[pedro]: https://github.com/Phvr06
[vitor]: https://github.com/thevitorhideki
[microdados]: https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enem
