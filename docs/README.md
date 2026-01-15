# Cuestiones de análisis 🕵️‍♂️

## 🔗 1. ¿Qué tipo de relación existe entre Agenda y Contacto?
 Agenda y contacto tiene una relación de composición, la agenda está compuesta por un conjunto de contactos. Si desaparece la agenda, contactos ya no tendria sentido.
## 🔗 2. ¿Qué tipo de relación existe entre Contacto y Telefono? 
 Contacto y telefono tiene una relación de agregación, aunque teléfono se use en contacto este si que existe por sí mismo, por eso no es una composición.
## 🔗 3. ¿Qué tipo de relación existe entre Contacto y Direccion? 
 Tienen una asociación, una relación sencilla entre clases, en este caso dentro de la clase contacto el atributo direccion dependera de como construyamos
 el objeto direccion.
## 🤔 4. ¿Por qué los tipos TipoTelefono y TipoVia se modelan como enumerados?
 Porque son los que marcan los estándares en algunos atributos tanto de Teléfono como de Dirección, esto limita los errores al escribirlos, sin importar por ejemplo las mayúsculas. También nos dará más facilidades si queremos cambiar los valores que se     pueden asignar en el futuro.
## 📌 5. ¿Qué relaciones del diagrama son asociaciones simples y cuáles podrían interpretarse como agregación o composición?
 👉 Agenda - Contacto --> Composición
 
 👉 Contacto - Telefono --> Agregación
 
 👉 Contacto - Direccion --> Asociación simple
 
