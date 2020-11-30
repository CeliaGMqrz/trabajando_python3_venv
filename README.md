# Crear entornos virtuales con python3 venv
Trabajando con entornos virtuales 

* Instalamos el paquete necesario para instalar módulos:

```powershell
apt-get install python3-venv
```

* Desde el usuario sin privilegios podemos crear un entorno virtual con python3:

```powershell
python3 -m venv entorno
```

* Activar y desactivar el entorno

```powershell
source entorno/bin/activate
(entorno)$ deactivate
```

* Instalar los paquetes de un fichero 'requirements.txt'

```powershell
pip install -r requirements.txt 
```

