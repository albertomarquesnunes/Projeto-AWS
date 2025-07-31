### 3. Documentação de Implantação

#### 1. Amazon EC2

- Acesso ao console AWS, criação de instância t2.micro para servidores web.
- Configuração de grupo de segurança permitindo portas 22 (SSH) e 80 (HTTP).
- Migração dos serviços locais para a instância EC2 via SSH/SCP.

#### 2. Amazon S3

- Criação de bucket “abstergo-backups”.
- Definição de políticas de acesso e criptografia.
- Migração de arquivos locais para o S3 usando AWS CLI.

#### 3. AWS Lambda

- Criação da função Lambda “processaEmail”.
- Configuração de trigger para evento de novo arquivo no bucket S3.
- Deploy do código Python de processamento e testes via console AWS.

---

**Assinatura do Responsável pelo Projeto:**  
Alberto Marques Nunes
