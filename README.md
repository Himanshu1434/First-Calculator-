<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:background="#2A2424"
    android:id="@+id/main"

    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:id="@+id/solution_tv"
        android:textSize="40sp"
        android:textAlignment="textEnd"
        android:textColor="@color/black"
        android:layout_above="@id/result_tv"
        android:background="#DBD0D0"
        android:layout_margin="16dp"
        tools:ignore="HardcodedText" />


    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/result_tv"
        android:textSize="64sp"
        android:textAlignment="textEnd"
        android:textColor="@color/black"
        android:background="#DBD0D0"
        android:layout_above="@id/buttons_layout"
        android:layout_margin="16dp"
        tools:ignore="HardcodedText" />


    <LinearLayout
        android:id="@+id/buttons_layout"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:background="#262424"
        android:orientation="vertical"
        android:paddingVertical="16dp">


        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:gravity="center"
            android:orientation="horizontal">


            <com.google.android.material.button.MaterialButton
                android:id="@+id/button_c"
                style="@style/ShapeAppearanceOverlay.Material3.FloatingActionButton"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_margin="12dp"
                android:backgroundTint="#BCEF2929"
                android:text="c"
                android:textColor="@color/white"
                android:textSize="32sp"
                app:cornerRadius="36dp"
                tools:ignore="HardcodedText" />

            <com.google.android.material.button.MaterialButton
                android:id="@+id/button_open_bracket"
                style="@style/ShapeAppearanceOverlay.Material3.FloatingActionButton"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_margin="12dp"
                android:backgroundTint="#A1A1A1"
                android:text="("
                android:textColor="@color/white"
                android:textSize="32sp"
                app:cornerRadius="36dp"
                tools:ignore="HardcodedText" />

            <com.google.android.material.button.MaterialButton
                android:id="@+id/button_closed_bracket"
                style="@style/ShapeAppearanceOverlay.Material3.FloatingActionButton"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_margin="12dp"
                android:backgroundTint="#A1A1A1"
                android:text=")"
                android:textColor="@color/white"
                android:textSize="32sp"
                app:cornerRadius="36dp"
                tools:ignore="HardcodedText" />

            <com.google.android.material.button.MaterialButton
                android:id="@+id/button_divide"
                style="@style/ShapeAppearanceOverlay.Material3.FloatingActionButton"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_margin="12dp"
                android:backgroundTint="#ADFF5722"
                android:text="/"
                android:textColor="@color/black"
                android:textSize="32sp"
                app:cornerRadius="36dp"
                tools:ignore="HardcodedText" />


        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:gravity="center"
            android:orientation="horizontal">


            <com.google.android.material.button.MaterialButton
                android:id="@+id/button_Seven"
                style="@style/ShapeAppearanceOverlay.Material3.FloatingActionButton"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_margin="12dp"
                android:backgroundTint="@color/black"
                android:text="7"
                android:textColor="@color/white"
                android:textSize="32sp"
                app:cornerRadius="36dp"
                tools:ignore="HardcodedText" />

            <com.google.android.material.button.MaterialButton
                android:id="@+id/button_Eight"
                style="@style/ShapeAppearanceOverlay.Material3.FloatingActionButton"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_margin="12dp"
                android:backgroundTint="@color/black"
                android:text="8"
                android:textColor="@color/white"
                android:textSize="32sp"
                app:cornerRadius="36dp"
                tools:ignore="HardcodedText" />

            <com.google.android.material.button.MaterialButton
                android:id="@+id/button_Nine"
                style="@style/ShapeAppearanceOverlay.Material3.FloatingActionButton"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_margin="12dp"
                android:backgroundTint="@color/black"
                android:text="9"
                android:textColor="@color/white"
                android:textSize="32sp"
                app:cornerRadius="36dp"
                tools:ignore="HardcodedText" />

            <com.google.android.material.button.MaterialButton
                android:id="@+id/button_Multiply"
                style="@style/ShapeAppearanceOverlay.Material3.FloatingActionButton"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_margin="12dp"
                android:backgroundTint="#ADFF5722"
                android:text="*"
                android:textColor="@color/black"
                android:textSize="32sp"
                app:cornerRadius="36dp"
                tools:ignore="HardcodedText" />


        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:gravity="center"
            android:orientation="horizontal">


            <com.google.android.material.button.MaterialButton
                android:id="@+id/button_Four"
                style="@style/ShapeAppearanceOverlay.Material3.FloatingActionButton"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_margin="12dp"
                android:backgroundTint="@color/black"
                android:text="4"
                android:textColor="@color/white"
                android:textSize="32sp"
                app:cornerRadius="36dp"
                tools:ignore="HardcodedText" />

            <com.google.android.material.button.MaterialButton
                android:id="@+id/button_Five"
                style="@style/ShapeAppearanceOverlay.Material3.FloatingActionButton"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_margin="12dp"
                android:backgroundTint="@color/black"
                android:text="5"
                android:textColor="@color/white"
                android:textSize="32sp"
                app:cornerRadius="36dp"
                tools:ignore="HardcodedText" />

            <com.google.android.material.button.MaterialButton
                android:id="@+id/button_Six"
                style="@style/ShapeAppearanceOverlay.Material3.FloatingActionButton"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_margin="12dp"
                android:backgroundTint="@color/black"
                android:text="6"
                android:textColor="@color/white"
                android:textSize="32sp"
                app:cornerRadius="36dp"
                tools:ignore="HardcodedText" />

            <com.google.android.material.button.MaterialButton
                android:id="@+id/button_Plus"
                style="@style/ShapeAppearanceOverlay.Material3.FloatingActionButton"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_margin="12dp"
                android:backgroundTint="#ADFF5722"
                android:text="+"
                android:textColor="@color/black"
                android:textSize="32sp"
                app:cornerRadius="36dp"
                tools:ignore="HardcodedText" />


        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:gravity="center"
            android:orientation="horizontal">


            <com.google.android.material.button.MaterialButton
                android:id="@+id/button_One"
                style="@style/ShapeAppearanceOverlay.Material3.FloatingActionButton"
                android:layout_width="wrap_content"
                android:layout_height="72dp"
                android:layout_margin="12dp"
                android:backgroundTint="@color/black"
                android:text="1"
                android:textColor="@color/white"
                android:textSize="32sp"
                app:cornerRadius="36dp"
                tools:ignore="HardcodedText" />

            <com.google.android.material.button.MaterialButton
                android:id="@+id/button_Two"
                style="@style/ShapeAppearanceOverlay.Material3.FloatingActionButton"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_margin="12dp"
                android:backgroundTint="@color/black"
                android:text="2"
                android:textColor="@color/white"
                android:textSize="32sp"
                app:cornerRadius="36dp"
                tools:ignore="HardcodedText" />

            <com.google.android.material.button.MaterialButton
                android:id="@+id/button_Three"
                style="@style/ShapeAppearanceOverlay.Material3.FloatingActionButton"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_margin="12dp"
                android:backgroundTint="@color/black"
                android:text="3"
                android:textColor="@color/white"
                android:textSize="32sp"
                app:cornerRadius="36dp"
                tools:ignore="HardcodedText" />

            <com.google.android.material.button.MaterialButton
                android:id="@+id/button_Minus"
                style="@style/ShapeAppearanceOverlay.Material3.FloatingActionButton"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_margin="12dp"
                android:backgroundTint="#ADFF5722"
                android:text="-"
                android:textColor="@color/black"
                android:textSize="32sp"
                app:cornerRadius="36dp"
                tools:ignore="HardcodedText" />


        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:gravity="center"
            android:orientation="horizontal">


            <com.google.android.material.button.MaterialButton
                android:id="@+id/button_ac"
                style="@style/ShapeAppearanceOverlay.Material3.FloatingActionButton"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_margin="12dp"
                android:backgroundTint="#BCEF2929"
                android:text="AC"
                android:textColor="@color/white"
                android:textSize="16sp"
                app:cornerRadius="36dp"
                tools:ignore="HardcodedText" />

            <com.google.android.material.button.MaterialButton
                android:id="@+id/button_Zero"
                style="@style/ShapeAppearanceOverlay.Material3.FloatingActionButton"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_margin="12dp"
                android:backgroundTint="@color/black"
                android:text="0"
                android:textColor="@color/white"
                android:textSize="32sp"
                app:cornerRadius="36dp"
                tools:ignore="HardcodedText" />

            <com.google.android.material.button.MaterialButton
                android:id="@+id/button_Dot"
                style="@style/ShapeAppearanceOverlay.Material3.FloatingActionButton"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_margin="12dp"
                android:backgroundTint="@color/black"
                android:text="."
                android:textColor="@color/white"
                android:textSize="32sp"
                app:cornerRadius="36dp"
                tools:ignore="HardcodedText" />

            <com.google.android.material.button.MaterialButton
                android:id="@+id/button_Equals"
                style="@style/ShapeAppearanceOverlay.Material3.FloatingActionButton"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_margin="12dp"
                android:backgroundTint="#ADFF5722"
                android:text="="
                android:textColor="@color/black"
                android:textSize="32sp"
                app:cornerRadius="36dp"
                tools:ignore="HardcodedText" />


        </LinearLayout>
    </LinearLayout>






</RelativeLayout>
