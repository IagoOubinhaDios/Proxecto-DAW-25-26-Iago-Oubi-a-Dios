# Requerimientos do sistema

- [Requerimientos do sistema](#requerimientos-do-sistema)
  - [1- Descrición Xeral](#1--descrición-xeral)
  - [2- Funcionalidades](#2--funcionalidades)
  - [3- Tipos de usuarios](#3--tipos-de-usuarios)
  - [4- Contorno operacional](#4--contorno-operacional)
  - [5- Normativa](#5--normativa)
  - [6- Melloras futuras](#6--melloras-futuras)


## 1- Descrición Xeral

O proxecto consiste no deseño e desenvolvemento dunha aplicación móbil e unha páxina web enfocadas á adopción de animais de compañía. Ppermitirá conectar persoas interesadas en adoptar cunha rede de refuxios e protectoras, facilitando o acceso á información e o proceso de adopción e coidado dos animais.

A aplicación ofrecerá un catálogo de animais dispoñibles, no que cada un contará cunha ficha detallada con información relevante como idade, raza, tamaño, estado de saúde, carácter e situación actual. Isto permitirá aos usuarios atopar a mascota que mellor se adapte ás súas condicións.

O sistema tamén incluirá funcionalidades de contacto mediante formularios e solicitudes de adopción, permitindo unha comunicación directa e sinxela entre os usuarios e as entidades responsables dos animais, garantindo un proceso claro e accesible.

En resumo, preténdese aproveitar as vantaxes das tecnoloxías web e móbiles para dar visibilidade aos animais que precisan fogar, apoiar o labor das protectoras, contribuír á redución do abandono animal e facilitar o coidado dos mesmos.



## 2- Funcionalidades

| Acción | Descrición |
|--------|------------|
| Consulta de animais | **Actor:** Usuario. <br> **Entrada:** filtros de busca (tipo, idade, tamaño, etc.). <br> **Proceso:** consulta na base de datos segundo os filtros aplicados. <br> **Saída:** listado de animais dispoñibles. |
| Visualización de detalles dun animal | **Actor:** Usuario. <br> **Entrada:** selección dun animal. <br> **Proceso:** recuperación da información completa do animal. <br> **Saída:** ficha detallada do animal. |
| Visualización de detalles dun refuxio | **Actor:** Usuario. <br> **Entrada:** selección dun refuxio. <br> **Proceso:** recuperación da información completa do refuxio. <br> **Saída:** ficha detallada do refuxio. |
| Solicitude de adopción | **Actor:** Usuario. <br> **Entrada:** formulario de solicitude (datos persoais, mensaxe, etc.). <br> **Proceso:** envío da solicitude ao refuxio correspondente. <br> **Saída:** rexistro da solicitude e notificación ao refuxio. |
| Contacto co refuxio | **Actor:** Usuario. <br> **Entrada:** mensaxe de contacto. <br> **Proceso:** envío da mensaxe á entidade responsable. <br> **Saída:** comunicación establecida entre usuario e refuxio. |
| Xestión de animais | **Actor:** Refuxio. <br> **Entrada:** datos do animal (nome, idade, descrición, imaxes, etc.). <br> **Proceso:** alta, modificación ou eliminación na base de datos. <br> **Saída:** catálogo actualizado de animais. |
| Xestión de solicitudes | **Actor:** Refuxio. <br> **Entrada:** solicitudes de adopción recibidas. <br> **Proceso:** revisión e resposta ás solicitudes. <br> **Saída:** estado actualizado da solicitude (aceptada, rexeitada, en proceso). |
| Alta de animais en adopción | **Actor:** Refuxio. <br> **Entrada:** Poñer a un animal ao seu coidado en disposición de ser adoptado e viceversa <br> (animais que contraen lesións ou enfermidades que requiren coidados, por exemplo) . <br> **Proceso:** modificación na base de datos. <br> **Saída:** Actualización dos datos do animal seleccionado. |

## 3- Tipos de usuarios

- **Usuario anónimo**  
  Poderá acceder á páxina web sen rexistrarse. Terá acceso á visualización xeral dos animais dispoñibles e poderá consultar información básica, pero non poderá realizar solicitudes nin contactar cos refuxios.

- **Usuario rexistrado**  
  Poderá crear unha conta e iniciar sesión na plataforma. Terá acceso a funcionalidades como gardar preferencias, enviar solicitudes de adopción e contactar cos refuxios. Ademais, poderá xestionar os seus datos persoais.

- **Refuxio / Protectora con plan básico**  
  Este tipo de usuario representará ás entidades responsables dos animais. Poderá dar de alta novos animais, modificar a súa información, eliminar rexistros e xestionar as solicitudes de adopción recibidas.

- **Refuxio / Protectora con plan premium**  
  Este tipo de usuario representará ás entidades responsables dos animais que paguen o plan premium, co cal contarán con funcionalidades extra, como peticións aos administradores de anuncios deles na aplicación, gráficos que mostren o ratio de adopcións nun tempo determinado, posibilidade de poñerse en contacto con outros refuxios para intercambiar animais en coidado en caso de que, por exemplo, o refuxio poida ter a súa capacidade de animais chea, poida ofrecer a dito animal mellores coidados, etc.

- **Administrador**  
  Terá control total sobre o sistema. Poderá xestionar usuarios, refuxios e contidos da plataforma, así como supervisar o correcto funcionamento da aplicación e resolver posibles incidencias.

- **Usuario bloqueado**  
  Usuario rexistrado que, por incumprimento das normas, ten restrinxido o acceso á plataforma ou a determinadas funcionalidades.



## 4- Contorno operacional

* **Dispositivo con acceso a internet**

  * Ordenador, tableta ou teléfono móbil.
  * A aplicación estará adaptada a distintos dispositivos (deseño responsive).

* **Navegador web actualizado**

  * Exemplos: Google Chrome, Mozilla Firefox, Safari ou Microsoft Edge.
  * Permite o correcto funcionamento da páxina e das súas funcionalidades.

* **Conexión a internet estable**

  * Necesaria para a carga de información de animais, envio de formularios, e deamis funcionalidades que requiran conexión a Internet.

* **Conta de correo electrónico (opcional pero recomendable)**

  * Para recibir respostas, confirmacións de solicitudes e comunicación cos refuxios.



## 5- Normativa

O desenvolvemento da aplicación web debe cumprir coa normativa legal vixente nos territorios onde vai operar, especialmente en materia de protección de datos e servizos dixitais. Ao tratarse dunha plataforma que recolle información persoal dos usuarios, é imprescindible garantir o correcto tratamento destes datos. Para isto, a aplicación será desenvolvida respectando as seguintes obrigas legais:

* **Lei Orgánica 3/2018, de Protección de Datos Persoais e garantía dos dereitos dixitais (LOPDGDD)**

  * Esta lei regula o tratamento de datos persoais en España.
  * A aplicación deberá garantir que os datos dos usuarios sexan recollidos de forma lícita, segura e transparente.
  * Os usuarios deberán ser informados sobre o uso dos seus datos e terán dereito a acceder, modificar ou eliminar a súa información persoal.

* **Regulamento Xeral de Protección de Datos (GDPR)**

  * De aplicación en toda a Unión Europea.
  * No caso de que a aplicación poida ser utilizada por usuarios doutros países europeos, deberá cumprir tamén con este regulamento.
  * Esixe medidas adicionais como o consentimento explícito do usuario e a protección reforzada da privacidade.

* **Lei de Servizos da Sociedade da Información e Comercio Electrónico (LSSI-CE)**

  * Regula os servizos prestados a través de internet en España.
  * Obriga a identificar claramente o responsable da páxina web e a ofrecer información de contacto.
  * Tamén regula o uso de cookies e as comunicacións electrónicas.

* **Cumprimento legal na aplicación web**

  * O proxecto incluirá obrigatoriamente os seguintes apartados visibles na web:

    * **Aviso legal**: onde se identifique a persoa ou entidade responsable da web.
    * **Política de privacidade**: explicando como se recollen, usan e protexen os datos persoais.
    * **Política de cookies**: informando sobre o uso de cookies e solicitando o consentimento do usuario.

* **Compromiso de cumprimento**

  * O proxecto comprométese a cumprir coa normativa vixente en materia de protección de datos e servizos dixitais.
  * Adoptaranse medidas técnicas e organizativas adecuadas para garantir a seguridade da información e a privacidade dos usuarios.



## 6- Melloras futuras

O proxecto da aplicación web de adopción de animais poderá ampliarse no futuro incorporando novas funcionalidades que melloren a experiencia dos usuarios e incrementen o seu impacto social. A continuación, descríbense algunhas posibles liñas de evolución:

* **Sistema de valoración e comentarios**

  * Permitir aos usuarios valorar refuxios ou experiencias de adopción.
  * Aumentar a confianza e transparencia na plataforma.

* **Chat en tempo real**

  * Comunicación directa entre usuarios e refuxios.
  * Axilizar o proceso de adopción.

* **Soporte multilingüe**

  * Tradución da aplicación a varios idiomas.
  * Ampliar o alcance a máis usuarios.

* **Integración con redes sociais**

  * Compartir animais facilmente.
  * Dar maior visibilidade ás adopcións.

* **Expansión internacional da plataforma**

  * Posibilidade de utilizar a aplicación en diferentes países, non limitándose só a España.
  * Adaptación ás normativas legais de cada país.
  * Colaboración con refuxios e protectoras internacionais.

[**<-Anterior**](../README.md)
