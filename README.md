# Для создания прокта запустить

```
docker build -t vueapp -f Dockerfile-creare-app .
```
```
docker run -itd -v ${PWD}:/app --name vueapp vueapp
```
```
docker exec -it vueapp vue create my-projectp
```
# Если Linux выдать права
```
sudo chown -R $USER:$(id -gn $USER) ./*
```

# Запуск проекта
```
docker-composer up
```

# Для prod версии
```
docker build -t vue-prod -f Dockerfile-build-app .
```
