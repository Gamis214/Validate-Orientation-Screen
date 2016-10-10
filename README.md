# Validate Orientation Screen
Para poder conocer la orientacion de una pantalla dentro de nuestro codigo tenemos que usar lo siguiente:
```java
@Override
public void onConfigurationChanged(Configuration newConfig) {
    super.onConfigurationChanged(newConfig);

    if (newConfig.orientation == Configuration.ORIENTATION_LANDSCAPE) {
        Toast.makeText(this,"Landscape Mode",Toast.SHORT).show
    }
    if (newConfig.orientation == Configuration.ORIENTATION_PORTRAIT) {
        Toast.makeText(this,"Portrait Mode",Toast.SHORT).show
    }
}
```
