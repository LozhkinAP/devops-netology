Домашнее задание к занятию "2.1. Системы контроля версий."
В каталоге terraform будут проигнорированы файлы:

**/.terraform/*
все файлы и каталоги в каталоге .terraform

*.tfstate
файлы с расширением .tfstate
*.tfstate.*
файлы, содержащие в названии .tfstate.

crash.log
файлы с названием crash.log
crash.*.log
файлы с названием, начинающимся на crash. и расширением .log

*.tfvars
файлы с расширением .tfvars
*.tfvars.json
файлы, названия которых заканчиваются на .tfvars.json

override.tf
override.tf.json
*_override.tf
*_override.tf.json
файлы override.tf, override.tf.json, и любые файлы, названия которых заканчиваются на _override.tf или _override.tf.json

.terraformrc
terraform.rc
файлы terraform.rc и .terraformrc

