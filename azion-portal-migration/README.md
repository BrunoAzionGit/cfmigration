# Azion Implementation Portal

Este repositório contém a estrutura pronta para deploy estático no **Azion Console** integrado via Git.

## Arquivos do Projeto

- `index.html`: Portal principal contendo os links para os importadores.
- `gemini-code-1785458000658.html`: Formulário de importação de arquivo BIND DNS.
- `cf-migration-index.html`: Formulário de automação Cloudflare -> Azion.

## Configuração de Deploy na Azion

1. Crie um novo projeto no **Azion Console** selecionando **Deploy via Git**.
2. Conecte com o seu repositório do GitHub.
3. Utilize as seguintes configurações:
   - **Preset / Framework**: `Static` ou `HTML`
   - **Root Directory**: `./`
   - **Build Command**: *(deixar em branco)*
   - **Install Command**: *(deixar em branco)*
   - **Output Directory**: `./`
