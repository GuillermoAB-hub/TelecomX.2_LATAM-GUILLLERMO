# TELECOMX_2

Este repositorio contiene un Jupyter Notebook para el proyecto **TELECOMX_2**, enfocado en la extracción, limpieza y análisis de un conjunto de datos de clientes de telecomunicaciones para LATAM.

## Descripción del Proyecto

Los principales objetivos de este notebook son:

- Importar y procesar datos de clientes desde un dataset previamente tratado.
- Eliminar columnas irrelevantes para el análisis.
- Explorar y limpiar los datos.
- Preparar el dataset para análisis o modelado posterior (por ejemplo, predicción de cancelación de clientes).

Los datos se obtienen de un archivo CSV (`datos_tratados.csv`) en este repositorio y se cargan directamente usando pandas.

## Estructura del Notebook

- **Importación de Datos:**  
  Carga el dataset tratado de clientes directamente desde GitHub utilizando pandas.
- **Limpieza de Datos:**  
  Elimina columnas innecesarias (como `ID`) y explora la estructura de los datos.
- **Exploración de Datos:**  
  Revisa tipos de datos, valores nulos y estadísticas básicas.
- **Preparación para Análisis:**  
  Se pueden agregar pasos para limpieza adicional y creación de nuevas variables.

## Columnas del Dataset

- `cancelo` (int): Indica si el cliente canceló el servicio (1) o no (0).
- `genero` (str): Género del cliente.
- `mayor_de_65` (int): Si el cliente es mayor de 65 años.
- `tiene_pareja` (int): Si el cliente tiene pareja.
- `tiene_dependentes` (int): Si el cliente tiene dependientes.
- `meses_de_contrato` (int): Meses de contrato.
- `servicio_telefonico` (str): Si el cliente tiene servicio telefónico.
- `lineas_multiples` (str): Si el cliente tiene múltiples líneas.
- `servicio_internet` (str): Tipo de servicio de internet.
- `seguridad_en_linea` (str): Servicio de seguridad en línea.
- `Soporte_en_linea` (str): Servicio de soporte en línea.
- `proteccion_dispositivos` (str): Servicio de protección de dispositivos.
- `soporte_tecnico` (str): Soporte técnico.
- `servicio_tv` (str): Servicio de TV.
- `servicio_peliculas` (str): Servicio de streaming de películas.
- `tipo_contrato` (str): Tipo de contrato.
- `facturas_electronicas` (int): Si el cliente utiliza facturación electrónica.
- `metodo_pago` (str): Método de pago.
- `gastos_mensuales` (float): Cargos mensuales.
- `gastos_totales` (float): Cargos totales.
- `cuentas_diarias` (float): Cargos diarios.

## ¿Cómo usar?

1. Clona o descarga este repositorio.
2. Abre el notebook `TELECOMX_2.ipynb` en Jupyter o Google Colab.
3. Ejecuta las celdas paso a paso para reproducir el flujo de análisis de datos.

## Requisitos

- Python 3.x
- pandas

Instala las dependencias con:

```bash
pip install pandas
```

## Licencia

Este proyecto es solo para fines educativos.

---

**Autor:** GuillermoAB-hub  
**Datos fuente:** Ver [`datos_tratados.csv`](https://github.com/GuillermoAB-hub/TelecomX.2_LATAM-GUILLLERMO/blob/main/datos_tratados.csv)
