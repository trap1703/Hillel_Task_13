# Hillel_Task_13
Домашнее задание 13
Добавлено: 19.02.2020 12:29
Your first infrastructure with CloudFormation
Создайте инфраструктуру из двух стеков: network и ec2

NetworkStack: Security Groups (for lb and ec2), Load Balancer
EC2Stack: Launch Config + AutoScaling Group
сделайте возможным пользователю понять что он получает ответ на http запрос 
по 80 порту на балансер от разных машин из ASG (а-ля "hello from $HOSTNAME")
