# Chart
- Charting Library

<div align="center">
    <img src="/ss/temp.jpg" width="400px"></img> 
</div>

```xml
  <com.trian.temperature.TemperatureView
            android:id="@+id/v_temp"
            android:layout_width="200dp"
            android:layout_height="400dp"
            android:layout_alignParentLeft="true"
            app:innerColor="@color/temp_low"
            app:outerColor="@color/text_blue"
            app:middleColor="@color/white"
            app:radius="60dp" />
```
- Set Data
```java
ThemperatureView temperatureView = findViewById(R.id.v_temp);
temperatureView.setCurrentTemp(/* data */);
```

# Cara install

- Tambahkan JitPack repository ke build file

```gradle
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
- Tambahkan dependency
```gradle
    dependencies {
	    ...
	    implementation 'com.github.triandamai:chart:1.0.0'
    }
```

# Next
[] WIP



