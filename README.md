<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:10002B,45:5A189A,100:C77DFF&height=200&section=header&text=Bruna%20Figueira%20Silva&fontSize=40&fontColor=FFFFFF&fontAlignY=36&animation=fadeIn&desc=Desenvolvedora%20Full%20Stack%20%26%20Mobile%20em%20forma%C3%A7%C3%A3o&descSize=15&descAlignY=58" alt="Bruna Figueira Silva — Desenvolvedora Full Stack e Mobile em formação"/>

<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=18&pause=1400&color=9D4EDD&center=true&vCenter=true&width=580&lines=Desenvolvimento+de+Sistemas+%E2%80%A2+Web+%26+Mobile;Do+banco+de+dados+%C3%A0+interface+acess%C3%ADvel;Foco+em+boas+pr%C3%A1ticas%2C+arquitetura+e+WCAG+2.2" alt="Desenvolvimento de Sistemas, Web e Mobile, boas práticas e WCAG 2.2"/>

<p>
  <img src="https://img.shields.io/badge/Dispon%C3%ADvel_para_est%C3%A1gio-2EA043?style=for-the-badge&logo=handshake&logoColor=white" alt="Disponível para estágio"/>
  <a href="https://github.com/SEU-USUARIO"><img src="https://img.shields.io/badge/GitHub-240046?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  <a href="https://www.linkedin.com/in/SEU-LINKEDIN/"><img src="https://img.shields.io/badge/LinkedIn-5A189A?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:SEU-EMAIL?subject=Oportunidade%20de%20est%C3%A1gio"><img src="https://img.shields.io/badge/E--mail-7B2CBF?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"/></a>
</p>

</div>

---

## Sobre mim

Estudante de **Desenvolvimento de Sistemas** com experiência prática na construção de aplicações completas — da modelagem relacional e regras de negócio no back-end até interfaces responsivas, acessíveis e aplicativos mobile.

Busco minha **primeira oportunidade de estágio** em desenvolvimento (back-end, front-end, full stack ou mobile) para evoluir em equipe por meio de revisões de código e boas práticas de engenharia de software.

---

## Stack & Ferramentas

<div align="center">

<img src="https://skillicons.dev/icons?i=php,laravel,mysql,html,css,js,dart,flutter,git,github,vscode&theme=dark&perline=11" alt="PHP, Laravel, MySQL, HTML, CSS, JavaScript, Dart, Flutter, Git, GitHub e VS Code"/>

<br/><br/>

| Camada | Tecnologias e práticas |
|:---|:---|
| **Back-end & Dados** | PHP 8+, Laravel 12, Eloquent ORM, autenticação por sessão, MySQL |
| **Front-end** | HTML5, CSS3, JavaScript (ES6+), Blade, Chart.js, Acessibilidade (WCAG 2.2) |
| **Mobile & Fluxo** | Flutter, Dart, Git, GitHub |

</div>

---

## Projeto em Destaque

<div align="center">

<p>
  <img src="assets/agrifarm-logo.png" height="68" alt="Logo do AgriFarm"/>
  &nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Animals/Cow.png" height="58" alt="Ícone animado"/>
</p>

### AgriFarm — Gestão Inteligente de Ração em Fazendas

<p>
  <img src="https://img.shields.io/badge/TCC-Desenvolvimento_de_Sistemas-5A189A?style=flat-square" alt="TCC"/>
  <img src="https://img.shields.io/badge/Laravel_12-245C32?style=flat-square&logo=laravel&logoColor=white" alt="Laravel 12"/>
  <img src="https://img.shields.io/badge/PHP_8+-245C32?style=flat-square&logo=php&logoColor=white" alt="PHP 8+"/>
  <img src="https://img.shields.io/badge/MySQL-245C32?style=flat-square&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/Flutter-245C32?style=flat-square&logo=flutter&logoColor=white" alt="Flutter"/>
  <img src="https://img.shields.io/badge/WCAG_2.2-AA%2FAAA-6AAA2E?style=flat-square" alt="WCAG 2.2 AA/AAA"/>
</p>

Plataforma web e mobile que centraliza o controle operacional de propriedades rurais — **fazendas, lotes, animais, cochos, rações, estoque e planos alimentares** — para reduzir desperdícios e apoiar decisões de reposição com dados reais.

</div>

<table>
<tr>
<td width="50%" valign="top">

**Módulos & Indicadores**
- **Dashboard dinâmico:** indicadores calculados no back-end (novos lotes na semana, variação de consumo, custo estimado e nível de estoque) com gráficos em Chart.js.
- **Domínio relacional:** CRUD completo apoiado por **9 Models Eloquent** interligados e relatórios gerenciais.

</td>
<td width="50%" valign="top">

**Acessibilidade Nativa (WCAG 2.2)**
- Componente global presente em todas as telas da aplicação.
- Temas claro, escuro e **alto contraste (AAA)**, ajuste de fonte/zoom, leitura em voz alta, atributos ARIA e **VLibras**.
- Preferências persistidas individualmente no banco de dados por usuário.

</td>
</tr>
</table>

### Arquitetura do Sistema

```mermaid
flowchart LR
    subgraph C["Camada de Apresentação"]
        direction TB
        W["Web • Blade + JS ES6+"]
        G["Gráficos • Chart.js"]
        AC["Acessibilidade • Temas, Voz & VLibras"]
        M["Mobile • Flutter"]
    end

    subgraph B["Back-end • Laravel 12"]
        direction TB
        R["Rotas & Sessão"]
        subgraph CT["Controllers"]
            direction TB
            DC["DashboardController"]
            CR["CRUD • Domínio Rural"]
            AP["AcessibilidadeController"]
        end
        MO["9 Models Eloquent"]
    end

    subgraph D["Banco de Dados • MySQL"]
        direction TB
        T1[("cadastros • fazendas • lotes • animals")]
        T2[("cochos • racaos • estoques • planos • relatorios")]
        T3[("acessibilidade_preferencias")]
    end

    W & G & AC & M --> R --> CT --> MO <--> T1 & T2 & T3

    classDef roxo fill:#5A189A,color:#fff,stroke:#C77DFF
    classDef verde fill:#245C32,color:#fff,stroke:#6AAA2E
    classDef escuro fill:#163A24,color:#fff,stroke:#6AAA2E
    class W,G,AC,M roxo
    class R,DC,CR,AP,MO verde
    class T1,T2,T3 escuro
    style C fill:transparent,stroke:#7B2CBF,color:#C77DFF
    style B fill:transparent,stroke:#6AAA2E,color:#6AAA2E
    style CT fill:transparent,stroke:#245C32,color:#6AAA2E
    style D fill:transparent,stroke:#6AAA2E,color:#6AAA2E
