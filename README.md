# LibraryDexCount

LibraryDexCount is a simple repository to display how many methods the most popular Android libraries have. This can be used as a reference for developers to decide if they want to include a library or not.

All the method counts where extracted using this tool: http://inloop.github.io/apk-method-count/

### Android Support Libraries

##### AppCompact v7:22.2.0: 11736

* Dependencies: 
   * support.v4: 7730
   * support.v7: 3986

```groovy
compile 'com.android.support:appcompat-v7:22.2.0'
```


### Common 3rd Party libraries

##### ButterKnife v7.0.1: 203

```groovy
compile 'com.jakewharton:butterknife:7.0.1'
```

#### Okhttp v2.0.0: 1964

* Dependencies:
   * Okio: 381

```groovy
compile 'com.squareup.okhttp:okhttp-urlconnection:2.0.0'
compile 'com.squareup.okhttp:okhttp:2.0.0'
```

#### Picasso v2.5.2: 536

```groovy
compile 'com.squareup.picasso:picasso:2.5.2'
```

#### Retrofit v1.9.0: 492

* Dependencies:
   * Okhttp: 1964
   
```groovy
compile 'com.squareup.retrofit:retrofit:1.9.0'
```

#### Okio v1.5.0: 381

```groovy
compile 'com.squareup.okio:okio:1.5.0'
```
