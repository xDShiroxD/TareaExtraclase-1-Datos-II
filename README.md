# TareaExtraclase-1-Datos-II
Primero se debe de correr el generator.cpp, este se corre desde la terminal con el siguiente comando ./generator -size SIZE -output OUTPUTH
Donde SIZE puede ser SMALL, MEDIUM o LARGE, y OUTPUTH es la ruta en donde se quiere crear el archivo
Luego se debe de correr el Sorter.cpp, este se corre desde la terminal con el comando ./sorter -input INPUT -output OUTPUTH -alg ALG
Donde INPUT es la ruta donde esta el archivo binario (Esta debe de ser igual al OUTPUTH de generator), OUTPUTH es la la ruta en donde se quiere crear el archivo con los enteros ordenados y ALG es el algoritmo que se desea usar para ordenar los enteros, las opciones serian IS, QS, BS para usar InsertionSort, QuickSort y BubbleSort respectivamente 

Notas:
Los archivos binarios quedaron con los tamanos de 1kb para SMALL, 512kb para MEDIUM y 1mb para LARGE, esto debido a que los metodos de ordenamiento duraban demasiado tiempo ordenando para los tamanos solicitados, entonces para poder demostrar el funcionamiento del programa sorter se necesito reducir el tamano de esa manera
No olvidar copilar los programas antes de iniciar para evitar posibles problemas
