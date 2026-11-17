# Aula 09 — Classes, Dataclasses e SQLite

Evolução gradual de modelagem em Python: de classes tradicionais para `@dataclass`, tipagem e persistência direta com `sqlite3` e `logging`.

## Estrutura

- `class/`: `marca.py`, `pessoa.py`, `veiculo.py` (classes tradicionais).
- `dataclass/`: `main.py`, `marca.py`, `pessoa.py`, `veiculo.py` (modelagem com `@dataclass`).
- `dataclass2/`: `marca.py`, `marca2.py`, `pessoa.py`, `type.py` (variações com tipagem).
- `db/`: `db.py`, `logger_config.py`, `marca.py`, `pessoa.py`, `veiculo.py` (persistência em SQLite com logging).

## Como executar

```bash
cd dataclass
python main.py
```
