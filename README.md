# H1_1T_PM_AlejandroRufianCruz

📜 Descripción

Es un juego de tipo clicker inspirado en títulos como Tap Titans y Cookie Clicker. Los jugadores ganan dinero al hacer clics, pueden comprar ítems que aumentan su nivel y consultar un ranking de usuarios.


📌 Características principales:

Sistema de clics: Gana dinero haciendo clics en la pantalla.
Compra de ítems: Mejora tu nivel adquiriendo ítems con el dinero ganado.
Ranking persistente: Consulta la clasificación de los jugadores, almacenada en SharedPreferences.
Navegación básica: Interfaz fluida con tres pantallas principales: inicio, juego y fin de partida.


⚙️ Instalación y ejecución

Requisitos previos:
Android Studio (versión recomendada: 2022.2.1 o superior)
Java (versión 11 o superior)
Emulador Android o dispositivo físico

Pasos para ejecutar:
Clona el repositorio:
git clone https://github.com/usuario/nombre-del-repo.git
Abre el proyecto en Android Studio.
Construye y ejecuta la aplicación en un emulador o dispositivo Android.


🛠️ Estructura del proyecto

📁 com.example.tapsouls
   ├── 📄 MainActivity.java
   ├── 📄 GameActivity.java
   ├── 📄 EndGameActivity.java
   ├── 📁 res/
   │   ├── 📄 activity_main.xml
   │   ├── 📄 activity_game.xml
   │   ├── 📄 activity_end_game.xml
   │   └── 📁 drawable/
   └── 📄 AndroidManifest.xml
   
Clases principales:
MainActivity: Pantalla de inicio del juego.
GameActivity: Lógica principal del juego, gestión de clics, dinero y niveles.
EndGameActivity: Muestra el ranking y los resultados finales.


🎮 Instrucciones de juego

Haz clic en la pantalla para ganar dinero.
Compra ítems para subir de nivel y aumentar tus ganancias.
Consulta el ranking para ver la clasificación de todos los jugadores.
