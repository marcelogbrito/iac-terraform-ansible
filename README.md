# Provisionamento de instancia EC2 da AWS com IAC (infraestrutura como codigo) usando Terraform

Esse script cria e sobe uma instancia micro gratuita Ubuntu no serviço EC2 da AWS

provisionando com terraform

```
terraform apply
```

configurando com ansible 
```
ansible-playbook playbook.yml -u ubuntu --private-key iac-ubuntu.pem -i hosts.yml 
```


servidor http configurado

http://3.80.85.55:8080/



