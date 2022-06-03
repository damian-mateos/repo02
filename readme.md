# Resumen de comandos de git

**NOTA**: este documento se basa en el enlace [Bloque de markdown](https://medium.com/@davidbernalgonzalez/3-markdown-c82d88c1d222 "Bloque de markdown, David Bernal González")  
___
| comando | uso | necesidad |
|:--- |:---- |:----:|
|cd *Desktop/*| ruta a la que quieres ir | solo si no usas git bash here |
|pwd| indica en qué directorio estás | información |
|ls| lista carpetas del directorio en que estás | información |
|cd ..| volver a un directorio anterior | situacional |
|mkdir *repo01*| crear carpeta | creación carpeta |
|git config --global user.name *user-name*| indica el usuario de git | si no te ha identificado en ese ordenador |
|git config user.name| indica si te has identificado | información |
|git init| inicia un repositorio git (.git) | creación repo git |
|git status| muestra el estado del repositorio | información |
|git add .| añade todos los archivos para commitear | previo al commmit |
|git rm --cached *archivo*| deshace el add | si te arrepientes tras add |
|touch *readme.md*| crear un archivo | creación archivo |
|git branch -M *main*| rama main en el repo | crear rama main |
|git push -u origin main| hacer un push de lo que está commiteado | primer push del proyecto |
|git push| hacer un push del repo local al remoto | resto de pushes |
|git remote -v| ver a que repo remoto apunta el push | información |
|git remote add origin...| comando que sale en gihub para apuntar al repo remoto  | apuntar al remoto deseado |
|git pull| se trae los cambios del repositorio remoto al local | remoto a local |
|git clone *https...*| clonar un repo remoto con su dirección | clonar un repo remoto |