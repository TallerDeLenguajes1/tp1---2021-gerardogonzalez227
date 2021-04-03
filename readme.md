#Taller de Lenguajes I
##Gonzalez jose Gerardo
##Trabajo Practico N°1
1.
    b. 
     ¿Por qué es conveniente incluirlo? ¿Cuándo se
debe hacer? ¿Cómo usaría la página https://www.gitignore.io/? ¿Cómo
configuraría el archivo .gitignore?
    El archivo "gitignore", que sirve para decirle a Git qué archivos o directorios completos debe ignorar y no subir al repositorio de código.
    Es conveniente utilizarlos ya que no todos los archivos y carpetas son necesarios de gestionar. Hay código que no necesitas enviar a Git,por no desear compartir o también pueden ser archivos binarios con datos que no necesitas mantener en el control de versiones, como diagramas, instaladores de software, etc.

    Su implementación es muy sencilla, se necesita crear un archivo especificando qué elementos se deben ignorar y, a partir de entonces, realizar el resto del proceso para trabajo con Git de manera habitual.

    Si colocamos la siguiente línea:

    *.exe
    Estaremos evitando que el sistema de control de versiones procese todos los archivos acabados de .exe.