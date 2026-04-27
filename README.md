# Mongo_Entrega
# Actividad Mongo con Python

## Descripción
Aplicación de consola desarrollada en Python (Google Colab) que realiza
operaciones CRUD sobre una colección de estudiantes usando MongoDB Atlas
y PyMongo.

## ☁️ Interacción con MongoDB Atlas

1. Se creó una cuenta en [MongoDB Atlas](https://www.mongodb.com/atlas)
2. Se configuró un cluster gratuito (M0)
3. Se creó un usuario de base de datos con permisos de lectura/escritura
4. Se añadió la IP `0.0.0.0/0` en Network Access para permitir conexiones desde Colab
5. Se obtuvo la cadena de conexión en formato `mongodb+srv://...`
6. Se usó esa cadena en el código con `MongoClient("cadena")`
7. La base de datos creada se llama `BD_CursoMongo` y la colección `Estudiantes`

---

## 🧭 Interacción con MongoDB Compass

1. Se descargó e instaló [MongoDB Compass](https://www.mongodb.com/products/compass)
2. Se pegó la cadena de conexión de Atlas en Compass y se conectó
3. Desde Compass se pudo visualizar la base de datos `BD_CursoMongo`
4. Se verificó que los documentos insertados desde Python aparecieran en la colección `Estudiantes`
5. También se usó Compass para ver los cambios en tiempo real al actualizar o eliminar estudiantes

---

