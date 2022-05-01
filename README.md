### Primera practica con virtualenv

esta es una practica inicial con virtualenv

Para llamar la consola interactiva de python (IDLE) usando un entorno virtual, se realiza por medio del flag -m, el cual indica que se va a cargar un modulo adicional.  En este caso el modulo es venv, el cual permite cargarla con un entorno virtual separado.

`
python3 -m venv venv
`

El anterior comando intala el modulo venv en el directorio de trabajo, creando una directorio llamado venv dentro del cual se almacenara todo lo que se requiera para la correcta operatividad del entorno virtual.

Este comando solamente crea el entorno virtual, pero no lo activa.  Para activarlo, se ejecuta el siguiente comando:

`
source venv/bin/activate
`

Nota: el comando anterior solo aplica en entornos tipo unix (Mac y Linux).  En windows el comando es distinto.
