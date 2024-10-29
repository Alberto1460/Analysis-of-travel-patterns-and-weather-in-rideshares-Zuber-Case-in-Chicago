# Análisis de patrones de viaje y el impacto del clima en la frecuencia de viajes compartidos: El caso de Zuber en Chicago

## Descripción del proyecto

Este proyecto explora los patrones de viaje y el impacto de las condiciones climáticas en la frecuencia y duración de los viajes compartidos en la ciudad de Chicago. La compañía de transporte compartido **Zuber** desea comprender los factores que influyen en el comportamiento de los pasajeros y optimizar su servicio. En particular, se investigan las preferencias de viaje y cómo el clima afecta la demanda de los servicios de transporte compartido.

### Objetivos

- Identificar patrones en los viajes realizados por los pasajeros de Zuber.
- Evaluar la influencia de factores externos, como el clima, en la demanda y duración de los viajes.
- Probar la hipótesis de que el clima afecta significativamente ciertos viajes en Chicago, especialmente en rutas claves como **Loop** al **Aeropuerto Internacional O'Hare**.

## Dataset

Los datos utilizados en este análisis incluyen información detallada de los viajes en taxi de Chicago, así como las condiciones meteorológicas. Puedes descargar el dataset desde el siguiente enlace:
[Dataset de viajes en taxi de Chicago](https://drive.google.com/drive/folders/1JDKA2hx2wBGkkCsMQDB7AoofKBytFmUC?usp=sharing)

## Estructura del proyecto

- `data/`: Contiene el dataset y archivos auxiliares.
- `notebooks/`: Análisis exploratorio de datos, visualización y pruebas de hipótesis.
- `scripts/`: Código para preprocesamiento, análisis y visualización.
- `results/`: Gráficos, tablas y conclusiones del análisis.
  
## Metodología

1. **Análisis exploratorio de datos**:
   - Identificación de las principales empresas de taxis y barrios de finalización de viajes.
   - Exploración de patrones de viaje por hora y día de la semana.
   
2. **Pruebas de hipótesis**:
   - Prueba t para evaluar el impacto de las lluvias en la duración de los viajes en rutas específicas.

3. **Análisis de resultados**:
   - Impacto del clima en la duración y frecuencia de los viajes.

## Resultados clave

- Se identificaron empresas de taxis líderes y barrios con alta actividad de viajes.
- La duración de los viajes entre el **Loop** y el **Aeropuerto Internacional O'Hare** es significativamente mayor en días lluviosos, especialmente los sábados, confirmando la hipótesis planteada.

## Conclusiones

Este análisis proporciona una base para que Zuber pueda optimizar su servicio considerando factores climáticos y patrones de demanda. La información obtenida es esencial para tomar decisiones informadas que mejoren la eficiencia y la satisfacción del cliente.

## Instalación

1. Clonar este repositorio:
    ```bash
    git clone https://github.com/Alberto1460/Analysis-of-travel-patterns-and-weather-in-rideshares-Zuber-Case-in-Chicago.git
    ```
2. Instalar las dependencias:
    ```bash
    pip install -r requirements.txt
    ```

3. Ejecutar los notebooks o scripts según la estructura mencionada.

## Autor

Este proyecto fue desarrollado por Alberto Abarca.
