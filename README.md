# Ing-devops
Repositorio de ingenieria devops

El encargo debe incluir los siguientes apartados:
1. Crean un repositorio Git en GitHub con las siguientes ramas: main, develop, feature/<nombre> y hotfix/<nombre>. (IE5)
2. Implementan GitFlow o trunk-based development, justificando su elección en el README del repositorio. (IE1)
3. Simulan un desarrollo colaborativo integrando al menos 2 cambios tipo feature y 1 tipo hotfix mediante pull requests. (IE2)
4. Documentan en un archivo README.md o wiki las convenciones de commits, flujos de merge, naming de ramas y estrategias de
revisión. (IE5)
5. Configuran al menos una acción básica de GitHub Actions que se ejecute con cada push a develop y pull request a main. (IE3/IE4)


Primer cambio del readme.md por Jean portiño
2. justificacion del uso de gitflow porque organiza el trabajo mediante distintas ramas siendo estas (main, develop, feature, release, hotfix), que nos permite desarrollar nuevas funciones facilitando las correcciones.

4. segundo cambio del readme.md por jean portiño
Naming de Ramas:
main: Rama de producción estable.
develop: Rama base para integración de desarrollo.
feature/ev-1: Ramas para nuevas funcionalidades.
hotfix/error-documentacion: Ramas para correcciones urgentes en producción.


Estructura del Proyecto:
src: Contiene la lógica y código fuente del microservicio.
github/workflows: Contiene los archivos de automatización.