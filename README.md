# practice_2
该代码主要目的是进行安卓的简单布局训练
一下分别为三个布局的代码和运行结果
线性布局：
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
    <android.support.v7.widget.LinearLayoutCompat
        android:layout_width="match_parent"
        android:layout_height="wrap_content">
        <Button

            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="two,one"
            />
        <Button

            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="two,two"
            />
        <Button

            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="two,three"
            />
        <Button

            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="two,four" />

    </android.support.v7.widget.LinearLayoutCompat>
    <android.support.v7.widget.LinearLayoutCompat
        android:layout_width="match_parent"
        android:layout_height="wrap_content">
        <Button

            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="three,one"
            android:textSize="10sp"
            />
        <Button

            android:layout_width="105dp"
            android:layout_height="wrap_content"
            android:text="three,two"
            android:textSize="10sp"
            />
        <Button

            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="three,three"
            android:textSize="10sp"
            />
        <Button

            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="three,four"
            android:textSize="10sp"/>

    </android.support.v7.widget.LinearLayoutCompat>
    <android.support.v7.widget.LinearLayoutCompat
        android:layout_width="match_parent"
        android:layout_height="wrap_content">
        <Button

            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="four,one"
            android:textSize="10sp"
            />
        <Button

            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="four,two"
            android:textSize="10sp"
            />
        <Button

            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="four,three"
            android:textSize="10sp"
            />
        <Button

            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="four,four"
            android:textSize="10sp"/>

    </android.support.v7.widget.LinearLayoutCompat>
	![](https://github.com/songge186/images/blob/master/74a05cc716a39cf10b7e62bcb16a8a7.png?raw=true)
	有限布局：
	<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#000000"
    tools:context=".Main2Activity">

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
</android.support.constraint.ConstraintLayout>
运行截图：
！[]（https://github.com/songge186/images/blob/master/2f4d5f68a6d08542b44ddbe156bd23b.png?raw=true）
表格布局：
<TableLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".Main3Activity">
    <TableRow
        android:id="@+id/row1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="vertical">

        <Button
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:background="#000000"
            android:text=" Open...                                                 Ctrl+O"
            android:textSize="20dp"
            android:gravity="center_vertical"
            android:textAllCaps="false"
            android:textColor="#FFFFFF"

            />
    </TableRow
        >
    <TableRow
        android:id="@+id/row2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="vertical">
        <Button
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:background="#000000"
            android:text=" Save...                                                  Ctrl+S"
            android:textSize="20dp"
            android:gravity="center_vertical"
            android:textAllCaps="false"
            android:textColor="#FFFFFF"/>

    </TableRow>
    <TableRow
        android:id="@+id/row3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="vertical">
        <Button
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:background="#000000"
            android:textSize="20dp"
            android:text=" Save as...                                  Ctrl+Shift+S"
            android:gravity="center_vertical"
            android:textAllCaps="false"
            android:textColor="#FFFFFF"/>

    </TableRow>
    <TableRow
        android:id="@+id/ow4"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="vertical">
        <TextView
            android:layout_width="match_parent"
            android:layout_height="5dp"
            android:background="#FFFFFF"
            />

    </TableRow>
    <TableRow
        android:id="@+id/row5"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="vertical">
        <Button
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:background="#000000"
            android:text="X Import...                                           "
            android:textSize="20dp"
            android:gravity="center_vertical"
            android:textAllCaps="false"
            android:textColor="#FFFFFF"/>

    </TableRow>
    <TableRow
        android:id="@+id/row6"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="vertical">
        <Button
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:background="#000000"
            android:text="X Export...                                            Ctrl+E"
            android:textSize="20dp"
            android:gravity="center_vertical"
            android:textAllCaps="false"
            android:textColor="#FFFFFF"/>

    </TableRow>
    <TableRow
        android:id="@+id/row7"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="vertical">
        <TextView
            android:layout_width="match_parent"
            android:layout_height="5dp"
            android:background="#FFFFFF"
            />

    </TableRow>
    <TableRow
        android:id="@+id/row8"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="vertical">
        <Button
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:background="#000000"
            android:text="Quiet...                                                                    "
            android:textSize="20dp"
            android:gravity="center_vertical"
            android:textAllCaps="false"
            android:textColor="#FFFFFF"/>

    </TableRow>
	运行截图：
	![](https://github.com/songge186/images/blob/master/df2bcb843ea5ab85dcaa1a4293d57ef.png?raw=true)
