# My App Helm Chart
## Descripción
Este es un Helm Chart 

## Instalación
```sh
helm install my-app ./my-app -f values.yaml
```

## Configuración
Para desplegar en desarrollo:
```sh
helm install my-app ./my-app -f values-dev.yaml
```

Para desplegar en producción:
```sh
helm install my-app ./my-app -f values-prod.yaml
```

## Validación del Chart
```sh
helm lint ./my-app
```
