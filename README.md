# Curso Introductorio de Jenkins – Notas y Recursos 🧠🛠️

![Licencia MIT](https://img.shields.io/badge/Licencia-MIT-blue.svg)
![Docker](https://img.shields.io/badge/Docker-gray.svg?logo=docker)
![Docker Compose](https://img.shields.io/badge/Docker--Compose-gray.svg?logo=docker)
![Jenkins](https://img.shields.io/badge/Jenkins-LTS-blue?logo=jenkins&logoColor=white)
![Python 3.13](https://img.shields.io/badge/Python-3.13-green?logo=python)
![uv](https://img.shields.io/badge/uv-gray.svg?logo=uv)
![pre-commit](https://img.shields.io/badge/pre--commit-enabled-red.svg)


Este repositorio contiene mis apuntes, recursos adicionales y ejemplos prácticos relacionados con el curso introductorio de Jenkins ofrecido por [The Linux Foundation](https://training.linuxfoundation.org/). Aquí encontrarás material complementario para reforzar lo aprendido, incluyendo teoría, lecturas recomendadas e instrucciones paso a paso para la instalación de Jenkins.


## 📚 Lecturas recomendadas
A continuación, iré recopilando artículos, documentación oficial y recursos que ayudan a entender mejor la teoría detrás de Jenkins y su ecosistema:

- [Documentación oficial de Jenkins](https://www.jenkins.io/doc/)
- [Understanding CI/CD](https://www.redhat.com/en/topics/devops/what-is-ci-cd)
- [Introducción a Jenkins: ¿qué es, para qué sirve y cómo funciona?](https://sentrio.io/blog/que-es-jenkins/)
- [Jenkins: Basics to Advanced for DevOps Engineer](https://medium.com/cloud-native-daily/jenkins-tutorial-basics-to-advanced-for-devops-engineer-27265e5ae67d)
- *(Agregar más enlaces aquí a medida que avances en el curso)*


## ⚙️ Instalación de Jenkins
Existen varias formas de instalar Jenkins: directamente en una máquina local, utilizando un servidor en la nube, o bien con contenedores. La opción más práctica y flexible, sobre todo para entornos de pruebas o aprendizaje, es usando **Docker Compose**.

Si querés ver el paso a paso para instalar Jenkins de esta forma, podés consultar el archivo [jenkins-docker-installation.md](./docs/jenkins-docker-installation.md), donde detallo el proceso completo.


## 📦 Gestión de dependencias con uv
Este proyecto utiliza [`uv`](https://github.com/astral-sh/uv), una herramienta ultrarrápida para gestionar entornos virtuales y dependencias en proyectos Python.

Con `uv`, es posible instalar, actualizar y compartir paquetes de manera eficiente, sin necesidad de `pip` ni `virtualenv`.

Para ver cómo configuramos el entorno del proyecto, agregamos y eliminamos dependencias, y ejecutamos scripts de forma reproducible, podés consultar el archivo [working-with-uv.md](./docs/working-with-uv.md).


## 🤝 Contribuciones
¡Las contribuciones son bienvenidas! Si querés mejorar el contenido o agregar nuevos recursos, sentite libre de abrir un issue o enviar un pull request.


## 📝 Licencia
Este proyecto está licenciado bajo la [Licencia MIT](LICENSE). Podés usar, modificar y distribuir el contenido libremente, siempre dando crédito correspondiente.

<!-- 
idea para implementar un proyecto mlops https://www.datacamp.com/es/tutorial/jenkins-tutorial

para tomar ideas de como usar jenkis
[text](https://medium.com/@iAadiDev/the-complete-jenkins-tutorial-you-will-ever-need-587d054ea1ac)

[text](https://softwaresennin.medium.com/jenkins-101-getting-started-with-jenkins-a69e1c3e4897)


[text](https://medium.com/@CJwrites154/master-jenkins-zero-to-hero-guide-part-1-961b8e38e014)

[text](https://medium.com/@venkatsatyanreddy_92646/beginners-guide-to-jenkins-pipelines-16a6181def97)

-->