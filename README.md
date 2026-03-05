# Entornos-7.2
ejercicio 1
```mermaid
graph LR
Usuario --> Encender_Luces
Usuario --> Apagar_Luces
```
ejercicio 2
```mermaid
graph LR
Cliente --> Comprar_Producto
Administrador --> Gestionar_Stock

Aplicar_Cupon -.->|extend| Comprar_Producto
```
ejercicio 3
```mermaid
graph LR

Espectador --> Reproducir_Pelicula
Espectador --> Renovar_Suscripcion

Editor --> Subir_Nuevo_Video

Pasarela_de_Pagos --> Renovar_Suscripcion

Reproducir_Pelicula --> Validar_Suscripcion
Activar_Subtitulos -.->|extend| Reproducir_Pelicula
```
