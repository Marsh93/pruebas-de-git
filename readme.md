# Aprendiendo Git desde cero

Sistema de control de versiones para el mantenimiento eficiente y confiable de archivos.

## Zonas de Git

1. Directorio de Trabajo
2. Área de preparación
3. Directorio Git

## Flujo de trabajo básico en Git

1. Modificas una serie de archivos en tu directorio de trabajo.
2. Preparas los archivos, añadiéndolos a tu área de preparación.
3. Confirmas los cambios, lo que toma los archivos tal y como están en el área de preparación y almacena esa copia instantánea de manera permanente en tu directorio de Git.

## Configurando Git por primera vez

```plain-text

git config --global user.name "Omar Zavala"
git config --global user.email "alexoamr1993@gmail.com"
git config --global core.editor "code -wait"
git config --list

```