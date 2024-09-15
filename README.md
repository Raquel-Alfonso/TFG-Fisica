# TFG-Fisica

En este repositorio aparecen los dos códigos que se emplearon en el trabajo, recogidos en Jupyter Notebooks y comentados. 

El primero de ellos, referido al paper de [Cervera-Lierta et al. 2021](https://arxiv.org/abs/2009.13545), trata sobre un tipo de VQE en el que aparece el parámetro de anisotropía $\Delta$ en una de sus capas, de ahí la nomenclatura meta-VQE. Con este parámetro, el modelo aprende el perfil general de energías en función de $\Delta$, con lo que consigue aproximar mejor en una segunda optimización que otros modelos sin este parámetro.

El segundo paper estudiado fue el de [Wiersema et al. (2020)](https://arxiv.org/abs/2008.02941), que utilizan un HVA, un tipo de QAOA alternado que se basa en la computación adiabática. La idea reside en que, partiendo del estado fundamental de una parte del hamiltoniano conseguiremos llegar al estado fundamental del hamiltoniano total.
