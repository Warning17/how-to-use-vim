# How-to-use-vim 🐧
**Vim es una versión mejorada del editor de texto Vi, presente en los sistemas UNIX. Suele utilizarse mucho al igual que el editor nano, aqui te muestro que no suele ser tan dificil como piensas en comparaciòn con el editor nano** 
![Alt text](https://github.com/Warning17/how-to-use-vim/blob/56b5c32a4d3a27d9bab5cd7fa2cfb77e0b19f9a4/vim.png)


Ejemplo de iniciar un archivo en vim --> **vim archivo.py**.

Tecleamos **I** o la tecla **Insert** para pasar del modo comando al modo edición y comenzar a escribir.

Pulsamos la tecla **ESC** para salir del modo edición y situarnos en el lugar inferior en modo normal, y **:**

    :q → sale del archivo, si no tenemos cambios sin guardar sale sin más.
    :q! → sale del archivo descartando los cambios no guardados.
    :w → Esto guarda lo que estamos haciendo, pero no sale de Vim para seguir editando el archivo.
    :wq,:x,→ guarda los cambios y sale de Vim.
    CTRL+G → Rehacer la última acción
    :A → Poner el cursor al final de la línea
    :earlier 1h → Volvemos el documento a como estaba hace 1 hora
    :later 10m → Ahora avanzamos 30 minutos (a como estaba hace 60-10=50m)
    :set number → Activa la numeración de líneas.
    :set nonumber → Desactiva la numeración de líneas. 
    :g/user: →  filtrar lo que diga user
    Para cortar o copiar debemos mover el cursor hasta cualquier posición de 
    la línea en cuestión y presionar dos veces la tecla d (dd) o y (yy),

    
    
    

