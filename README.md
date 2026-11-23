<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:10002B,45:5A189A,100:C77DFF&height=200&section=header&text=Bruna%20Figueira%20Silva&fontSize=40&fontColor=FFFFFF&fontAlignY=36&animation=fadeIn&desc=Desenvolvedora%20em%20forma%C3%A7%C3%A3o%20%E2%80%A2%20Web%20%E2%80%A2%20Mobile&descSize=15&descAlignY=58" alt="Bruna Figueira Silva — Desenvolvedora em formação"/>

<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=18&pause=1400&color=9D4EDD&center=true&vCenter=true&width=560&lines=Desenvolvimento+de+Sistemas;Laravel+%E2%80%A2+Flutter+%E2%80%A2+MySQL;Acessibilidade+digital+segundo+a+WCAG+2.2" alt="Desenvolvimento de Sistemas · Laravel, Flutter e MySQL · Acessibilidade digital"/>

<a href="https://github.com/SEU-USUARIO"><img src="https://img.shields.io/badge/GitHub-240046?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="https://www.linkedin.com/in/SEU-LINKEDIN/"><img src="https://img.shields.io/badge/LinkedIn-5A189A?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:SEU-EMAIL"><img src="https://img.shields.io/badge/E--mail-7B2CBF?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"/></a>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:10002B,50:7B2CBF,100:10002B&height=2&section=header" alt=""/>

## Sobre mim

Sou **Bruna Figueira Silva**, estudante de Desenvolvimento de Sistemas. Trabalho com aplicações completas, do banco de dados à interface, com foco em back-end com Laravel, interfaces acessíveis e aplicativos mobile com Flutter.

Atualmente desenvolvo o **AgriFarm**, meu Trabalho de Conclusão de Curso, e busco uma oportunidade de estágio na área de desenvolvimento.

## Tecnologias

<div align="center">

<img src="https://skillicons.dev/icons?i=html,css,js,php,laravel,mysql,dart,flutter,git,github,vscode&theme=dark&perline=11" alt="HTML, CSS, JavaScript, PHP, Laravel, MySQL, Dart, Flutter, Git, GitHub e VS Code"/>

</div>

| Área | Tecnologias |
|:---|:---|
| Back-end | PHP 8+, Laravel 12, Eloquent, Blade |
| Front-end | HTML5, CSS3, JavaScript ES6+, Chart.js |
| Mobile | Flutter, Dart |
| Banco de dados | MySQL |
| Versionamento | Git, GitHub |

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:10002B,50:7B2CBF,100:10002B&height=2&section=header" alt=""/>

## Projeto em destaque

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:163A24,45:245C32,100:6AAA2E&height=120&section=header&text=AgriFarm&fontSize=42&fontColor=FFFFFF&fontAlignY=40&animation=fadeIn&desc=Gest%C3%A3o%20inteligente%20de%20ra%C3%A7%C3%A3o%20em%20fazendas&descSize=13&descAlignY=70" alt="AgriFarm — Gestão inteligente de ração em fazendas"/>

<p>
  <img src="assets/agrifarm-logo.png" height="150" alt="Logo do AgriFarm"/>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Animals/Cow.png" height="130" alt="Vaca animada"/>
</p>

<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=16&pause=1200&color=6AAA2E&center=true&vCenter=true&width=520&lines=Fazendas%2C+lotes%2C+cochos+e+estoque+em+um+s%C3%B3+lugar;Dashboard+com+dados+reais+de+cada+fazenda;Acessibilidade+digital+WCAG+2.2" alt="Fazendas, lotes, cochos e estoque · Dashboard com dados reais · Acessibilidade WCAG 2.2"/>

![Laravel](https://img.shields.io/badge/Laravel_12-245C32?style=flat-square&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP_8+-245C32?style=flat-square&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-245C32?style=flat-square&logo=mysql&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-245C32?style=flat-square&logo=flutter&logoColor=white)
![WCAG](https://img.shields.io/badge/WCAG_2.2-AA%2FAAA-6AAA2E?style=flat-square)

</div>

O **AgriFarm** é uma plataforma de gestão de ração para fazendas. Ela reúne em um único sistema as informações que costumam ficar espalhadas na rotina da propriedade: lotes, animais, rações, cochos, estoque e planos alimentares. Com os dados centralizados, fica mais fácil identificar desperdícios e planejar a reposição.

<table>
<tr>
<td width="50%" valign="top">

**Dashboard por fazenda**
Cards e gráficos que exibem os dados reais da fazenda selecionada: novos lotes na semana, variação de consumo, custo estimado de ração e situação do estoque. Os cálculos são feitos no back-end.

**Gestão completa**
Cadastro, consulta, edição e exclusão de fazendas, lotes, cochos, rações, estoques, planos alimentares e relatórios, com 9 Models Eloquent relacionados.

</td>
<td width="50%" valign="top">

**Acessibilidade digital**
Componente único, presente em todas as telas:
- temas claro, escuro e alto contraste (AAA);
- ajuste de fonte e zoom;
- leitura em voz alta;
- integração com o VLibras;
- atributos ARIA;
- preferências salvas por usuário no banco de dados.

</td>
</tr>
</table>

### Arquitetura

```mermaid
flowchart LR
    W["Aplicação Web<br/>Blade + JavaScript"] --> L["Laravel 12<br/>Controllers + Eloquent"]
    M["Aplicativo<br/>Flutter"] --> L
    L <--> DB[("MySQL")]

    classDef roxo fill:#5A189A,color:#fff,stroke:#C77DFF
    classDef verde fill:#245C32,color:#fff,stroke:#6AAA2E
    class W,M roxo
    class L,DB verde
```

<div align="center">

<a href="https://github.com/SEU-USUARIO/SEU-REPOSITORIO-AGRIFARM"><img src="https://img.shields.io/badge/Ver_reposit%C3%B3rio-245C32?style=for-the-badge&logo=github&logoColor=white" alt="Ver repositório do AgriFarm"/></a>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:10002B,50:7B2CBF,100:10002B&height=2&section=header" alt=""/>

<div align="center">

## Contato

Aberta a oportunidades de estágio e a projetos colaborativos.

<a href="https://www.linkedin.com/in/SEU-LINKEDIN/"><img src="https://img.shields.io/badge/LinkedIn-5A189A?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:SEU-EMAIL"><img src="https://img.shields.io/badge/E--mail-7B2CBF?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"/></a>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:10002B,45:5A189A,100:C77DFF&height=110&section=footer&animation=twinkling" alt=""/>

</div>
