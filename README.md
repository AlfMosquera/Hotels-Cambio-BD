# Hotels-Cambio-BD
# Cambio De Base De Datos 
Cambios realizados en el "aplicattion.propierties"
# Antes:
[![imagen-2024-07-01-143425448.png](https://i.postimg.cc/RhwwHF5g/imagen-2024-07-01-143425448.png)](https://postimg.cc/zHXLmqfh)
Como se puede ver, el programa se encuentra conectado a una base de datos H2
# Despúes:
[![imagen-2024-07-01-143827913.png](https://i.postimg.cc/Vkh5z82v/imagen-2024-07-01-143827913.png)](https://postimg.cc/tsh9zLqG)
Se realizaron cambios en el url, el driver, el usuario, el password y el puerto.
Además, a la estructura general del proyecto, se le agregaron las dependencias correspondientes a postgres, como se puede ver a continuación en el archivo "pom.xml"
# Antes:
[![imagen-2024-07-01-145959190.png](https://i.postimg.cc/Zq1cBXvK/imagen-2024-07-01-145959190.png)](https://postimg.cc/R3Lf2sTj)
Se puede observar en el apartado "dependencies" que no se encuentran las dependencias de postgres, tan solo las de H2.
# Despúes:
[![imagen-2024-07-01-150105878.png](https://i.postimg.cc/3NZCqRSd/imagen-2024-07-01-150105878.png)](https://postimg.cc/hQfdzSqB)
Ahora, se puede observar como en el archivo "pom.xml" se muestran las dependecias que corresponden a postgres.
# Con estos cambios el programa puede funcionar en postgres adecuadamente.
