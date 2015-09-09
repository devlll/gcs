# gcs
google cloud storage java example, working version, not the official one


Google Platform is awesome, at least the free credit is. :) ,but their official Java example does not work(maven) .





###  login using gcloud SDK on your server or workstation 

```
gcloud auth login
```

In case you are using fish on your server,especially on your compute engine instance ,
keep in mind to update your PATH in your fish config

```
vim .config/fish/config.fish
```

add the following line to your config file, you can adjust the installation directory respectively

```
set -gx PATH  ~/google-cloud-sdk/bin  $PATH
```

  
  
### run the sample code,which is from official repo

```
./gradlew run  -Pargs="procect-id action bucket"
```



