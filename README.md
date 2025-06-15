# CRM Inteligente – SynAppsSys

Este proyecto tiene como objetivo centralizar, enriquecer y activar de forma inteligente los contactos comerciales utilizando:

- Validación y clasificación de correos electrónicos
- Diagnóstico técnico de dominios
- Enriquecimiento desde LinkedIn (manual-asistido)
- Generación de mensajes estratégicos por proveedor o gap técnico
- Consolidación en base de datos SQLite
- Visualización y gestión desde una app CRM (Streamlit)

## Estructura del proyecto

```
crm_inteligente/
├── app_crm.py
├── fusionador.py
├── normalizador_lusha.py
├── generador_mensajes.py
├── requirements.txt
├── db/crm_inteligente.db
├── data/
├── modules/
└── docs/
```

## Módulos principales

- `normalizador_lusha.py`: limpia y estandariza datos exportados desde Lusha.
- `fusionador.py`: consolida datos técnicos y comerciales en una única base de datos.
- `generador_mensajes.py`: genera mensajes personalizados según proveedor o perfil.
- `app_crm.py`: interfaz visual para filtrar, consultar y activar contactos.

## Repositorio privado

Este repositorio es confidencial y forma parte del portafolio privado de SynAppsSys.
