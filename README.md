# Mongo_Entrega
# Actividad Mongo con Python

## Descripción
Aplicación desarrollada en Python (Google Colab) que realiza
operaciones CRUD sobre una colección de estudiantes usando MongoDB Atlas
y PyMongo.

## ☁️ Interacción con MongoDB Atlas

Se llevó a cabo la configuración mediante la creación de una cuenta en MongoDB Atlas y el uso de un clúster gratuito. El proceso incluyó la gestión de seguridad a través de un usuario con permisos de lectura y la habilitación del acceso de red global (0.0.0.0/0) para facilitar la conexión desde Google Colab. Finalmente, se integró la cadena de conexión mongodb+srv:// en el código utilizando la librería MongoClient, estableciendo la colección Estudiantes para gestión de los datos.

---

## 🧭 Interacción con MongoDB Compass

Para la validación y gestión visual de la información, se integró MongoDB Compass como cliente de escritorio, estableciendo la conexión con el clúster de Atlas. Esta herramienta permitió verificar la persistencia de los documentos en la colección Estudiantes tras ser insertados mediante Python, facilitando además el monitoreo en tiempo real de los cambios, actualizaciones y eliminaciones realizados sobre los datos.

---

