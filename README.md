# Invillia recruitment challenge
## Explicação:

Para atender o projeto, desenvolvi 4 serviços em 4 bancos diferentes, desta forma atendendo o requisito de microserviçoes, fugindo da arquitetura monolítica. O motivo de ter sido desenvolvido desta maneira é para preservar o sistema de supostas falhas, caso um serviço pare, continuamos com os demais em pleno funcionamento.

#Requisitos não implementados (Falta de tempo):

Job (Quartz) para realizar o backup e centralização das informações dos 4 bancos.
Spring Security para autenticar via HTTP um usuário que terá permissão para executar os servições (Podendo ser em memória, JDBC ou JPA).
Docker para centralizar os containers das instalações do Java e Mysql.