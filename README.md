# Terraform + Yandex Cloud

Две виртуальные машины Ubuntu 24.04 с сетью, подсетью и дисками в Yandex Cloud.

## Запуск
1. `cp .env.example .env` и заполни значения
2. `source .env`
3. `terraform init && terraform plan && terraform apply`

Удаление: `terraform destroy`.
