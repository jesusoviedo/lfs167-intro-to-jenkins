# Jenkins con Docker Compose

Este repositorio contiene los archivos necesarios para instalar y ejecutar Jenkins utilizando Docker Compose.

## Requisitos previos

- **Docker**: [Instalación de Docker](https://docs.docker.com/get-docker/)
- **Docker Compose**: [Instalación de Docker Compose](https://docs.docker.com/compose/install/)

## Pasos para iniciar Jenkins

1. **Verifica tu archivo** `docker-compose.yml` con el siguiente contenido:

```yaml
services:
    jenkins:
    image: jenkins/jenkins:lts
    ports:
        - "8080:8080"
    volumes:
        - ./data_jenkis:/var/jenkins_home
    ssh-agent:
    image: jenkins/ssh-agent
```

2. **Crea la carpeta** para los datos de Jenkins:

```bash
mkdir -p data_jenkis
```

3. **Levanta los contenedores**:

```bash
docker compose up -d
```

   - Jenkins estará disponible en [http://localhost:8080](http://localhost:8080).

4. **Detén y elimina** los contenedores:

```bash
docker compose down
```

_¡Listo! Ya tienes Jenkins corriendo con tu configuración de Docker Compose._

---

Para obtener más información sobre la instalación de Jenkins y conocer otras alternativas disponibles, puedes consultar la [documentación oficial de instalación ](https://www.jenkins.io/doc/book/installing/)





