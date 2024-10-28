# Desafio AWS + Terraform

## Descrição
Este desafio consiste em realizar o processo de provisionamento de infraestrutura na AWS utilizando Terraform. O objetivo é criar um grupo de segurança (Security Group), uma instância EC2 e realizar o deploy de um site via script (script.sh), com o resultado acessível via browser, com Terraform.

## Etapas do Desafio

1. **Criar conta na AWS**  
   Criar uma conta gratuita no provedor de nuvem AWS.

2. **Instalação do Terraform**  
   Baixar e instalar o Terraform localmente em sua máquina.

3. **Adicionar Provedor AWS no Terraform**  
   Configurar o provedor AWS no Terraform para vincular a conta à infraestrutura.

4. **Escrever os Arquivos de Configuração**  
   Criar os arquivos de configuração necessários para o provisionamento da infraestrutura na AWS.

5. **Criar Grupo e Usuário IAM**  
   Configurar um grupo e um usuário IAM com as permissões necessárias.

6. **Configurar Chave de Acesso**  
   Gerar uma chave de acesso para o usuário IAM e configurá-la no AWS CLI da máquina local.

7. **Criar Instância EC2 Ubuntu 24.04 LTS via Terraform**  
   Utilizar Terraform para provisionar a instância EC2.

## Comandos do Terraform

- **Inicializar o Terraform**  
  ```bash
  terraform init
- **Infraestrutura Provisória na AWS**  
  ```bash
  terraform apply
- **Destruir Recursos Provisionados**  
  ```bash
  terraform destroy
