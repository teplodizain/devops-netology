# devops-netology
# Local .terraform directories
**/.terraform/*
#Игнорировать во всех директориях директорию .terraform с любыми файлами

# .tfstate files
*.tfstate
#игнорировать все файлы с расширением .tfstate
*.tfstate.*
#игнорировать все файлы с расширением .tfstate. и любыми символами полсе точки

# Crash log files
crash.log
# игнорировать файл crash.log
crash.*.log
#игнорировать файлы  crash.*.log заместо * любые симоволы


# Exclude all .tfvars files, which are likely to contain sensitive data, such as
# password, private keys, and other secrets. These should not be part of version 
# control as they are data points which are potentially sensitive and subject 
# to change depending on the environment.
*.tfvars
*.tfvars.json
#игнорировать все файлы с расширениями *.tfvars, *.tfvars.json


# Ignore override files as they are usually used to override resources locally and so
# are not checked in
override.tf
override.tf.json
*_override.tf
*_override.tf.json
#игнорировать файлы override.tf override.tf.json
#игнорировать все файлы с расширениями, *_override.tf, *_override.tf.json

# Include override files you do wish to add to version control using negated pattern
# !example_override.tf

# Include tfplan files to ignore the plan output of command: terraform plan -out=tfplan
# example: *tfplan*

# Ignore CLI configuration files
.terraformrc
terraform.rc
Footer
#игнорировать файлы .terraformrc, terraform.rc, Footer

