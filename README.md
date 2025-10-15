# 🩺 SkinDiseasesRNC

**SkinDiseasesRNC** es un proyecto académico enfocado en la clasificación de imágenes de enfermedades de la piel** mediante el uso de redes neuronales convolucionales (RNC).  
El modelo se entrenó para reconocer **cuatro enfermedades dermatológicas**: **acné, dermatitis atópica, psoriasis y rosácea**.

---

## 🧠 Modelo utilizado
Se empleó la arquitectura **EfficientNetV2-B0**, utilizada con distintas configuraciones

---

## 📊 Resultados obtenidos
El mejor modelo alcanzó una **exactitud del 91%**, mostrando un desempeño equilibrado entre las cuatro clases.

---

## 🧩 Conjunto de datos
Los datos fueron obtenidos de diferentes fuentes públicas, combinadas y limpiadas para formar un único dataset balanceado.  
En total, se utilizaron **3 629 imágenes** distribuidas en dos subconjuntos:

- **Entrenamiento:** 70 %  
- **Prueba:** 30 %
- Durante el entrenamiento, el 20 % de las imágenes del conjunto de entrenamiento se reservó para validación, con el fin de monitorear el rendimiento del modelo.

Datasets utilizados:
- Nayan Chaure – *Acne Dataset* (Kaggle)  
- Haroom Alam – *20 Skin Diseases Dataset* (Kaggle)  
- Riya Eliza Shaju – *Skin Disease Classification Dataset* (Kaggle)  
- Ismail Hossain – *Skin Diseases Image Dataset* (Kaggle)  
- Pallapu Rajkumar – *Psoriasis Skin Dataset* (Kaggle)  
- *DermNet NZ – Rosacea Images*

---

## 👩‍💻 Autores
Proyecto académico desarrollado por:
- **Danny Manquillo**  
- **Mario Morales**
- **Laura Sanchez**  
