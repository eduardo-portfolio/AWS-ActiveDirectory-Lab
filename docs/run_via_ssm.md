# Exemplos de execução de scripts PowerShell via AWS SSM
# Exemplo:
# aws ssm send-command --targets "Key=InstanceIds,Values=i-1234567890abcdef0" --document-name "AWS-RunPowerShellScript" --comment "Executar create_users.ps1" --parameters 'commands=["C:\\scripts\\create_users.ps1"]'

