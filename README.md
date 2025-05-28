# Mi App Personal - Flutter

Aplicación Flutter con 3 pantallas estáticas para práctica de widgets básicos.

## Archivos Creados

```
lib/
├── main.dart                 # Archivo principal
├── pantalla_inicio.dart      # Pantalla de bienvenida
├── pantalla_perfil.dart      # Pantalla de perfil personal  
└── pantalla_hobbies.dart     # Pantalla de hobbies
```

## Descripción de Archivos

### `main.dart`
- Configuración principal de la app
- Importa las 3 pantallas
- Define qué pantalla mostrar en línea 17

### `pantalla_inicio.dart`
- AppBar con título "Bienvenido"
- Texto de bienvenida
- Botón "Ver mi perfil" (sin funcionalidad)
- Colores azules

### `pantalla_perfil.dart`
- Imagen de perfil circular
- Información personal (nombre, carrera, descripción)
- Datos de contacto (email, teléfono, ubicación)
- Colores verdes

### `pantalla_hobbies.dart`
- Lista de 4 hobbies con íconos
- Descripción de cada hobby
- Actividades adicionales
- Colores morados

## Widgets Utilizados
- Scaffold, AppBar, Text, Image, Column, Row
- Container, Padding, SizedBox, ElevatedButton, Icon

## Cómo Probar las Pantallas

Cambiar la línea 17 en `main.dart`:

```dart
home: PantallaInicio(),    // Para pantalla de inicio
home: PantallaPerfil(),    // Para pantalla de perfil
home: PantallaHobbies(),   // Para pantalla de hobbies
```

Después presionar 'r' para Hot Reload.

## Autor
Jerson - Arequipa, Perú
