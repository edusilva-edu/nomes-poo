








## Formatação de Texto e ALERTS

### 1. Formatação Básica de Texto

A formatação em Markdown é feita através de símbolos simples ao redor do texto.

| Estilo | Sintaxe (Como digitar) | Resultado Visual |
| :--- | :--- | :--- |
| **Negrito** | `**Texto em negrito**` | **Texto em negrito** |
| *Itálico* | `*Texto em itálico*` | *Texto em itálico* |
| ***Negrito e Itálico*** | `***Ambos***` | ***Ambos*** |
| ~~Tachado~~ | `~~Texto riscado~~` | ~~Texto riscado~~ |
| `Código (Inline)` | `` `Variável` `` | `Variável` |
| Citação | `> Texto citado` | > Texto citado |
| Link | `[Google](https://google.com)` | [Google](https://google.com) |

### Títulos
Use a hashtag `#` seguida de um espaço para criar títulos. A quantidade de hashtags define o nível (tamanho) do título.

```markdown
# Título 1 (H1 - Principal)
## Título 2 (H2 - Seção)
### Título 3 (H3 - Subseção)
```

### Listas
* **Não ordenadas:** Use `-`, `*` ou `+`.
* **Ordenadas:** Use `1.`, `2.`, etc.

---

### 2. Alerts (Avisos Destacados)

Os **Alerts** são uma extensão do Markdown (muito usada no GitHub, Obsidian e documentações) para criar caixas coloridas de destaque. A sintaxe baseia-se em uma citação (`>`) seguida de uma tag específica entre colchetes.

> **Nota:** A renderização das cores depende da plataforma onde o Markdown é visualizado (GitHub, VS Code, etc).

### Sintaxe Geral
```markdown
> [!TIPO]
> O conteúdo do aviso vai aqui.
```

### Tipos de Alerts Disponíveis

#### 🔵 Note (Nota)
Usado para informações gerais que o usuário deve saber.
```markdown
> [!NOTE]
> Informação útil e destaques neutros.
```

#### 🟢 Tip (Dica)
Usado para sugerir melhorias ou caminhos alternativos.
```markdown
> [!TIP]
> Tente usar atalhos de teclado para salvar tempo.
```

#### 🟣 Important (Importante)
Informações cruciais para o sucesso da tarefa.
```markdown
> [!IMPORTANT]
> Não esqueça de salvar seu progresso.
```

#### 🟡 Warning (Aviso/Atenção)
Alerta sobre algo que precisa de atenção imediata ou potenciais problemas.
```markdown
> [!WARNING]
> A bateria está fraca.
```

#### 🔴 Caution (Cuidado)
Usado para avisar sobre ações destrutivas ou erros graves.
```markdown
> [!CAUTION]
> Esta ação não pode ser desfeita.
```

---

### Dica Profissional: Blocos de Código
Para compartilhar trechos de código com formatação colorida (syntax highlighting), use três crases e o nome da linguagem:

```python
print("Olá, Mundo")
def soma(a, b):
    return a + b
```