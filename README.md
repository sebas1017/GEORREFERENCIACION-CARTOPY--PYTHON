Durante este proyecto de analitica ,utilizo un conjunto de datos en formato csv proporcionado por el DANE este archivo es publico desde la fuente de datos del DANE
se hizo un limpiado previo al csv eliminando las filas que tuvieran datos faltantes, luego de esto se requiere realizar un analisis sobre estos datos para dar respuesta
al problema propuesto en el archivo "Planteamiento problema" para dar respuesta a ciertas cuestiones
 
 ![alt text](https://github.com/sebas1017/GEORREFERENCIACION-CARTOPY--PYTHON/blob/main/Planteamiento_problema.png?raw=true)
 
 
Se realizo el analisis utilizando jupyter , y la libreria cartopy de python espcialmente diseñada para el analisis y trazado de mapas 
se debe contar con las siguientes librerias instaladas para llevar a cabo la ejecucion del notebook correctamente:



# cartopy
conda install -c conda-forge cartopy
si desea ejecutar este comando desde el shell de conda o si desea hacerlo desde anaconda navigator tambien es valido

#mathplotlip
python -m pip install -U matplotlib


al final del analisis podra tener un menu donde puede escoger la feature(Caracteristica) mediante la cual podra cambiar la proporcionalidad 
de los circulos graficados en el mapa , estos son proporcionales al valor del dato de la caracteristica escogida proveniente del csv
 
 
 preview del analisis geografico
 
 ![alt text](https://github.com/sebas1017/GEORREFERENCIACION-CARTOPY--PYTHON/blob/main/preview_analisisgeografico.png?raw=true)



