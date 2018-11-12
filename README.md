# Some important gradles

**Add for Kotlin support**  
`apply plugin: 'kotlin-kapt'` and use `kapt` place of `annotationProcessor(Java)`  

**ViewModel and LiveData**  
```  
implementation "android.arch.lifecycle:extensions:$lifecycle_version"
annotationProcessor "android.arch.lifecycle:compiler:$lifecycle_version"  
```

