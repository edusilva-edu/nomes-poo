# Aprendendo Markdown

## Trechos de código

Você pode inserir código ou um comando dentro de uma frase usando crases simples. O texto entre as crases não será formatado. Você também pode usar o atalho de teclado Command+E (Mac) ou Ctrl+E (Windows/Linux) para inserir as crases de um bloco de código em uma linha de Markdown.

```
    Use `git status` para listar todos os arquivos novos ou modificados que ainda não foram commitados.
```
Para formatar código ou texto em um bloco distinto, use três crases invertidas (`).

```
    Alguns comandos básicos do Git são:
    ```
    git status
    git add
    git commit
    ```
```

# Listas

## Lista desordenada

É possível fazer uma lista desordenada colocando os seguintes caracteres antes das palavras: -, * ou +.

### Exemplo

+ A
* B
+ C

## Lista ordenada

Para fazer uma lista ordenada, coloque números.

### Exemplo

1. Primeiro
1. Segundo
1. Terceiro



## Alerts

> [!NOTE]
> Informações uteis para se lembrar.

> [!TIP]
> Dicas.

> [!IMPORTANT]
> Informações chaves.

> [!WARNING]
> Informações Urgentes.

> [!CAUTION]
> Avisos para tomar cuidado.

## Imagens

Inicia com exclamação (!) e a descrição da imagem vai dentro de colchetes []. O link da imagem vai dentro de parênteses.

Ex:

```markdown
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)
```