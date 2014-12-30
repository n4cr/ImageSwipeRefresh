ImageSwipeRefresh
=================

This is the material pull to refresh with an image in the middle 

<img src="http://i.imgur.com/TGkyLj1.gif">

### Usage
Similar to native `SwipeRefreshLayout` insert your `ScrollView` in the component but use `src` to set the image.

``` xml

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
```