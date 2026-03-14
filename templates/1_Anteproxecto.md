# Anteproxecto

- [Anteproxecto](#anteproxecto)
  - [1- Idea do proxecto](#1--idea-do-proxecto)
  - [2- Contextualización](#2--contextualización)
  - [3- Estudio de alternativas e viabilidade](#3--estudio-de-alternativas-e-viabilidade)
    - [3.1- Estudio de alternativas](#31--estudio-de-alternativas)
    - [3.2- Xustificación da alternativa](#32--xustificación-da-alternativa)
  - [4- Requirimentos técnicos](#4--requirimentos-técnicos)
    - [Infraestrutura](#infraestrutura)
    - [Backend](#backend)
    - [Frontend](#frontend)
  - [5- Planificación](#5--planificación)
    - [Diagrama do proxecto](#diagrama-do-proxecto)


## 1- Idea do proxecto

 O noso proxecto consiste no deseño e desenvolvemento dunha **aplicación e páxina web dedicada á adopción de animais de compañía**. O obxectivo principal é crear un espazo en internet onde persoas interesadas poidan coñecer animais que precisan un fogar e iniciar o proceso de adopción dun xeito sinxelo e claro.

 Permitirase ver información de cada animal, facilitando que os usuarios poidan atopar a mascota que mellor se adapte á súa situación. Ademais, incluirá formularios de contacto ou solicitude para que as persoas interesadas poidan comunicarse facilmente cos refuxios responsables dos animais.

 En resumo, este proxecto pretende promover a adopción responsable, reducir o abandono de animais e dar visibilidade ao traballo das protectoras e refuxios, ademais de aproveitar as vantaxes de internet para facilitar todo o proceso de información e contacto.



## 2- Contextualización

 Na actualidade existe un *gran número de animais abandonados ou en refuxios e protectoras á espera de atopar un fogar*. Moitas veces, as persoas interesadas en adoptar non saben *onde buscar información* ou non teñen *acceso fácil aos animais dispoñibles*, e moitas asociacións pequenas non contan con *ferramentas dixitais eficaces para ter visibilidade*.

 O proxecto consiste crear un **punto de encontro entre persoas dispostas a adoptar unha mascota e institucións con animais en busca dun fogar**. Os usuarios poderán ver información sobre os animais dispoñibles, coñecer as súas características e contactar coas entidades responsables para iniciar o proceso de adopción.

 Entre os principais obxectivos do proxecto están facilitar o acceso á información sobre os animais, fomentar a adopción responsable e axudar a reducir o abandono animal. Tamén se pretende ofrecer ás protectoras unha ferramenta sinxela coa que poidan publicar e xestionar os perfís dos animais. Ademais, esta aplicación tamén pode abrir unha oportunidade de negocio, ofrecendo servizos a refuxios, asociacións ou clínicas veterinarias para publicar información ou promocionar determinados servizos relacionados co coidado dos animais. Incluso podería incluír colaboracións con tendas de mascotas, publicidade ou servizos premium para mellorar a visibilidade dos animais ou das entidades participantes.



## 3- Estudio de alternativas e viabilidade

### 3.1- Estudio de alternativas

 Agora, analizaremos varias alternativas tecnolóxicas para o desenvolvemento da nosa plataforma web. Valoraránse diferentes opcións tendo en conta criterios técnicos, económicos, de tempo de desenvolvemento e recursos dispoñibles, co obxectivo de seleccionar a solución máis axeitada para o proxecto.

 Alternativas

 - A1 – Desenvolvemento desde cero con Java Spring Boot + HTML5 + CSS3 + JavaScript.
 - A2 – Desenvolvemento desde cero con Node.js (Express) + HTML5 + CSS3 + JavaScript.
 - A3 – Desenvolvemento cun modelo PHP + MySQL + HTML5 + CSS3 + JavaScript.
 - A4 – Desenvolvemento utilizando Laravel + Vue.js + Tailwind CSS.

 | **Alternativa** |  **Viabilidade técnica** | **Viabilidade económica** | **Temporalidade** | **Valoración Global** |
 | ------ | ------ |  ------ | ------ | ------ |
 | A1 | Baixa-media (4/10): Spring Boot é un framework moi potente e profesional para crear APIs robustas.  **Fortalezas**: Escalabilidade, arquitectura sólida e moi utilizada en empresas.  **Debilidades**: Curva de aprendizaxe elevada e maior complexidade na configuración inicial. |	Media (6/10): Require un servidor con soporte para Java ou un VPS. Isto incrementa o custo do hosting respecto a outras opcións máis simples. |	Baixa (4/10): Debido á curva de aprendizaxe e á configuración do proxecto, o desenvolvemento podería prolongarse entre 4 e 6 meses. |	5/10 |
 | A2 | Media-Alta (7/10): Node.js con Express permite crear APIs REST de forma rápida e flexible.  **Fortalezas**: Uso de JavaScript tanto en frontend como backend e gran cantidade de librarías dispoñibles.  **Debilidades**: Necesítase organizar correctamente a estrutura do proxecto para evitar problemas de mantemento.	| Alta (8/10): Existen plataformas de despregue económico ou gratuíto compatibles con Node.js. O resto das ferramentas utilizadas son de código aberto. |	Media (6/10): O desenvolvemento podería completarse nun período aproximado de 3 a 4 meses. | 7/10 |
 | A3 |	Alta (9/10): PHP e MySQL son tecnoloxías moi coñecidas e sinxelas de implementar.  **Fortalezas**: Facilidade de aprendizaxe, ampla documentación e integración directa con servidores web.  **Debilidades**: Algunhas funcionalidades (seguridade, validacións ou estrutura avanzada) deben implementarse manualmente. |	Moi alta (9/10): Hosting compartido con soporte PHP e base de datos MySQL é moi económico (aprox. 2–5 €/mes). |	Alta (8/10): permite desenvolver e despregar a aplicación nun prazo relativamente curto, aproximadamente 2–3 meses.	| 9/10 |
 | A4 | Media (6/10): Laravel ofrece unha estrutura moderna e organizada, mentres que Vue.js permite crear interfaces dinámicas.  **Fortalezas**: arquitectura limpa, ferramentas integradas para seguridade, rutas e autenticación.  **Debilidades**: require aprender varios frameworks e ferramentas adicionais. | Alta (8/10): software libre, pero pode requirir hosting con características algo máis avanzadas (Composer, SSH, PHP actualizado). | Media-Baixa (5/10): debido á aprendizaxe dos frameworks e configuración do proxecto, o tempo estimado sería de 4–5 meses.	| 6/10 |


### 3.2- Xustificación da alternativa

 Tras analizar as diferentes opcións, decídese elixir a alternativa A3 (PHP + MySQL + HTML5 + CSS3 + JavaScript) para o desenvolvemento da aplicación web de adopción de animais. Esta opción destaca principalmente por:

 - Alta viabilidade técnica, ao utilizar tecnoloxías coñecidas e amplamente documentadas.
 - Baixo custo económico, xa que o hosting necesario é barato e fácil de contratar.
 - Menor tempo de desenvolvemento, permitindo crear unha primeira versión funcional da plataforma nun prazo máis curto.
 - A fricción para o despregue é prácticamente mínimo.

 Para unha aplicación inicial que permita mostrar animais dispoñibles, xestionar información e contactar coas protectoras, esta tecnoloxía resulta suficiente e eficiente.

 A opción A1 é unha tecnoloxía moi potente e utilizada en proxectos empresariais, pero require unha complexidade, curva de aprendizaxe e tempo de configuración e desenvolvemento moi elevados, mais do adecuado para este proxecto.
 A opción A2 é unha opción moderna e flexible para desenvolver a aplicación, especialmente para proxectos escalables. Sen embargo, require estruturar a aplicación dende cero e dedicar máis tempo á organización do backend.
 A opción A3 é unha arquitectura avanzada e profesional, pero implica aprender e configurar varios frameworks, incrementando considerablemente o tempo de desenvolvemento e a complexidade do proxecto para unha primeira versión da aplicación.



## 4- Requirimentos técnicos

 ### Infraestrutura
 Para que a aplicación web poida estar dispoñible en internet será necesario contar cunha infraestrutura básica composta polos seguintes elementos:
 - **Dominio web:** Enderezo que permitirá acceder á páxina (*www.pawtnersfurever.com*).
 - **Hosting ou servidor web:** Servizo onde se aloxará a aplicación, con soporte para **PHP** e **MySQL**.
 - **Servidor de base de datos:** Usarase **MySQL** para almacenar a información da aplicación.
 - **Almacenamento:** Espazo no servidor para gardar os ficheiros da web, como imaxes dos animais e outros recursos.
 - **Memoria e rendemento:** Ao tratarse dunha aplicación relativamente sinxela, un hosting básico con recursos estándar (2–3 GB de almacenamento e soporte para bases de datos) será suficiente para o funcionamento inicial do proxecto.

 ### Backend
 Tecnoloxías utilizadas:
 - **PHP:** Linguaxe de programación principal para desenvolver a lóxica do servidor. Permitirá xestionar usuarios, animais, formularios e conexión coa base de datos.
 - **MySQL:** Sistema de xestión de bases de datos que almacenará toda a información da aplicación (usuarios, animais, refuxios, solicitudes, etc.).
 - **Arquitectura básica tipo MVC:** Para organizar mellor o código separando datos, lóxica e presentación.
 - **PHPMyAdmin:** Ferramenta web para administrar e xestionar a base de datos de forma sinxela.
 - **XAMPP:** Entorno de desenvolvemento local que inclúe servidor Apache, PHP e MySQL para probar a aplicación.

 ### Frontend
 Tecnoloxías utilizadas:
 - **HTML5:** Estrutura e contido das páxinas web.
 - **CSS3:** Deseño e estilos das interfaces para crear a web.
 - **JavaScript:** Interactividade á páxina, como validación de formularios ou actualización de contido.
 - **Imaxes e recursos multimedia:** Para mostrar fotografías dos animais dispoñibles para adopción.



## 5- Planificación

Para organizar o desenvolvemento da aplicación, establecerase unha planificación dividida en fases. Cada fase inclúe unha serie de tarefas específicas que permitirán avanzar de maneira ordenada desde a idea inicial ata unha versión funcional da aplicación.

A duración total estimada do proxecto será de aproximadamente **3 meses**, tendo en conta o tempo necesario para realizar todas as fases do proxecto, que serán as detalladas na seguinte táboa:

 | Fase | Data de inicio | Duración estimada | Descrición das tarefas |
 |-----|---------------|------------------|------------------------|
 | **Estudo preliminar** | 09/03/2026 | 1 semana | Definición da idea do proxecto, análise do problema do abandono animal e identificación das necesidades dos usuarios e das protectoras. Investigación de plataformas similares e primeiras decisións tecnolóxicas. |
 | **Análise** | 16/03/2026 | 1 semana | Definición dos requisitos aplicación. Identificación dos tipos de usuarios (administradores, refuxios e adoptadores). Definición inicial da estrutura da base de datos e fluxos principais da aplicación. |
 | **Deseño** | 23/03/2026 | 3 semanas | Deseño da arquitectura da aplicación (modelo MVC), creación do modelo da base de datos, elaboración de wireframes e bocetos das interfaces da web, definición da navegación entre páxinas e organización do proxecto. |
 | **Codificación e probas** | 13/04/2026 | 2 meses | Desenvolvemento da aplicación utilizando PHP, MySQL, HTML, CSS e JavaScript. Implementación das funcionalidades principais: rexistro de usuarios, xestión de animais, visualización de información e formularios de contacto. Realización de probas para detectar e corrixir erros antes do despregue final. |

 ### Diagrama do proxecto
 | Fase | Marzo | Abril | Maio | Xuño |
 |-----|------|------|------|------|
 | **Estudo preliminar** | ███&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp; |
 | **Análise** | &nbsp;&nbsp;&nbsp;&nbsp;███ |&nbsp;&nbsp;&nbsp;&nbsp; |&nbsp;&nbsp;&nbsp;&nbsp; |&nbsp;&nbsp;&nbsp;&nbsp; |
 | **Deseño** | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;█████████ |&nbsp;&nbsp;&nbsp;&nbsp; |&nbsp;&nbsp;&nbsp;&nbsp; |&nbsp;&nbsp;&nbsp;&nbsp; |
 | **Codificación e probas** |&nbsp;&nbsp;&nbsp;&nbsp; | █████████ | █████████ | █ |

[**<-Anterior**](../README.md)
