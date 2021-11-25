# IIC3633 Sistemas Recomendadores
Agosto-Diciembre 2021

**AVISOS**
El Jueves 26 de Septiembre hay clase en sala A7, es hibrida así es que pueden asistir presencialmente o de forma remota por el link zoom de siempre.


### Equipo Docente e Información Administrativa
**Instructor**: [Denis Parra](http://dparra.sitios.ing.uc.cl), Profesor Asociado PUC Chile, Ph.D. University of Pittsburgh

**Ayudantes**:  
[Vladimir Araujo](https://vgaraujov.github.io/), Estudiante de Doctorado en Ciencia de la Computación PUC Chile.  
[Andrés Carvallo](https://scholar.google.com/citations?user=DinpmCUAAAAJ&hl=es), Estudiante de Doctorado en Ciencia de la Computación PUC Chile.  
[Francisca Cattan](https://www.linkedin.com/in/franciscacattan/), Estudiante de Doctorado en Ciencia de la Computación PUC Chile.  
[Alvaro Labarca](#), Estudiante de Magister, en Ciencia de la Computación PUC Chile.  
[Jorge Pérez Facuse](#), Estudiante de Magister, en Ciencia de la Computación PUC Chile.  
 

**Institución**: Pontificia Universidad Católica de Chile

**Horario**: Martes y Jueves, Módulo 3 (11:30 a 12:50).

Programa IIC 3633, 2do Semestre 2021: [pdf](https://dparra.sitios.ing.uc.cl/pdfs/IIC3633Sist%20Recomendadores_v5.pdf).

### Descripción del Curso

El curso de Sistemas Recomendadores cubre las principales tareas de recomendación, algoritmos, fuentes de datos y evaluación de estos sistemas. Al final de este curso serás capaz de decidir qué técnicas y fuentes de datos usar para implementar y evaluar sistemas recomendadores.

**Software**: [pyRecLab](https://github.com/gasevi/pyreclab/).

La componente práctica de este curso se enseña a través del uso de pyRecLab desarrollado por Gabriel Sepúlveda (ex-alumno de este curso), biblioteca de software para desarrollo de sistemas recomendadores en Python.

**Contenido**:

## Contenidos por Semana

<!-- Tick      : &#10003 -->
<!-- Bold tick : &#10004 -->

| Semana  | Tema             | link slide(s) | link video | comentario(s) |
|:--------|:-----------------|:-------------:|:----------:|:-------------:|
| 1       | Introducción                                          | x    | [video](https://drive.google.com/file/d/1LwlP2avrSnU6gId_I9ywF3nFU7nboL09/view?usp=sharing)    |                   |
| 1       | Ranking no personalizado y Filtrado colaborativo (FC) | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2021/blob/master/clases/s1-c2-nonpers-UBCF.pdf)    | [video](https://drive.google.com/file/d/10rL3XbuNVCCETiSvncFmcIpkKJ9B6Krg/view?usp=sharing)    |                   |
| 1       | User-based FC con clustering                          | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2021/blob/master/clases/s1-c2-UBCF_clustering.pdf)    | [video](#)  |                   |
| 2       | Pendiente Uno                                         | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2021/blob/master/clases/s1-c2-SlopeOne.pdf)    | [video](https://drive.google.com/file/d/1MAAo4hlJKnNvBAyFyHmGimtHju-ytSpi/view?usp=sharing)   |                   |
| 2       | Item-based FC                                         | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2021/blob/master/clases/s2_c1-IBCF.pdf)    | [video](https://drive.google.com/file/d/1MAAo4hlJKnNvBAyFyHmGimtHju-ytSpi/view?usp=sharing)    |                   |
| 2       | Factorización Matricial: FunkSVD                      | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2021/blob/master/clases/s2_c2-Factorizacion_matricial.pdf)    | [video](https://drive.google.com/file/d/1GSVTKI6QXDEmhWfRb0YqjMe7HHcUVfbv/view?usp=sharing)    |                   |
| 3       | Implicit Feedback CF                                  | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2021/blob/master/clases/s3_c1-Implicit-feedback.pdf)    | [video](https://drive.google.com/file/d/1xR3QK2erxukNCMlyQJLB1rA6Qu45gLlG/view?usp=sharing)  |                   |
| 3       | Bayesian Personalized Ranking (BPR)                   | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2021/blob/master/clases/s3_c2-BPR.pdf)    | [video](https://drive.google.com/file/d/1cq0_y7q5G6xqMa7HM9nxSrRCOGZHXzBa/view?usp=sharing)    |                   |
| 4       | Evaluación: metricas de error y ranking               | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2021/blob/master/clases/s4_c1-metricas.pdf)    | [video](https://drive.google.com/file/d/1Rr_-3HF4Bkal_RV1036A9PjwZX-fAcYj/view?usp=sharing)    |   [slides P Castells LARS 2019](http://ir.ii.uam.es/castells/lars2019.pdf)                |
| 4       | Evaluación II: Cobertura, diversidad, novedad                        | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2021/blob/master/clases/s4_c1-metricas.pdf)    | [video](#)     |                   |
| 4       | Evaluación III: Tests estadísticos                        | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2021/blob/master/clases/s4_c2-tests_estadisticos.pdf)     | [video](#)    |                   |
| 5       | Recomendación basada en contenido 1                   | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2021/blob/master/clases/s5_c1-content.pdf)    | [video](https://drive.google.com/file/d/1SGsph_uYSxJuWBhLfh1YhZCazZXFCTCQ/view?usp=sharing)    |                   |
| 5       | Recomendación basada en contenido 2                   | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2021/blob/master/clases/s5_c2-content.pdf)    | [video](#)    |                   |
| 6       | Recomendación híbrida                                 | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2021/blob/master/clases/s6_c1-hibridos.pdf)    | [video](https://drive.google.com/file/d/1aUNYNli4l4xk_hGRB7v-PaRr0xtJWQau/view?usp=sharing)    |                   |
| 6       | Recomendación por ensambles                           | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2021/blob/master/clases/s6_c2_p3-blending_ensemble.pdf)    | [video](https://drive.google.com/file/d/1o5cL5JspHI8QizFeMT8_9HQKqNT2rmqm/view?usp=sharing)    |                   |
| 6       | Recomendación basada en contexto                      | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2021/blob/master/clases/s6_c1-contexto.pdf)    | [video1](https://drive.google.com/file/d/1fC3Ypg5aF8Be_8b7ZpPFqwVdtJS2kwzm/view?usp=sharing) [video2](https://drive.google.com/file/d/10r_6DzrKflF8sVzgZ1mU8xb8mJC2BcgO/view?usp=sharing)   |                   |
| 6       | Máquinas de Factorización                             | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2021/blob/master/clases/s6_c2_p2-FMachines.pdf)    | [video](https://drive.google.com/file/d/111IK4ZIE-bqiNWmYLyafQoS0kthETLUr/view?usp=sharing)    |                   |
| 7       | Deep Learning I: Intro                             |  [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2021/blob/master/clases/s7_c1_deep_learning.pdf)    | [video](https://drive.google.com/file/d/1KHpLMWd4ISSNOadeXdngK-fQSXpVUols/view?usp=sharing)    |                   |
| 7       | Deep Learning II: Tres proyectos                             |  [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2021/blob/master/clases/s7_c2_deep_learning_s.pdf)    | [video](https://drive.google.com/file/d/1l3fkgyubvrbMjziieKiLglbaJR9USTVA/view?usp=sharing)    |                   |
| 8       | SR Centrados en el Usuario                             | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2021/blob/master/clases/s9_c1_usercentric.pdf)    | [video](https://drive.google.com/file/d/1B8-N2ZtyE9p5KBr-EuoT1YQ-Fy0GDUF1/view?usp=sharing)    |                   |
| 8       | Sistemas Justos, Explicables y Transparentes                              | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2021/blob/master/clases/s9_c2_FATv2.pdf)    | [video](https://drive.google.com/file/d/1HooxTDVwa9WQM1YXQWjDTRT-i1dmkO8m/view?usp=sharing)    |                   |
| 9       |  Aprendizaje Activo (Active Learning)                             | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2021/blob/master/clases/s10_c1_activelearning_v3.pdf)    | [video](https://drive.google.com/file/d/1_hMeckheVQLauyNrFNheBrcn3qpoCwJO/view?usp=sharing)    |                   |
| 9       |  Bandits                            | [slides](https://drive.google.com/file/d/1SlDt7UCDrtJBIPUxAMjhqzsjz6uelyIn/view?usp=sharing)    | [video](https://drive.google.com/file/d/1PyIFL8dDtQ4W0y_t89jrXzJnZcl56TEj/view?usp=sharing)    |                   |
| --       | Semana Break                             | Break    | Break    |                   |



<!--
| 8       | [Ideas de Proyecto](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/tree/master/proyecto) |  [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/proyecto/Denis-IdeasProyectosFinales-2020.pdf)        |   [video1](https://drive.google.com/file/d/1o8TFNtax9cYiIrVFdnxGxJ3P3fItIFwA/view?usp=sharing) [video2](https://drive.google.com/file/d/1NjC6iw9LRDmaKGh-rSAHVm_iolcsvMy1/view?usp=sharing)      |                   |
| 9       | Evaluación centrada en usuarios                             | [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s9_c1_usercentric.pdf)    | [video1](https://drive.google.com/file/d/1N6KBXkGN6Gh409mxkkD8KFGLs8Bvntz7/view?usp=sharing)  [video2](https://drive.google.com/file/d/1NlALFJzBcLv1SZGFSiOgjFoINlKzkdN4/view?usp=sharing)  |                   |
| 9       | Sistemas Justos, Explicables y Transparentes                                      |   [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s9_c2_FATv2.pdf)       |  [video](https://drive.google.com/file/d/1kgJHc3DoKem0VW1gKvm2RaweGJJF3uPv/view?usp=sharing)        |                   |
| 10       | Aprendizaje Activo (Active Learning)                                    |   [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s10_c1_activelearning.pdf)       |  [video](https://drive.google.com/file/d/1tb1qhBWUgO5jHrpQIYhWhvmy3z93Jimc/view?usp=sharing)        |                   |
| 10       | Bandits: Invitada [PhD(c) Andrea Barraza](https://apbarraza.com/)                                      |   [slides](https://gitlab.insight-centre.org/andbar/bears/raw/c4f04b377f6ad30a1ab0e5f1c97d05eaacec364e/tutorials/RECSYS2020/slides/%5BRecSys2020%5D%20Introduction%20to%20Bandits%20in%20Recommender%20Systems.pdf)       |  [video1](https://drive.google.com/file/d/1tTnkIjVOUu8Y_PkNYKZVBuWWscwn2Zni/view?usp=sharing)  [video2](https://drive.google.com/file/d/1Q8dYPUQ-EPmg_JEYK86Jw7smtr0ZPrEc/view?usp=sharing)        |   Tutorial eng. RecSys 2020 [video](https://player.vimeo.com/video/460128124) [slides](https://gitlab.insight-centre.org/andbar/bears/raw/c4f04b377f6ad30a1ab0e5f1c97d05eaacec364e/tutorials/RECSYS2020/slides/%5BRecSys2020%5D%20Introduction%20to%20Bandits%20in%20Recommender%20Systems.pdf)                 |
| 11       | Aprendizaje Profundo para RecSys (Intro y FC)                                      |   [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s11_c1_deep_learning.pdf)       |  [video](https://drive.google.com/file/d/1-T_vxETMbzqk2FNJzUPGaPJtIpfe-R9g/view?usp=sharing)        |                   |
| 11       | Aprendizaje Profundo para RecSys (Secuencias)                                    |   [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s11_c2_secu_deep_learning.pdf)       |  [video](https://drive.google.com/file/d/1krx9jda3TC8xyIn0n5FGuR-xgp-zezev/view?usp=sharing)        |                   |
| 12       | Aprendizaje Profundo para RecSys (Imágenes, Transformer, Grafos)                                    |   [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s12_c1_deep_learning_s.pdf)       |  [video1](https://drive.google.com/file/d/11aUkSvabuHZMevDd4yP0dBTrc3_2eNtV/view?usp=sharing)  [video2](https://drive.google.com/file/d/1LJ6jI3gHPqS45Olv-Iu29W5DunO8ZbF6/view?usp=sharing)      |                   |
| 12       | 10 problemas en Sistemas de Recomendación                                     |   [slides](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/clases/s12_c2_10bigproblems-recsys-small.pdf)       |  [video](https://drive.google.com/file/d/1DtyzGOfMZY8UE223SMM2ROczH_qHhkNc/view?usp=sharing)        | | -->

### Parte II del curso: seminario

A partir de noviembre el curso toma modalidad seminario, los alumnos hacen presentaciones de los siguientes papers:

<!-- Tick      : &#10003 -->
<!-- Bold tick : &#10004 -->

| Semana  | Paper            | link slide(s) | link video | conferencia |
|:--------|:-----------------|:-------------:|:----------:|:-------------:|
|10       |Towards Question-based Recommender Systems|[slides](https://drive.google.com/file/d/10XYI2tyArpuUwU_kUx4XbwMLuS4ayqxa/view?usp=sharing)|[video](https://drive.google.com/file/d/1P10wU06ISrKbzb7ZG7J_bKVRxOcB-MU4/view?usp=sharing)|[SIGIR 2020](https://arxiv.org/abs/2005.14255)|
|10       |AutoDebias: Learning to Debias for Recommendation|[slides](https://drive.google.com/file/d/16dNsfR8YXzFi99tXOdofEbxF6CA59e_u/view?usp=sharing)|[video](https://drive.google.com/file/d/16dNsfR8YXzFi99tXOdofEbxF6CA59e_u/view?usp=sharing)|[SIGIR 2021](https://arxiv.org/pdf/2105.04170.pdf)|
|10       |An Audit of Misinformation Filter Bubbles on YouTube: Bubble Bursting and Recent Behavior Changes|[slides](https://drive.google.com/file/d/1heKsYaps3kXTVRJ4kNvep-uQT5r-dKcm/view?usp=sharing)|[video](https://drive.google.com/file/d/18KdwYhiJjOMgFKOCBe5F7BELSrVU0-ru/view?usp=sharing)|[RECSYS 2021](https://dl.acm.org/doi/pdf/10.1145/3460231.3474241)|
|10       |Counterfactual Explainable Recommendation|[slides](https://drive.google.com/file/d/1bbf2wGidclixsyh21SlMyR1LYEKOr7AI/view?usp=sharing)|[video](https://drive.google.com/file/d/10IMr4MFXLgzZQsX5Krn_M0wUBrb8qJhg/view?usp=sharing)|[CIKM 2021](https://arxiv.org/abs/2108.10539)|
|11       |A Neural Influence Diffusion Model for Social Recommendation|[slides](https://drive.google.com/file/d/1rakUMbq7lvMgHT0z-v03peZuutz5ZjPt/view?usp=sharing)|[video](https://drive.google.com/file/d/1GK3DbExUMrG_CdSEoldNIrYpSaG1L96h/view?usp=sharing)|[SIGIR 2019](https://dl.acm.org/citation.cfm?id=3331214)|
|11       |An Efficient Adaptive Transfer Neural Network for Social-aware Recommendation|[slides](https://drive.google.com/file/d/14_armbAS3eraJtdl8pYpeiO6i7QRboxh/view?usp=sharing)|[video](https://drive.google.com/file/d/1CYzYkSuxxYlPYiEqyAa02TM6IMzudTlC/view?usp=sharing)|[SIGIR 2019](https://dl.acm.org/doi/10.1145/3331184.3331192)|
|11       |Sequential Recommendation for Cold-start Users with Meta Transitional Learning|[slides](https://drive.google.com/file/d/1Gtl0Wya5ZzqGodNKIIwEZKt04mAfPIQU/view?usp=sharing)|[video](https://drive.google.com/file/d/1Z64bDh-0a3Z38P4LKIRZceoGKxfcddsI/view?usp=sharing)|[SIGIR 2021](http://people.tamu.edu/~jwang713/pubs/MetaTL-sigir2021)|
|11       |“Serving Each User”: Supporting Different Eating Goals Through a Multi-List Recommender Interface|[slides](https://drive.google.com/file/d/1p-xbuH34xfilAmZ9YwSeLdJO1ar_n62O/view?usp=sharing)|[video](https://drive.google.com/file/d/1sVQ2vm_6CCwZXJCkskkPBDrK8aWht79Q/view?usp=sharing)|[RECSYS 2021](https://dl.acm.org/doi/pdf/10.1145/3460231.3474232)|
|11       |Learning disentangled representations for recommendation|[slides](https://drive.google.com/file/d/1JZGVGwzrJ61sT7KK3v_o64EzoyyWg5yY/view?usp=sharing)|[video](https://drive.google.com/file/d/14Q4oD-1sKjfL99EvA72gkwL0dYmrUjT9/view?usp=sharing)|[Neurips 2019](https://dl.acm.org/doi/abs/10.5555/3454287.3454800)|
|12       |Cold Start Similar Artists Ranking with Gravity-Inspired Graph Autoencoders|[slides](https://drive.google.com/file/d/1MoKhaqvM1xFrL786lO1ImabyGZ2i5BpS/view?usp=sharing)|[video](https://drive.google.com/file/d/1HdGrK2g2dgc7gzM6cgclYIFBYD7nKBs-/view?usp=sharing)|[RECSYS 2021](https://arxiv.org/pdf/2108.01053.pdf)|
|12       |A Study of Defensive Methods to Protect Visual Recommendation Against Adversarial Manipulation of Images|[slides](https://drive.google.com/file/d/1z3i3GYMLXzrxDalQMi-QX6tv_GtHZUpF/view?usp=sharing)|[video](https://drive.google.com/file/d/1o6lsiuUyyGb8wu4P9_p8etV0EON7JN93/view?usp=sharing)|[SIGIR 21](https://dl.acm.org/doi/abs/10.1145/3404835.3462848)|
|12       |Reward Constrained Interactive Recommendation with Natural Language Feedback|[slides](https://drive.google.com/file/d/1MMeiiQfnraZXYDBJiONgs5Q0dPWduBo2/view?usp=sharing)|[video](https://drive.google.com/file/d/1kpidqRMutix3GBP49_LRVFLb3_ILL0LF/view?usp=sharing)|[Neurips 2019](https://papers.nips.cc/paper/2019/hash/52130c418d4f02c74f74a5bc1f8020b2-Abstract.html)|
|12       |Neural Attentional Rating Regression with Review-level Explanations|[slides](https://drive.google.com/file/d/1Vf1XvQEet1O7eoC4t2hi_Jha7iWvmnJu/view?usp=sharing)|[video](https://drive.google.com/file/d/1M2pSKx2hQHiPahwEpp3uJ_LZc7H36QAM/view?usp=sharing)|[WWW'18](https://dl.acm.org/doi/10.1145/3178876.3186070)|
|12       |Justifying Recommendations using Distantly-Labeled Reviews and Fine-Grained Aspects|[slides](https://drive.google.com/file/d/1LyMIUACq-_wrXL661BvBArtQ4_pVudsA/view?usp=sharing)|[video](https://drive.google.com/file/d/1jayH4aDRbPnw8_k36agLfgzyisxU5TTd/view?usp=sharing)|[EMNLP-IJCNLP '19](https://cseweb.ucsd.edu/~jmcauley/pdfs/emnlp19a.pdf)|
|12       |Neural Personalized Ranking for Image Recommendation|[slides](https://drive.google.com/file/d/1GZGqHAf7SRxhSVEZ4O3bNAWngGnJnqxJ/view?usp=sharing)|[video](https://drive.google.com/file/d/1dACQJJnTCu2hPzOyqjCuOJY5yiiEe7h6/view?usp=sharing)|[WSDM '18](https://dl.acm.org/doi/10.1145/3159652.3159728)|
|13       |Progressive Layered Extraction (PLE): A Novel Multi-Task Learning (MTL) Model for Personalized Recommendations|[slides](https://drive.google.com/file/d/1kQf0uv-7mAiCESALmCJInBo6__DEac_g/view?usp=sharing)|[video](https://drive.google.com/file/d/1EHz5xNHPixO0-Fp2P1DwM85lQdDldu3o/view?usp=sharing)|[RecSys'20](https://dl.acm.org/doi/10.1145/3383313.3412236)|
|13       |Alleviating Cold-Start Problems in Recommendation through Pseudo-Labelling over Knowledge Graph|[slides](https://drive.google.com/file/d/1HiKyHMkWpd0s2bdedb-BoNE7awRdpEpd/view?usp=sharing)|[video](https://drive.google.com/file/d/1KPx84eReljnuy4yjgtnkf8490UoL4PRb/view?usp=sharing)|[WSDM 2021](https://arxiv.org/abs/2011.05061)|
|13       |Towards Deep Conversational Recommenders|[slides](https://drive.google.com/file/d/1ei9CCwlb73oGGh00xEehq8Vk7H06Ybc6/view?usp=sharing)|[video](https://drive.google.com/file/d/1hT5k2urDP5pHY7rjwB95q89VlahGX56q/view?usp=sharing)|[Neurips'18](https://proceedings.neurips.cc/paper/2018/file/800de15c79c8d840f4e78d3af937d4d4-Paper.pdf)|
|13       |Graph Convolutional Network for Recommendation with Low-pass Collaborative Filters|[slides](https://drive.google.com/file/d/1yqY5D-vgxICvIQ0iIsUNhrsttrzyX4M9/view?usp=sharing)|[video](https://drive.google.com/file/d/1qoOqiqB0MFvijqlgX4V4pWMWt5E4EoK9/view?usp=sharing)|[ICML'20](https://proceedings.icml.cc/static/paper_files/icml/2020/530-Paper.pdf)|
|13       |On Sampled Metrics for Item Recommendation|[slides](https://drive.google.com/file/d/1tfIs8xXJLzkD8XiYKOVPB7rbYlYYi_Z7/view?usp=sharing)|[video](https://drive.google.com/file/d/1JgEyER47enp52cXF8_K4U2UOx85XqSqV/view?usp=sharing)|[KDD'20](https://doi.org/10.1145/3394486.3403226)|
|13       |Pessimistic Reward Models for Off-Policy Learning in Recommendation|[slides](https://drive.google.com/file/d/16A32tcnfy6ho8noaIwW2TBr2QyPbwPjY/view?usp=sharing)|[video](https://drive.google.com/file/d/1G5tsMZcFxqcIj97pwmLWb7CYVFN1fSKr/view?usp=sharing)|[RECSYS 2021](https://dl.acm.org/doi/10.1145/3460231.3474247)|

### Proyectos finales

L@s estudiantes trabajan en grupo sobre proyectos finales de curso, produciendo un poster, paper y repositorio con código para cada uno:

<!-- Imagen de la sesión de posters en gather.town del 15 de diciembre de 2020. 
![iic3633-2020-2-posters](https://user-images.githubusercontent.com/208111/102280274-9a3fe180-3f0b-11eb-80ba-a5975227984a.png)
-->

<!-- Tick      : &#10003 -->
<!-- Bold tick : &#10004 -->

Los siguientes son ejemplos del 2020, se actualizará con información del 2021.
| Grupo | Proyecto             | Poster | Paper | 
|:------|:---------------------|:------:|:-----:|
| 1      | Recomendación a conjuntos de usuarios en grupos heterogeneos <br/> Cartagena, Huerfano, Toscano | [poster](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/posters/N2-cartegana_huerfano_toscano.png)    | [paper](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/proyecto/proy_finales_2020/Cartagena%20et%20al.pdf)    | 
| 2      | Personality bias in music recommendation:Beyond accuracy Objectives <br/> Valencia, Gonzalez | [poster](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/posters/N3-Valencia-Gonz%C3%A1lez.png)    | [paper](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/proyecto/proy_finales_2020/Valencia%20et%20al.pdf)    |
| 3      | Attack learning: a method using GANs  <br/> Castro, Casassus  | [poster](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/posters/N4_castro_casassus.png)    | [paper](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/proyecto/proy_finales_2020/Castro%20et%20al.pdf)    |

<!--
| 4      | Metrica Beyond Accuracy: Personal <br/> Labarca, Fuentes | [poster](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/posters/N5-Labarca_Fuentes.png)    | [paper](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/proyecto/proy_finales_2020/Fuentes%20et%20al.pdf)    |
| 5      | Sequential Recommenders for MeLiDataChallenge 2020 <br/> Aguilera, Everke   | [poster](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/posters/N6-Aguilera_Everke.png)    | [paper](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/proyecto/proy_finales_2020/Everke%20et%20al.pdf)    |
| 6      | Exploración de recomendadores híbridos para música <br/> Suarez, Carreño, Alipanah   | [poster](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/posters/N7-suarez_carreno_alipanah.png)    | [paper](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/proyecto/proy_finales_2020/Alipanah%20et%20al.pdf)    |
| 7      | Impacto del Sesgo de Popularidad en el tiempo, considerando multiples stakeholders <br/> Guiñez, Ruiz, Sanchez   | [poster](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/posters/N8-Guinez_Ruiz_Sanchez.png)    | [paper](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/proyecto/proy_finales_2020/Guinez%20et%20al.pdf)    |
| 8      | Recomendación de items basada en la secuencia de compras: Aplicación DotA <br/> Salinas   | [poster](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/posters/V1-salinas.png)    | [paper](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/proyecto/proy_finales_2020/Salinas%20et%20al.pdf)    |
| 9      | Delay and preference based flight recommendation  <br/> Waugh, Hanuch, Ricke | [poster](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/posters/V2-waugh_hanuch_ricke.jpg)    | [paper](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/proyecto/proy_finales_2020/Hanuch%20et%20al.pdf)    |
| 10      | Changing the way we predict game purchases  <br/> Duarte, Lopez, Rodriguez | [poster](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/posters/V3_duarte_lopez_rodriguez.png)    | [paper](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/proyecto/proy_finales_2020/Duarte%20et%20al.pdf)    |
| 11      | MelAE: A content-based next track recommendation from Mel Sprectrograms  <br/> Diaz, Vinay  | [poster](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/posters/V4-diaz_vinay.png)    | [paper](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/proyecto/proy_finales_2020/Diaz%20et%20al.pdf)    |
| 12      | Optimizing Hyper-parameters un RecSys using rolling averages  <br/> Alliende   | [poster](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/posters/V5-alliende.png)    | [paper](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/proyecto/proy_finales_2020/Alliende.pdf)    |
| 13      | Ramos Perez on MeliChallenge 2020  <br/> Perez, Ramos   | [poster](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/posters/V6_perez_ramos.png)    | [paper](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/proyecto/proy_finales_2020/Ramos%20et%20al.pdf)    |
| 14      | RL Algorithms for video game recsys <br/> Tapia, Villagrán    | [poster](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/posters/V7-tapia_villagran.png)    | [paper](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/proyecto/proy_finales_2020/Tapia%20et%20al.pdf)    |
| 15      | Matrix factorizacion and content-based recsysy for playlist continuation  <br/> Biskupovic   | [poster](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/posters/V8-biskupovic.png)    | [paper](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/proyecto/proy_finales_2020/Biskupovic%20et%20al.pdf)    |
| 16      | Topic Recommendation for Call Centers  <br/> Andrade, Dominguez, Patillo   | [poster](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/posters/A1-andrade_dominguez_pattillo.jpg)    | [paper](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/proyecto/proy_finales_2020/Andrade%20et%20al.pdf)    |
| 17      | Recomendacion a grupos: metrica de similaridad y modelos de agrupacion  <br/> Olguin, Ibarra   | [poster](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/posters/A3-olguin_lopez_ibarra.png)    | [paper](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/proyecto/proy_finales_2020/Olguin%20et%20al.pdf)    |
| 18      | Recommendation of COVID-19 articles using Deep Knowledge-Aware Network <br/> Donoso-Guzmán    | [poster](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/posters/A4_donosoguzman.png)    | [paper](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/proyecto/proy_finales_2020/Donoso%20et%20al.pdf)    |
| 19      | RecGAN as anime recommender systems  <br/> Codoceo, Escudero, Torres   | [poster](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/posters/A5-codoceo_escudero_torres.pptx.png)    | [paper](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/proyecto/proy_finales_2020/Codoceo%20et%20al.pdf)    |
| 20      | Sistema Recomendador de Lecciones Aprendidas en Cursos Capstone  <br/> Contreras, Molina, Stambuk   | [poster](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/posters/A6-Contreras_Molina_Stambuk.png)    | [paper](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/proyecto/proy_finales_2020/Contreras%20et%20al.pdf)    |
| 21      | Finding Similar Users with Recommender Systems  <br/> Ovalle, Valdes   | [poster](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/posters/A7-ovalle_valdes.png)    | [paper](https://github.com/PUC-RecSys-Class/RecSysPUC-2020/blob/master/proyecto/proy_finales_2020/Valdes%20et%20al.pdf)    |
-->

### Planificación y Evaluaciones

**MES 1** En las primeras semanas nos enfocaremos en métodos básicos para hacer recomendación usando y prediciendo ratings (filtrado colaborativo User-based & item-based, slope-one). Luego veremos métodos de factorización matricial para ratings y para feedback implícito. En la 3ra semana veremos formas adicionales de evaluar más alla de la métricas de error de predicción de rating (MAE, MSE, RMSE) e incorporaremos métricas para evaluar listas de ítems (precision, recall, MAP, P@n, nDCG). Veremos métodos basados en contenido y sistemas híbridos.

**MES 2** Métodos basados en contexto, máquinas de factorización y modelos fundamentales de deep learning para recomendación. Recapitulación de las tareas de recomendacion (predecir rating, predecir una lista de items, recomendar una secuencia, recomendación TopN) y de su evaluacion considerando diversidad, novedad, coverage, y otras métricas.

**MES 3** User-centric RecSys, FAT (Fairness, Accountability and Transparency), Aplicaciones de Deep learning para problemas más específicos: recomendación de ropa, multimedia, etc. Modelos profundos generativos para recomendación. Revisaremos problemas de recomendación aún no resueltos en el área.

**MES 4** Principalmente presentaciones de alumnos.

### Código de Honor

Este curso adscribe el Código de Honor establecido por la Escuela de Ingeniería el que es vinculante. Todo trabajo evaluado en este curso debe ser propio. En caso de que exista colaboración permitida con otros estudiantes, el trabajo deberá referenciar y atribuir correctamente dicha contribución a quien corresponda. Como estudiante es su deber conocer la versión en línea del Código de Honor

### Evaluaciones

Detalles de las evaluaciones en [esta presentacion](https://docs.google.com/presentation/d/1cuLgkwgrYTrJc-fuE8mSq0DWYUX82ockdMxCyLAJn6Y/edit#slide=id.g15879d578a_0_66).

**Tarea 1**

Al final de las primeras 4 semanas, las(los) estudiantes implementarán mecanismos de recomendación para predecir ratings y para rankear items en un dataset que se entregará durante clases. Usarán la biblioteca pyreclab para los métodos básicos, pero si quieren optar a la nota máxima debe hacer un sistema híbrido o contextual que utilice información de contenido, como texto o imágenes. Para tener una idea de qué se trata la tarea, pueden revisar el [enunciado de la tarea](https://github.com/PUC-RecSys-Class/RecSysPUC-2021/blob/master/tareas/Tarea_1_RecSys_2021_2.pdf)



**Lecturas: Blog y Presentación**

Fecha de revisión de blogs: El post de la semana x, tiene fecha de entrega el lunes a las 20:00 de la semana x+1. Ejemplo: Las lecturas de la semana 1 (clases el 17 y 19 de agosto) se entregan a más tardar el lunes 23 de agosto de 2021 a las 20:00.

Cada alumno tendrá un repositorio en github (debe indicarlo en [este formulario](https://forms.gle/5L9T1TDy8ZsZqgWh7)) donde escribirá en markdown sus comentarios respecto de los papers indicados como obligatorios. No es necesario hacer un resumen largo del paper, sino indicar un resumen corto, puntos que pueden abrir discusión, mejoras o controversias: Evaluación inadecuada, parámetros importantes no considerados, potenciales mejoras de los algoritmos, fuentes de datos que podían mejorar los resultados, etc.

Adicionalmente, cada alumno presentará al menos una vez durante el semestre un paper sobre un tópico, con el objetivo de abrir una discusión sobre el tema durante la clase.

**Proyecto Final** 

Durante septiembre, las(los) estudiantes enviarán una idea de proyecto final, la cual desarrollarán durante octubre y noviembre. Enviarán un informe de avance a fines de octubre, para hacer una presentación de su proyecto al final del curso en una sesión de posters.

## Planificación general (sujeta a actualización)

(actualizada el 17 de agosto de 2021)

![Planificacion RecSys 2021](https://user-images.githubusercontent.com/37160854/134259748-be5f1ab5-3e1c-4a42-a5d6-b75c4627945c.png)

## Lecturas por Semana

Para descargar los archivos se sugiere buscarlos en [Scholar](https://scholar.google.cl) o a través de [EZProxy](https://login.pucdechile.idm.oclc.org/)

### Semana 1 (entrega el 23 de agosto):  

**Obligatorias**  
* Schafer, J. B., Frankowski, D., Herlocker, J., & Sen, S. (2007). Collaborative filtering recommender systems. In The adaptive web (pp. 291-324). Springer Berlin Heidelberg. [pdf](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.130.4520&rep=rep1&type=pdf)

**Sugeridas**
* Sarwar, B., Karypis, G., Konstan, J., & Riedl, J. (2001). Item-based collaborative filtering recommendation algorithms. In Proceedings of the 10th international conference on World Wide Web (pp. 285-295).
* [Post original FunkSVD](https://sifter.org/~simon/journal/20061211.html)  
* Lemire, D., & Maclachlan, A. (2005). Slope One Predictors for Online Rating-Based Collaborative Filtering. In SDM (Vol. 5, pp. 1-5).
* Kluver, D., Ekstrand, M. D., & Konstan, J. A. (2018). Rating-based collaborative filtering: algorithms and evaluation. Social Information Access, 344-390.

### Semana 2 (entrega el 30 de agosto):

**Obligatorias**  
* Koren, Y., Bell, R., & Volinsky, C. (2009). Matrix factorization techniques for recommender systems. Computer, 42(8), 30-37. [pdf](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.441.3234&rep=rep1&type=pdf)

**Sugeridas**  
* Hu, Y., Koren, Y., & Volinsky, C. (2008). Collaborative filtering for implicit feedback datasets. In Data Mining, 2008. ICDM’08. Eighth IEEE International Conference on (pp. 263-272). IEEE.  
* Takács, G., Pilászy, I., Németh, B., & Tikk, D. (2009). Scalable collaborative filtering approaches for large recommender systems. Journal of machine learning research, 10(Mar), 623-656.  
* Rendle, S., Freudenthaler, C., Gantner, Z., & Schmidt-Thieme, L. (2009). BPR: Bayesian personalized ranking from implicit feedback. In Proceedings of the Twenty-Fifth Conference on Uncertainty in Artificial Intelligence (pp. 452-461). AUAI Press.
* Pan, R., Zhou, Y., Cao, B., Liu, N. N., Lukose, R., Scholz, M., & Yang, Q. (2008). One-class collaborative filtering. In 2008 Eighth IEEE International Conference on Data Mining (pp. 502-511). IEEE. En este artículo aparecen la derivación y reglas de actualización de los parámetros así como las nociones de AMAN y AMAU.
* Jannach, D., Lerche, L., & Zanker, M. (2018). Recommending based on implicit feedback. In Social Information Access (pp. 510-569). Springer, Cham.
* Srebro, N., & Jaakkola, T. (2003). Weighted low-rank approximations. In Proceedings of the 20th International Conference on Machine Learning (ICML-03) (pp. 720-727). Artículo citado por Pan et al. (2008) indicando detalles de la versión no regularizada que inspira OCCF.
* El siguiente paper es opcional, pero permite entender cómo se deriva <a href="https://www.codecogs.com/eqnedit.php?latex=y_i=(X^TC^iX&plus;&space;\lambda&space;I)^{-1}&space;X^TC^ip(i)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?y_i=(X^TC^iX&plus;&space;\lambda&space;I)^{-1}&space;X^TC^ip(i)" title="y_i=(X^TC^iX+ \lambda I)^{-1} X^TC^ip(i)" /></a> e <a href="https://www.codecogs.com/eqnedit.php?latex=x_u=(Y^TC^uY&plus;&space;\lambda&space;I)^1&space;Y^TC^up(u)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?x_u=(Y^TC^uY&plus;&space;\lambda&space;I)^{-1}&space;Y^TC^up(u)" title="x_u=(Y^TC^uY+ \lambda I)^1 Y^TC^up(u)" /></a> del paper de Hu et al.: Takács, G., Pilászy, I., & Tikk, D. (2011). Applications of the conjugate gradient method for implicit feedback collaborative filtering. In Proceedings of the fifth ACM conference on Recommender systems (pp. 297-300). ACM.
* Verstrepen, K., Bhaduriy, K., Cule, B., & Goethals, B. (2017). Collaborative filtering for binary, positiveonly data. ACM Sigkdd Explorations Newsletter, 19(1), 1-21.

### Semana 3 (entrega el 6 de septiembre):

**Obligatorias**  
* Guy, S., & Gunawardana, A.. (2011) “Evaluating recommendation systems.” In Recommender systems handbook, pp. 257-297. Springer US, 2011. [pdf](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.712.4138&rep=rep1&type=pdf)

**Sugeridas**  
* Herlocker, J. L., Konstan, J. A., Terveen, L. G., & Riedl, J. T. (2004). Evaluating collaborative filtering recommender systems. ACM Transactions on Information Systems (TOIS), 22(1), 5-53.  
* Cremonesi, P., Koren, Y., & Turrin, R. (2010). Performance of recommender algorithms on top-n recommendation tasks. In Proceedings of the fourth ACM conference on Recommender systems (pp. 39-46). ACM.  

### Semana 4 (entrega el 13 de septiembre):

**Obligatorias**  
* Pazzani, M. J., & Billsus, D. (2007). Content-based recommendation systems. In The adaptive web (pp. 325-341). Springer Berlin Heidelberg. Xu, W., Liu, X., & Gong, Y. (2003).[pdf](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.448.662&rep=rep1&type=pdf)

**Sugeridas**  
* Document clustering based on non-negative matrix factorization. In Proceedings of the 26th annual international ACM SIGIR conference on Research and development in informaion retrieval (pp. 267-273). ACM.
* Messina, P., Dominguez, V., Parra, D., Trattner, C., & Soto, A. (2019). Content-based artwork recommendation: integrating painting metadata with neural and manually-engineered visual features. User Modeling and User-Adapted Interaction, 29(2), 251-290.
* Celma, Ò., & Herrera, P. (2008). A new approach to evaluating novel recommendations. In Proceedings of the 2008 ACM conference on Recommender systems (pp. 179-186).
* Van den Oord, A., Dieleman, S., & Schrauwen, B. (2013). Deep content-based music recommendation. In Advances in neural information processing systems (pp. 2643-2651).

### Semana 5 (entrega el 20 de septiembre):

**Obligatorias (esta semana se puede elegir una de las dos para entregar*)**  
* Adomavicius, G., Mobasher, B., Ricci, F. and Tuzhilin, A. (2011). Context-Aware Recommender Systems. AI Magazine, 32(3), 67-80. 
* Jahrer, M., Töscher, A. and Legenstein, R. (2010). Combining predictions for accurate recommender systems. In Proceedings of the 16th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, 693-702. ACM.

**Sugeridas**  
* Pigi K., Shobeir F., James F., Magdalini E. and Lise G. (2015). HyPER: A Flexible and Extensible Probabilistic Framework for Hybrid Recommender Systems. In Proceedings of the 9th ACM Conference on Recommender Systems (RecSys '15), 99–106. ACM. 
* Rendle, S. (2010). Factorization machines. In 2010 IEEE International Conference on Data Mining (pp. 995-1000). IEEE.

*No olvidar declarar en la crítica el título elegido.

### Semanas 6 (entrega el 27 de septiembre):

**Obligatorias**
* Hasta la sección 3.4 (incluyendo 3.4): Zhang, S., Yao, L., Sun, A., & Tay, Y. (2019). Deep learning based recommender system: A survey and new perspectives. ACM Computing Surveys (CSUR), 52(1), 1-38.

**Sugeridas**
* Covington, P., Adams, J., & Sargin, E. (2016). Deep neural networks for youtube recommendations. In Proceedings of the 10th ACM conference on recommender systems (pp. 191-198).
* Bansal, T., Belanger, D., & McCallum, A. (2016). Ask the gru: Multi-task learning for deep text recommendations. In Proceedings of the 10th ACM Conference on Recommender Systems (pp. 107-114).

### Semana 7 (entrega el 4 de octubre):

**Obligatorias**
* He, C., Parra, D., & Verbert, K. (2016). Interactive recommender systems: A survey of the state of the art and future research challenges and opportunities. Expert Systems with Applications, 56, 9-27.
 
**Sugeridas**
* Bostandjiev, S., O'Donovan, J., & Höllerer, T. (2012). TasteWeights: a visual interactive hybrid recommender system. In Proceedings of the sixth ACM conference on Recommender systems (pp. 35-42).
* Knijnenburg, B., Bostandjiev, S., O'Donovan, J., and Kobsa, A. (2012). Inspectability and control in social recommenders. RecSys'12 - Proceedings of the 6th ACM Conference on Recommender Systems. 
* Pu, P., Chen, L. and Hu, R. (2011). A user-centric evaluation framework for recommender systems. RecSys'11 - Proceedings of the 5th ACM Conference on Recommender Systems. 157-164.
* Parra, D., Brusilovsky, P., and Trattner, C. (2014). See What You Want to See: Visual User-Driven Approach for Hybrid Recommendation. International Conference on Intelligent User Interfaces, Proceedings IUI.
* Andjelkovic, I., Parra, D., & O’Donovan, J. (2019). Moodplay: Interactive music recommendation based on Artists’ mood similarity. International Journal of Human-Computer Studies, 121, 142-159.


<!-- 

### Semana 9 :

**Obligatorias**
* Cañamares, R., Redondo, M., & Castells, P. (2019). Multi-armed recommender system bandit ensembles. In Proceedings of the 13th ACM Conference on Recommender Systems (pp. 432-436).
* Bendada, W., Salha, G., & Bontempelli, T. (2020). Carousel Personalization in Music Streaming Apps with Contextual Bandits. In Fourteenth ACM Conference on Recommender Systems (pp. 420-425).

**Sugeridas**
* Lacerda, A., Santos, R. L., Veloso, A., & Ziviani, N. (2015). Improving daily deals recommendation using explore-then-exploit strategies. Information Retrieval Journal, 18(2), 95-122.
* Guillou, F., Gaudel, R., & Preux, P. (2016). Scalable explore-exploit collaborative filtering. In Pacific Asia Conference On Information Systems (PACIS). Association For Information System.
* Teo, C. H., Nassif, H., Hill, D., Srinivasan, S., Goodman, M., Mohan, V., & Vishwanathan, S. V. N. (2016). Adaptive, personalized diversity for visual discovery. In Proceedings of the 10th ACM conference on recommender systems (pp. 35-38).

### Semana 10 :

**Obligatorias**
* Hasta la sección 3.4 (incluyendo 3.4): Zhang, S., Yao, L., Sun, A., & Tay, Y. (2019). Deep learning based recommender system: A survey and new perspectives. ACM Computing Surveys (CSUR), 52(1), 1-38.

**Sugeridas**
* Covington, P., Adams, J., & Sargin, E. (2016). Deep neural networks for youtube recommendations. In Proceedings of the 10th ACM conference on recommender systems (pp. 191-198).
* Bansal, T., Belanger, D., & McCallum, A. (2016). Ask the gru: Multi-task learning for deep text recommendations. In Proceedings of the 10th ACM Conference on Recommender Systems (pp. 107-114).

### Semana 11 :

**Obligatorias**

* Desde la sección 3.5 en adelante: Zhang, S., Yao, L., Sun, A., & Tay, Y. (2019). Deep learning based recommender system: A survey and new perspectives. ACM Computing Surveys (CSUR), 52(1), 1-38.

**Sugeridas**
* Chen, J., Zhang, H., He, X., Nie, L., Liu, W., & Chua, T. S. (2017). Attentive collaborative filtering: Multimedia recommendation with item-and component-level attention. In Proceedings of the 40th International ACM SIGIR conference on Research and Development in Information Retrieval (pp. 335-344).
* Liang, D., Krishnan, R. G., Hoffman, M. D., & Jebara, T. (2018). Variational autoencoders for collaborative filtering. In Proceedings of the 2018 World Wide Web Conference (pp. 689-698).
-->
