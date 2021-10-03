# ConstraintLayoutTest
 <TextView
        android:id="@+id/input"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginTop="24dp"
        android:gravity="left"
        android:text="input"
        android:textSize="40dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"></TextView>

    <TextView
        android:id="@+id/display"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginTop="32dp"
        android:background="#BBBB99"
        android:gravity="right"
        android:text="0.0"
        android:textSize="40dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/input"></TextView>

    <Button
        android:id="@+id/seven"
        android:layout_width="85dp"
        android:layout_height="35dp"
        android:layout_marginStart="8dp"
        android:layout_marginLeft="8dp"
        android:layout_marginTop="96dp"
        android:text="7"
        app:layout_constraintBottom_toTopOf="@+id/point"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/display"
        app:layout_constraintVertical_bias="0.032" />

    <Button
        android:id="@+id/eifht"
        android:layout_width="85dp"
        android:layout_height="35dp"
        android:text="8"
        app:layout_constraintBottom_toBottomOf="@+id/seven"
        app:layout_constraintEnd_toStartOf="@+id/nine"
        app:layout_constraintStart_toEndOf="@+id/seven"
        app:layout_constraintTop_toTopOf="@+id/seven"
        app:layout_constraintVertical_bias="0.0" />

    <Button
        android:id="@+id/nine"
        android:layout_width="85dp"
        android:layout_height="35dp"
        android:layout_marginEnd="12dp"
        android:layout_marginRight="12dp"
        android:text="9"
        app:layout_constraintBottom_toBottomOf="@+id/eifht"
        app:layout_constraintEnd_toStartOf="@+id/divide"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toEndOf="@+id/seven"
        app:layout_constraintTop_toTopOf="@+id/eifht"
        app:layout_constraintVertical_bias="0.0" />

    <Button
        android:id="@+id/divide"
        android:layout_width="85dp"
        android:layout_height="35dp"
        android:layout_marginStart="204dp"
        android:layout_marginLeft="204dp"
        android:text="/"
        app:layout_constraintBottom_toBottomOf="@+id/nine"
        app:layout_constraintStart_toEndOf="@+id/seven"
        app:layout_constraintTop_toTopOf="@+id/nine"
        app:layout_constraintVertical_bias="0.0" />

    <Button
        android:id="@+id/four"
        android:layout_width="85dp"
        android:layout_height="35dp"
        android:text="4"
        app:layout_constraintBottom_toTopOf="@+id/one"
        app:layout_constraintEnd_toEndOf="@+id/seven"
        app:layout_constraintHorizontal_bias="0.875"
        app:layout_constraintStart_toStartOf="@+id/seven"
        app:layout_constraintTop_toBottomOf="@+id/seven" />

    <Button
        android:id="@+id/one"
        android:layout_width="85dp"
        android:layout_height="35dp"
        android:text="1"
        app:layout_constraintBottom_toTopOf="@+id/point"
        app:layout_constraintEnd_toEndOf="@+id/four"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="@+id/four"
        app:layout_constraintTop_toBottomOf="@+id/seven"
        app:layout_constraintVertical_bias="0.751" />

    <Button
        android:id="@+id/point"
        android:layout_width="85dp"
        android:layout_height="35dp"
        android:layout_marginBottom="48dp"
        android:text="."
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="@+id/one"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="@+id/one" />

    <Button
        android:id="@+id/five"
        android:layout_width="85dp"
        android:layout_height="35dp"
        android:layout_marginStart="87dp"
        android:layout_marginLeft="87dp"
        android:layout_marginTop="68dp"
        android:text="5"
        app:layout_constraintBottom_toBottomOf="@+id/four"
        app:layout_constraintEnd_toEndOf="@+id/eifht"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toStartOf="@+id/eifht"
        app:layout_constraintTop_toTopOf="@+id/four"
        app:layout_constraintVertical_bias="1.0" />

    <Button
        android:id="@+id/six"
        android:layout_width="85dp"
        android:layout_height="35dp"
        android:text="6"
        app:layout_constraintBottom_toBottomOf="@+id/five"
        app:layout_constraintEnd_toEndOf="@+id/nine"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="@+id/nine"
        app:layout_constraintTop_toTopOf="@+id/five"
        app:layout_constraintVertical_bias="1.0" />

    <Button
        android:id="@+id/multipl"
        android:layout_width="85dp"
        android:layout_height="35dp"
        android:text="*"
        app:layout_constraintBottom_toBottomOf="@+id/six"
        app:layout_constraintEnd_toEndOf="@+id/divide"
        app:layout_constraintStart_toStartOf="@+id/divide"
        app:layout_constraintTop_toTopOf="@+id/six" />

    <Button
        android:id="@+id/two"
        android:layout_width="85dp"
        android:layout_height="35dp"
        android:layout_marginStart="4dp"
        android:layout_marginLeft="4dp"
        android:text="8"
        app:layout_constraintBottom_toBottomOf="@+id/one"
        app:layout_constraintEnd_toEndOf="@+id/five"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toStartOf="@+id/five"
        app:layout_constraintTop_toTopOf="@+id/one"
        app:layout_constraintVertical_bias="1.0" />

    <Button
        android:id="@+id/three"
        android:layout_width="85dp"
        android:layout_height="35dp"
        android:text="9"
        app:layout_constraintBottom_toBottomOf="@+id/two"
        app:layout_constraintEnd_toEndOf="@+id/six"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="@+id/six"
        app:layout_constraintTop_toTopOf="@+id/two"
        app:layout_constraintVertical_bias="0.0" />

    <Button
        android:id="@+id/ad"
        android:layout_width="85dp"
        android:layout_height="35dp"
        android:text="+"
        app:layout_constraintBottom_toBottomOf="@+id/three"
        app:layout_constraintEnd_toEndOf="@+id/multipl"
        app:layout_constraintHorizontal_bias="0.741"
        app:layout_constraintStart_toStartOf="@+id/multipl"
        app:layout_constraintTop_toTopOf="@+id/three"
        app:layout_constraintVertical_bias="0.0" />

    <Button
        android:id="@+id/zero"
        android:layout_width="85dp"
        android:layout_height="35dp"
        android:text="0"
        app:layout_constraintBottom_toBottomOf="@+id/point"
        app:layout_constraintEnd_toEndOf="@+id/two"
        app:layout_constraintHorizontal_bias="0.1"
        app:layout_constraintStart_toStartOf="@+id/two"
        app:layout_constraintTop_toTopOf="@+id/point"
        app:layout_constraintVertical_bias="0.0" />

    <Button
        android:id="@+id/equa"
        android:layout_width="85dp"
        android:layout_height="35dp"
        android:text="="
        app:layout_constraintBottom_toBottomOf="@+id/zero"
        app:layout_constraintEnd_toEndOf="@+id/three"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="@+id/three"
        app:layout_constraintTop_toTopOf="@+id/zero"
        app:layout_constraintVertical_bias="0.0" />

    <Button
        android:id="@+id/sybtract"
        android:layout_width="85dp"
        android:layout_height="35dp"
        android:text="-"
        app:layout_constraintBottom_toBottomOf="@+id/equa"
        app:layout_constraintEnd_toEndOf="@+id/ad"
        app:layout_constraintHorizontal_bias="0.583"
        app:layout_constraintStart_toStartOf="@+id/ad"
        app:layout_constraintTop_toTopOf="@+id/equa"
        app:layout_constraintVertical_bias="0.0" />
