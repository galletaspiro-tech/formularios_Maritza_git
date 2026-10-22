# Proyecto Fotografias 


**STATUS** ![EN DESARROLLO](https://img.shields.io/badge/STATUS-EN_DESARROLLO-blue)

## Maritza Contreras Salguero

### Lista de Actividades

En esta sección irán las listas de actividades enumeradas:

- Frontend ![STATUS](https://img.shields.io/badge/STATUS-EN_Proceso-green)
- Backend ![STATUS](https://img.shields.io/badge/STATUS-EN_Proceso-orange)
- Base de Datos ![STATUS](https://img.shields.io/badge/STATUS-EN_DESARROLLO-red)


### Lista de actividades concluidas

- [x] Interfaz inicial
- [x] Menu Principal
- [x] Formularios
- [ ] Descipción
- [ ] Enlaces
- [ ] otras ventanas 

###  Bloque de código ejemplo

```php
<?php
$fotos_restantes = 3;

echo "Iniciando procesamiento de galería...\n";

while ($fotos_restantes > 0) {
    echo " Procesando foto. Quedan: " . $fotos_restantes . "\n";
    $fotos_restantes--; 
}

echo " ¡Todas las fotos han sido procesadas!";
?>