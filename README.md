# devops-netology
thirst change to this file
second
third

and another
________________________________

The folowing files will be ignored because of terraform/.gitignored:

**/.terraform/* - в независимости от кол-ва вложенных каталогов, в которых находится каталог .terraform, 
игнорирование всего его содержания (за исключением вложенных каталогов)

*.tfstate  *.tfstate.* - игнорирование файлов с расширением tfstate, либо с имеющих в названии .tfstate. между 
другими любыми символами

crash.log  override.tf override.tf.json .terraformrc terraform.rc - игнорирование файлов с таким названием

*.tfvars *_override.tf *_override.tf.json - игнорирование файла с соответствующим окончанием в названии файла, 
вместо звездочки произвольный набор символов 
_______________________________

