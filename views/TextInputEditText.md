Things to remember
* use TextInputLayout as container.
* always use hint, inputType, maxLines and imeOptions for much better ui.

```xml
<android.support.design.widget.TextInputLayout
        android:id="@+id/textInputLayout"
        android:layout_width="200dp"
        android:layout_height="64dp"
        android:layout_marginLeft="16dp"
        android:layout_marginStart="16dp"
        android:layout_marginTop="24dp"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/imageView2">

        <android.support.design.widget.TextInputEditText
            android:id="@+id/orgName"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:hint="@string/name_of_organization"
            android:imeOptions="actionDone"
            android:inputType="text"
            android:maxLines="1"/>
```
