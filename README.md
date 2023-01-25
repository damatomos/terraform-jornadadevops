# Terraform com DigitalOcean
Criação da arquitetura de deployment com terraform


### Run

Para rodar tenha certeza que o terraform está instalado ou configurado
nas variáveis de ambiente


- Crie uma chave ssh para o digital ocean
- Crie um token de aplicação no digital ocean
- Crie um arquivo terraform.tfvars
- Modifique as variáveis em terraform.tfvars

Em terraform.tfvars:
```
do_token     = "" #token criado no digital ocean
ssh_key_name = "" #chave ssh adicionada no digital ocean
region       = "" #regiao do digital ocean
```

Rode o comando:
```
terraform apply
```
