# Tienda Pixel

Aplicacion web de catalogo de videojuegos creada con Django. Los datos viven en las vistas y no se usan modelos propios.

## Ejecucion

1. Crea y activa un entorno virtual:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

2. Instala las dependencias:

```powershell
pip install -r requirements.txt
```

3. Ejecuta las migraciones:

```powershell
python manage.py migrate
```

4. Inicia el servidor:

```powershell
python manage.py runserver
```

Abre http://127.0.0.1:8000/ en el navegador.

## Rutas

- `/` muestra todos los juegos del catalogo.
- `/juego/<id>/` muestra el detalle del juego indicado.
