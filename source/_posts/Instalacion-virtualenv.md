---
title: Instalacion virtualenv
tags:
  - python
categories:
  - fundamentos-programacion
date: 2017-03-14 00:56:24
---

Quizas muchos no conozcan virtualenv y su importancia en la cual radica que nosotros podamos tener nuestras dependencias de nuestro proyecto en un archivo; dependencias se llaman a los paquetes que instalamos por medio de pip.
<!--more-->
## Instalacion Windows
Para instalar en windows simplemente tenemos que asegurarnos que tenemos instalado pip, para esto abrimos el cmd o el git bash de preferencia y tipeamos
```
pip --help
```
![](http://drive.google.com/uc?export=view&id=0B5eV7W42S7ndcmNOX2tkSmdiZGs "pip help")
Luego lo que hacemos es instalar virtualenv simplemente con la linea
```
pip install virtualenv
```
<!--imagen de virtualenv installado-->
Para asegurarnos de que todo esta bien lo que hacemos es ejecutar en la consola lo siguiente
```
virtualenv --help
```
![](http://drive.google.com/uc?export=view&id=0B5eV7W42S7ndUll0bHBSNGVuaDA "virtualenv help")
## Instalacion en linux
En linux hacemos unos pocos pasos mas, pero en escencia es lo mismo. Para instalar primero nos haceguramos que tenemos pip
```
pip --help
```
Si no instalamos con
```
sudo apt-get install python3-pip
```
Para instalar virtualenv lo hacemos lo mismo que en Windows
```
pip install virtualenv
```
Y nos aseguramos que los tenemos instalado
```
virtualenv --help
```
