# Código Node-RED para TFM

Este repositorio contiene los **flows de Node-RED** desarrollados para el TFM, organizados en cuatro archivos `.json`. Cada archivo corresponde a un conjunto de flujos específicos que permiten la comunicación con PLCs, gestión de datos y visualización en dashboard.

---

## Archivos incluidos

1. **PLC1.json**  
   - Comunicación OPC UA con el **PLC de la Planta 1**.  
   - Dashboard para interactuar con la Planta 1.  

2. **PLC2.json**  
   - Comunicación OPC UA con el **PLC de la Planta 2**.  
   - Dashboard para interactuar con la Planta 2.  

3. **Global.json**  
   - Dashboard general.  
   - Genera y registra datos en **InfluxDB**.  

4. **Data.json**  
   - Consulta de histórico de datos.  
   - Visualización de datos en dashboards.  

---

## Cómo importar los flows en Node-RED

1. Abrir Node-RED.  
2. Hacer clic en el **menú de la esquina superior derecha → Import → Clipboard**.  
3. Copiar el contenido de cada archivo `.json` **uno por uno** en Node-RED.  
4. Guardar los flows importados.  

---

> Nota: Cada flow corresponde a un módulo independiente que puede funcionar de manera autónoma o combinada según la arquitectura del TFM.
