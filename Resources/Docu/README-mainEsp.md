# UnityEditor-MiniExtension
Mini extension para el editor de Unity3D

Descripcion: Peque�o a�adido para el motor Unity3D,A�adiendole funcionalidad al Editor base.

## Project Setup

1. Necesitas Unity3D free o Pro (Testeado en 4.6.1+)
2. Necesitas la extension de Visual Studio para Unity3D

### Recursos

1. [Visual Studio Tools](https://visualstudiogallery.msdn.microsoft.com/20b80b8c-659b-45ef-96c1-437828fe7cf2)

## Caracteristicas [V. 1.0.18]

> Actuales
> 
> - Limpiar los PlayerPrefs y EditorPrefs
> - Crear una captura de pantalla de la pantalla Escena (Unity3d PRO solo)
> - A�adida una herramienta para el Debug con RayCast
> - A�adido Idiomas diferentes para el editor(Ingles / Espa�ol)
> - A�adido Manager ScriptableObject
> - A�adido About.
> - Mini Localization
> - Archivo Ini
> - Sistema decal

> Futuras
>
> - Console

### Capturas

Limpiar PlayerPrefs y EditorPrefs
![Screenshot software](https://raw.githubusercontent.com/lPinchol/UnityEditor-MiniExtension/master/Resources/Img/ClearEditExt.png "ClearEditExt")

Tomar captura de pantalla
![Screenshot software](https://raw.githubusercontent.com/lPinchol/UnityEditor-MiniExtension/master/Resources/Img/ScreenShotGOExt.png "ScreenShotGOExt")

Crear un Debug RayCast
![Screenshot software](https://raw.githubusercontent.com/lPinchol/UnityEditor-MiniExtension/master/Resources/Img/RayCastDebugExt.png "RayCastDebugExt")

Crear un asset (ScriptableObject)
![Screenshot software](https://raw.githubusercontent.com/lPinchol/UnityEditor-MiniExtension/master/Resources/Img/ScriptableObjectExt.png "ScriptableObjectExt")
Para incorporar una nueva opcion
```csharp
[Serializable]
public class ClassTemplateTest : ScriptableObject 
{

}
```

Usa localization
![Screenshot software](https://raw.githubusercontent.com/lPinchol/UnityEditor-MiniExtension/master/Resources/Img/LocalizationExt.png "LocalizationExt")