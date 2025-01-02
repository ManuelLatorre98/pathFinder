## Planificador de caminos para robot autonomo
- La planificacion se realiza con el algoritmo A* con una heuristica Manhattan.
- Esta hecho todo con python, use jupyter notes para tener mayor flexibilidad y poder hacer el desarrollo mas incremental.
- Cada casilla representa una ubicacion en el espacio, el vehiculo (ODOR) tiene la capacidad de ubicarse en el espacio detectando codigos QR con una camara.
- Las casillas verdes de riesgo son utilizadas para darle un margen de seguridad al ODOR y que no se choque con paredes u obstaculos, obviamente hay 
  sitaciones donde tiene que pasar por zonas de riesgo y por lo tanto esto se considera como un parametro agregado a la heuristica Manhattan que es la utilizada.
- Las zonas de transicion representan puertas hacia otras zonas del edificio, al cruzarlas se deberia cargar un "nuevo mundo" a partir del cual planificar
- Lo ideal a futuro es definir como objetivo una zona previa a la de transicion, una vez en el objetivo ejecutar un protocolo aparte de reubicacion y salida.


![output2](https://github.com/user-attachments/assets/982f6e38-cc72-4fc6-a83c-76f01fc4274b)
![output](https://github.com/user-attachments/assets/df889ce9-282e-45ee-bf74-dbb19e31333e)
![output4](https://github.com/user-attachments/assets/1963e88e-90fd-4a4f-a413-c3e74cd9bf3e)
![output3](https://github.com/user-attachments/assets/7ecfd380-7233-4ec9-b7da-a814fbadc4a4)
