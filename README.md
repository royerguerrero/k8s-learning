# Kubernetes K8s

## Repaso de contenedores
Los contenedores no son un _fisrt calss citizen_ del kernel de Linux, un conetenedor no es una entidad previamente definida. Es un concepto abstracto conformado por diferentes tecnologias que se potencian las unas a las otras y trabajando en conjunto componen esta tecnologia

### Contenedores
*container* = namespaces * cgroups * chroot + ...
- namespaces: Vistas de los recursos del sistema (Insolate los procesos, existen 7 tipos de namespaces)
- cgroups: Limitan y miden los recursos del SO (Maneja y limita los recursos de memoria, disco y cpu)
- chroot: Cambia el `root directory` de un proceso (Permite conectar el disco con los volumenes de docker entre muchas otras cosas mas)


# Read notes 
- Open source en la educacion tradicional
- Extension para tomar notas de las lecturas
