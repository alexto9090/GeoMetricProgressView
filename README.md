# GeoMetricProgressView

Customizable progress indicator in the form of 2D geometric shapes 

## Usage

```xml
<net.bohush.geometricprogressview.GeometricProgressView
    android:id="@+id/progressView"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    app:gp_type="triangle"
    app:gp_number_of_angles="7"
    app:gp_color="@android:color/black"
    app:gp_duration="800"
    app:gp_figure_padding="3dp" />
```

## Customize programmatically
```java
GeometricProgressView progressView = (GeometricProgressView) findViewById(R.id.progressView);
progressView.setType(TYPE.KITE);
progressView.setNumberOfAngles(6);
progressView.setColor(Color.parseColor("#00897b"));
progressView.setDuration(1000);
progressView.setFigurePadding(getResources().getDimensionPixelOffset(R.dimen.figure_padding));
```
## Download
Gradle

```javascript
dependencies {
  implementation 'com.github.alexto9090:GeoMetricProgressView:1.0'
}
```
