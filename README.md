# devops-netology
Первое изменение файла

# Terraform
Корневой `.gitignore` будет игнорировать:
- временные файлы операционных систем;
- настройки редакторов и IDE;
- swap-файлы;
- log-файлы;
- временные каталоги `tmp/` и `temp/`.

В каталоге `terraform` добавлен отдельный `.gitignore`, который будет игнорировать:
- локальные каталоги `.terraform/`;
- файлы состояния Terraform `*.tfstate`;
- crash logs Terraform;
- файлы переменных `*.tfvars` и `*.tfvars.json`, так как они могут содержать пароли, токены и другие секреты;
- локальные override-файлы;
- служебные lock-файлы Terraform;
- локальные CLI-конфиги `.terraformrc` и `terraform.rc`.
