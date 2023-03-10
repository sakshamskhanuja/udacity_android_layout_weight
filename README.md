## Layout Weight

### About

The application uses ViewGroup Layout Parameters ```layout_weight``` to position and set the size of a child <b>View</b> in ```LinearLayout```.

```xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout...>

    <ImageView
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="1"
        android:contentDescription="@string/beach_description"
        android:scaleType="centerCrop"
        android:src="@drawable/beach" />

    ...
</LinearLayout>
```

### Screenshots

| Device | Virtual | OS | API | Orientation |
| --- | --- | --- | --- | --- |
| Pixel 6 Pro | Yes | Android Q | 29 | [Portrait](https://user-images.githubusercontent.com/122201501/224398660-dc9e705b-43bd-4261-aee5-28afffc51c7f.png) |
| Pixel 6 Pro | Yes | Android Q | 29 | [Landscape](https://user-images.githubusercontent.com/122201501/224398637-de2b4f9a-e1f6-4f69-bc8f-aabced9a9948.png) |
