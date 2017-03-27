Things to remember
* if you want ellipsize="marquee", use maxLines="1". If maxLines does not work, use deprecated singleLine="true".
```xml
<TextView
            android:id="@+id/name"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:ellipsize="marquee"
            android:maxLines="1"
            android:text=""
            android:textAppearance="@style/TextAppearance.AppCompat.Medium.Inverse"
            android:textColor="@color/md_white_1000"/>
```
