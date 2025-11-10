# AWS-ActiveDirectory-Lab
Active Directory em AWS Managed Microsoft AD.

## Objetivo
- Criar usuários, grupos e relatórios via PowerShell.
- Permitir reproduzir um lab AD na AWS.
- Automação de AD e integração com AWS (SSM).

## Estrutura do repositório
- `scripts/` : Scripts PowerShell (create_users, create_group, report_users)
- `docs/` : Documentação de uso e execução via SSM
- `cloudformation/` : Templates de infraestrutura AWS
- `.gitignore` : Arquivos que não podem commit
- `README.md` : Documentação 
- `LICENSE` : Licença do projeto

## Pré-requisitos
- AWS Managed Microsoft AD provisionado
- Instância EC2 Windows unida ao domínio
- Permissões AWS para SSM 
- PowerShell com módulo ActiveDirectory disponível na instância

## Como usar
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/AWS-ActiveDirectory-Lab.git
