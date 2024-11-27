# RNIF
## Redes Neuronales Informadas por Fisica
Este repositorio contiene el trabajo practicos integrador de la materia Redes Neuronales Informadas por Fisica de la Especialización en Inteligencia Artificial (CEIA) de la Facultad de Ingeniería de la Universidad de Buenos Aires (FIUBA).

1 Enunciado

Estamos interesados en estimar el número de generación de calor en una aleta rectangular con conductividad térmica y generación de calor dependientes de la temperatura. 
La forma no dimensional de la ecuación diferencial ordinaria no lineal se muestra a continuación,
![image](https://github.com/user-attachments/assets/10a0a35e-4560-405f-831a-0f250396cae4)

Donde:

![image](https://github.com/user-attachments/assets/f13c1a29-f5d0-4d9f-af44-82be31789092)

![image](https://github.com/user-attachments/assets/281ec5a0-dd31-4d96-974c-e412c0552471)

Las condiciones de contorno estan definidas como:

![image](https://github.com/user-attachments/assets/5069547b-9d84-4ef5-8ca0-6a5afbcd609f)

1- Primeramente se entrena una red full connected utilizando el dataset proporcionado, con el fin de aprender la relacion entre el campo de temperatura y el valor de G. Se la entrena con diferente numero de muestras y se analiza la variacion del error cuadratico medio con el numero de muestras utilizadas.
En la segunda parte se entrena un modelo PINN en la que se consideran las condiciones de contorno.
