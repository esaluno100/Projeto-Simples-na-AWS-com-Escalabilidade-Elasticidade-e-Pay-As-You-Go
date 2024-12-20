# Projeto-Simples-na-AWS-com-Escalabilidade-Elasticidade-e-Pay-As-You-Go
Aqui está um projeto simplificado que utiliza os princípios de escalabilidade, elasticidade e o modelo de pagamento pay-as-you-go, implementado com serviços básicos da AWS. O foco será criar uma aplicação web funcional usando EC2, Auto Scaling, Load Balancer e S3 para armazenamento estático.
Objetivo
Criar uma aplicação web escalável e econômica que permite:

Escalabilidade: Ajustar automaticamente a capacidade para atender à demanda.
Elasticidade: Adicionar ou remover recursos conforme necessário.
Pay-As-You-Go: Pagar somente pelos recursos utilizados.
Serviços Utilizados
Amazon EC2: Para hospedar a aplicação web.
Elastic Load Balancer (ELB): Para distribuir o tráfego entre as instâncias.
Auto Scaling: Para ajustar dinamicamente o número de instâncias.
Amazon S3: Para armazenar arquivos estáticos (imagens, CSS, JS).
Amazon CloudWatch: Para monitoramento.


simple-cloud-project/
├── docs/
│   └── projeto_aws.md


├── app/
│   └── index.html
└── README.md
