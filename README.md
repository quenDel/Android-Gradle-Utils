# Some important gradles

**Add for Kotlin support**  
`apply plugin: 'kotlin-kapt'  
kapt { generateStubs = true }`  and use `kapt` place of `annotationProcessor(Java)`  

**Versions**  
``` 
def lifecycle_version = "1.1.1"
supportLibraryVersion = "27.1.1"
daggerVersion = "2.15"
rxJavaVersion = "2.1.0"
rxAndroidVersion = "2.0.1"
timberVersion = "4.5.1"
priorityJobQueueVersion = "2.0.1"
playServicesVersion = "11.6.0"
retrofitVersion = "2.1.0"
okHttpVersion = "3.4.1"
rxRelayVersion = "2.0.0"
rxLintVersion = "1.6
```

**ViewModel and LiveData**  
```  
dataBinding { enabled = true } 
implementation "android.arch.lifecycle:extensions:$lifecycle_version"
annotationProcessor "android.arch.lifecycle:compiler:$lifecycle_version"  
```  
**Android database Room-persistance-library**  
```
implementation "android.arch.persistence.room:runtime:$lifecycle_version"
implementation "android.arch.persistence.room:rxjava2:$lifecycle_version"
annotationProcessor "android.arch.persistence.room:compiler:$lifecycle_version"
```  
