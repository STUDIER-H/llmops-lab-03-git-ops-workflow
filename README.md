# 🧪 LAB 03: Git Flow Profissional, Pre-Commit Hooks & Conventional Commits

## 🎯 Objetivo do Lab
Estabelecer um padrão profissional de controle de código fonte (GitOps) no ambiente de desenvolvimento, integrando hooks automatizados de linting e validação de commits.

---

## 📋 Pré-requisitos
- Ter concluído *Version Control with Git and GitHub* (Johns Hopkins).
- Git 2.30+, Python `pre-commit`, `ruff`, `black`, `shellcheck`.

---

## 🛠️ O que você deve construir neste Lab:

### Etapa 1: Configuração de Hooks Automatizados
1. Configure o arquivo `.pre-commit-config.yaml` com as seguintes verificações:
   - Formatador de Python: `black` ou `ruff format`.
   - Linter de Python: `ruff`.
   - Linter de scripts Bash: `shellcheck`.
   - Validador de arquivos YAML e JSON.

### Etapa 2: Directivas de Commit & Git Flow
1. Crie uma regra de validação de mensagens de commit seguindo a especificação **Conventional Commits** (`feat:`, `fix:`, `infra:`, `docs:`).
2. Configure `.github/pull_request_template.md` e `.github/commit_template.txt`.

---

## ✅ Critérios de Aceitação & Entrega
- [ ] `.pre-commit-config.yaml` funcionando e bloqueando commits fora do padrão.
- [ ] Histórico de commits no repositório 100% aderente ao Conventional Commits.
- [ ] Template de Pull Request ativo e configurado no repositório.
