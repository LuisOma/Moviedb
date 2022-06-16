# Moviedb
Proyecto de demostraci�n con Movie DB, basado en una arquitectura CLEAN con MVVM.

## Funciones de la aplicaci�n

- Los usuarios pueden ver la lista de las �ltimas pel�culas.
- Los usuarios pueden hacer clic en cualquier pel�cula para ver los detalles de la misma.

## Arquitectura de la aplicaci�n
Basado en la arquitectura Clean y el patr�n de repositorio.

## La aplicaci�n incluye los siguientes componentes principales:
- Un servicio de API web.
- Un repositorio que trabaja con el servicio api, proporcionando una interfaz de datos unificada.
- Un ViewModel que proporciona datos espec�ficos para la interfaz de usuario.
- La interfaz de usuario, que muestra una representaci�n visual de los datos en ViewModel.

## Paquetes de aplicaciones
- constants.
- data.
- di.
- ui.
- utils.

## Especificaciones de la aplicaci�n
- SDK m�nimo 21
- Java (en la rama maestra) y Kotlin (en la rama kotlin_support)
- Arquitectura MVVM
- Componentes de la arquitectura de Android (LiveData, ViewModel, componente de navegaci�n, ConstraintLayout)
- **Retrofit 2** para integraci�n API.
- **Gson** para serializaci�n.
- **Glide** para cargar im�genes.
- **ViewModel** para�pasar datos�del modelo a las vistas
- **LiveData**
- **Hilt** para inyecci�n de dependencias.
- **Corutinas**
- **Room** para persistencia de datos
- **Navigation**
