ImageSwipeRefresh
=================

This is the material pull to refresh with an image in the middle 

<img src="http://i.imgur.com/TGkyLj1.gif">

### Usage
Similar to native `SwipeRefreshLayout` but use `app:src` to set the image

``` xml
    <RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
        xmlns:tools="http://schemas.android.com/tools"
        xmlns:app="http://schemas.android.com/apk/res-auto"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:paddingLeft="@dimen/activity_horizontal_margin"
        android:paddingRight="@dimen/activity_horizontal_margin"
        android:paddingTop="@dimen/activity_vertical_margin"
        android:paddingBottom="@dimen/activity_vertical_margin"
        tools:context=".MainActivity">

        <TextView
            android:text="@string/hello_world"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content" />

        <io.semicolon.imageswiperefresh.ImageSwipeRefresh
            android:id="@+id/swipe_container"
            android:layout_width="match_parent"
            app:src="@drawable/ic_launcher"
            android:layout_height="match_parent">

            <ListView
                android:id="@+id/list"
                android:layout_width="match_parent"
                android:layout_height="match_parent" />

        </io.semicolon.imageswiperefresh.ImageSwipeRefresh>
    </RelativeLayout>
```