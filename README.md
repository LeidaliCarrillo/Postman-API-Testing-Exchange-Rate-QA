![QA](https://img.shields.io/badge/QA-API%20Testing-blue)
![Postman](https://img.shields.io/badge/Postman-API-orange?logo=postman)
![Jira](https://img.shields.io/badge/Jira-Project%20Management-blue?logo=jira)
![Status](https://img.shields.io/badge/Status-Completed-green)
# 🧪 Postman API Testing - Exchange Rate QA

## 📌 Descripción
Proyecto de pruebas API utilizando **:contentReference[oaicite:0]{index=0}** para validar el funcionamiento de la Exchange Rate API mediante casos de prueba positivos y negativos con gestión en **:contentReference[oaicite:1]{index=1}**.

---

## 🌍 API utilizada
- Exchange Rate API  
- https://v6.exchangerate-api.com  
- Proveedor: :contentReference[oaicite:2]{index=2}  

---

## 🛠 Herramientas utilizadas
- Postman → pruebas de API  
- Jira → gestión de casos de prueba  
- GitHub → documentación del proyecto  

---

## 🧪 Casos de prueba

### ✔️ TC-01 - API Key válida (positivo)
- Validar respuesta correcta con API key válida  
- Se espera status 200 y tasas de cambio  
- Resultado: PASS ✔️  

---

### ❌ TC-02 - API Key inválida (negativo)
- Validar manejo de error con API key inválida  
- Se espera error `invalid-key`  
- Resultado: PASS ✔️ (comportamiento correcto del sistema)  

---

## 📸 Evidencias
<img width="971" height="484" alt="image" src="https://github.com/user-attachments/assets/5bb20a2d-5c4a-4157-abd5-464177d3cac0" />

<img width="1277" height="582" alt="Jira1" src="https://github.com/user-attachments/assets/eb5c1774-102a-4879-afc4-86be2dbee2ea" />

<img width="773" height="302" alt="image" src="https://github.com/user-attachments/assets/16c191fc-7e27-478c-b5f3-b7d614abf348" />


---

## 📊 Resultado general
Se validó el correcto funcionamiento de la API en escenarios positivos y negativos, comprobando autenticación, manejo de errores y consistencia de respuestas.

---

## 🚀 Conclusión
La API responde correctamente tanto en casos exitosos como en errores controlados, lo cual confirma su correcto funcionamiento desde una perspectiva de QA.

---

## 👨‍💻 Autor
Proyecto de práctica QA - API Testing con Postman
