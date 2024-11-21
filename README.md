<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <Button
        android:id="@+id/button"
        android:layout_width="184dp"
        android:layout_height="81dp"
        android:layout_alignParentBottom="true"
        android:backgroundTint="#990606"
        android:text="Выбрать экскурсию"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.497"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.636" />

    <ImageView
        android:id="@+id/imageView2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="144dp"
        android:layout_marginBottom="129dp"
        app:layout_constraintBottom_toTopOf="@+id/imageButton8"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:srcCompat="@drawable/__no_bg_preview__carve_photos_" />

    <ImageView
        android:id="@+id/imageView8"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginEnd="13dp"
        android:layout_marginBottom="16dp"
        app:layout_constraintBottom_toBottomOf="@+id/imageView9"
        app:layout_constraintEnd_toEndOf="@+id/imageView9"
        app:srcCompat="@drawable/_edited_free__carve_photos_" />

    <ImageView
        android:id="@+id/imageView9"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="43dp"
        android:layout_marginEnd="16dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:srcCompat="@drawable/_edited_free__carve_photos____edited_free__carve_photos_" />

    <ImageButton
        android:id="@+id/imageButton8"
        android:layout_width="94dp"
        android:layout_height="0dp"
        android:layout_marginStart="144dp"
        android:layout_marginBottom="66dp"
        android:backgroundTint="#FDFCFD"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/imageView2"
        app:srcCompat="@drawable/____3" />

</androidx.constraintlayout.widget.ConstraintLayout>
