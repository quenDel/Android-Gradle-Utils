# Some important gradles

**Add for Kotlin support**  
`apply plugin: 'kotlin-kapt'` and use `kapt` place of `annotationProcessor(Java)`  

**Versions**  
``` 
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
implementation "android.arch.lifecycle:extensions:$lifecycle_version"
annotationProcessor "android.arch.lifecycle:compiler:$lifecycle_version"  
```

