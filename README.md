<!-- ===================== HEADER ===================== -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:161B22,100:2F81F7&height=230&section=header&text=Amadeus%20Bertoline&fontSize=58&fontColor=E6EDF3&fontAlignY=38&desc=Software%20Engineer%20%7C%20Java%20%26%20Spring%20Boot&descSize=20&descAlignY=60&animation=fadeIn" width="100%" alt="header"/>

<a href="https://github.com/AmadeusBertoline">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=1000&color=2F81F7&center=true&vCenter=true&width=640&height=40&lines=%24+whoami+%E2%86%92+Amadeus;Backend+Java+%7C+Spring+Boot+%7C+SQL;Arquitetura+em+camadas+%7C+Boas+pr%C3%A1ticas;C%C3%B3digo+que+se+sustenta+em+produ%C3%A7%C3%A3o" alt="Typing SVG" />
</a>

<br/>

<a href="https://www.linkedin.com/in/amadeus-bertoline-8432a6194/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://github.com/AmadeusBertoline">
  <img src="https://img.shields.io/badge/GitHub-161B22?style=for-the-badge&logo=github&logoColor=white"/>
</a>
<a href="mailto:amadeusbertoline123@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<br/><br/>

<img src="https://img.shields.io/badge/status-aberto%20a%20oportunidades-2EA043?style=flat-square&labelColor=0D1117"/>
<img src="https://img.shields.io/badge/foco-backend%20%2F%20java-2F81F7?style=flat-square&labelColor=0D1117"/>
<img src="https://img.shields.io/badge/local-S%C3%A3o%20Paulo%2C%20BR-8B949E?style=flat-square&labelColor=0D1117"/>

</div>

<br/>

## `~/sobre-mim`

```java
public class Amadeus implements SoftwareEngineer {

    private final String formacao  = "Análise e Desenvolvimento de Sistemas @ Fatec Zona Leste";
    private final String atuacao   = "Estagiário em implantação de software → migrando para desenvolvimento";
    private final String foco      = "Backend com Java, Spring Boot e SQL";
    private final String objetivo  = "Primeira oportunidade como Engenheiro de Software";

    @Override
    public String filosofia() {
        return "Código que se sustenta em produção, não só 'funciona na minha máquina'.";
    }
}
```

- 🏦 Meus projetos simulam **regras de negócio complexas**: sistemas financeiros, concorrência, reservas e controle de estado
- 🧱 Gosto de **arquitetura em camadas**, boas práticas, testes e performance
- 🔐 Preocupação real com **segurança, integridade de dados e consistência transacional**
- 🌱 Sempre estudando: mensageria, arquitetura distribuída e microsserviços

<br/>

## `~/stack`

<div align="center">

**Linguagem & Frameworks**

<img src="https://skillicons.dev/icons?i=java,spring,hibernate,maven&theme=dark" /> 

**Dados & Cache**

<img src="https://skillicons.dev/icons?i=mysql,redis&theme=dark" />

**Infra & Ferramentas**

<img src="https://skillicons.dev/icons?i=docker,git,github,linux,intellij,postman&theme=dark" />

<br/>

<img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white"/>
<img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white"/>
<img src="https://img.shields.io/badge/JUnit%205-25A162?style=for-the-badge&logo=junit5&logoColor=white"/>
<img src="https://img.shields.io/badge/Mockito-78A641?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black"/>
<img src="https://img.shields.io/badge/Docker%20Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white"/>

</div>

<br/>

## `~/projetos`

<table>
<tr>
<td width="50%" valign="top">

### 💰 [api-bank](https://github.com/AmadeusBertoline/api-bank)
**API REST de um banco digital com transferências via Pix**

- 🔐 Autenticação **JWT + BCrypt**, perfis usuário/admin
- ⚛️ Transferências **atômicas** com **lock pessimista** (evita condição de corrida)
- ⚡ Cache com **Redis**, limite diário configurável, extrato paginado
- 📄 Swagger UI + Docker Compose
- 🧪 **45 testes** (JUnit 5 + Mockito)
- 🚀 Deploy em produção (**Railway**)

<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/> <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>

</td>
<td width="50%" valign="top">

### 🎬 [poltrona](https://github.com/AmadeusBertoline/poltrona)
**API REST para reserva de ingressos e gestão de assentos de cinema**

- 🪑 Sessões, salas e disponibilidade de assentos em tempo real
- 🔒 Controle de **concorrência** e integridade na reserva
- 🛡️ Autenticação e autorização com **JWT + Spring Security**
- ⚡ Cache de consultas frequentes com **Redis**
- 🐳 Ambiente containerizado com **Docker**
- 🧪 Testes unitários e de integração (JUnit 5 + Mockito)

<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/> <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>

</td>
</tr>
</table>

<br/>

## `~/em-evolucao`

```yaml
estudando_agora:
  - Spring Security avançado
  - Microsserviços do zero
  - Mensageria: RabbitMQ e Kafka
  - API Gateway e arquitetura distribuída
  - Performance e cache distribuído com Redis
meta: "Engenheiro de Software em um banco / empresa de tecnologia"
```

<div align="center">

<img src="https://skillicons.dev/icons?i=rabbitmq,kafka,redis,docker&theme=dark" />

</div>

<br/>

## `~/github-stats`

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=AmadeusBertoline&show_icons=true&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=2F81F7&icon_color=2F81F7&text_color=C9D1D9&count_private=true" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AmadeusBertoline&layout=compact&theme=github_dark&hide_border=true&bg_color=0D1117&title_color=2F81F7&text_color=C9D1D9" />

<br/>

<img src="https://streak-stats.demolab.com/?user=AmadeusBertoline&theme=github-dark-blue&hide_border=true&background=0D1117" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=AmadeusBertoline&bg_color=0D1117&color=2F81F7&line=2F81F7&point=E6EDF3&area=true&area_color=2F81F7&hide_border=true" width="95%" />

</div>

<br/>

## `~/fora-do-codigo`

<div align="center">

🏋️ Academia &nbsp;•&nbsp; ✈️ Viagens &nbsp;•&nbsp; 🎧 Música &nbsp;•&nbsp; 🎬 Cinema (sou bem cinéfilo) &nbsp;•&nbsp; 🍻 Bons momentos com amigos

</div>

<br/>

## `~/contato`

<div align="center">

Vamos conversar sobre backend, arquitetura ou oportunidades!

<a href="https://www.linkedin.com/in/amadeus-bertoline-8432a6194/"><img src="https://img.shields.io/badge/Falar%20no%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:amadeusbertoline123@gmail.com"><img src="https://img.shields.io/badge/Enviar%20e--mail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=AmadeusBertoline&style=for-the-badge&color=2F81F7&label=VISITAS&labelColor=0D1117" alt="Contador de visitas"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2F81F7,50:161B22,100:0D1117&height=120&section=footer" width="100%" alt="footer"/>
