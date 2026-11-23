<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:10002B,45:5A189A,100:C77DFF&height=220&section=header&text=Bruna%20Figueira%20Silva&fontSize=42&fontColor=FFFFFF&fontAlignY=36&animation=fadeIn&desc=Desenvolvimento%20de%20Sistemas%20%E2%80%A2%20Web%20%E2%80%A2%20Mobile%20%E2%80%A2%20IoT&descSize=15&descAlignY=58" alt="Banner roxo com o nome Bruna Figueira Silva"/>

<a href="https://github.com/SEU-USUARIO">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=C77DFF&center=true&vCenter=true&width=620&lines=Desenvolvedora+em+forma%C3%A7%C3%A3o;Laravel+%2B+Flutter+%2B+MySQL;Acessibilidade+digital+(WCAG+2.2);Agricultura+4.0+e+IoT+com+ESP32;Jogos+3D+multiplayer+no+navegador" alt="Desenvolvedora em formação · Laravel, Flutter e MySQL · Acessibilidade digital · Agricultura 4.0 e IoT · Jogos 3D multiplayer"/>
</a>

<br/>

<a href="https://github.com/SEU-USUARIO"><img src="https://img.shields.io/badge/GitHub-240046?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="https://www.linkedin.com/in/SEU-LINKEDIN/"><img src="https://img.shields.io/badge/LinkedIn-5A189A?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="SEU-PORTFOLIO"><img src="https://img.shields.io/badge/Portf%C3%B3lio-7B2CBF?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfólio"/></a>
<a href="mailto:SEU-EMAIL"><img src="https://img.shields.io/badge/E--mail-C77DFF?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"/></a>

<img src="https://komarev.com/ghpvc/?username=SEU-USUARIO&style=flat-square&color=7B2CBF&label=visitas" alt="Contador de visitas ao perfil"/>

</div>

---

## 👩‍💻 Sobre mim

Sou **Bruna Figueira Silva**, estudante de Desenvolvimento de Sistemas. Gosto de pegar um problema concreto e levar até uma aplicação que funciona de ponta a ponta: banco de dados, back-end, interface web, app mobile e, quando faz sentido, hardware.

Meu projeto principal é o **AgriFarm**, uma plataforma de gestão de ração para fazendas, onde trabalhei desde a modelagem do banco até um sistema de acessibilidade completo seguindo a WCAG 2.2.

```js
const bruna = {
  foco:        ["Desenvolvimento web", "Mobile", "APIs", "Banco de dados"],
  estudando:   ["Arquitetura com Laravel", "Flutter", "Three.js", "Socket.IO"],
  interesses:  ["Acessibilidade digital", "IoT", "Agricultura 4.0", "Jogos web"],
  buscando:    "Estágio ou primeira oportunidade na área de desenvolvimento",
};
```

## 🧰 Tecnologias

<div align="center">

<img src="https://skillicons.dev/icons?i=html,css,js,php,laravel,mysql,dart,flutter,nodejs,threejs,arduino,git,github,vscode&theme=dark&perline=7" alt="Ícones: HTML, CSS, JavaScript, PHP, Laravel, MySQL, Dart, Flutter, Node.js, Three.js, Arduino, Git, GitHub, VS Code"/>

</div>

| Área | Tecnologias | Onde usei |
|:---|:---|:---|
| **Back-end** | PHP 8+, Laravel 12, Eloquent, Blade | AgriFarm |
| **Front-end** | HTML5, CSS3, JavaScript ES6+, Chart.js | AgriFarm, sites de clientes |
| **Mobile** | Flutter, Dart | AgriFarm |
| **Banco de dados** | MySQL | AgriFarm |
| **Tempo real e 3D** | Node.js, Socket.IO, Three.js, cannon-es | City Racing Online |
| **IoT** | ESP32, sensores | AgriFarm |
| **Ferramentas** | Git, GitHub, VS Code | Todos os projetos |

---

## 🌱 Projeto em destaque — AgriFarm

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:163A24,45:245C32,100:6AAA2E&height=125&section=header&text=AgriFarm&fontSize=42&fontColor=FFFFFF&fontAlignY=38&desc=Gest%C3%A3o%20inteligente%20de%20ra%C3%A7%C3%A3o%20em%20fazendas&descSize=13&descAlignY=68" alt="Banner verde do AgriFarm"/>

<img src="assets/agrifarm-logo.png" width="380" alt="Logo do AgriFarm"/>

![Laravel](https://img.shields.io/badge/Laravel_12-245C32?style=flat-square&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP_8+-245C32?style=flat-square&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-245C32?style=flat-square&logo=mysql&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-245C32?style=flat-square&logo=flutter&logoColor=white)
![WCAG](https://img.shields.io/badge/WCAG_2.2-AA%2FAAA-6AAA2E?style=flat-square)
![Status](https://img.shields.io/badge/status-TCC_em_desenvolvimento-163A24?style=flat-square)

</div>

**O problema.** Na rotina da fazenda, as informações sobre alimentação animal ficam espalhadas: quantos animais há em cada lote, qual ração eles recebem, quanto cabe em cada cocho e quanto resta em estoque. Sem esses dados juntos, é difícil perceber desperdício ou planejar a reposição a tempo.

**A solução.** O AgriFarm centraliza fazendas, lotes, animais, rações, cochos, estoque, planos alimentares e relatórios em um único sistema, com dashboard por fazenda, app mobile e espaço para integração com sensores.

### O que já está implementado

<table>
<tr>
<td width="50%" valign="top">

**📊 Dashboard por fazenda**
Ao selecionar uma propriedade, os cards e gráficos (Chart.js) mostram os dados reais dela, vindos do banco: lotes novos na semana, variação de consumo em relação ao dia anterior, custo estimado da ração e status do estoque. Todos os cálculos ficam no back-end.

**🗂️ Gestão completa (CRUD)**
Fazendas, lotes, cochos, rações, estoques, planos alimentares e relatórios, com 9 Models Eloquent relacionados entre si e rotas nomeadas.

</td>
<td width="50%" valign="top">

**♿ Acessibilidade digital (WCAG 2.2)**
Um único componente reutilizado em todas as telas, com:
- temas claro, escuro e alto contraste (nível AAA);
- ajuste de tamanho de fonte e zoom;
- leitura em voz alta com a Web Speech API;
- integração com o VLibras (Libras);
- ARIA completo (`role="dialog"`, `aria-expanded`, `aria-live`);
- preferências salvas no MySQL por usuário, sincronizadas entre dispositivos.

</td>
</tr>
</table>

### Arquitetura

```mermaid
flowchart LR
    subgraph Clientes
        W["🖥️ Web<br/>Blade + JS"]
        M["📱 App<br/>Flutter"]
    end
    subgraph Servidor
        L["⚙️ Laravel 12<br/>Controllers + Eloquent"]
        A["♿ Módulo de<br/>acessibilidade"]
    end
    DB[("🗄️ MySQL")]
    S["📡 ESP32<br/>sensores"]

    W --> L
    M --> L
    L <--> DB
    A <--> DB
    W -.-> A
    S -. "planejado" .-> L

    classDef roxo fill:#5A189A,color:#fff,stroke:#C77DFF
    classDef verde fill:#245C32,color:#fff,stroke:#6AAA2E
    classDef escuro fill:#163A24,color:#fff,stroke:#6AAA2E
    class W,M roxo
    class L,A verde
    class DB,S escuro
```

<details>
<summary><b>📁 Modelo de dados (clique para ver)</b></summary>

<br/>

| Tabela | Responsabilidade |
|:---|:---|
| `cadastros` | Usuários e autenticação |
| `fazendas` | Propriedades de cada usuário |
| `lotes` | Grupos de animais por fazenda |
| `animals` | Animais vinculados aos lotes |
| `cochos` | Capacidade e nível de cada cocho |
| `racaos` | Tipos de ração |
| `estoques` | Quantidades e movimentações |
| `planos` | Planos alimentares e consumo |
| `relatorios` | Relatórios gerados |
| `acessibilidade_preferencias` | Preferências de acessibilidade por usuário |

</details>

<div align="center">

<a href="https://github.com/SEU-USUARIO/SEU-REPOSITORIO-AGRIFARM"><img src="https://img.shields.io/badge/Ver_reposit%C3%B3rio-245C32?style=for-the-badge&logo=github&logoColor=white" alt="Repositório do AgriFarm"/></a>

</div>

---

## 🚀 Outros projetos

<table>
<tr>
<td width="100%" valign="top" colspan="2">

### 🏎️ City Racing Online &nbsp; ![Em desenvolvimento](https://img.shields.io/badge/em_desenvolvimento-5A189A?style=flat-square)

Jogo de corrida 3D em terceira pessoa, multiplayer online, rodando no navegador, com cidade aberta e modos corrida livre, corrida de rua, contra o relógio, drift e corrida profissional. O foco é jogabilidade real: física de veículos, colisões e partidas sincronizadas entre jogadores.

**Stack:** Three.js · cannon-es · Node.js · Socket.IO · front-end e back-end separados

[Ver repositório](https://github.com/SEU-USUARIO/SEU-REPOSITORIO-CITY-RACING)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 💅 Site Natalia Berretta

Site para profissional de beleza, pensado para quem acessa pelo celular: apresentação dos serviços e caminho curto até o agendamento.

**Stack:** HTML · CSS · JavaScript

[Ver repositório](https://github.com/SEU-USUARIO/SEU-REPOSITORIO)

</td>
<td width="50%" valign="top">

### ✨ Studio Monica Monique

Site para estúdio de estética, com apresentação dos procedimentos, organização de horários e foco no agendamento online.

**Stack:** HTML · CSS · JavaScript

[Ver repositório](https://github.com/SEU-USUARIO/SEU-REPOSITORIO)

</td>
</tr>
</table>

---

## 📈 Estatísticas

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=SEU-USUARIO&show_icons=true&theme=midnight-purple&hide_border=true&rank_icon=github&count_private=true" alt="Estatísticas gerais do GitHub"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SEU-USUARIO&layout=compact&theme=midnight-purple&hide_border=true&langs_count=8" alt="Linguagens mais usadas"/>

<img width="80%" src="https://streak-stats.demolab.com?user=SEU-USUARIO&theme=midnight-purple&hide_border=true&locale=pt_BR" alt="Sequência de contribuições"/>

</div>

---

## 🎯 Próximos passos

- [x] Sistema de acessibilidade unificado no AgriFarm
- [x] Dashboard integrado ao banco de dados
- [ ] Integração do ESP32 com o nível dos cochos
- [ ] Publicar a API documentada para o app Flutter
- [ ] Multiplayer estável no City Racing Online
- [ ] Testes automatizados (PHPUnit)

---

<div align="center">

### 📬 Vamos conversar?

Estou aberta a oportunidades de estágio, projetos colaborativos e trocas com quem também está aprendendo.

<a href="https://www.linkedin.com/in/SEU-LINKEDIN/"><img src="https://img.shields.io/badge/LinkedIn-5A189A?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:SEU-EMAIL"><img src="https://img.shields.io/badge/E--mail-7B2CBF?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"/></a>

<br/>

*Construindo, aprendendo e evoluindo, um projeto de cada vez.*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:10002B,45:5A189A,100:C77DFF&height=110&section=footer" alt=""/>

</div>

<!--
CHECKLIST ANTES DE PUBLICAR
1. Substitua SEU-USUARIO, SEU-LINKEDIN, SEU-PORTFOLIO e SEU-EMAIL (use Ctrl+H no VS Code).
2. Coloque a logo em assets/agrifarm-logo.png (o repositório do perfil precisa ter o mesmo nome do seu usuário).
3. Atualize os links dos repositórios de cada projeto.
4. Ajuste o checklist de "Próximos passos" conforme o andamento real.
5. Se os cards de estatísticas ficarem fora do ar, faça deploy próprio do github-readme-stats na Vercel
   (instruções no repositório anuraghazra/github-readme-stats) e troque a URL base.
-->
