# Programación Orientada a Objetos

### Brenda Dayana Torres Murcia - 29|07|2024


####  PARTE 1 : Actividad Modificaciones Git :

- [x] Clone el repositorio. Llamaremos en adelante a este repositorio repositorio(1)
- [x] Observe la carpeta oculta .git creada dentro del disco duro
- [x] Cree un archivo de texto en markdown(.md) dentro del repositorio. Este archivo debe tener su nombre en formato nombre\_apellido. Ejm PEDRO\_PEREZ.md
- [x] Agregue el archivo al repositorio local
- [x] Agregue el archivo un nuevo texto que diga "Oh Gloria inmarcesible, oh júbilo inmortal"
- [x] Agregue el archivo al stagging area  `git add ruta del archivo`
- [x] Haga commit al archivo. Recuerde poner un comentario en el archivo.  `git commit -m "su mensaje"`
- [x]  Haga push al repositorio remoto para subir los cambios hechos al repositorio  `git push origin main`

#### PARTE 2 : Actividad Modificaciones Git (Conflictos) :

- [x]  Clone el repositorio remoto en un  \*\*directorio diferente\*\*  al que usó en la parte de familiarización (Repositorio 1)
- [x]  En el segundo repositorio modifique la primera línea del primer archivo.md que creo con el formato  \_nombre\_apellido.md\_. Quite lo que estaba y en su lugar escriba "En un lugar de la mancha de cuyo nombre no quiero acordarme"
- [x] Guarde el archivo
- [x] Agregue el archivo al stagging area:  `git add ruta del archivo`
- [x] Haga commit del archivo en el repositorio local:  `git commit -m "su mensaje"`
- [x] Haga push al repositorio remoto:  `git push origin main`

#### PARTE 3 : Actividad Modificaciones Git (Crear conflicto en el mismo archivo) :

- [x]  Vuelva a la carpeta del primer repositorio que clonó. (Repositorio 1)
- [x]   Abra el archivo que creó con el formato  \_nombre\_apellido.md\_.
- [x]   Agregue al texto que ya tiene lo siguiente: "En surcos de dolores el bien germina ya".( Note que en esta copia del repositorio todavía no se ve reflejado los cambios que hizo en el repositorio(1) en el paso anterior, por lo que todavía tiene una parte del himno nacional)
- [x]   Guarde el archivo
- [x]   Agregue el archivo al stagging area:  `git add ruta del archivo`
- [x]  Haga commit del archivo en el repositorio local:  `git commit -m "su mensaje"`
- [x]   Intente hacer push al repositorio remoto:  `git push origin main`. Debe aparecerle un error similar a este  `! [rejected] master -> master (fetch first)`. Esto significa que Git rechazó el push al repositorio remoto porque el mismo archivo fue modificado desde repositorios diferentes. La última versión del repositorio remoto no coincide con la versión del repositorio local que esta intentado hacer el push

#### PARTE 4 : Actividad Modificaciones Git ( Resolver conflicto cuando un mismo archivo tiene diferente información) :

- [ ] Hacer pull al repositorio
- [ ] Abrir con el editor preferido los archivos que tienen conflicto y editarlos  \_manualmente\_. Las líneas de código que están después de la etiqueta HEAD corresponden a lo que está en el repositorio local y lo que está después de ===== corresponde a lo que está en el repositorio remoto. Quien corrije el error decide cuál de las dos versiones permanece en el archivo. En todo caso recuerde eliminar las etiquetas <<<<<<< HEAD, ======= y >>>>>>>.
- [ ] Haga que en la primera línea quede el siguiente texto:  \_"Oh Gloria inmarcesible, oh júbilo inmortal. En surcos de dolores el bien germina ya. En un lugar de la mancha de cuyo nombre no quiero acordarme"\_
- [ ]  Una vez terminado el ajuste:
- [ ] Agregué el archivo al repositorio remoto  `git add ruta`
- [ ] Haga commit del archivo  `git commit -m "su mensaje"`
- [ ]  Haga push al repositorio remoto  `git push origin main`
- [ ] Sus cambios debieron de subir correctamente al repositorio remoto. Verifique en la página de Github que el archivo subido tenga la versión ajustada.
