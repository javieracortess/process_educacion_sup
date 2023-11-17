## Paso1: Redirigete a la carpeta del proyecto

## Paso2: Cree el ambiente virtual
python -m very myenv

## Paso3: Activar el entorno virtual
myenv\Scripts\activate

## Observacion: si esta MacOs o Linux
source myenv/bin/activate

## Paso4: Instala las librerias del archivo requirements.txt
pip install -r requirements.txt

## Paso 5: Luego descargar el csv mas reciente de la siguiente url:
https://datosabiertos.mineduc.cl/titulados-en-educacion-superior/

## Paso 6: ejecutar la aplicacion
python get_excel_resumen_es.py
