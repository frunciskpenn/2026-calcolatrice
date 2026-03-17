# 2026-calcolatrice

Adesso ho la:

- somma



## Setup ambiente di sviluppo con uv

Installare [uv](https://docs.astral.sh/uv/) per gestire l'ambiente di sviluppo:

```bash 
- uv venv
- source .venv/bin/activate  ( o equivalente su Windows )
- uv pip compile requirements.in -o requirements.txt
- uv pip install -r requirements.txt
```

## Testing con pytest

Useremo [pytest](https://docs.pytest.org/en/stable/) per eseguire i tests:

```bash
pytest
```
