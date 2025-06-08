# Stellar Classification

## Configuração rápida do ambiente

Instale o **uv** (Mac / Linux):

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

Crie um ambiente virtual e instale as dependências:

```bash
uv venv .
source .venv/bin/activate
uv sync
```

No Windows, instale `uv` via `pip install uv` e ative o ambiente com `./.venv/Scripts/activate`.

---

## Estrutura do projeto

```
├── data/raw/               # arquivos CSV com o dataset e seus splits
├── notebooks/
│   ├── 0-data_split.ipynb  # divisão treino / teste / análise
│   ├── 1-initial-EDA.ipynb # EDA inicial
│   ├── 1.5-EDA.ipynb       # EDA aprofundada
│   └── 2-models.ipynb      # modelos de classificação
└── README.md
```

---

## Como rodar

1. Entre no notebook
2. Escolha o kernel `.venv`, direcionando pro venv criado com o `uv sync`

