# Estudio sobre la privacidad en el aprendizaje federado mediante el desarrollo de un sistema de recomendación online

Hola, soy Ibai Guillén y el presente repositorio es el proyecto fin de grado que realizé durante 4 de carrera en la Universidad de Deusto.

## Descripción del proyecto

Este trabajo fin de grado pretende reforzar los aspectos de privacidad de la información y los perfiles de usuario en un sistema de recomendaciones de tal forma que este sea capaz de funcionar de forma distribuida con aprendizaje federado. De esta manera los datos para mejorar los modelos de recomendación quedan desacoplados del usuario que los generó y por tanto, se preserva la privacidad y seguridad de la información manteniendo una eficacia de las recomendaciones aceptable. El estudio comparará a nivel de rendimiento, latencia y privacidad de la información un modelo centralizado de recomendación con todos los datos en claro de los usuarios con un modelo distribuido y federado donde los datos son anonimizados. Este TFG explora un campo novedoso donde se une el aprendizaje máquina y el internet de las cosas mediante un ejemplo real distribuido con dispositivos periféricos basados en Raspberry pi y NVIDIA Jetson nano como núcleo central para agregar modelos.

## Estructura del repositorio

El repositorio cuenta con dos ramas, master y develop, cada una con un objetivo diferente. Todos los cambios se realizan en la rama develop y únicamente son pasados a máster cuando la versión es estable y limpia, las modificaciones que sean inestables no serán aceptadas como pull request hasta que se corrijan.

graph LR
    A[master] --Develop Branch---> B((feature))
    A --Stable version branch--> D
    B --> E((feature))
    E --> D[master]
    D --Develop Branch--> F((feature))
    D --Stable version branch--> G[master]
    F --> G


Por lo cual, si se quiere consultar el proyecto estable descargue la versión de la rama master, si prefiere conocer el estado del desarrollo puede descargar la rama develop.
