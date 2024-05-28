# Control de Gastos con React, TypeScript, useReducer y Context API

Este proyecto es una aplicación de control de gastos desarrollada con las siguientes tecnologías y herramientas:

- **React con Vite**: Utilizado para la construcción rápida y eficiente de la aplicación.
- **TypeScript**: Proporciona un sistema de tipos estáticos que mejora la calidad del código y la facilidad de mantenimiento.
- **Tailwind CSS**: Un framework de CSS utilitario para diseñar interfaces de usuario de manera rápida y personalizable.
- **useReducer**: Un hook de React que se utiliza para manejar el estado complejo de la aplicación de forma más estructurada y predecible.
- **Context API**: Proporciona un mecanismo para pasar datos a través del árbol de componentes sin tener que pasar props manualmente en cada nivel.

## Características del Proyecto

1. **Gestión Eficiente del Estado**:
   - Se utiliza `useReducer` para manejar el estado de la aplicación de manera centralizada. Esto permite gestionar de forma clara y predecible las acciones y los cambios de estado relacionados con los gastos.
   - La combinación con TypeScript asegura que las acciones y el estado estén bien tipados, reduciendo errores y mejorando la autocompletación en los entornos de desarrollo.

2. **Compartición de Estado Global**:
   - La Context API se utiliza para proporcionar el estado global y las funciones despachadoras a todos los componentes que lo necesiten. Esto elimina la necesidad de pasar props innecesarias y simplifica la gestión del estado en componentes anidados.

3. **Interfaz de Usuario Atractiva y Responsiva**:
   - Tailwind CSS permite construir una interfaz de usuario moderna y responsiva de manera rápida, con utilidades que facilitan el diseño adaptativo y el estilo personalizado.
   - El uso de clases de Tailwind CSS en JSX permite un desarrollo más rápido y coherente de la interfaz.

4. **Configuración Rápida y Eficiente**:
   - Vite proporciona una configuración rápida y optimizada para el desarrollo de aplicaciones React, permitiendo tiempos de inicio rápidos y recarga en caliente (hot module replacement).

## Funcionalidades Principales

- **Añadir Gastos**: Permite a los usuarios añadir nuevos gastos con detalles como la descripción, el monto y la fecha.
- **Listar Gastos**: Muestra una lista de todos los gastos registrados, con opciones para filtrarlos o categorizarlos.
- **Eliminar Gastos**: Los usuarios pueden eliminar gastos específicos de la lista.
- **Resumen de Gastos**: Proporciona un resumen de los gastos totales y las estadísticas relevantes.

## Beneficios del Enfoque Usado

- **Mantenibilidad**: El uso de TypeScript y `useReducer` mejora la mantenibilidad del código, permitiendo una clara separación de las acciones y el estado.
- **Escalabilidad**: La Context API permite una escalabilidad fácil del estado global, haciendo que la aplicación pueda crecer sin complicaciones significativas en la gestión del estado.
- **Desarrollo Rápido**: Tailwind CSS y Vite aceleran significativamente el desarrollo, proporcionando herramientas y configuraciones optimizadas para una experiencia de desarrollo fluida.

## Conclusión

Este proyecto de Control de Gastos demuestra cómo una combinación de tecnologías modernas puede crear una aplicación robusta, eficiente y fácil de mantener. La integración de React con Vite, TypeScript, Tailwind CSS, `useReducer` y Context API proporciona una base sólida para desarrollar aplicaciones web complejas con una gestión de estado y una interfaz de usuario efectivas.


## Demo

Puedes ver una demostración del proyecto [aquí](https://control-de-gastos-react-jsb.netlify.app/).
