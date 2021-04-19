# doctl-create-simple-cluster
Script .sh que permite crear un cluster kubernetes mediante doctl y kubectl para el provider DigicalOcean

## Funciones

- Provisiona un nuevo cluster
- Guarda el Kubeconfig en la maquina local y lo setea como el contexto por defecto
- Se obtiene el nombre y el contexto del cluster para las funciones posteriores
- Se instala el Ingress Controller >nginx-0.26.1
- Se obtiene la IP Externa del Load Balancer creado
- Se instala el cert-manager 0.12.0

## Notas

_La configuración permite trabajar con recursos Ingress con la versión networking.k8s.io/v1beta1 ._
