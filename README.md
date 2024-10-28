Desafio AWS + Terraform
Aluno: Eduardo Wesley Andrade Silva
O desafio consiste em realizar o processo de provisionamento da infra na AWS via Terraform, onde será criado o security group, a EC2 e por último o deploy do site (via o arquivo script.sh) que resultará na imagem abaixo (acessando via browser).
•	Conta criada free no provedor de nuvem (AWS):
•	Instale o Terraform localmente:
•	Adicione um provedor (AWS) localmente:
•	Escreva os arquivos de configuração. (receitinha de bolo):
•	Criado o grupo e o usuário IAM:  
•	Chave de acesso para vincular ao AWS CLI na máquina:
•	Criada instância EC2 Ubuntu 24.04 LTS - Terraform: 
o	Inicialize o Terraform. (# terraform init):
o	Visualizar a infraestrutura a ser criada. (# terraform plan):
o	O provisionamento na AWS. (# terraform apply):
o	Para eliminar os recursos provisionados. (# terraform destroy)
