# Proyecto Final clone de Spotify

### Asignatura: Computación tolerante a fallas

### Profesor: Michel Emanuel Lopez Franco

### Seccion: D06

### Integrantes: 

Jorge Ocampo Villalobos 

### Presentacion del proyecto:

Presentacion proyecto: [https://docs.google.com/presentation/d/12cm2SCBJ3fipTdX3TpVH__Dhiao35k2s/edit?usp=sharing&ouid=104606311353454357168&rtpof=true&sd=true](https://docs.google.com/presentation/d/12cm2SCBJ3fipTdX3TpVH__Dhiao35k2s/edit?usp=sharing&ouid=104606311353454357168&rtpof=true&sd=true)

Presentacion video proyecto: https://drive.google.com/file/d/1rwuvFDW4u24v3LzNlJy8vgxWYoEVV0mq/view?usp=sharing

### Tecnologías usadas:
  Este proyecto está hecho con [Angular CLI](https://github.com/angular/angular-cli) version 13.2.2.
  
  Node.js
  

### Tutorial

GitHub

- 1.Clonar el repositorio

Docker

- 1.Elaborar los Dockerfile 

- 2.Subirlos a DockerHub

- 3.Crear un docker-compose.yaml con los microservicios, donde la imagen es para cada microservicio la de Dockerhub.

- 4.docker build -t ng-docker-k8s:1.0 .
 
Kubernetes

- 1.Activar minikube start

- 2.eval $(minikube docker-env)
  
- 3.kubectl get deployments
  
- 4.kubectl get pods

- 5.kubectl get svc
  
- 6.minikube ip
  
- 7.kubectl get nodes -o wide
  
- 8.minikube dashboard
  
- 9.minikube dashboard --url

### Istio
- 1.Intalación de istioctl 
  
- 2.Kubectl apply -f .\ng-deployment.yaml
  
- 3.kubectl label namespace default istio-injection=enable
  
- 4.Aceder en el navegador a localhost:31000.
  

### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. 

### Code scaffolding

Run `ng generate component component-name` genera un nuevo component. Tambien puedes usar `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build

Run `ng build` para contruir el proyecto. Los artefactos de contrucción se almacenarán en el `dist/` directory.

### Ejecución de pruebas unitarias

Run `ng test` para ejecutar las pruebas unitarias a traves de [Karma](https://karma-runner.github.io).

### Ejecucion de pruebas de extro a extremo

Run `ng e2e` para ejecutar las pruebas de extremo a extremo a traves de una plataforma de su eleccion. para usar este comando, primero debe agreagar un paquete que implemente capacidades de prueba de un extremo a otro.

