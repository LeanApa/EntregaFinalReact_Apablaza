# Bienvenido a mi app de e-commerce con React

Este proyecto fue realizado con create-react-app para el curso de programación de React de Coder House.

### Consideraciones

Por un lado, decidí utilizar la librería de sweet alert para ayudar a visualizar cuando no se confirma correctamente el mail.

Además, para evitar compras que dejen el stock en negativo, agregué la logica para que no se muestren los botones de suma, resta y compra de artículos en itemDetail. De esta manera, solo aparecerá "Sin stock".

Por último, para probar esta funcionalidad, dejé el jean wrangel montana con un stock de 2.

Ejecutar para correr el contenedor de jenkins en windows
docker run -d --name jenkins_container -p 8080:8080 -p 50000:50000 -v jenkins_home:/var/jenkins_home -v /run/docker.sock:/var/run/docker.sock --privileged jenkins/jenkins


