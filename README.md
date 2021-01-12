# Bottom Navigation - Android

## Purpose:
The purpose of this code base is to explore the different ways that you can add a Bottom Navigation Bar to an app.

## Implentations:
At the moment, I understand their are two primary ways to implement a TabBarController. One is using the Jetpack Navigation Componenets which will handle the destinations of the user interactions. The other is the more 'traditional' approach using a OnNavigationItemSelectedListener.

### Jetpack

### OnNavigationItemSelectedListener
When implemen


# Move Later:
### Navigation Graph

#### Preview not appearing:

```
  <fragment
        android:id="@+id/homeFragment"
        android:name="com.example.bottomnavigationjetpack.HomeFragment"
        android:label="HomeFragment"
        />
```

Should be:

```
  <fragment
        android:id="@+id/homeFragment"
        android:name="com.example.bottomnavigationjetpack.HomeFragment"
        android:label="HomeFragment"
        tools:layout="@layout/fragment_home"
        />
```
