# Requerimientos do sistema

- [Requerimientos do sistema](#requerimientos-do-sistema)
  - [1- Descrición Xeral](#1--descrición-xeral)
  - [2- Funcionalidades](#2--funcionalidades)
  - [3- Tipos de usuarios](#3--tipos-de-usuarios)
  - [4- Contorno operacional](#4--contorno-operacional)
  - [5- Normativa](#5--normativa)
  - [6- Melloras futuras](#6--melloras-futuras)

> *EXPLICACION*: Este documento describe os requirimentos para "nome do proxecto" especificando que funcionalidade ofrecerá e de que xeito.

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

> *EXPLICACION* Neste apartado deben describirse os recursos necesarios, dende o punto de vista do usuario, para poder operar coa aplicación web. Habitualmente consiste nun navegador web actualizado e unha conexión a internet.
Se é necesario algún hardware ou software adicional, deberá indicarse.

## 5- Normativa

> *EXPLICACION* Investigarase que normativa vixente afecta ao desenvolvemento do proxecto e de que maneira. O proxecto debe adaptarse ás esixencias legais dos territorios onde vai operar.
> 
> Pola natureza dos sistema de información, unha lei que se vai a ter que mencionar de forma obrigatoria é la [Ley Orgánica 3/2018, de 5 de diciembre, de Protección de Datos Personales y garantía de los derechos digitales (LOPDPGDD)](https://www.boe.es/buscar/act.php?id=BOE-A-2018-16673). O ámbito da LOPDPGDD é nacional. Se a aplicación está pensada para operar a nivel europeo, tamén se debe facer referencia á [General Data Protection Regulation (GDPR)](https://eur-lex.europa.eu/eli/reg/2016/679/oj). Na documentación debe afirmarse que o proxecto cumpre coa normativa vixente.
>
> Para cumplir a LOPDPGDD e/ou GDPR debe ter un apartado na web onde se indique quen é a persoa responsable do tratamento dos datos e para que fins se van utilizar. Habitualmente esta información estructúrase nos seguintes apartados:
>
> - Aviso legal.
> - Política de privacidade.
> - Política de cookies.
>
> É acosenllable ver [exemplos de webs](https://www.spotify.com/es/legal/privacy-policy/) que conteñan textos legais referenciando a LOPDPGDD ou GDPR.

## 6- Melloras futuras

> *EXPLICACION* É posible que o noso proxecto se centre en resolver un problema concreto que se poderá ampliar no futuro con novas funcionalidades, novas interfaces, etc.

[**<-Anterior**](../../README.md)
