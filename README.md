# Sistema de Gestión Veterinaria

## Descripción General

El **Sistema de Gestión Veterinaria** es una aplicación desarrollada en Python para optimizar la administración de clínicas veterinarias. Permite registrar clientes y mascotas, agendar y gestionar citas, actualizar información y generar reportes.

## Características

- Registro y gestión de clientes y sus mascotas.
- Programación, modificación y cancelación de citas veterinarias.
- Consulta del historial de citas de cada mascota.
- Generación de reportes de clientes y mascotas.

## Requisitos

Para ejecutar el proyecto, necesitas:

- **Python 3.x** instalado.
- Librerías necesarias (pueden instalarse con `pip`).

Instalar dependencias con el siguiente comando:

```bash
pip install -r requirements.txt
```

## Uso

1. Clonar el repositorio:

```bash
git clone <https://github.com/EdinsonHernandez92/Reto2_Sistema_Gestion_Veterinaria>
cd sistema_gestion_veterinaria
```

2. Ejecutar el programa:

```bash
python main.py
```

3. Seguir las instrucciones en la interfaz para gestionar clientes, mascotas y citas.

## Estructura del Proyecto

```
├── main.py            # Archivo principal
├── models/            # Clases y estructuras del sistema
│   ├── cliente.py     # Gestión de clientes
│   ├── mascota.py     # Gestión de mascotas
│   ├── cita.py        # Gestión de citas
├── reports/           # Generación de reportes
├── README.md          # Documentación del proyecto
├── requirements.txt   # Dependencias
```

## Contribución

Si deseas mejorar el sistema, por favor crea un *fork* del repositorio y envía un *pull request* con tus cambios.
