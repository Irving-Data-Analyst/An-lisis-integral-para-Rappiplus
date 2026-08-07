Se trabajan con múltiples datasets del negocio:

- **rappiplus_orders_raw.csv** → información de pedidos, precios, descuentos y revenue  
- **rappiplus_catalog.csv** → costos de productos, categorías y proveedores  
- **rappiplus_marketing_spend.csv** → inversión en marketing por canal y país  
- **events / users / user_activity (SQL)** → comportamiento del usuario dentro de la plataforma  
- **experiment_checkout_ui.csv** → resultados de un experimento A/B en el checkout  

El análisis sigue una lógica clara y progresiva:

1. 🔍 Evaluar si podemos confiar en los datos (calidad de datos en Python) 
2. 💰 Analizar si el negocio es rentable (revenue, costos y profit)  
3. 🛒 Entender dónde se pierden los usuarios (funnel de conversión)  
4. 🔁 Evaluar si los usuarios regresan (retención por cohortes)  
5. 🧪 Validar si los cambios generan impacto (test estadístico)  
6. 📊 Comunicar los resultados (dashboard en BI)

A lo largo del proyecto, se transforman datos en insights para responder preguntas clave del negocio y proponer **recomendaciones accionables**.
