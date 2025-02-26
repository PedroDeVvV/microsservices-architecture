# Microsservice Architecture


I created this infrastructure to learn about microsservices architecture.

## What did I use ?
- Java 17
- SpringBoot
- Migrations
- Service Discovery and Registry
- API Gateway 
- Load Balancer
- Spring Feign
- Circuit Breaker and Fallback


## 🚀How does it works ?

The service discover show all running microsservices, with their ports and uris, i used spring eureka to make this service.
Any request is sent to the api gateway, where the service redistributes the requests to the desired microservice, and in this case, to the free instance.

## ✅What are the benefits ?

Microservices architecture allows you to maintain different parts of the system without having to compromise the entire application structure, and also optimizing time taking into account that you can build each part separately.

## PT-BR 

# Arquitetura de Microsserviços
Criei essa infraestrutura para aprender sobre arquitetura de microsserviços.

## 📌 O que utilizei?
- Java 17
- Spring Boot
- Migrations
- Service Discovery e Registry
- API Gateway
- Load Balancer
- Spring Feign
- Circuit Breaker e Fallback

## 🚀 Como funciona?

O Service Discovery exibe todos os microsserviços em execução, juntamente com suas portas e URIs. Para isso, utilizei o Spring Eureka.

Toda requisição é enviada para o API Gateway, que redistribui as chamadas para o microsserviço desejado, garantindo que a solicitação seja encaminhada para uma instância disponível e otimizada.

## ✅ Quais são os benefícios?
A arquitetura de microsserviços permite manter diferentes partes do sistema de forma independente, sem comprometer toda a estrutura da aplicação. Além disso, otimiza o tempo de desenvolvimento, pois cada serviço pode ser construído e implantado separadamente.
