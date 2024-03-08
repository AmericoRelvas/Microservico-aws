## 🔨 Projeto CDK Java

Este projeto foi desenvolvido no curso de Microserviços na prática: IaC com CDK e deploy na AWS na plataforma Alura.
Foi desenvolvido um projeto de Infraestrutura como Código (IaC) do zero, utilizando o AWS CDK (Cloud Development Kit) e escrevendo seu código em Java. Também criou classes específicas para cada stack, provisionando recursos de CPU, memória, configurando Load Balancer, Auto Scaling e definindo métricas para que o ambiente na nuvem controle o momento certo de criar ou destruir novas instâncias.

Este projeto usa diversas tecnologias e ferramentas como:

**Java 17:** Linguagem de programação back-end.

**Spring Boot:** Para a construção da aplicação Java de maneira rápida e eficiente.

**Maven:** Como gerenciador de dependências, facilitando o processo de construção e execução do projeto.

**MySQL:** Como banco de dados relacional da aplicação.

**AWS ECR:** Serviço totalmente gerenciado que permite armazenar, gerenciar e implantar imagens de contêineres do Docker na nuvem da AWS. 

**AWS RDS:** Serviço de banco de dados relacional totalmente gerenciado que facilita a configuração, operação e escalabilidade de bancos de dados relacionais na nuvem da AWS. 

**AWS ECS:** Serviço de orquestração de contêineres altamente dimensionável e totalmente gerenciado que permite executar, interromper e gerenciar contêineres Docker em uma infraestrutura escalável.

**AWS CDK:** Estrutura de desenvolvimento de software que permite definir recursos de infraestrutura como código usando linguagens de programação.

**AWS Cloudformation:** Serviço que permite modelar e provisionar recursos da AWS de forma automatizada e previsível, usando arquivos de modelo YAML ou JSON. 

**Docker:** Plataforma de software que permite que você empacote, distribua e execute aplicativos em contêineres. 

## 🔨 Objetivos do projeto

 - Entender a motivação para levar a infraestrutura para o ambiente Cloud e os recursos necessários para o deploy
 - Conheçer o AWS CDK (Cloud Development Kit), framework de desenvolvimento para escrever e provisionar a infra utilizando linguagens de programação conhecidas
 - Saiber o que é ECS, ECR, Fargate, RDS e qual o papel de cada um deles na sua solução arquitetural
 - Descubrir o que é necessário para conectar a aplicação a um banco de dados gerenciado pelo RDS
 - Realizar o deploy na nuvem AWS de todas as Stacks 
 - Monitorar os logs da aplicação com o Cloudwatch e fazer o Auto Scaling dos serviços

