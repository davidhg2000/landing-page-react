# Landing page en React
Es una simple landing page hecha por React
![pantallazo.](./capturas/image.jpg)
## Guía de instalación
1. Hacer un fork y/o clonar la app [repo](https://github.com/davidhg2000/landing-page-react.git)
![fork](./capturas/fork.jpg)
Si hacemos un fork no es necesario añadir un remoto  (porque es nuestro repositorio) y 
no hacemos ``git init`` a no ser que queramos reiniciar el proyecto 

2. Instalamos dependencias de node 


````shell
npm install
````
3. Arrancamos el servidor del pruebas 
````shell
npm run dev
````
y saldrá por consola
````
> landing-page-distribuida@0.0.0 dev
> vite


  VITE v6.3.3  ready in 851 ms

  ➜  Local:   http://localhost:5173/
  ➜  Network: use --host to expose
````
4. Hacemos las modificaciones pertinentes
5. Hacemos un commit 
```` shell
git add --all 
git commit -m "nombre del commit"
````
6. Subimos los cambios al repositorio
````shell
git push origin master
````shell
git push origin master
````
## Despliegue en Netlify
No es necesario hacer el ``npm run build`` porque lo hacen ellos
aunque podemos hacerlo si queremos verlo en local o subirlo a cualquier sitio
- En netlify hacemos un deploy de un repo de github
![deploy netlify](./capturas/netlify.jpg)
-le asignamos una url disponible y le damos al deploy
![deploy netlify](./capturas/deploy.jpg)

y observamos el despliegue
![vemos app](./capturas/desplegada.jpg)