# all-android-need

<h1>I don't want to searching anymore </h1>

<p align="center"><img src="https://thumbs.gfycat.com/AnyMessyBison-size_restricted.gif"/></p>
<h2><Maven Repository></h2>
<h2> Retrofit</h2><br>
  <h4> Retrofit2 New version link</h4><br>
  <a href="https://mvnrepository.com/artifact/com.squareup.retrofit2/retrofit"> Retrofit2</a><br>
  <a href="https://mvnrepository.com/artifact/com.squareup.retrofit2/converter-gson"> Converter:Gson</a>
  
```gradle
  dependencies{
  def retrofit2_version = "2.9.0"
  implementation("com.squareup.retrofit2:retrofit:2.9.0")
  implementation("com.squareup.retrofit2:converter-gson:2.9.0")
}
```
<br><br>
<h2> okHttp3</h2><br>
  <h4> okHttp3 New version link</h4><br>
  <a href="https://mvnrepository.com/artifact/com.squareup.okhttp3/okhttp"> okhttp3</a><br>
  <a href="https://mvnrepository.com/artifact/com.squareup.okhttp3/logging-interceptor"> logging-interceptor</a>
  
```gradle
    dependencies {
    def okhttp3_version = "4.9.3"
    implementation("com.squareup.okhttp3:okhttp:$okhttp3_version")
    implementation("com.squareup.okhttp3:logging-interceptor:$okhttp3_version")
    }
```
<br><br>  
<br><br>
<h2> Glide</h2><br>
  <h4> Glide New version link</h4><br>
  
  <a href="https://github.com/bumptech/glide"> Glide</a><br>

  
```gradle
 repositories {
  google()
  mavenCentral()
}

dependencies {
  implementation 'com.github.bumptech.glide:glide:4.13.0'
  annotationProcessor 'com.github.bumptech.glide:compiler:4.13.0'
}
```
<br><br>  
</hr>
<h2> Kotlin Coroutines</h2><br>
  <h4> Kotlin Coroutines version link</h4><br>
  <a href="https://github.com/Kotlin/kotlinx.coroutines"> Coroutines</a><br>
  
 
```gradle
  def coroutines_version ="1.6.0"
  dependencies {
    implementation("org.jetbrains.kotlinx:kotlinx-coroutines-core:$coroutines_version")
}
```
<br><br>
<h2> LiveData</h2><br>
  <h4> LiveData New version link</h4><br>
  <a href="https://mvnrepository.com/artifact/androidx.lifecycle/lifecycle-livedata"> LiveData</a><br>
  
```gradle
    dependencies {
    def livedata_version ="2.4.1"
    runtimeOnly("androidx.lifecycle:lifecycle-livedata:$livedata_version")
    }
```
<br><br>
<h2> LiveCycle</h2><br>
  <h4> LiveCycle New version link</h4><br>
  <a href="https://mvnrepository.com/artifact/androidx.lifecycle/lifecycle-livedata-core"> LiveCycle</a><br>
  
```gradle
    dependencies {
   def lifecycle_version="2.4.1"
    implementation("androidx.lifecycle:lifecycle-viewmodel-ktx:$lifecycle_version")
    }
```
<br><br>
<h2>Navigation</h2><br>
  <h4> LiveCycle New version link</h4><br>
  <a href="https://mvnrepository.com/artifact/androidx.navigation/navigation-fragment-ktx"> Navigation</a><br>
  
```gradle
    def nav_version = "2.4.1"
    implementation("androidx.navigation:navigation-fragment-ktx:$nav_version")
    implementation("androidx.navigation:navigation-ui-ktx:$nav_version")
    implementation "androidx.navigation:navigation-dynamic-features-fragment:$nav_version"
    androidTestImplementation "androidx.navigation:navigation-testing:$nav_version"
    // Jetpack Compose Integration
    implementation "androidx.navigation:navigation-compose:2.5.0-alpha03"
```
<br><br>
<h2>Swiperefreshlayout</h2><br>
  <h4> Swiperefreshlayout New version link</h4><br>
  <a href="https://developer.android.com/jetpack/androidx/releases/swiperefreshlayout?hl=ko"> Swiperefreshlayout</a><br>
  
```gradle
    dependencies {
    implementation("androidx.swiperefreshlayout:swiperefreshlayout:1.1.0")
}
```   
    
