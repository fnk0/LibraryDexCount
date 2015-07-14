# LibraryDexCount

LibraryDexCount is a simple repository to display how many methods the most popular Android libraries have. This can be used as a reference for developers to decide if they want to include a library or not.

All the method counts where extracted using this tool: http://inloop.github.io/apk-method-count/

A empty Android app with the App Compact v7 library has: 14439 methods.

### Android Support Libraries

##### AppCompact v7:22.2.0: 11736 methods

* Dependencies: 
   * support.v4: 7730 methods
   * support.v7: 3986 methods

```groovy
compile 'com.android.support:appcompat-v7:22.2.0'
```

### Google Play Services v7.5.0

Note that most all the Play services share the Base Dependency which by itself is ** 3876 methods ** so
when adding multiple services the amount of methods for each library will drastically reduce. I will eventually update this with disclosure
of the dependencies inside play services as well.

##### Play Services Base: 3876 methods

```groovy
compile 'com.google.android.gms:play-services-base:7.5.0'
```

##### Google Plus: 5144 methods

```groovy
compile 'com.google.android.gms:play-services-plus:7.5.0'
```

##### Play Services Identity: 3987 methods

```groovy
compile 'com.google.android.gms:play-services-identity:7.5.0'
```

##### Play Services App Indexing: 4289 methods

```groovy
compile 'com.google.android.gms:play-services-appindexing:7.5.0'
```

##### Google Maps: 6281 methods

```groovy
compile 'com.google.android.gms:play-services-maps:7.5.0'
```

##### Android Wear: 5452 methods

```groovy
compile 'com.google.android.gms:play-services-wearable:7.5.0'
```

### Common 3rd Party libraries

##### ButterKnife v7.0.1: 203 methods

```groovy
compile 'com.jakewharton:butterknife:7.0.1'
```

##### Okhttp v2.0.0: 2292 methods

* Dependencies:
   * Okhttp: 1578
   * Okio: 381 methods
   * Others: 333 methods

```groovy
compile 'com.squareup.okhttp:okhttp-urlconnection:2.0.0'
compile 'com.squareup.okhttp:okhttp:2.0.0'
```

##### Picasso v2.5.2: 687 methods

* Dependencies
    * Picasso: 536
    * Okhttp: 25 methods
    * Others:126 methods
```groovy
compile 'com.squareup.picasso:picasso:2.5.2'
```

##### Retrofit v1.9.0: 1767 Total methods

* Dependencies:
   * Retrofit: 492 methods
   * Okhttp: 25 methods
   * Gson: 964 Methods
   * Others: 286 methods
   
```groovy
compile 'com.squareup.retrofit:retrofit:1.9.0'
```

##### Okio v1.5.0: 381 methods

```groovy
compile 'com.squareup.okio:okio:1.5.0'
```

##### Otto v1.3.8: 85 methods

```groovy
compile 'com.squareup:otto:1.3.8'```
