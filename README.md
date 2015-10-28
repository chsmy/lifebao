# lifebao
android5.0新特性

<android.support.design.widget.CoordinatorLayout
    android:id="@+id/coordinatorLayout"
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@color/white"
    android:fitsSystemWindows="true"
    android:clipToPadding="true"
    >

    <android.support.design.widget.AppBarLayout
        android:id="@+id/appBarLayout"
        android:layout_width="match_parent"
        android:layout_height="wrap_content">
        <android.support.v7.widget.Toolbar
            android:id="@+id/toolbar"
            android:layout_height="wrap_content"
            android:layout_width="match_parent"
            android:minHeight="?attr/actionBarSize"
            android:background="?attr/colorPrimary"
            app:layout_scrollFlags="scroll|enterAlways"
            />
        <FrameLayout
            android:id="@+id/id_content"
            android:layout_width="fill_parent"
            android:layout_height="0dp"
            android:layout_weight="1"
            ></FrameLayout>
    </android.support.design.widget.AppBarLayout>
    <include layout="@layout/bottom" />
</android.support.design.widget.CoordinatorLayout

recycleview 
