# Template de Novo Livro

Este é uma sugestão para estruturar seu projeto de resolução de exercícios que visa facilitar a leitura, manutenção e colaboração em projetos similares aqui na organização **Matemática como Hobby**.

## Estrutura do Projeto

A estrutura do projeto segue o seguinte formato:

```
|
|- main.tex
|- main.pdf
|- bibliografia.bib
|- capítulos/
    |- cap1.tex
    |- cap2.tex
    |- cap3.tex
    ...
    |- cap12.tex
```

- **`main.tex`**: Arquivo principal que organiza o documento LaTeX, incluindo pacotes, configurações gerais e os capítulos.
- **`main.pdf`**: Documento renderizado em PDF a partir do arquivo `main.tex`.
- **`bibliografia.bib`**: Arquivo contendo as referências bibliográficas utilizadas no projeto.
- **`capítulos/`**: Pasta que contém os arquivos `.tex` dos capítulos, nomeados no formato `cap<número>.tex`.


## Compilação do PDF

Sugerimos compilar o arquivo `main.pdf`  localmente e subir junto com arquivo main.tex.


### Exemplos

Para ver outros exemplos de projetos seguindo este padrão, acesse o repositório oficial da organização no GitHub: [Matemática como Hobby](https://github.com/Matematica-como-Hobby). Como exemplo, você pode explorar o repositório: [A Teoria dos Conjuntos e os Fundamentos da Matemática](https://github.com/Matematica-como-Hobby/A-Teoria-dos-Conjuntos-e-os-Fundamentos-da-Matematica).

## Qual Licença Usar?

Use a [Licença MIT](LICENSE), ou seja, permitindo o uso livre, modificação e redistribuição, desde que a atribuição seja mantida.
