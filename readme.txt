README - Ejecución de pruebas automatizadas de servicios REST

Este proyecto contiene pruebas automatizadas para servicios REST de la PetStore. Para ejecutar las pruebas, se debe seguir los siguientes pasos:
Como prerequisito se necesita: tener Node JS instalado, en caso de no tenerlo, puede revisar el siguiente enlace: https://nodejs.org/en/download y descargar la ultima version.

1. En la consola, correr lo siguiente:
cd <nombre_de_la_carpeta>
npm install

2. Luego correr lo siguiente en consola:
npx cypress install

3. Correr Las pruebas
npx cypress run --spec "cypress/e2e/*"
