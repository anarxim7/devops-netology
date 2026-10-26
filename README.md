# devops-netology
first modification
Благодаря .gitignore будут игнорироваться:
журналы ошибок Terraform(crash.log, crash.*.log),
файлы состояния Terraform (*.tfstate, *.tfstate.*),
локальный каталог Terraform (.terraform/), 
файлы с конфиденциальными данными (*.tfvars, *.tfvars.json)
локальные данные переопределения конфигурации (override.tf override.tf.json, *_override.tf,*_override.tf.json),
временный файл блокировки состояния(.terraform.tfstate.lock.info),
локальные файлы конфигурации Terraform CLI(.terraformrc, terraform.rc).


Изменения в ветке fix
