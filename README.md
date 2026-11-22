<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:58A6FF&height=200&section=header&text=Gustavo%20Santos&fontSize=60&fontColor=FFFFFF&fontAlignY=38&desc=Full%20Stack%20Developer%20%7C%20Automation%20%+%20Software%20Quality&descAlignY=58&descSize=20&animation=fadeIn" alt="Banner" width="100%"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=EXP%3A+BNDES+%2B+SERPRO+%2B+RIEX;Stack%3A+Java+%2B+Spring+%2B+React;Cypress+%2B+Docker+%2B+CI%2FCD" alt="Typing SVG" /></a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Gustavo_Santos-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gustavoolsantos/)
[![Gmail](https://img.shields.io/badge/Gmail-Contato-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contato@gustavoolsantos.dev.br)
[![Portfólio](https://img.shields.io/badge/Portfólio-gustavoolsantos.dev.br-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://www.gustavoolsantos.dev.br/)

</div>

<br/>

## Sobre mim

```java
public class Gustavo implements Developer {

    private final String[] stack = {"Java", "Spring Boot", "React", "JavaScript", "PHP"};
    private final String[] tools = {"VScode", "Cypress", "Docker", "RabbitMQ", "CI/CD", "AI"};
    private final String focus   = "Backend-focused Full Stack";
    private final String[] experience = {"BNDES", "Serpro", "Riex"};

    @Override
    public String[] currentlyLearning() {
        return new String[]{"Microservices"};
    }
}
```

Desenvolvedor Full Stack com foco em Back-end Java, atuando no desenvolvimento e manutenção de aplicações corporativas, APIs REST e integrações entre sistemas. Tenho experiência com Java, Spring Boot, Spring Security, JPA/Hibernate e React, além de automação de processos, testes automatizados e CI/CD.

Atualmente, trabalho com desenvolvimento de sistemas no BNDES, após experiências no SERPRO e em projetos de desenvolvimento e automação na Riex. Nessas experiências, participei da manutenção de sistemas em produção, otimização de consultas SQL, integração de serviços, automação de processos e implementação de testes E2E com Cypress.

Sou estudante de Ciência da Computação na Universidade Veiga de Almeida e técnico em Automação Industrial pelo CEFET/RJ. Tenho interesse em engenharia de software, arquitetura de sistemas e desenvolvimento de soluções que resolvam problemas reais.

Atualmente, desenvolvo projetos próprios utilizando Java, Spring Boot e React, com destaque para o Sentry e o Skill Up.

<br/>

## Tech Stack

<div align="left">

### Backend  <img src="https://skillicons.dev/icons?i=java,spring,php" />
### Frontend <img src="https://skillicons.dev/icons?i=react,js,bootstrap,html,css,wordpress" />
### Bancos de Dados <img src="https://skillicons.dev/icons?i=mysql,mongodb,postgres" />
### Mensageria <img src="https://skillicons.dev/icons?i=rabbitmq" />
### Testes     <img src="https://skillicons.dev/icons?i=cypress" />
### DevOps e ferramentas <img src="https://skillicons.dev/icons?i=docker,git,linux,github,githubactions,gitlab" />

</div>

<br/>

## Projetos em destaque

### [Sentry — Plataforma de Gestão de Vulnerabilidades](https://github.com/GustavoOlSantos/sentry)

Aplicação full stack voltada à descoberta de ativos e serviços de rede, identificação de vulnerabilidades e avaliação de configurações de segurança.

<img src="./home.png" height="300px"/>

- **Backend:** Java e Spring Boot, com APIs REST para gerenciamento de varreduras, ativos e findings.
- **Varredura e análise:** integração com Nmap para descoberta de hosts e serviços, consulta à base NVD para identificação de vulnerabilidades associadas a CVEs e verificações automatizadas de configurações.
- **Mensageria:** RabbitMQ para processamento assíncrono das solicitações de varredura.
- **Frontend:** React para visualização e gerenciamento dos resultados.
- **Infraestrutura:** Docker e Docker Compose para execução dos serviços e ambiente de laboratório.

<p>
  <a href="https://github.com/GustavoOlSantos/sentry">
    <img src="https://img.shields.io/badge/Repositório-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="https://github.com/GustavoOlSantos/sentry#readme">
    <img src="https://img.shields.io/badge/README-Documentação-blue?style=for-the-badge&logo=readthedocs&logoColor=white"/>
  </a>
</p>

### [SkillUp — Plataforma de Cursos Online](https://github.com/GustavoOlSantos/skill-up)

Plataforma EAD full stack com funcionalidades de gerenciamento de cursos, matrículas, reprodução de aulas e avaliações de usuários.

<img src="./skill-up.png" height="300px"/>

- **Backend:** Java 21 e Spring Boot, com APIs REST, autenticação e autorização utilizando Spring Security e JWT.
- **Persistência:** MySQL para cursos, categorias e compras; MongoDB para avaliações.
- **Frontend:** React e Cloudinary para hospedagem de imagens.
- **CI/CD:** GitHub Actions com build paralelo de frontend e backend, testes E2E com Cypress, seed automatizado de banco de dados, análise estática e verificações de segurança.
- **Observabilidade:** logging estruturado com Logback e Logstash Encoder, com configurações específicas para os ambientes local e produção.
- **Performance:** identificação e correção de um gargalo que gerava mais de 16 requisições individuais para carregar avaliações, substituindo-as por uma consulta consolidada em um único endpoint. Utilização de `Collectors.teeing` para processamento combinado dos dados e cache de aplicação em endpoints com baixa necessidade de atualização em tempo real.

<p>
  <a href="https://github.com/GustavoOlSantos/skill-up">
    <img src="https://img.shields.io/badge/Repositório-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="https://skillup.gustavoolsantos.dev.br/">
    <img src="https://img.shields.io/badge/Deploy-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
  </a>
  <a href="https://github.com/GustavoOlSantos/skill-up#readme">
    <img src="https://img.shields.io/badge/README-Arquitetura_detalhada-blue?style=for-the-badge&logo=readthedocs&logoColor=white"/>
  </a>
</p>

<br/>

## GitHub Stats

<div align="center">
  <img height="165" src="https://github-readme-stats-fast.vercel.app/api?username=GustavoOlSantos&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=GustavoOlSantos&layout=compact&theme=tokyonight&hide_border=true" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=GustavoOlSantos&theme=tokyonight&hide_border=true" />
</div>

<br/>

## Vamos conversar

<div align="center">

Estou sempre aberto a trocar ideia sobre backend, arquitetura de sistemas ou boas práticas de engenharia.

[![LinkedIn](https://img.shields.io/badge/-Conecte--se_no_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gustavoolsantos/)
[![Gmail](https://img.shields.io/badge/-Envie_um_e--mail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contato@gustavoolsantos.dev.br)

<sub>⭐ Se algum projeto aqui te interessou, deixa uma estrela!</sub>

</div>
