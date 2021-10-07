# relative-layout

<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@drawable/images"
    tools:context=".MainActivity">

    <ImageView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:src="@drawable/logo" />

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/signin"
        android:text="Sign in"
        android:textSize="60sp"
        android:textColor="@color/black"
        android:layout_margin="50dp"
        android:gravity="center"
        android:textStyle="bold" />

    <EditText
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/username"
        android:layout_below="@id/signin"
        android:hint="username"
        android:textColorHint="@color/black"
        android:layout_margin="20dp"
        android:textColor="@color/black"
        android:textSize="30sp"
        android:padding="10dp"
        android:drawableLeft="@drawable/ic_baseline_person_24"
        android:drawablePadding="20dp"
        android:autofillHints="" />

    <EditText
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/password"
        android:layout_below="@id/username"
        android:hint="password"
        android:textColorHint="@color/black"
        android:layout_margin="20dp"
        android:textColor="@color/black"
        android:textSize="30sp"
        android:padding="10dp"
        android:drawableLeft="@drawable/ic_info"
        android:drawablePadding="20dp" />

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/password"
        android:layout_centerHorizontal="true"
        android:layout_marginStart="20dp"
        android:layout_marginTop="20dp"
        android:layout_marginEnd="20dp"
        android:layout_marginBottom="20dp"
        android:backgroundTint="@color/cardview_dark_background"
        android:text="@string/log_in" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/forget"
        android:layout_below="@id/button"
        android:text="forgot password"
        android:layout_margin="50dp"
        android:backgroundTint="@color/cardview_dark_background"
        android:layout_centerHorizontal="true"
        android:textSize="30sp"
        android:textColor="@color/black" />


</RelativeLayout>
