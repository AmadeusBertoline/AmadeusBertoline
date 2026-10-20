<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,60:1a1a1a,100:3d3d3d&height=220&section=header&text=Amadeus%20Bertoline&fontSize=54&fontColor=F2F2F2&fontAlignY=40&desc=Software%20Engineer%20%C2%B7%20Backend&descSize=18&descColor=A3A3A3&descAlignY=62&animation=fadeIn" width="100%" alt="header"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=3200&pause=1200&color=A3A3A3&center=true&vCenter=true&width=620&height=36&lines=Java+%C2%B7+Spring+Boot+%C2%B7+SQL;APIs+REST+com+regras+de+neg%C3%B3cio+reais;Concorr%C3%AAncia+%C2%B7+Seguran%C3%A7a+%C2%B7+Testes" alt="typing"/>

<br/><br/>

<a href="https://www.linkedin.com/in/amadeus-bertoline-8432a6194/"><img src="https://img.shields.io/badge/LinkedIn-1f1f1f?style=flat-square&logo=linkedin&logoColor=white&labelColor=0a0a0a"/></a>
<a href="https://github.com/AmadeusBertoline"><img src="https://img.shields.io/badge/GitHub-1f1f1f?style=flat-square&logo=github&logoColor=white&labelColor=0a0a0a"/></a>
<a href="mailto:amadeusbertoline123@gmail.com"><img src="https://img.shields.io/badge/E--mail-1f1f1f?style=flat-square&logo=gmail&logoColor=white&labelColor=0a0a0a"/></a>
<img src="https://img.shields.io/badge/S%C3%A3o%20Paulo%2C%20BR-1f1f1f?style=flat-square&logo=googlemaps&logoColor=white&labelColor=0a0a0a"/>
<img src="https://img.shields.io/badge/aberto%20a%20oportunidades-e6e6e6?style=flat-square&labelColor=0a0a0a&color=e6e6e6&logoColor=black"/>

</div>

<br/>

## 01 &nbsp;/&nbsp; Quem sou eu

```text
amadeus@github:~$ whoami

  Nome ........... Amadeus Bertoline
  Cargo alvo ..... Software Engineer (Backend)
  Atual .......... Estagiário em implantação de software
  Formação ....... Análise e Desenvolvimento de Sistemas · Fatec Zona Leste
  Foco ........... Java · Spring Boot · SQL
  Local .......... São Paulo, Brasil
  Status ......... Em busca da primeira posição como Engenheiro de Software
```

Sou estudante de ADS e trabalho com **implantação de software**, onde convivo com sistemas reais, clientes e processos. Meu foco de carreira é **backend em Java**: construo APIs REST com arquitetura em camadas, autenticação, cache, testes e deploy, e gosto de projetos com regra de negócio difícil, como **transações financeiras** e **disputa concorrente por recursos**.

<br/>

## 02 &nbsp;/&nbsp; Resumo do currículo

| | |
|---|---|
| **Formação** | Tecnólogo em Análise e Desenvolvimento de Sistemas, Fatec Zona Leste (em andamento) |
| **Experiência atual** | Estágio em implantação de software, em transição para desenvolvimento |
| **Objetivo** | Primeira vaga como Software Engineer / Backend, de preferência em banco ou empresa de tecnologia |
| **Projetos** | 2 APIs completas, com deploy, CI, testes e demo em vídeo |
| **Em estudo** | Microsserviços, mensageria (RabbitMQ, Kafka), API Gateway |

<br/>

## 03 &nbsp;/&nbsp; O que eu sei fazer

| Área | O que eu entrego |
|---|---|
| **APIs REST** | Spring Boot 3 com arquitetura em camadas (Controller, Service, Repository), DTOs imutáveis com `record`, tratamento de erros centralizado e documentação com Swagger/OpenAPI |
| **Segurança** | Autenticação stateless com JWT, hash de senha com BCrypt, autorização por papéis com Spring Security e checagem de propriedade nos services |
| **Concorrência** | Lock pessimista, lock otimista (`@Version`), índice único funcional e `UPDATE` condicional atômico, para evitar race condition, deadlock e estoque negativo |
| **Banco de dados** | MySQL 8, modelagem relacional, migrações versionadas com Flyway, triggers, índices e queries com JPA/Hibernate |
| **Performance** | Cache com Redis (TTL e invalidação nas escritas), paginação e exportação de dados |
| **Qualidade** | Testes unitários com JUnit 5 e Mockito (220+ no Poltrona), pipeline de CI com GitHub Actions |
| **Infra** | Docker e Docker Compose, deploy em nuvem (Render, Aiven, Railway) e variáveis de ambiente para os segredos |

<br/>

## 04 &nbsp;/&nbsp; Projetos

<table>
<tr>
<td width="50%" valign="top">

### 🎬 [Poltrona](https://github.com/AmadeusBertoline/poltrona)
**API de venda de ingressos e gestão de cinemas**

Hierarquia de proprietários, gerentes, cinemas e salas, com layout dinâmico de poltronas, grade de sessões, venda de ingressos e bomboniere, e PDF com QR Code.

- Dois clientes nunca compram a mesma poltrona: **índice único funcional** no MySQL
- Venda **atômica** (tudo ou nada) e estoque que nunca fica negativo
- Locks pessimistas com ordem definida para evitar deadlock
- JWT, 4 papéis, cache Redis, migrações Flyway
- **220+ testes** e CI no GitHub Actions
- Em produção no Render (API e Redis) e Aiven (MySQL)

[Repositório](https://github.com/AmadeusBertoline/poltrona) · [Swagger](https://poltrona.onrender.com/swagger-ui.html) · [Demo](https://www.youtube.com/watch?v=AZDOz4xqvSI)

<img src="https://img.shields.io/badge/Java%2021-1f1f1f?style=flat-square&logo=openjdk&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/Spring%20Boot-1f1f1f?style=flat-square&logo=springboot&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/MySQL-1f1f1f?style=flat-square&logo=mysql&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/Redis-1f1f1f?style=flat-square&logo=redis&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/Flyway-1f1f1f?style=flat-square&logo=flyway&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/Docker-1f1f1f?style=flat-square&logo=docker&logoColor=white&labelColor=0a0a0a"/>

</td>
<td width="50%" valign="top">

### 💰 [API Bank](https://github.com/AmadeusBertoline/api-bank)
**Banco digital com transferências Pix**

Cadastro com conta criada automaticamente, chaves Pix com detecção de tipo, limite diário, extrato paginado e painel de administração.

- Transferências **atômicas** com lock pessimista e ordenação de locks (sem deadlock)
- Extrato em cache no Redis, com invalidação a cada novo Pix
- Exportação do extrato em **CSV** com filtro por período
- Auditoria de status de conta via **trigger nativa** no MySQL
- JWT + BCrypt, perfis usuário e admin
- **64 testes** unitários e Docker Compose

[Repositório](https://github.com/AmadeusBertoline/api-bank) · [Demo](https://youtu.be/ftyhAU3ST7s)

<img src="https://img.shields.io/badge/Java%2021-1f1f1f?style=flat-square&logo=openjdk&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/Spring%20Boot-1f1f1f?style=flat-square&logo=springboot&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/Spring%20Security-1f1f1f?style=flat-square&logo=springsecurity&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/MySQL-1f1f1f?style=flat-square&logo=mysql&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/Redis-1f1f1f?style=flat-square&logo=redis&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/Docker-1f1f1f?style=flat-square&logo=docker&logoColor=white&labelColor=0a0a0a"/>

</td>
</tr>
</table>

<br/>

## 05 &nbsp;/&nbsp; Stack

| | |
|---|---|
| **Linguagem** | <img src="https://img.shields.io/badge/Java-1f1f1f?style=flat-square&logo=openjdk&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/SQL-1f1f1f?style=flat-square&logo=postgresql&logoColor=white&labelColor=0a0a0a"/> |
| **Frameworks** | <img src="https://img.shields.io/badge/Spring%20Boot-1f1f1f?style=flat-square&logo=springboot&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/Spring%20Security-1f1f1f?style=flat-square&logo=springsecurity&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/Spring%20Data%20JPA-1f1f1f?style=flat-square&logo=spring&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/Hibernate-1f1f1f?style=flat-square&logo=hibernate&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/JWT-1f1f1f?style=flat-square&logo=jsonwebtokens&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/Swagger-1f1f1f?style=flat-square&logo=swagger&logoColor=white&labelColor=0a0a0a"/> |
| **Dados** | <img src="https://img.shields.io/badge/MySQL-1f1f1f?style=flat-square&logo=mysql&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/Redis-1f1f1f?style=flat-square&logo=redis&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/Flyway-1f1f1f?style=flat-square&logo=flyway&logoColor=white&labelColor=0a0a0a"/> |
| **Testes** | <img src="https://img.shields.io/badge/JUnit%205-1f1f1f?style=flat-square&logo=junit5&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/Mockito-1f1f1f?style=flat-square&labelColor=0a0a0a"/> |
| **Infra & CI** | <img src="https://img.shields.io/badge/Docker-1f1f1f?style=flat-square&logo=docker&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/GitHub%20Actions-1f1f1f?style=flat-square&logo=githubactions&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/Render-1f1f1f?style=flat-square&logo=render&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/Railway-1f1f1f?style=flat-square&logo=railway&logoColor=white&labelColor=0a0a0a"/> |
| **Ferramentas** | <img src="https://img.shields.io/badge/Maven-1f1f1f?style=flat-square&logo=apachemaven&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/Git-1f1f1f?style=flat-square&logo=git&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/IntelliJ-1f1f1f?style=flat-square&logo=intellijidea&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/VS%20Code-1f1f1f?style=flat-square&logo=visualstudiocode&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/Insomnia-1f1f1f?style=flat-square&logo=insomnia&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/DBeaver-1f1f1f?style=flat-square&logo=dbeaver&logoColor=white&labelColor=0a0a0a"/> |
| **Estudando** | <img src="https://img.shields.io/badge/RabbitMQ-3d3d3d?style=flat-square&logo=rabbitmq&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/Kafka-3d3d3d?style=flat-square&logo=apachekafka&logoColor=white&labelColor=0a0a0a"/> <img src="https://img.shields.io/badge/Microsservi%C3%A7os-3d3d3d?style=flat-square&labelColor=0a0a0a"/> |

<br/>

## 06 &nbsp;/&nbsp; Fora do código

```text
amadeus@github:~$ cat interesses.txt

  anime ........ jojo e diário de uma apotecária
  música ....... todas
  cinema ....... cinéfilo
  academia ..... rotina
  viagens ...... sempre que dá
```

<br/>

## 07 &nbsp;/&nbsp; Contato

<div align="center">

Aberto a conversar sobre vagas de backend, Java e arquitetura de APIs.

<a href="https://www.linkedin.com/in/amadeus-bertoline-8432a6194/"><img src="https://img.shields.io/badge/LinkedIn-e6e6e6?style=for-the-badge&logo=linkedin&logoColor=black&labelColor=e6e6e6"/></a>
<a href="mailto:amadeusbertoline123@gmail.com"><img src="https://img.shields.io/badge/E--mail-1f1f1f?style=for-the-badge&logo=gmail&logoColor=white&labelColor=1f1f1f"/></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3d3d3d,40:1a1a1a,100:000000&height=110&section=footer" width="100%" alt="footer"/>

</div>
