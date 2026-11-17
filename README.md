# Desenvolvimento Rápido de Aplicações em Python

Repositório organizado com os códigos, exemplos e exercícios da disciplina **Desenvolvimento Rápido de Aplicações em Python**, além de projetos e práticas complementares desenvolvidas fora de aula.

> Baseado no repositório original do professor: [KauaRios/DEV_RAPIDO_PYTHON](https://github.com/KauaRios/DEV_RAPIDO_PYTHON). Os arquivos originais foram reorganizados em pastas padronizadas, formatados seguindo as convenções da PEP 8 e documentados com `README.md` individuais para facilitar o estudo e a navegação.

## Estrutura do Repositório

```text
dev-rapido-aplicacoes-python/
├── aulas/
│   ├── 01-introducao/
│   ├── 02-classes-dataclasses/
│   ├── 03-arquivos-e-caminhos/
│   ├── 04-strings-e-regex/
│   ├── 05-collections-e-excecoes/
│   ├── 06-arquivos-binarios-e-imagens/
│   ├── 07-persistencia-em-arquivos/
│   ├── 08-sqlalchemy-e-crud/
│   ├── 09-classes-e-sqlite/
│   ├── 10-introducao-tkinter/
│   ├── 11-widgets-e-eventos-tkinter/
│   ├── 12-layouts-e-componentes-tkinter/
│   └── 13-treeview-e-cadastro-sqlite/
├── estudos-casa/
├── .gitignore
└── README.md
```

## Índice das Aulas

| Aula | Pasta | Conteúdo Principal |
| --- | --- | --- |
| 01 | [01-introducao](aulas/01-introducao/) | Apresentação da disciplina (sem códigos). |
| 02 | [02-classes-dataclasses](aulas/02-classes-dataclasses/) | Classes, `dataclass` e gerenciador de tarefas. |
| 03 | [03-arquivos-e-caminhos](aulas/03-arquivos-e-caminhos/) | Leitura e escrita de arquivos (`open`, `with`, `readline`, `os`) e exercícios. |
| 04 | [04-strings-e-regex](aulas/04-strings-e-regex/) | Manipulação de strings, expressões regulares e formulário. |
| 05 | [05-collections-e-excecoes](aulas/05-collections-e-excecoes/) | Módulo `collections` (`Counter`, `defaultdict`, `deque`, `namedtuple`), tratamento de exceções e exercício de notas. |
| 06 | [06-arquivos-binarios-e-imagens](aulas/06-arquivos-binarios-e-imagens/) | Arquivos binários, manipulação de diretórios, imagens e exercícios (agenda e gerenciador de alunos). |
| 07 | [07-persistencia-em-arquivos](aulas/07-persistencia-em-arquivos/) | Agenda de contatos e sistema de pedidos com persistência em arquivos. |
| 08 | [08-sqlalchemy-e-crud](aulas/08-sqlalchemy-e-crud/) | Banco de dados com SQLAlchemy e exercício de CRUD. |
| 09 | [09-classes-e-sqlite](aulas/09-classes-e-sqlite/) | Classes, `dataclass`, tipagem e persistência com SQLite e logging. |
| 10 | [10-introducao-tkinter](aulas/10-introducao-tkinter/) | Continuação da aula 09 e criação da primeira janela com Tkinter. |
| 11 | [11-widgets-e-eventos-tkinter](aulas/11-widgets-e-eventos-tkinter/) | Widgets, eventos e organização de interfaces Tkinter com classes. |
| 12 | [12-layouts-e-componentes-tkinter](aulas/12-layouts-e-componentes-tkinter/) | Layouts, centralização, ícones, abas, colunas, relógio e cadastro com Tkinter. |
| 13 | [13-treeview-e-cadastro-sqlite](aulas/13-treeview-e-cadastro-sqlite/) | `Treeview` e aplicação completa de cadastro de usuários com Tkinter e SQLite. |
| Extras | [estudos-casa](estudos-casa/) | Exercícios extras, estudos de POO, organizador de arquivos e projeto *Tracker de Estudos*. |

## Pré-requisitos e Execução

- **Python 3.10+** instalado.
- Dependências externas utilizadas em aulas específicas:
  - `sqlalchemy` (Aula 08)
  - `pillow` (Aula 06, manipulação de imagens)
  - `tkinter` (Aulas 10 a 13 e `estudos-casa/organizador_arquivos` — geralmente incluso na instalação padrão do Python no Windows).

Para executar qualquer script, recomenda-se entrar na pasta do respectivo exemplo (pois vários scripts utilizam caminhos relativos para arquivos `.txt`, `.db` ou `.bin` locais):

```bash
cd aulas/02-classes-dataclasses/alunos
python Aula1.py
```
