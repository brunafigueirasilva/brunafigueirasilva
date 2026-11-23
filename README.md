
<div align="center">

# Bruna Figueira Silva

### Desenvolvedora de Sistemas em formação

Desenvolvimento Web · Back-end · Mobile

<br>

<a href="https://brunafigueirasilva.github.io/portifolio">
  <img src="https://img.shields.io/badge/PORTF%C3%93LIO-7B2CBF?style=for-the-badge&logo=googlechrome&logoColor=white" />
</a>
<a href="https://github.com/BrunaFigueiraSilva">
  <img src="https://img.shields.io/badge/GITHUB-240046?style=for-the-badge&logo=github&logoColor=white" />
</a>
<a href="https://www.linkedin.com/in/bruna-figueira-silva-a2b918451/">
  <img src="https://img.shields.io/badge/LINKEDIN-5A189A?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="mailto:brunafsilva.09@icloud.com">
  <img src="https://img.shields.io/badge/CONTATO-C77DFF?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

</div>

---

## Sobre mim

Sou estudante de **Desenvolvimento de Sistemas**, com interesse em desenvolvimento de software, arquitetura de aplicações, banco de dados e tecnologia aplicada à resolução de problemas reais.

Tenho experiência acadêmica e prática no desenvolvimento de aplicações web e mobile, trabalhando desde a modelagem de dados e implementação de regras de negócio até a construção de interfaces e integração entre sistemas.

Atualmente, desenvolvo o **AgriFarm**, uma plataforma de gerenciamento inteligente de ração em fazendas, como projeto de conclusão de curso.

Busco minha primeira oportunidade profissional na área de tecnologia, especialmente em desenvolvimento de software, onde possa contribuir com meus conhecimentos, evoluir tecnicamente e aprender com uma equipe.

---

## Tecnologias e ferramentas

<div align="center">

### Desenvolvimento Web

<img src="https://skillicons.dev/icons?i=html,css,js,php,laravel" />

### Banco de dados

<img src="https://skillicons.dev/icons?i=mysql" />

### Desenvolvimento Mobile

<img src="https://skillicons.dev/icons?i=dart,flutter" />

### Ferramentas

<img src="https://skillicons.dev/icons?i=git,github,vscode" />

</div>

<table>
<tr>
<td width="50%" valign="top">

### Back-end

- PHP 8+
- Laravel 12
- Eloquent ORM
- Controllers e rotas
- APIs REST
- Autenticação
- Regras de negócio

</td>
<td width="50%" valign="top">

### Front-end

- HTML5
- CSS3
- JavaScript ES6+
- Blade
- Interfaces responsivas
- Chart.js

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Banco de dados

- MySQL
- Modelagem relacional
- SQL
- Relacionamentos
- Integridade dos dados

</td>
<td width="50%" valign="top">

### Mobile e ferramentas

- Flutter
- Dart
- Git
- GitHub
- Visual Studio Code

</td>
</tr>
</table>

---

## Projetos

### AgriFarm — Gestão Inteligente de Ração em Fazendas

<div align="center">

<img src="assets/agrifarm-logo.png" width="130" alt="Logo AgriFarm"/>

<br>

<img src="https://img.shields.io/badge/Laravel_12-245C32?style=flat-square&logo=laravel&logoColor=white"/>
<img src="https://img.shields.io/badge/PHP_8-245C32?style=flat-square&logo=php&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-245C32?style=flat-square&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Flutter-245C32?style=flat-square&logo=flutter&logoColor=white"/>
<img src="https://img.shields.io/badge/IoT-245C32?style=flat-square&logoColor=white"/>

</div>

O **AgriFarm** é uma plataforma desenvolvida para centralizar e otimizar o gerenciamento de ração em propriedades rurais, integrando informações sobre fazendas, lotes, cochos, consumo e estoque.

O projeto busca transformar dados operacionais em informações úteis para auxiliar produtores na tomada de decisões, reduzir desperdícios e melhorar o controle alimentar.

#### Funcionalidades

- Dashboard com indicadores específicos por fazenda.
- Gerenciamento de fazendas e lotes.
- Controle de cochos e consumo de ração.
- Gerenciamento de rações e estoque.
- Planos alimentares.
- Relatórios de desempenho.
- Gráficos de consumo e indicadores.
- Integração com sensores IoT.
- Aplicação mobile com Flutter.
- Recursos de acessibilidade digital.

#### Diferenciais técnicos

| Área | Implementação |
|---|---|
| Arquitetura | MVC |
| Back-end | Laravel 12 |
| Persistência | MySQL |
| ORM | Eloquent |
| Interface web | Blade, HTML, CSS e JavaScript |
| Visualização de dados | Chart.js |
| Mobile | Flutter e Dart |
| IoT | ESP32 e sensores |
| Acessibilidade | WCAG, contraste, zoom e leitura em voz alta |

#### Arquitetura do sistema

```mermaid
flowchart TD

    U["Usuário"]

    subgraph FRONT["Interfaces"]
        WEB["Aplicação Web<br/>Blade • JavaScript"]
        MOB["Aplicativo Mobile<br/>Flutter"]
    end

    subgraph BACK["Back-end"]
        API["Rotas e APIs"]
        AUTH["Autenticação"]
        CTRL["Controllers"]
        ORM["Models • Eloquent"]
    end

    subgraph DATA["Banco de Dados"]
        DB[("MySQL")]
    end

    subgraph IOT["Integração IoT"]
        ESP["ESP32"]
        SENSOR["Sensores"]
    end

    U --> WEB
    U --> MOB

    WEB --> API
    MOB --> API

    API --> AUTH
    AUTH --> CTRL
    CTRL --> ORM
    ORM <--> DB

    SENSOR --> ESP
    ESP --> API

    class WEB,MOB front
    class API,AUTH,CTRL,ORM backend
    class DB database
    class ESP,SENSOR iot

    classDef front fill:#5A189A,color:#FFFFFF,stroke:#C77DFF
    classDef backend fill:#240046,color:#FFFFFF,stroke:#9D4EDD
    classDef database fill:#163A24,color:#FFFFFF,stroke:#6AAA2E
    classDef iot fill:#245C32,color:#FFFFFF,stroke:#6AAA2E
```

#### Acessibilidade

O sistema também possui recursos voltados à acessibilidade digital:

- Modo claro e escuro.
- Alto contraste.
- Ajuste de tamanho de fonte.
- Controle de zoom.
- Leitura de conteúdo em voz alta.
- Integração com VLibras.
- Elementos semânticos e atributos ARIA.
- Persistência das preferências do usuário.

<div align="center">

<a href="https://github.com/BrunaFigueiraSilva">
<img src="https://img.shields.io/badge/REPOSIT%C3%93RIOS-245C32?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</div>

---

### Portfólio pessoal

<div align="center">

<img src="https://img.shields.io/badge/HTML5-7B2CBF?style=flat-square&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-7B2CBF?style=flat-square&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-7B2CBF?style=flat-square&logo=javascript&logoColor=white"/>

</div>

Desenvolvi meu portfólio pessoal para apresentar minha trajetória, habilidades técnicas, projetos e experiências de desenvolvimento.

O site conta com uma apresentação interativa, animações, navegação entre seções e um estudo de caso detalhado do AgriFarm, incluindo uma simulação de sensores e visualização dinâmica de dados.

<div align="center">

<a href="https://brunafigueirasilva.github.io/portifolio/">
<img src="https://img.shields.io/badge/VISUALIZAR_PORTF%C3%93LIO-7B2CBF?style=for-the-badge&logo=googlechrome&logoColor=white"/>
</a>

<a href="https://github.com/BrunaFigueiraSilva/portifolio">
<img src="https://img.shields.io/badge/C%C3%93DIGO_FONTE-240046?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</div>

---

## GitHub

<div align="center">

### Estatísticas

<img src="https://github-readme-stats.vercel.app/api?username=BrunaFigueiraSilva&show_icons=true&hide_border=true&title_color=C77DFF&icon_color=9D4EDD&text_color=E0AAFF&bg_color=10002B&rank_icon=github" height="165" alt="Estatísticas do GitHub"/>

### Linguagens mais utilizadas

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=BrunaFigueiraSilva&layout=compact&hide_border=true&title_color=C77DFF&text_color=E0AAFF&bg_color=10002B&langs_count=8" height="165" alt="Linguagens mais utilizadas"/>

### Contribuições

<img src="https://github-readme-streak-stats.herokuapp.com/?user=BrunaFigueiraSilva&hide_border=true&background=10002B&stroke=5A189A&ring=C77DFF&fire=9D4EDD&currStreakLabel=E0AAFF&sideLabels=E0AAFF&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=9D4EDD" width="75%" alt="Sequência de contribuições"/>

</div>

---

## Objetivo profissional

<div align="center">

<img src="https://img.shields.io/badge/OPEN_TO_WORK-9D4EDD?style=for-the-badge&logoColor=white"/>

</div>

Busco uma oportunidade de **estágio em Desenvolvimento de Sistemas**, com interesse em:

- Desenvolvimento Back-end.
- Desenvolvimento Full Stack.
- Desenvolvimento Web.
- Desenvolvimento Mobile.
- Banco de dados.
- Engenharia de software.

Tenho disposição para aprender, desenvolver novas habilidades, colaborar em equipe e participar de projetos que contribuam para meu crescimento profissional e para os resultados da empresa.

---

## Contato

<div align="center">

Vamos conversar sobre tecnologia, projetos ou oportunidades profissionais?

<br>

<a href="mailto:brunafsilva.09@icloud.com">
<img src="https://img.shields.io/badge/E--MAIL-7B2CBF?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/in/bruna-figueira-silva-a2b918451/">
<img src="https://img.shields.io/badge/LINKEDIN-5A189A?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://brunafigueirasilva.github.io/portifolio/">
<img src="https://img.shields.io/badge/PORTF%C3%93LIO-C77DFF?style=for-the-badge&logo=googlechrome&logoColor=white"/>
</a>

<a href="https://github.com/BrunaFigueiraSilva">
<img src="https://img.shields.io/badge/GITHUB-240046?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<br><br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:10002B,50:5A189A,100:C77DFF&height=100&section=footer"/>

</div>
