# Latino-VSCode
![GitHub package.json version](https://img.shields.io/github/package-json/v/melving24/latino-vscode)
![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/MelvinGuerrero.latino-vscode)
![GitHub](https://img.shields.io/github/license/melving24/latino-vscode)
---
<!-- ![Image](https://github.com/MelvinG24/Latino-VSCode/blob/master/.readme/Latino-VSCodeInstall.gif?raw=true) -->
![Image](.readme/Latino-VSCodeInstall.gif)

# Sintaxis de Lenguaje Latino para VS Code
Esta es la extensión oficial de Latino en Visual Studio Code.

## Caracteristicas
* Resaltado de sintaxis de Latino (Syntax highlighting)
* Ejecusion del código (Ctrl+Alt+R)
* Snippets

![Image](.readme/buscarBinario.gif)

## Requerimientos de extension
* Se necesita tener Latino instalado para la función de "Ejecutar en la Terminal"

![Image](.readme/terminalLatino.gif)

# Funciones
| Acción         | Función                                                                                   |
|----------------|-------------------------------------------------------------------------------------------|
| Ctrl+Alt+R     | Ejecuta el código de Latino en la terminal (*Requiere primero guardar el archivo)         |

![Image](.readme/ejecutarLatino.gif)

# Fargmentos de código (snippets)
En VS Code para usar los snippets, escribimos el desencadenador deseado y presionamos TAB.

| Desencadenador | Nombre                                  | codigo                                          |
|----------------|-----------------------------------------|-------------------------------------------------|
| si             | si condicional                          | si condicion #codigo fin                        |
| sino           | si sino condicional                     | si condicion #codigo sino #codigo fin           |
| osi            | si osi sino condicional                 | si condicion #codigo osi #codigo #sino #codigo  |
| caso           | caso condicional(Which Case1,case2)     | elegir(sentencia)caso1,caso2,caso3,defento,fin  |
| mien           | ciclo mientras                          | mientras condition #codigo fin                  |
| rep            | ciclo repetir                           | repetir #codigo hasta condicion                 |
| des            | ciclo desde                             | desde ( i = 0; i < 10; i++) #codigo fin         |
| fun            | funcion                                 | funcion nombre_funcion (argumentos) #codigo fin |
| ret            | retorno                                 | retorno valor                                   |
| esc            | escribir                                | escribir("mensaje")                             |
| imp            | imprimir                                | imprimir("mensaje")                             |
| impf           | imprimirf                               | imprimirf("%s\n", variable)                     |
| inc            | incluir                                 | incluir "modulo"                                |
| encabezado     | encabezado                              | genera un encabezado de código comentado        |

>Alternativamente, presione `Ctrl` +` Space` (Windows, Linux) o `Cmd` +` Space` (OSX) para activar los snippets desde el editor.

# Reporte de errores
Cualquier error lo puedes reportar en: https://github.com/MelvinG24/Latino-VS/issues

# Documentación de Latino
Para aprender más sobre este maravilloso lenguaje de programación llamado Latino, puedes visitar la documentación oficial en el siguiente enlace: https://manual.lenguajelatino.org/

# License
Licenciado bajo la licencia [MIT](https://github.com/MelvinG24/Latino-VSCode/blob/master/LICENSE)