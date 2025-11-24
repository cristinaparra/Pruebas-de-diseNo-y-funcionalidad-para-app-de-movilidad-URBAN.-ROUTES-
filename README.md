## 💻 Proyecto: Pruebas de diseño y funcionalidad para app de movilidad | Bootcamp TripleTen (2025)

## 1. Prueba de diseño

**Resultados:**
- Se probó correctamente el estado inicial del formulario.  
- Se validaron las tres tarifas (Daily, Camping, Luxury).  
- Se verificaron elementos clave: licencia de conducir y método de pago.  
- Se probó la funcionalidad del temporizador de 30 segundos.  
- Se comprobó la ventana **"Automóvil reservado"** y los procesos de cancelación.  

**Bugs críticos detectados:**
- El ícono del automóvil seleccionado **no aumenta de tamaño** al hacer clic.  
- Solo se muestran automóviles de la tarifa seleccionada.  
- Problemas en las descripciones de tarifas.  

**Bug crítico faltante por detectar:**
- Los vehículos se muestran solo en una dirección cuando se usa automóvil compartido.

---

## 2. Prueba de funcionalidad del formulario

**Resultados:**

**Campo Número de tarjeta**
- No se agregan espacios automáticamente al perder el foco.  
- El botón permanece inactivo con menos de 12 caracteres.  
- No se permite ingresar más de 12 caracteres.  
- El sistema no valida correctamente caracteres no permitidos.

**Campo CVV/CVC**
- El botón permanece inactivo con menos de 2 caracteres.  
- No se permite ingresar más de 2 caracteres.  
- No se valida correctamente el rango **01–99**.

---

## 3. Prueba de la lógica del botón “Reservar”

**Resultados de los 5 estados probados:**

- **Todos los campos completos →** *Reservar* (Aprobado).  
- **Sin licencia →** *Agregar licencia de conducir y reservar* (No aprobado, bug reportado).  
- **Sin método de pago →** *Agregar método de pago y reservar* (No aprobado, bug reportado).  
- **Sin direcciones →** Botón inhabilitado (No aprobado, bug esperado).  
- **Campos incompletos →** Error en comportamiento (No aprobado, bug reportado).  

---

## 4. Prueba de la funcionalidad de Reservar

**Resultados:**
- Se incluyó el caso principal de reserva exitosa.  
- Se replicaron adecuadamente casos con comportamientos idénticos.  
- Se validaron escenarios con campos faltantes.

---

## 🧩 Habilidades destacadas

- Pruebas de diseño  
- Documentación de errores  
- Validación de flujo y funcionalidad  

---

## 🖥 Herramientas utilizadas

- FIGMA  
- JIRA  
- Herramientas de desarrollo  

---

## 🔗 Documento original  
[(https://docs.google.com/document/d/10MEVSTywR_OvOlDerA6YJ1na1QVgKk2yvkNHHhBee04/edit?usp=sharing)]
