# practice_2
该代码主要目的是进行安卓的简单布局训练
一下分别为三个布局的代码和运行结果
线性布局源代码：

    <android.support.v7.widget.LinearLayoutCompat
        android:layout_width="match_parent"
        android:layout_height="wrap_content">
        <Button

            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="one,one"
            />
        <Button

            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="one,two"
            />
        <Button

            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="one,three"
            />
        <Button

            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="one,four" />

    </android.support.v7.widget.LinearLayoutCompat>


运行截图：
![](https://raw.githubusercontent.com/songge186/images/master/74a05cc716a39cf10b7e62bcb16a8a7.png)


有限布局源代码：

<Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="8dp"
        android:layout_marginTop="8dp"
        android:background="@android:color/holo_red_light"
        android:text="red"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <Button
        android:id="@+id/button2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="8dp"
        android:layout_marginTop="8dp"
        android:layout_marginEnd="8dp"
        android:background="@android:color/holo_orange_light"
        android:text="orange"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <Button
        android:id="@+id/button3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="8dp"
        android:layout_marginEnd="8dp"
        android:text="yellow"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <Button
        android:id="@+id/button4"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="8dp"
        android:layout_marginTop="8dp"
        android:layout_marginEnd="8dp"
        android:layout_marginBottom="8dp"
        android:background="@android:color/holo_blue_light"
        android:text="blue"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="@+id/button2" />

    <Button
        android:id="@+id/button5"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="8dp"
        android:layout_marginBottom="8dp"
        android:background="@android:color/holo_green_light"
        android:text="green"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintRight_toLeftOf="@+id/button4"
        android:layout_marginRight="20dp"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.51"
        tools:layout_editor_absoluteX="52dp" />

    <Button
        android:id="@+id/button6"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="8dp"
        android:layout_marginBottom="8dp"
        android:text="indigo"
        android:background="#3232CD"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toRightOf="@+id/button4"
        app:layout_constraintTop_toTopOf="parent"
        android:layout_marginLeft="20dp"
        app:layout_constraintVertical_bias="0.51"
        tools:layout_editor_absoluteX="248dp" />

    <Button
        android:id="@+id/button7"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginBottom="8dp"
        android:text="violet"
        android:background="#871F78"
        app:layout_constraintBottom_toBottomOf="parent"
        tools:layout_editor_absoluteX="2dp" />
