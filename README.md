# 🛡️ SISTEMA EXPERTO QUE APOYA AL COMERCIO RETAIL EN PROMART HOMECENTER

Proyecto de investigación (Maestría en IA – UNI) para apoyar la venta en el sector retail. 


---

## 👥 Autores

- Andree Ochoa
- Mesias Miranda
- Edwin Turin

---

## 📊 Dataset
- **Fuente**: Promart Homecenter (con fines didácticos)
- **Registros**: 47,462 productos  
- **Variables**: Informacion de producto (Descripcion, Caracteristicas, Recomendaciones, Observaciones, Ficha Tecnica, Producto)
- **Versión usada**: descargada el 15/07/2025  
 
----

## 🗂️ Estructura del repositorio
```
data/
 ├── raw/          # dataset original
 ├── processed/    # dataset limpio y transformado
 ├── test/         # dataset para pruebas semanticas
notebooks/         
 ├── 01_EDA.ipynb               # Análisis exploratorio inicial
 ├── 02_DOWNLOAD_MODEL.ipynb    # Script para la descarga de los modelos a usar de forma offline
 ├── 03_EMBEDING.ipynb          # Proceso de transformacion de los chunks a embedings
 ├── 04_BASELINE.ipynb          # Uso de los modelos con consultas SML
 └── 05_RESULTADOS.ipynb        # Resultados obtenidos del experimento
html/               
 ├── index.html               # Web de prueba de la aplicacion
 └── public                   # Css, Js, Imagenes y otros archivos.
modelos/                # modelos utilizados descargados en local.
logs/                   # archivos de logging y métricas
embeddings/             # Embedings de los chunchs vectorizados
README.md
```

---

## 🚀 Cómo ejecutar el pipeline

Correr de forma ordenada los notebooks desde el 01_EDA al 04_BASELINE

---

## ⚙️ MODELOS UTILIZADOS

- All-MiniLM-L6-v2
- Phi-4-mini-instruct
- SpaCy

----
<img width="990" height="321" alt="Captura de pantalla 2025-09-25 a la(s) 8 25 53 p  m" src="https://github.com/user-attachments/assets/53c518d3-daae-4fde-995b-437ce6789dcf" />


----
<img width="995" height="396" alt="Captura de pantalla 2025-09-25 a la(s) 8 27 41 p  m" src="https://github.com/user-attachments/assets/9a631701-c765-4314-b32b-b66558f9fcab" />


----
<img width="1009" height="402" alt="Captura de pantalla 2025-09-25 a la(s) 8 28 18 p  m" src="https://github.com/user-attachments/assets/0dd7f34f-74f9-4de1-b522-437de2165ad3" />


----
DIAGRAMA DE FLUJO DE CONSULTA AL SISTEMA EXPERTO

<img width="804" height="425" alt="Captura de pantalla 2025-09-25 a la(s) 8 29 01 p  m" src="https://github.com/user-attachments/assets/1cf92262-ac9e-4485-b2b9-7268e7167f8d" />


----
PRUEBA FUNCIONAL DEL SML CON INFORMACION DEL PRODUCTO

<img width="984" height="408" alt="Captura de pantalla 2025-09-25 a la(s) 8 29 27 p  m" src="https://github.com/user-attachments/assets/6bbcdad7-cdd2-423c-9f44-eb173774bf66" />
