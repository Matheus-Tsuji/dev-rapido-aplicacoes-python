# Aula 13 — Treeview e Cadastro de Usuários (Tkinter + SQLite)

Exibição tabular de dados com `ttk.Treeview` e integração completa entre interface gráfica Tkinter e banco de dados SQLite.

## Estrutura

- `treeview/`:
  - `janela2.py`: Exemplo de uso do componente `Treeview`.
- `exercicios/`:
  - `exercicio.py`: Exercício prático com Tkinter.
- `cadastro_usuarios/`:
  - `database.py`: Camada de acesso ao banco SQLite.
  - `main.py`: Interface principal do sistema de cadastro.
    > **Nota:** A linha 131 (`ttk.Button(botoes,text="Pesquisar",command=)`) está incompleta no repositório original do professor (mantida intacta).
  - `test_database.py`: Testes das operações de banco de dados.
  - `usuarios.db`: Banco SQLite de exemplo.

## Como executar

```bash
cd cadastro_usuarios
python test_database.py
```
