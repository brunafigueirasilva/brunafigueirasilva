
<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:10002B,45:5A189A,100:C77DFF&height=200&section=header&text=Bruna%20Figueira%20Silva&fontSize=40&fontColor=FFFFFF&fontAlignY=36&animation=fadeIn&desc=T%C3%A9cnica%20em%20Desenvolvimento%20de%20Sistemas%20%E2%80%A2%20Web%20%E2%80%A2%20Mobile&descSize=15&descAlignY=58" alt="Bruna Figueira Silva — Técnica em Desenvolvimento de Sistemas"/>

<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=18&pause=1400&color=9D4EDD&center=true&vCenter=true&width=560&lines=Desenvolvedora+de+Sistemas;Laravel+%E2%80%A2+Flutter+%E2%80%A2+MySQL;Desenvolvimento+Web+e+Mobile;Tecnologia+aplicada+a+solu%C3%A7%C3%B5es+reais" alt="Desenvolvedora de Sistemas · Laravel · Flutter · MySQL"/>

<br>

<a href="https://brunafigueirasilva.github.io/portifolio/">
<img src="https://img.shields.io/badge/PORTF%C3%93LIO-9D4EDD?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfólio"/>
</a>
<a href="https://github.com/BrunaFigueiraSilva">
<img src="https://img.shields.io/badge/GITHUB-240046?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>
<a href="https://www.linkedin.com/in/bruna-figueira-silva-a2b918451/">
<img src="https://img.shields.io/badge/LINKEDIN-5A189A?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:brunafsilva.09@icloud.com">
<img src="https://img.shields.io/badge/CONTATO-C77DFF?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"/>
</a>

</div>

---

## Sobre mim

Sou **Bruna Figueira Silva**, Técnica em Desenvolvimento de Sistemas, com conhecimentos em desenvolvimento web, mobile, banco de dados e engenharia de software.

Tenho experiência prática no desenvolvimento de aplicações completas, trabalhando desde a modelagem de bancos de dados e implementação de regras de negócio até a construção de interfaces e integração entre sistemas.

Possuo conhecimentos em **PHP, Laravel, MySQL, JavaScript, Flutter e Dart**, além de interesse em acessibilidade digital, desenvolvimento de APIs e soluções tecnológicas inovadoras.

Desenvolvi o **AgriFarm**, uma plataforma de gerenciamento inteligente de ração em fazendas, como projeto de conclusão de curso, aplicando conhecimentos de desenvolvimento web, mobile, banco de dados e IoT.

Busco minha primeira oportunidade profissional na área de tecnologia, onde possa aplicar meus conhecimentos, contribuir com projetos reais e continuar evoluindo como desenvolvedora.

---

## Tecnologias

<div align="center">

### Web Development

<img src="https://skillicons.dev/icons?i=html,css,js,php,laravel&theme=dark" alt="HTML, CSS, JavaScript, PHP e Laravel"/>

### Banco de Dados

<img src="https://skillicons.dev/icons?i=mysql&theme=dark" alt="MySQL"/>

### Mobile Development

<img src="https://skillicons.dev/icons?i=dart,flutter&theme=dark" alt="Dart e Flutter"/>

### Ferramentas

<img src="https://skillicons.dev/icons?i=git,github,vscode&theme=dark" alt="Git, GitHub e Visual Studio Code"/>

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
- Integridade de dados

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

### AgriFarm

<div align="center">

<img src="assets/agrifarm-logo.png" width="130" alt="Logo AgriFarm"/>

<br>

<img src="https://img.shields.io/badge/LARAVEL_12-245C32?style=flat-square&logo=laravel&logoColor=white"/>
<img src="https://img.shields.io/badge/PHP_8-245C32?style=flat-square&logo=php&logoColor=white"/>
<img src="https://img.shields.io/badge/MYSQL-245C32?style=flat-square&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/FLUTTER-245C32?style=flat-square&logo=flutter&logoColor=white"/>
<img src="https://img.shields.io/badge/IoT-245C32?style=flat-square&logoColor=white"/>

</div>

**Gerenciamento Inteligente de Ração em Fazendas**

O AgriFarm é uma plataforma desenvolvida para centralizar e otimizar o gerenciamento de ração em propriedades rurais, integrando informações sobre fazendas, lotes, cochos, consumo e estoque.

O sistema utiliza tecnologia para transformar dados operacionais em informações úteis para auxiliar produtores na tomada de decisões, reduzir desperdícios e melhorar o controle alimentar.

#### Funcionalidades

<table>
<tr>
<td width="50%" valign="top">

**Gestão**

- Cadastro de fazendas.
- Gerenciamento de lotes.
- Controle de cochos.
- Cadastro de rações.
- Controle de estoque.
- Planos alimentares.

</td>

<td width="50%" valign="top">

**Monitoramento**

- Dashboard por fazenda.
- Indicadores de consumo.
- Gráficos de desempenho.
- Relatórios gerenciais.
- Integração com sensores IoT.
- Aplicativo mobile.

</td>
</tr>
</table>

#### Arquitetura

```mermaid
flowchart TD

    U["Usuário"]

    subgraph UI["Interfaces"]
        WEB["Web<br/>Blade • JavaScript"]
        MOB["Mobile<br/>Flutter"]
    end

    subgraph APP["Aplicação Laravel"]
        ROUTE["Rotas"]
        AUTH["Autenticação"]
        CTRL["Controllers"]
        MODEL["Models • Eloquent"]
    end

    subgraph DB["Persistência"]
        MYSQL[("MySQL")]
    end

    subgraph SENSOR["IoT"]
        ESP["ESP32"]
        SENS["Sensores"]
    end

    U --> WEB
    U --> MOB

    WEB --> ROUTE
    MOB --> ROUTE

    ROUTE --> AUTH
    AUTH --> CTRL
    CTRL --> MODEL
    MODEL <--> MYSQL

    SENS --> ESP
    ESP --> ROUTE

    classDef purple fill:#5A189A,color:#fff,stroke:#C77DFF
    classDef backend fill:#240046,color:#fff,stroke:#9D4EDD
    classDef green fill:#245C32,color:#fff,stroke:#6AAA2E

    class WEB,MOB purple
    class ROUTE,AUTH,CTRL,MODEL backend
    class MYSQL,ESP,SENS green
```

#### Tecnologias utilizadas

| Tecnologia | Aplicação |
|---|---|
| Laravel 12 | Estrutura e back-end |
| PHP | Regras de negócio |
| MySQL | Persistência dos dados |
| Eloquent ORM | Relacionamento e consultas |
| Blade | Interface web |
| JavaScript | Interatividade |
| Chart.js | Gráficos e indicadores |
| Flutter | Aplicativo mobile |
| ESP32 | Integração IoT |

#### Acessibilidade digital

O sistema conta com recursos de acessibilidade para proporcionar uma experiência mais inclusiva:

- Modo claro e escuro.
- Alto contraste.
- Ajuste de fonte.
- Controle de zoom.
- Leitura em voz alta.
- Integração com VLibras.
- Atributos ARIA.
- Preferências persistidas no banco de dados.

<div align="center">

<a href="https://github.com/BrunaFigueiraSilva?tab=repositories">
<img src="https://img.shields.io/badge/VER_REPOSIT%C3%93RIOS-245C32?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</div>

---

### Portfólio pessoal

<div align="center">

<img src="https://img.shields.io/badge/HTML5-7B2CBF?style=flat-square&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-7B2CBF?style=flat-square&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/JAVASCRIPT-7B2CBF?style=flat-square&logo=javascript&logoColor=white"/>

</div>

Desenvolvi meu portfólio para apresentar minha trajetória profissional, habilidades técnicas e projetos.

O site possui uma apresentação interativa, animações, navegação dinâmica e um estudo de caso detalhado do AgriFarm, incluindo simulação de sensores e visualização de dados.

<div align="center">

<a href="https://brunafigueirasilva.github.io/portifolio/">
<img src="https://img.shields.io/badge/ACESSAR_PORTF%C3%93LIO-9D4EDD?style=for-the-badge&logo=googlechrome&logoColor=white"/>
</a>

<a href="https://github.com/BrunaFigueiraSilva/portifolio">
<img src="https://img.shields.io/badge/C%C3%93DIGO_FONTE-240046?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</div>

---

## GitHub Analytics

<div align="center">

### Estatísticas gerais

<img src="https://github-readme-stats.vercel.app/api?username=BrunaFigueiraSilva&show_icons=true&hide_border=true&title_color=C77DFF&icon_color=9D4EDD&text_color=E0AAFF&bg_color=10002B&rank_icon=github" height="180" alt="Estatísticas GitHub"/>

<br>

### Linguagens mais utilizadas

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=BrunaFigueiraSilva&layout=compact&hide_border=true&title_color=C77DFF&text_color=E0AAFF&bg_color=10002B&langs_count=8" height="180" alt="Linguagens mais utilizadas"/>

<br>

### Histórico de contribuições

<img src="https://github-readme-streak-stats.herokuapp.com/?user=BrunaFigueiraSilva&hide_border=true&background=10002B&stroke=5A189A&ring=C77DFF&fire=9D4EDD&currStreakLabel=E0AAFF&sideLabels=E0AAFF&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=9D4EDD" width="75%" alt="Histórico de contribuições"/>

</div>

---

## Objetivo profissional

<div align="center">

<img src="https://img.shields.io/badge/OPEN_TO_WORK-9D4EDD?style=for-the-badge&logoColor=white"/>

</div>

Técnica em Desenvolvimento de Sistemas, em busca da minha primeira oportunidade profissional na área de tecnologia.

Tenho interesse em oportunidades de:

- Desenvolvimento Back-end.
- Desenvolvimento Full Stack.
- Desenvolvimento Web.
- Desenvolvimento Mobile.
- Engenharia de Software.

Busco integrar uma equipe onde possa aplicar meus conhecimentos, participar de projetos, colaborar com outros profissionais e ampliar minha experiência prática.

---

## Contato

<div align="center">

Estou aberta a oportunidades, networking e projetos relacionados à tecnologia.

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

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:10002B,45:5A189A,100:C77DFF&height=100&section=footer"/>

</div>
