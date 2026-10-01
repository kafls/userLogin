# Sistema de Login

Projeto desenvolvido para a atividade avaliativa de **Git e GitHub**. Consiste em uma página de login com validação de campos em JavaScript, uma tela de dashboard e um formulário de cadastro de usuários, tudo versionado com Git seguindo o fluxo de branches `main`, `develop`, `feature/`, `hotfix/` e `release/`.

## Links

- Repositório: https://github.com/SEU-USUARIO/SEU-REPO
- Site hospedado: https://SEU-USUARIO.github.io/SEU-REPO/

## Funcionalidades

- **Login** (`index.html`): formulário de usuário e senha com mensagens de erro quando os campos estão vazios.
- **Dashboard** (`dashboard.html`): menu simples e mensagem de boas-vindas ao usuário autenticado.
- **Cadastro** (`cadastro.html`): formulário de novos usuários com validação de nome, e-mail, usuário e senha.

## Tecnologias

- HTML5
- CSS3
- JavaScript (puro, sem bibliotecas)
- Git e GitHub
- GitHub Pages (hospedagem)

## Estrutura do projeto

```
├── index.html        # Página de login
├── dashboard.html    # Painel principal
├── cadastro.html     # Cadastro de usuários
├── style.css         # Estilos do login
├── script.js         # Validação dos campos do login
└── README.md         # Documentação
```

## Como executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/SEU-USUARIO/SEU-REPO.git
   ```

2. Entre na pasta do projeto:

   ```bash
   cd SEU-REPO
   ```

3. Abra o arquivo `index.html` no navegador (duplo clique ou extensão Live Server do VS Code).

## Fluxo de branches

| Tipo    | Nome                       | Base    | Finalidade                        |
|---------|----------------------------|---------|-----------------------------------|
| Estável | `main`                     | —       | Código publicado                  |
| Dev     | `develop`                  | `main`  | Desenvolvimento ativo             |
| Feature | `feature/validacao`        | develop | Validação de campos do login      |
| Feature | `feature/dashboard`        | develop | Criar painel principal            |
| Feature | `feature/cadastro-usuario` | develop | Criar tela de cadastro            |
| Hotfix  | `hotfix/erro-html`         | main    | Corrigir erro estrutural no HTML  |
| Release | `release/v1.1.0`           | develop | Preparar a versão 1.1.0           |

## Versão

**v1.1.0**: login com validação, dashboard, cadastro de usuários e correção da estrutura HTML.

## Autor

Seu Nome: https://github.com/SEU-USUARIO