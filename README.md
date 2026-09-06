# Analy's Librería

Proyecto web desarrollado para la práctica de la **Maestría en Ingeniería de Software Avanzada**.

## Información académica

- **Maestrante:** Beto Roberto Ascarrunz Quispe
- **Actividad:** Evaluación práctica, semana 1
- **Tema:** Desarrollo de una página web y uso de Git

## Descripción

Analy's Librería es una interfaz web para gestionar materiales escolares. El proyecto simula el acceso de un usuario a un sistema administrativo con un dashboard y módulos para consultar y registrar productos, ventas y pedidos.

## Funcionalidades

- Página pública de inicio con catálogo y categorías.
- Login simulado con redirección al dashboard.
- Dashboard con resumen de productos, ventas y pedidos.
- Listado de materiales escolares.
- Registro de nuevos productos.
- Listado de ventas realizadas.
- Registro de nuevas ventas.
- Listado de pedidos atendidos, pendientes y cancelados.
- Registro de nuevos pedidos.
- Diseño responsive para pantallas grandes y dispositivos móviles.

## Páginas principales

| Página | Descripción |
| --- | --- |
| `index.html` | Página pública de la librería, catálogo y categorías. |
| `login.html` | Formulario de inicio de sesión simulado. |
| `home.html` | Dashboard principal después del login. |
| `productos.html` | Listado y gestión de materiales escolares. |
| `registro-producto.html` | Formulario para registrar productos. |
| `ventas.html` | Listado de ventas realizadas. |
| `registro-venta.html` | Formulario para registrar ventas. |
| `pedidos.html` | Listado de pedidos atendidos y pendientes. |
| `registro-pedido.html` | Formulario para registrar pedidos. |

## Flujo de navegación

```text
index.html
    └── login.html
	    └── home.html
		    ├── productos.html
		    │     └── registro-producto.html
		    ├── ventas.html
		    │     └── registro-venta.html
		    └── pedidos.html
			    └── registro-pedido.html
```

## Tecnologías utilizadas

- HTML5
- CSS3
- Git y GitHub

## Estructura del proyecto

```text
libreria/
├── index.html
├── login.html
├── home.html
├── productos.html
├── registro-producto.html
├── ventas.html
├── registro-venta.html
├── pedidos.html
├── registro-pedido.html
├── styles.css
└── README.md
```

## Ejecución local

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/betoascarrunz/libreria.git
   ```

2. Abrir la carpeta del proyecto en Visual Studio Code.

3. Abrir `index.html` directamente en el navegador o utilizar una extensión como **Live Server**.
