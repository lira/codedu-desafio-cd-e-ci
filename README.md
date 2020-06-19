# Desafio Deploy Continuo

## Regras

- Quando qualquer push ou uma PR for relizada no Github em um branch diferente do Master, o processo de CI tem que ser executado.
- Quando um merge ou um push entrarem no branch Master, o processo de CI/CD deve ser chamado, fazendo assim o deploy de forma automática no Kubernetes.