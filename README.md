
# Rapport
1. Började med att klona(fork) repository från LenaSYS.
2. Öppnade mitt eget klonade repository från Android Studio.
3. Öppnar design-vyn för "activity_main.xml". Noterar att texten refererar till "strings.xml". ![](Referens.png)
4. Går in i "strings.xml" och ändrar text till "Prototypen". ![](Strings.png)
```
<resources>
    <string name="app_name">Prototypen</string>
</resources>
```
5. Nu syns i Design-vyn att texten ändrats. ![](Designview.png)
6. I kodvyn står referensen kvar
```
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="@string/app_name"          <--------------- referens står kvar     
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/appBarLayout" />
```

7. Kör appen i min virtuella device och ser att texten är som den ska
8. Sparar samt commit och push.

/Christian F