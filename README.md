# ejercicio7
Se estan ejecutando 2 contenedores
nicopaez/jobvacancy-ruby:1.3.0
postgres:14.4-alpine
Version del compose file
definiciones de servicioes
nombre de servicio
imagen asociada al servicio
asociasiones de imagenes
definiciones de ports, en este caso expone el puerto 300
definicion de variables de entorno para dicho contenedor
dependencias con otros contenedores
DockerCompose define una red para todos los contenedores del mismo composes, sumado a eso estamos definiendo un link entre los contenedores
