# IIC3633 Sistemas Recomendadores
Marzo-Junio 2024

### Equipo Docente e Información Administrativa
**Instructor**: [Denis Parra](http://dparra.sitios.ing.uc.cl), Profesor Asociado PUC Chile, Ph.D. University of Pittsburgh

**Ayudantes**:  
[Pablo Messina](#), Estudiante de Doctorado, Ciencia de la Computación PUC Chile.  
[Carlos Muñoz](#), Estudiante de Doctorado, Ciencia de la Computación PUC Chile.  
 
**Institución**: Pontificia Universidad Católica de Chile

**Horario cátedra**: Martes y Jueves, Módulo 3, sala H3 (11:00 a 12:10).<br/>
**Horario ayudantía**: Lunes, Módulo 5, sala BC22 (14:50 a 16:00).

Programa IIC 3633, 1er Semestre 2024: [pdf](https://dparra.sitios.ing.uc.cl/pdfs/IIC3633Sist%20Recomendadores_v5.pdf).

### AVISOS
* (18/03) Tarea 1 liberada, puedes encontrar el enunciado en [este link](https://github.com/denisparra/RecSysPUC-2024/blob/master/tareas/Tarea_1_RecSys_2024.pdf)
* (12/03) Calendario de actividades del curso actualizado

### Descripción del Curso

El curso de Sistemas Recomendadores cubre las principales tareas de recomendación, algoritmos, fuentes de datos y evaluación de estos sistemas. Al final de este curso serás capaz de decidir qué técnicas y fuentes de datos usar para implementar y evaluar sistemas recomendadores.

**Evaluaciones**:

*En proceso de actualización* Detalles de las evaluaciones en [esta presentacion](https://docs.google.com/presentation/d/1KW1cXwXInXQD7GXol2KjriPIaZFZLHoyQuB3Fbl0BmA/edit?usp=sharing).

**Software**: [Suprise](http://surpriselib.com/), [Implicit](https://github.com/benfred/implicit) y [pyRecLab](https://github.com/gasevi/pyreclab/).

**Contenido**:

## Contenidos por Semana

<!-- Tick      : &#10003 -->
<!-- Bold tick : &#10004 -->

| Semana  | Tema             | link slide(s) | 
|:--------|:-----------------|:-------------:|
| 1       | **Introducción**                                          | x    | 
| 2       | **Ranking no personalizado y Filtrado colaborativo (FC)** | [slides](https://github.com/denisparra/RecSysPUC-2024/blob/master/clases/s1-c2-nonpers-UBCF.pdf)    | 
| 2       | **User-based FC con clustering**                          | [slides](https://github.com/denisparra/RecSysPUC-2024/blob/master/clases/s1-c2-UBCF_clustering.pdf)    | 
| 2       | Pendiente Uno                                         | [slides](https://github.com/denisparra/RecSysPUC-2024/blob/master/clases/s1-c2-SlopeOne.pdf)    | 
| 2       | **Item-based FC**                                         | [slides](https://github.com/denisparra/RecSysPUC-2024/blob/master/clases/s2_c1-IBCF.pdf)    | 
| 2       | **Factorización Matricial: FunkSVD**                      | [slides](https://github.com/denisparra/RecSysPUC-2024/blob/master/clases/s2_c2-Factorizacion_matricial.pdf)    |
| 3       | Implicit Feedback CF                                  | [slides](https://github.com/denisparra/RecSysPUC-2024/blob/master/clases/s3_c1-Implicit-feedback.pdf)    |
| 3       | Bayesian Personalized Ranking (BPR)                   | [slides](https://github.com/denisparra/RecSysPUC-2024/blob/master/clases/s3_c2-BPR.pdf)    |
| 4       | Evaluación: metricas de error y ranking               | [slides](https://github.com/denisparra/RecSysPUC-2024/blob/master/clases/s4_c1-metricas.pdf)    | [video](https://drive.google.com/file/d/1Rr_-3HF4Bkal_RV1036A9PjwZX-fAcYj/view?usp=sharing)    |   [slides P Castells LARS 2019](http://ir.ii.uam.es/castells/lars2019.pdf)                |
| 4       | Evaluación II: Cobertura, diversidad, novedad                        | [slides](https://github.com/denisparra/RecSysPUC-2024/blob/master/clases/s4_c1-metricas.pdf)    | 
| 4       | Evaluación III: Tests estadísticos                        | [slides](https://github.com/denisparra/RecSysPUC-2024/blob/master/clases/s4_c2-tests_estadisticos.pdf)     |
| 5       | Recomendación basada en contenido 1                   | [slides](https://github.com/denisparra/RecSysPUC-2024/blob/master/clases/s5_c1-content-2024.pdf)    | 
| 5       | Recomendación basada en contenido 2                   | [slides](https://github.com/denisparra/RecSysPUC-2024/blob/master/clases/s5_c2-content.pdf)    | 
| 6       | Recomendación híbrida                                 | [slides](https://github.com/denisparra/RecSysPUC-2024/blob/master/clases/s6_c1-hibridos.pdf)    | 
| 6       | Recomendación por ensambles                           | [slides](https://github.com/denisparra/RecSysPUC-2024/blob/master/clases/s6_c2_p3-blending_ensemble.pdf)    |
| 6       | Recomendación basada en contexto                      | [slides](https://github.com/denisparra/RecSysPUC-2024/blob/master/clases/s6_c1-contexto.pdf)    |
| 6       | Máquinas de Factorización                             | [slides](https://github.com/denisparra/RecSysPUC-2024/blob/master/clases/s6_c2_p2-FMachines.pdf)    | 
| 7       | Deep Learning I: Intro                             |  [slides](https://github.com/denisparra/RecSysPUC-2024/blob/master/clases/s7_c1_deep_learning.pdf)    | 
| 7       | Deep Learning II: Tres proyectos                             |  [slides](https://github.com/denisparra/RecSysPUC-2021/blob/master/clases/s7_c2_deep_learning_s.pdf)    |
| 8       | SR Centrados en el Usuario                             | [slides](https://github.com/denisparra/RecSysPUC-2024/blob/master/clases/s9_c1_usercentric.pdf)    | 
| 8       | Sistemas Justos, Explicables y Transparentes                              | [slides](https://github.com/denisparra/RecSysPUC-2024/blob/master/clases/s9_c2_FATv2.pdf)    | 
| 9       |  Aprendizaje Activo (Active Learning)                             | [slides](https://github.com/denisparra/RecSysPUC-2024/blob/master/clases/s10_c1_activelearning_v3.pdf)    |
| 9       |  Bandits                            | [slides](https://drive.google.com/file/d/1SlDt7UCDrtJBIPUxAMjhqzsjz6uelyIn/view?usp=sharing)    |
| 10       |  Aprendizaje Reforzado | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2022/blob/master/clases/s10_c1_aprendizaje_reforzado.pdf)    |



<!--
| 8       | [Ideas de Proyecto](https://github.com/PUC-RecSys-Class/RecSysPUC-2022/tree/master/proyecto) |  [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2022/blob/master/proyecto/Denis-IdeasProyectosFinales-2020.pdf)        |   [video1](https://drive.google.com/file/d/1o8TFNtax9cYiIrVFdnxGxJ3P3fItIFwA/view?usp=sharing) [video2](https://drive.google.com/file/d/1NjC6iw9LRDmaKGh-rSAHVm_iolcsvMy1/view?usp=sharing)      |                   |
| 9       | Evaluación centrada en usuarios                             | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2022/blob/master/clases/s9_c1_usercentric.pdf)    | [video1](https://drive.google.com/file/d/1N6KBXkGN6Gh409mxkkD8KFGLs8Bvntz7/view?usp=sharing)  [video2](https://drive.google.com/file/d/1NlALFJzBcLv1SZGFSiOgjFoINlKzkdN4/view?usp=sharing)  |                   |
| 9       | Sistemas Justos, Explicables y Transparentes                                      |   [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2022/blob/master/clases/s9_c2_FATv2.pdf)       |  [video](https://drive.google.com/file/d/1kgJHc3DoKem0VW1gKvm2RaweGJJF3uPv/view?usp=sharing)        |                   |
| 10       | Aprendizaje Activo (Active Learning)                                    |   [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2022/blob/master/clases/s10_c1_activelearning.pdf)       |  [video](https://drive.google.com/file/d/1tb1qhBWUgO5jHrpQIYhWhvmy3z93Jimc/view?usp=sharing)        |                   |
| 10       | Bandits: Invitada [PhD(c) Andrea Barraza](https://apbarraza.com/)                                      |   [slides](https://gitlab.insight-centre.org/andbar/bears/raw/c4f04b377f6ad30a1ab0e5f1c97d05eaacec364e/tutorials/RECSYS2020/slides/%5BRecSys2020%5D%20Introduction%20to%20Bandits%20in%20Recommender%20Systems.pdf)       |  [video1](https://drive.google.com/file/d/1tTnkIjVOUu8Y_PkNYKZVBuWWscwn2Zni/view?usp=sharing)  [video2](https://drive.google.com/file/d/1Q8dYPUQ-EPmg_JEYK86Jw7smtr0ZPrEc/view?usp=sharing)        |   Tutorial eng. RecSys 2020 [video](https://player.vimeo.com/video/460128124) [slides](https://gitlab.insight-centre.org/andbar/bears/raw/c4f04b377f6ad30a1ab0e5f1c97d05eaacec364e/tutorials/RECSYS2020/slides/%5BRecSys2020%5D%20Introduction%20to%20Bandits%20in%20Recommender%20Systems.pdf)                 |
| 11       | Aprendizaje Profundo para RecSys (Intro y FC)                                      |   [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2022/blob/master/clases/s11_c1_deep_learning.pdf)       |  [video](https://drive.google.com/file/d/1-T_vxETMbzqk2FNJzUPGaPJtIpfe-R9g/view?usp=sharing)        |                   |
| 11       | Aprendizaje Profundo para RecSys (Secuencias)                                    |   [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2022/blob/master/clases/s11_c2_secu_deep_learning.pdf)       |  [video](https://drive.google.com/file/d/1krx9jda3TC8xyIn0n5FGuR-xgp-zezev/view?usp=sharing)        |                   |
| 12       | Aprendizaje Profundo para RecSys (Imágenes, Transformer, Grafos)                                    |   [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2022/blob/master/clases/s12_c1_deep_learning_s.pdf)       |  [video1](https://drive.google.com/file/d/11aUkSvabuHZMevDd4yP0dBTrc3_2eNtV/view?usp=sharing)  [video2](https://drive.google.com/file/d/1LJ6jI3gHPqS45Olv-Iu29W5DunO8ZbF6/view?usp=sharing)      |                   |
| 12       | 10 problemas en Sistemas de Recomendación                                     |   [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2022/blob/master/clases/s12_c2_10bigproblems-recsys-small.pdf)       |  [video](https://drive.google.com/file/d/1DtyzGOfMZY8UE223SMM2ROczH_qHhkNc/view?usp=sharing)        | | -->

### Parte II del curso: seminario

A partir de Junio el curso toma modalidad seminario, los alumnos hacen presentaciones de los siguientes papers (La lista de papers aun no será subida, la actualizaremos y avisaremos cuando corresponda).

<!-- Tick      : &#10003 -->
<!-- Bold tick : &#10004 -->


| Semana  | Paper            | Link slide(s) | Link video | Conferencia | Grupo |
|:--------|:-----------------|:-------------:|:----------:|:-------------:|:-------------:|
|11       |Drug Discovery as a Recommendation Problem: Challenges and Complexities in Biological Decisions|[slides](https://drive.google.com/file/d/1MKlZtJU_Niz_Iovl1JjRVwBfsk3T7zD7/view?usp=sharing)|[video]|[Recsys 2021](https://dl.acm.org/doi/abs/10.1145/3460231.3474598)| 12 |
|11       |Exploiting Negative Preference in Content-based Music Recommendation with Contrastive Learning|[slides](https://drive.google.com/file/d/1V3FTdMXCibK38Fy6b7DsPlYmodf4m4aw/view?usp=sharing)|[video](https://drive.google.com/file/d/1tGMbgECdtrFrVHbEXnhAlE3OpOnpTFSc/view?usp=sharing)|[Recsys 2022](https://dl.acm.org/doi/10.1145/3523227.3546768)| 2 |
|11       |Tops, Bottoms, and Shoes: Building Capsule Wardrobes via Cross-Attention Tensor Network|[slides](https://drive.google.com/file/d/1VXjc4qlFjUazMAJ5C8GmFduGC0GokNRZ/view?usp=sharing)|[video]|[Recsys 2021](https://dl.acm.org/doi/proceedings/10.1145/3460231)| 14 |
<!-- |12       |BRUCE: Bundle Recommendation Using Contextualized item Embeddings|[slides](https://drive.google.com/file/d/1D6ezymM34rJ9Y-Cod197cWjNMxx7pOUO/view?usp=sharing)|[video]|[Recsys 2022](https://dl.acm.org/doi/pdf/10.1145/3523227.3546754)| 6 |
|12       |Post Processing Recommender Systems with Knowledge Graphs for Recency, Popularity, and Diversity of Explanations|[slides](https://drive.google.com/file/d/1qGOvSLPj6cbNqYye7NhvB2NPR6HWG4ci/view?usp=sharing)|[video]|[SIGIR 2022](https://dl.acm.org/doi/10.1145/3477495.3532041)| 7 |
|12       |Rethinking Reinforcement Learning for Recommendation: A Prompt Perspective |[slides](https://drive.google.com/file/d/1j1zZscC4-bzV_dScXNLNBZ7aUlKUAfsE/view?usp=share_link)|[video]|[SIGIR 2022](https://dl.acm.org/doi/10.1145/3477495.3531714)| 23 |
|12       |Negative Interactions for Improved Collaborative Filtering: Don’t go Deeper, go Higher|[slides](https://drive.google.com/file/d/1pQsQgO9Y8nqZ2wvWqaQ3JL_qYwwkJq_q/view?usp=share_link)|[video]|[Recsys 2021](https://dl.acm.org/doi/abs/10.1145/3460231.3474273)| 16 |
|13       |Choosing the Best of Both Worlds: Diverse and Novel Recommendations through Multi-Objective Reinforcement Learning|[slides](https://drive.google.com/file/d/1H64JOe66oSOWiHz1G2GThktOAN-XyKcx/view?usp=share_link)|[video](https://drive.google.com/file/d/1AD06C39iliUDRqAr3aXMFuWuNeQIGpL3/view?usp=share_link)|[WSDM 2022](https://dl.acm.org/doi/10.1145/3488560.3498471)| 19 |
|13       |Reducing Cross-Topic Political Homogenization in Content-Based News Recommendation|[slides](https://drive.google.com/file/d/1vg5Sx8S5hwX5OzyWm2iX9C3ttxP6q2ax/view?usp=share_link)|[video]|[Recsys 2021](https://dl.acm.org/doi/10.1145/3523227.3546782)| 34 |
|13       |Price DOES Matter!: Modeling Price and Interest Preferences in Session-based Recommendation|[slides](https://drive.google.com/file/d/1Isyqh4CC7Z7dB8uJWyQI7Ele-L5aR63V/view?usp=share_link)|[video]|[SIGIR 2022](https://dl.acm.org/doi/10.1145/3477495.3532043)| 18 |
|14       |CAPTOR: A Crowd-Aware Pre-Travel Recommender System for Out-of-Town Users|[slides](https://drive.google.com/file/d/1_ySpuzbrDaEoX9Lyp_-eZDxep0McLO3F/view?usp=share_link)|[video]|[SIGIR 2022](https://dl.acm.org/doi/10.1145/3477495.3531949)| 15 |
|14       |Thinking inside The Box: Learning Hypercube Representations for Group Recommendation|[slides](https://drive.google.com/file/d/1gqZL5-pjKKjIT2XqzoLytJBBc5zUDPN6/view?usp=share_link)|[video](https://drive.google.com/file/d/195KRiq6JprUv9AOJ_zX3Fd1cafpc8hmm/view?usp=share_link)|[SIGIR 2022](https://dl.acm.org/doi/10.1145/3477495.3532066)| 9 |
|14       |Single-shot Embedding Dimension Search in Recommender System|[slides](https://drive.google.com/file/d/1lEoH0vN7HlUzSiybQyu7wKyYN697VE0V/view?usp=share_link)|[video](https://drive.google.com/file/d/19VZVsPlJ0GcdqqPiXP_sv7ebOVMukGeY/view?usp=share_link)|[SIGIR 2022](https://dl.acm.org/doi/10.1145/3477495.3532060)| 13 |
|14       |The Dual Echo Chamber: Modeling Social Media Polarization for Interventional Recommending|[slides](https://drive.google.com/file/d/1vY-0nPJYPe6nczZKsHLMKxLPZaW57bSo/view?usp=share_link)|[video](https://drive.google.com/file/d/1X_ITTXqODD1729QA79YOXH0402NbXsE4/view?usp=share_link)|[Recsys 2021](https://dl.acm.org/doi/10.1145/3460231.3474261)| 1 |
|14       |S-Walk: Accurate and Scalable Session-based Recommendation with Random Walks|[slides](https://drive.google.com/file/d/1PhgTWz6mLS3SBY3DHd5xZXBtn3kh23sW/view?usp=share_link)|[video](https://drive.google.com/file/d/1Hh5EAlEHvpH6atB2ljSRIzN2wZbAfxJA/view?usp=share_link)|[WSDM 2022](https://dl.acm.org/doi/10.1145/3488560.3498464)| 28 |
|14       |A User-Centered Investigation of Personal Music Tours|[slides](https://drive.google.com/file/d/1acjxQRN3XQKa4nj9wDMsZ5l5aBQjHgM2/view?usp=share_link)|[video](https://drive.google.com/file/d/10p9eKHEBAexG_Od1Wb2CWeNl0bG1wzE2/view?usp=share_link)|[RecSys 2022](https://dl.acm.org/doi/10.1145/3523227.3546776)| 30 |
-->

### Parte III del curso: Proyectos finales

L@s estudiantes trabajan en grupo sobre proyectos finales de curso, produciendo un poster, paper y repositorio con código para cada uno (A medida que los estudiantes vayan haciendo las entregas actualizaremos la lista de prsentaciones y posters aqui).

### Planificación y Evaluaciones

**MES 1** En las primeras semanas nos enfocaremos en métodos básicos para hacer recomendación usando y prediciendo ratings (filtrado colaborativo User-based & item-based, slope-one). Luego veremos métodos de factorización matricial para ratings y para feedback implícito. En la 3ra semana veremos formas adicionales de evaluar más alla de la métricas de error de predicción de rating (MAE, MSE, RMSE) e incorporaremos métricas para evaluar listas de ítems (precision, recall, MAP, P@n, nDCG). Veremos métodos basados en contenido y sistemas híbridos.

**MES 2** Métodos basados en contexto, máquinas de factorización y modelos fundamentales de deep learning para recomendación. Recapitulación de las tareas de recomendacion (predecir rating, predecir una lista de items, recomendar una secuencia, recomendación TopN) y de su evaluacion considerando diversidad, novedad, coverage, y otras métricas.

**MES 3** User-centric RecSys, FAT (Fairness, Accountability and Transparency), Aplicaciones de Deep learning para problemas más específicos: recomendación de ropa, multimedia, etc. Modelos profundos generativos para recomendación. Revisaremos problemas de recomendación aún no resueltos en el área.

**MES 4** Principalmente presentaciones de alumnos.

### Código de Honor

Este curso adscribe el Código de Honor establecido por la Escuela de Ingeniería el que es vinculante. Todo trabajo evaluado en este curso debe ser propio. En caso de que exista colaboración permitida con otros estudiantes, el trabajo deberá referenciar y atribuir correctamente dicha contribución a quien corresponda. Como estudiante es su deber conocer la versión en línea del Código de Honor

### Evaluaciones

** En proceso de actualizacion** : Detalles de las evaluaciones en [esta presentacion](#) 

<!-- Detalles de las evaluaciones en [esta presentacion](https://docs.google.com/presentation/d/19U5aaiUR1CE6lttf3lfzspsR37kwERRfn_zJ6m54MwE/edit#slide=id.p).-->

**Tarea 1**

Al final de las primeras 4 semanas, las(los) estudiantes implementarán mecanismos de recomendación para predecir ratings y para rankear items en un dataset que se entregará durante clases. Usarán las biblioteca pyreclab, surprise e implicit para los métodos básicos, pero si quieren optar a la nota máxima debe hacer un sistema híbrido o contextual que utilice información de contenido, como texto o imágenes. 
[enunciado de la tarea 1 - 2024 del curso](https://github.com/denisparra/RecSysPUC-2024/blob/master/tareas/Tarea_1_RecSys_2024.pdf)



**Lecturas: Blog y Presentación**

Fecha de revisión de comentarios de lecturas: El post de la semana x, tiene fecha de entrega el lunes a las 20:00 de la semana x+1. Ejemplo: Las lecturas de la semana 1 (clases el 9 y 11 de agosto) se entregan a más tardar el lunes 15 de agosto de 2022 a las 20:00.

Cada alumno debe crear una cuenta en el sitio [Perusall](https://app.perusall.com) con su correo uc. Cada semana deberá escribir 5 comentarios propios y 2 comentarios respondiendo a sus compañeros en los módulos de las lecturas marcadas como obligatorias. El codigo de curso para inscribirse es **LLWBU**.

Adicionalmente, cada alumno presentará al menos una vez durante el semestre un paper sobre un tópico, con el objetivo de abrir una discusión sobre el tema durante la clase.

**Proyecto Final** 

Durante septiembre, las(los) estudiantes enviarán una idea de proyecto final, la cual desarrollarán durante octubre y noviembre. Enviarán un informe de avance a fines de octubre, para hacer una presentación de su proyecto al final del curso en una sesión de posters.

## Planificación general (sujeta a actualización)

(actualizada el 1 de abril de 2024)

![Calendario 2024-1](https://github.com/denisparra/RecSysPUC-2024/assets/208111/635a05df-4d4d-4e4d-b06d-2699bcbd19be)

<!--[Calendario 2024-1](https://github.com/denisparra/RecSysPUC-2024/assets/208111/a0719944-b266-44b7-b19d-459609314714)-->

<!--[Calendario 2022-2](https://user-images.githubusercontent.com/53876461/183516596-1f981762-93f4-4892-aff2-7818ad5c1ed2.png)-->

## Lecturas por Semana

Para descargar los archivos se sugiere buscarlos en [Scholar](https://scholar.google.cl) o a través de [EZProxy](https://login.pucdechile.idm.oclc.org/).

Cada alumno debe crear una cuenta en el sitio [Perusall](https://app.perusall.com) con su correo uc (codigo de curso **LLWBU**). Cada semana deberá escribir 5 comentarios propios y 2 comentarios respondiendo a sus compañeros en los módulos de las lecturas marcadas como obligatorias

### Semana 1 (entrega el 18 de Marzo):  

**Obligatorias**  
* Kluver, D., Ekstrand, M. D., & Konstan, J. A. (2018). Rating-based collaborative filtering: algorithms and evaluation. Social information access: Systems and technologies, 344-390.
[pdf](https://doi.org/10.1007/978-3-319-90092-6_10)
**secciones (1-4)**

**Sugeridas**
* Schafer, J. B., Frankowski, D., Herlocker, J., & Sen, S. (2007). Collaborative filtering recommender systems. In The adaptive web (pp. 291-324). Springer Berlin Heidelberg. [pdf](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.130.4520&rep=rep1&type=pdf)
* Sarwar, B., Karypis, G., Konstan, J., & Riedl, J. (2001). Item-based collaborative filtering recommendation algorithms. In Proceedings of the 10th international conference on World Wide Web (pp. 285-295).
* [Post original FunkSVD](https://sifter.org/~simon/journal/20061211.html)  
* Lemire, D., & Maclachlan, A. (2005). Slope One Predictors for Online Rating-Based Collaborative Filtering. In SDM (Vol. 5, pp. 1-5).

### Semana 2 (entrega el 25 de Marzo):

**Obligatorias**  

* Kluver, D., Ekstrand, M. D., & Konstan, J. A. (2018). Rating-based collaborative filtering: algorithms and evaluation. Social information access: Systems and technologies, 344-390.
[pdf](https://doi.org/10.1007/978-3-319-90092-6_10)
**secciones (5-7)**

**Sugeridas**  
* Hu, Y., Koren, Y., & Volinsky, C. (2008). Collaborative filtering for implicit feedback datasets. In Data Mining, 2008. ICDM’08. Eighth IEEE International Conference on (pp. 263-272). IEEE.  
* Takács, G., Pilászy, I., Németh, B., & Tikk, D. (2009). Scalable collaborative filtering approaches for large recommender systems. Journal of machine learning research, 10(Mar), 623-656.  
* Rendle, S., Freudenthaler, C., Gantner, Z., & Schmidt-Thieme, L. (2009). BPR: Bayesian personalized ranking from implicit feedback. In Proceedings of the Twenty-Fifth Conference on Uncertainty in Artificial Intelligence (pp. 452-461). AUAI Press.
* Koren, Y., Bell, R., & Volinsky, C. (2009). Matrix factorization techniques for recommender systems. Computer, 42(8), 30-37. [pdf](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.441.3234&rep=rep1&type=pdf)
* Pan, R., Zhou, Y., Cao, B., Liu, N. N., Lukose, R., Scholz, M., & Yang, Q. (2008). One-class collaborative filtering. In 2008 Eighth IEEE International Conference on Data Mining (pp. 502-511). IEEE. En este artículo aparecen la derivación y reglas de actualización de los parámetros así como las nociones de AMAN y AMAU.
* Jannach, D., Lerche, L., & Zanker, M. (2018). Recommending based on implicit feedback. In Social Information Access (pp. 510-569). Springer, Cham.
* Srebro, N., & Jaakkola, T. (2003). Weighted low-rank approximations. In Proceedings of the 20th International Conference on Machine Learning (ICML-03) (pp. 720-727). Artículo citado por Pan et al. (2008) indicando detalles de la versión no regularizada que inspira OCCF.
* El siguiente paper es opcional, pero permite entender cómo se deriva <a href="https://www.codecogs.com/eqnedit.php?latex=y_i=(X^TC^iX&plus;&space;\lambda&space;I)^{-1}&space;X^TC^ip(i)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?y_i=(X^TC^iX&plus;&space;\lambda&space;I)^{-1}&space;X^TC^ip(i)" title="y_i=(X^TC^iX+ \lambda I)^{-1} X^TC^ip(i)" /></a> e <a href="https://www.codecogs.com/eqnedit.php?latex=x_u=(Y^TC^uY&plus;&space;\lambda&space;I)^1&space;Y^TC^up(u)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?x_u=(Y^TC^uY&plus;&space;\lambda&space;I)^{-1}&space;Y^TC^up(u)" title="x_u=(Y^TC^uY+ \lambda I)^1 Y^TC^up(u)" /></a> del paper de Hu et al.: Takács, G., Pilászy, I., & Tikk, D. (2011). Applications of the conjugate gradient method for implicit feedback collaborative filtering. In Proceedings of the fifth ACM conference on Recommender systems (pp. 297-300). ACM.
* Verstrepen, K., Bhaduriy, K., Cule, B., & Goethals, B. (2017). Collaborative filtering for binary, positiveonly data. ACM Sigkdd Explorations Newsletter, 19(1), 1-21.

### Semana 3 (entrega el 1 de Abril):

**Obligatorias**  
* Kluver, D., Ekstrand, M. D., & Konstan, J. A. (2018). Rating-based collaborative filtering: algorithms and evaluation. Social information access: Systems and technologies, 344-390.
[pdf](https://doi.org/10.1007/978-3-319-90092-6_10)
**secciones (8-10)**

**Sugeridas**  
* Eva Zangerle and Christine Bauer. 2022. Evaluating Recommender Systems: Survey and Framework. ACM Comput. Surv. Just Accepted (July 2022). https://doi.org/10.1145/3556536
* Krichene, W., & Rendle, S. (2022). On sampled metrics for item recommendation. Communications of the ACM, 65(7), 75-83. https://dl.acm.org/doi/pdf/10.1145/3535335
* Guy, S., & Gunawardana, A.. (2011) “Evaluating recommendation systems.” In Recommender systems handbook, pp. 257-297. Springer US, 2011. [pdf](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.712.4138&rep=rep1&type=pdf)
* Herlocker, J. L., Konstan, J. A., Terveen, L. G., & Riedl, J. T. (2004). Evaluating collaborative filtering recommender systems. ACM Transactions on Information Systems (TOIS), 22(1), 5-53.  
* Cremonesi, P., Koren, Y., & Turrin, R. (2010). Performance of recommender algorithms on top-n recommendation tasks. In Proceedings of the fourth ACM conference on Recommender systems (pp. 39-46). ACM.  

### Semana 4 (entrega el 05 de Septiembre):

**Obligatorias**  
* Pazzani, M. J., & Billsus, D. (2007). Content-based recommendation systems. In The adaptive web (pp. 325-341). Springer Berlin Heidelberg. Xu, W., Liu, X., & Gong, Y. (2003).[pdf](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.448.662&rep=rep1&type=pdf)

**Sugeridas**  
* Document clustering based on non-negative matrix factorization. In Proceedings of the 26th annual international ACM SIGIR conference on Research and development in informaion retrieval (pp. 267-273). ACM.
* Messina, P., Dominguez, V., Parra, D., Trattner, C., & Soto, A. (2019). Content-based artwork recommendation: integrating painting metadata with neural and manually-engineered visual features. User Modeling and User-Adapted Interaction, 29(2), 251-290.
* Celma, Ò., & Herrera, P. (2008). A new approach to evaluating novel recommendations. In Proceedings of the 2008 ACM conference on Recommender systems (pp. 179-186).
* Van den Oord, A., Dieleman, S., & Schrauwen, B. (2013). Deep content-based music recommendation. In Advances in neural information processing systems (pp. 2643-2651).

### Semana 5 (entrega el 12 de Septiembre):

**Obligatorias (esta semana se puede elegir una de las dos para entregar*)**  
* Adomavicius, G., Mobasher, B., Ricci, F. and Tuzhilin, A. (2011). Context-Aware Recommender Systems. AI Magazine, 32(3), 67-80. 
* Jahrer, M., Töscher, A. and Legenstein, R. (2010). Combining predictions for accurate recommender systems. In Proceedings of the 16th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, 693-702. ACM.

**Sugeridas**  
* Pigi K., Shobeir F., James F., Magdalini E. and Lise G. (2015). HyPER: A Flexible and Extensible Probabilistic Framework for Hybrid Recommender Systems. In Proceedings of the 9th ACM Conference on Recommender Systems (RecSys '15), 99–106. ACM. 
* Rendle, S. (2010). Factorization machines. In 2010 IEEE International Conference on Data Mining (pp. 995-1000). IEEE.


### Semanas 6 (entrega el 19 de Septiembre):

**Obligatorias**
* Hasta la sección 3.4 (incluyendo 3.4) + sección 4: Zhang, S., Yao, L., Sun, A., & Tay, Y. (2019). Deep learning based recommender system: A survey and new perspectives. ACM Computing Surveys (CSUR), 52(1), 1-38.


**Sugeridas**
* Covington, P., Adams, J., & Sargin, E. (2016). Deep neural networks for youtube recommendations. In Proceedings of the 10th ACM conference on recommender systems (pp. 191-198).
* Bansal, T., Belanger, D., & McCallum, A. (2016). Ask the gru: Multi-task learning for deep text recommendations. In Proceedings of the 10th ACM Conference on Recommender Systems (pp. 107-114).
* He, R., & McAuley, J. (2016). VBPR: visual bayesian personalized ranking from implicit feedback. In Proceedings of the AAAI conference on artificial intelligence (Vol. 30, No. 1).

### Semana 7 (entrega el 26 de Septiembre):

**Obligatorias**
* He, C., Parra, D., & Verbert, K. (2016). Interactive recommender systems: A survey of the state of the art and future research challenges and opportunities. Expert Systems with Applications, 56, 9-27.
 
**Sugeridas**
* Bostandjiev, S., O'Donovan, J., & Höllerer, T. (2012). TasteWeights: a visual interactive hybrid recommender system. In Proceedings of the sixth ACM conference on Recommender systems (pp. 35-42).
* Knijnenburg, B., Bostandjiev, S., O'Donovan, J., and Kobsa, A. (2012). Inspectability and control in social recommenders. RecSys'12 - Proceedings of the 6th ACM Conference on Recommender Systems. 
* Pu, P., Chen, L. and Hu, R. (2011). A user-centric evaluation framework for recommender systems. RecSys'11 - Proceedings of the 5th ACM Conference on Recommender Systems. 157-164.
* Parra, D., Brusilovsky, P., and Trattner, C. (2014). See What You Want to See: Visual User-Driven Approach for Hybrid Recommendation. International Conference on Intelligent User Interfaces, Proceedings IUI.
* Andjelkovic, I., Parra, D., & O’Donovan, J. (2019). Moodplay: Interactive music recommendation based on Artists’ mood similarity. International Journal of Human-Computer Studies, 121, 142-159.


### Semana 8 (entrega el 03 de Octubre):

**Obligatorias**
* Cañamares, R., Redondo, M., & Castells, P. (2019). Multi-armed recommender system bandit ensembles. In Proceedings of the 13th ACM Conference on Recommender Systems (pp. 432-436).
* Bendada, W., Salha, G., & Bontempelli, T. (2020). Carousel Personalization in Music Streaming Apps with Contextual Bandits. In Fourteenth ACM Conference on Recommender Systems (pp. 420-425).

**Sugeridas**
* Lacerda, A., Santos, R. L., Veloso, A., & Ziviani, N. (2015). Improving daily deals recommendation using explore-then-exploit strategies. Information Retrieval Journal, 18(2), 95-122.
* Guillou, F., Gaudel, R., & Preux, P. (2016). Scalable explore-exploit collaborative filtering. In Pacific Asia Conference On Information Systems (PACIS). Association For Information System.
* Teo, C. H., Nassif, H., Hill, D., Srinivasan, S., Goodman, M., Mohan, V., & Vishwanathan, S. V. N. (2016). Adaptive, personalized diversity for visual discovery. In Proceedings of the 10th ACM conference on recommender systems (pp. 35-38).

### Semana 9 (entrega el 11 de Octubre):

**Obligatorias**
* Sun, F., Liu, J., Wu, J., Pei, C., Lin, X., Ou, W., & Jiang, P. (2019). BERT4Rec: Sequential recommendation with bidirectional encoder representations from transformer. In Proceedings of the 28th ACM international conference on information and knowledge management (pp. 1441-1450).

**Sugeridas**
* Chen, Q., Zhao, H., Li, W., Huang, P., & Ou, W. (2019). Behavior sequence transformer for e-commerce recommendation in alibaba. In Proceedings of the 1st International Workshop on Deep Learning Practice for High-Dimensional Sparse Data (pp. 1-4).
* Chen, J., Zhang, H., He, X., Nie, L., Liu, W., & Chua, T. S. (2017). Attentive collaborative filtering: Multimedia recommendation with item-and component-level attention. In Proceedings of the 40th International ACM SIGIR conference on Research and Development in Information Retrieval (pp. 335-344).
* Liang, D., Krishnan, R. G., Hoffman, M. D., & Jebara, T. (2018). Variational autoencoders for collaborative filtering. In Proceedings of the 2018 World Wide Web Conference (pp. 689-698).

