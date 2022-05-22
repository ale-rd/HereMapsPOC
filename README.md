## Configuración del proyecto
Setup de environment para react native:  
 *Con "React Native CLI Quickstart", target Android:*  
https://reactnative.dev/docs/environment-setup

HERE Maps:
1. Hacerse una cuenta en https://developer.here.com/
2. Descargar SDK para android de https://platform.here.com/portal/  
    Inicialmente probamos con *HERE SDK Explore Edition for Android*
3. Generar credenciales como indican en el paso anterior e ingresarlas en el archivo *android/app/src/main/AndroidManifest.xml*
4. Copiar el SDK (heresdk-explore-android-4.11.3.0.8810.aar) dentro de la carpeta *android/app/libs*


Instalar dependencias
> yarn install

Iniciar aplicación
> yarn react-native run-android

*Se ejecuta en el emulador de android studio*


## Módulo para usar SDK de HERE Maps
react-native-heremaps  
https://github.com/Weopt/react-native-here-maps