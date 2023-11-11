# App-WhatsDAM.-Sprint-1
## App WhatsDAM. Sprint 1 Alejandro Rubio

L'aplicació es compon de dues pantalles principals:

### 1. Pantalla inicial d'introducció de dades (MainActivity)

![imagen](https://github.com/alejandrorubio29/App-WhatsDAM.-Sprint-1/assets/145864071/1bd8410c-856c-4474-b01f-98569b551e28)

En esta pantalla es recull la funcionalitat A, habilitant el registre de nom d'usuari i servidor, i la funcionalitat B, d'execució de la connexió en prémer en el botó de connexió si els camps compleixen els criteris requerits. La pantalla es compon per un layout com a objectes no interactuables, i dos editbox i un botó com a objectes interactuables.

L' editbox del nom permetrà la introducció de qualsevol cadena de caràcters no buida

![imagen](https://github.com/alejandrorubio29/App-WhatsDAM.-Sprint-1/assets/145864071/0a598c4e-d408-450d-91b7-ae90c423ad35)
![imagen](https://github.com/alejandrorubio29/App-WhatsDAM.-Sprint-1/assets/145864071/fd90aa6c-5b8b-419e-9d2f-c13a6dee372a)

L' editbox d'adreça del servidor implementa una comprovació d'adreça IP vàlida. S'empra Patterns per incompatibilitat de la API empleada.

La implementació d'elements en interfícies s'ha realitzat mitjançant View Binding

<img width="525" alt="Captura de pantalla 2023-11-11 083246" src="https://github.com/al<img width="476" alt="Captura de pantalla 2023-11-11 083240" src="https://github.com/alejandrorubio29/App-WhatsDAM.-Sprint-1/assets/145864071/0ae6cfa9-c464-4591-b42c-c3d5c1f13ae5">
ejandrorubio29/App-WhatsDAM.-Sprint-1/assets/145864071/8ec1f366-4181-47e9-a4e1-efe2f13a43c6">

La funcionalitat d'iniciar l'activitat MessagesWindows s'implementa mitjançant un intent associat a un botó. És important passar les variables necessàries a aquesta activitat (i recollir-les des de la nova activitat, com es veurà més a baix)

![imagen](https://github.com/alejandrorubio29/App-WhatsDAM.-Sprint-1/assets/145864071/9ff9889c-072e-423b-aa3a-70fbe9b3e3ba)

Si l'usuari no introdueix una IP vàlida i una cadena de text no nul·la com a nom d'usuari, el botó no donarà pas a la següent pantalla. No s'ha implementat cap missatge emergent. 

### 2.. Pantalla de missatges (MessagesWindows)

La segona pantalla únicament mostra un rectangle de connexió reeixida i presenta en la part inferior un editbox amb un botó d'enviament.

![imagen](https://github.com/alejandrorubio29/App-WhatsDAM.-Sprint-1/assets/145864071/6c639ee7-b422-4a6d-ba4f-2d50ace246d1)

Tal com es descriu en la funcionalitat C, han de recollir-se les variables enviades des de la pantalla anterior (Les credencials d'usuari) per a mostrar-les en el quadre superior.
EL Botó d'enviament, de moment en esta versió de l'aplicació, unicamente esborra el missatge creat anteriorment, complint la funcionalitat D. 

![imagen](https://github.com/alejandrorubio29/App-WhatsDAM.-Sprint-1/assets/145864071/06efc6c5-3251-41b9-b959-489ddbfc88e0)














