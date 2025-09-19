# DevOps  

Repositório criado para a disciplina de **DevOps** da faculdade.  
Aqui serão desenvolvidos os exercícios propostos em aula e, posteriormente, adicionados os itens das entregas somativas.  

Durante a matéria, aprendemos sobre **Git** e **GitHub**, incluindo o uso do **GitHub Desktop**, além de conhecer outros sistemas de controle de versão que podem ser utilizados.   

---

## CI/CD  

Também estudamos os conceitos de **CI/CD**:  

- **CI (Continuous Integration):** prática de integrar pequenas partes do código em um repositório compartilhado várias vezes ao dia, garantindo que cada mudança seja testada e validada automaticamente.  
- **CD (Continuous Delivery):** mantém o código em um estado pronto para ser implantado em produção a qualquer momento, mas a implantação ainda é feita manualmente.  
- **CD (Continuous Deployment):** vai além do continuous delivery — o código é implantado automaticamente em produção assim que passa por todas as etapas de teste e validação, sem necessidade de intervenção manual.  

Após a teoria, aplicamos esses conceitos na prática, implementando pipelines de CI/CD neste repositório.  

---

## Docker  

Aprendemos a instalar e criar nossos próprios containers com **Docker**, além de configurar o **Docker** dentro do **GitHub Actions** para automatizar o fluxo de desenvolvimento.  

---

## Alertas (Logs e Monitoramento)  

Estudamos a importância de **logs e monitoramento**, e na prática configuramos alertas para o **Discord**, notificando quando uma nova funcionalidade é adicionada.  

---

## Testes  

Discutimos a importância de **testes automatizados**, analisando casos reais de prejuízos causados pela ausência de testes.  

Na prática:  

1. Criamos testes em **Python** para as funções do projeto.  
2. Integramos esses testes ao pipeline de **CI**.  
3. Recebemos alertas no **GitHub** quando algum teste falha, permitindo corrigir os erros antes de enviar o código para produção.  

---
