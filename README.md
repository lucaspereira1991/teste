# Estrutura criada automaticamente

- `frontend/`: Projeto TypeScript Hello World
- `.github/workflows/release.yml`: GitHub Action para build e release

## Como funciona o workflow

1. O usuário executa o workflow manualmente e informa o número da versão.
2. O workflow faz checkout do repositório, instala dependências, builda o projeto e gera um artefato zip.
3. Cria uma release no GitHub com o artefato gerado.

Para rodar localmente:

```powershell
cd frontend
npm install
npm run build
```