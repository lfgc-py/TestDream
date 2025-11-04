# Test de Github :v:

---------

### Pruebas de funcionalidad.

__________
>"El aburrimiento se cura con curiosidad. La curiosidad no se cura con nada." 
-Dorothy Parker. 



##### Lista de Links:

- [Vídeo 1](https://youtu.be/H2E76CEuct0?si=kqqAKVckOQRHAlyx) 
- [Vídeo 2](https://youtu.be/QaFqZpS7OrU?si=CCQzInmxdTMDKNQu)

##### Imágen:

![Imágen 1](https://img.wattpad.com/useravatar/CalamardoTentaculo73.128.491721.jpg)

##### Código de Shutdown ^^

```python
import os
import platform

def apagar_equipo():
    sistema = platform.system()
    confirmar = input("¿Seguro que quieres apagar la computadora? (s/n): ").lower()

    if confirmar != "s":
        print("Cancelado.")
        return

    if sistema == "Windows":
        os.system("shutdown /s /t 0")
    elif sistema == "Linux" or sistema == "Darwin":  # Darwin = macOS
        os.system("sudo shutdown now")
    else:
        print(f"Sistema operativo no soportado: {sistema}")

if __name__ == "__main__":
    apagar_equipo()
```
**Python** es un lenguaje de programación de alto nivel, interpretado y multiparadigma, diseñado para ser legible, flexible y fácil de aprender. Se caracteriza por su sintaxis clara y su amplia biblioteca estándar, que **permite** realizar desde **tareas** sencillas hasta **proyectos** complejos como inteligencia artificial, análisis de datos, desarrollo web, automatización, ciberseguridad **y más**. 

**Es multiplataforma**, lo que significa que el mismo código puede ejecutarse **en** distintos sistemas operativos sin cambios significativos. Además, **su gran comunidad y ecosistema de librerías** lo convierten en *una de las herramientas más poderosas y versátiles* ***del mundo*** tecnológico actual.

| Lenguaje   | Tipo de uso principal              | Nivel de dificultad | Popularidad |
|-------------|------------------------------------|---------------------|--------------|
| Python      | Ciencia de datos, IA, automatización | Fácil              | Muy alta     |
| JavaScript  | Desarrollo web, apps interactivas  | Media               | Muy alta     |
| C++         | Videojuegos, sistemas, rendimiento | Alta                | Alta         |

##### Checklist:

- [x] Introducción
- [ ] Desarrollo
- [ ] Finalización
