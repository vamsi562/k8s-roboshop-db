```
    for i in mongodb mysql redis rabbitmq catalogue user cart shipping payment frontend; 
    do
        kubectl apply -f "$i/manifest.yaml"
    done
```
```
    for i in mongodb mysql redis rabbitmq catalogue user cart shipping payment frontend; 
    do
        kubectl delete -f "$i/manifest.yaml"
    done
```