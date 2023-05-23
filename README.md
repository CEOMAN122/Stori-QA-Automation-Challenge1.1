# Stori-QA-Automation-Challenge1.1
conjunto de pruebas automatizadas utilizando el framework Selenide para realizar pruebas de automatización en la página web "https://rahulshettyacademy.com/AutomationPractice/". El código incluye métodos de prueba para realizar acciones de funcionalidad de la pagina
PruebaManuel
Este repositorio contiene un proyecto de automatización de pruebas utilizando Selenide y Allure.


Requisitos previos
JDK 20 o superior
Maven 3.8.1 o superior
ChromeDriver compatible con la versión de Chrome instalada en el sistema
Configuración del entorno
Clonar el repositorio:
bash
Copy code
git clone https://github.com/tu-usuario/PruebaManuel.git
Navegar al directorio del proyecto:
bash
Copy code
cd PruebaManuel
Compilar y ejecutar las pruebas:
bash
Copy code
mvn clean test
Estructura del proyecto
El proyecto está estructurado de la siguiente manera:

src/main/java/com/stori/pruebamanuel: Contiene la clase MainPage que representa la página principal del sitio web y define los elementos y acciones que se pueden realizar en ella.
src/test/java/com/stori/pruebamanuel: Contiene la clase MainPageTest que define los casos de prueba utilizando el framework JUnit 5 y Allure para la generación de reportes.
pom.xml: Archivo de configuración de Maven que contiene las dependencias y plugins necesarios para la ejecución de las pruebas.
Generación de reportes
Después de ejecutar las pruebas, se generará un informe de reporte utilizando Allure. Para visualizar el informe, ejecuta el siguiente comando:

Copy code
mvn allure:serve
Esto abrirá el informe en tu navegador web predeterminado.

Contribuciones
Las contribuciones son bienvenidas. Si encuentras algún problema o tienes alguna sugerencia de mejora, por favor abre un issue en este repositorio.

Licencia
Este proyecto se distribuye bajo la Licencia MIT. Consulta el archivo LICENSE para obtener más información

Autor: Manuel Fernando Guiza Cubides    
Fecha: -    22-05-2023
