```
docker run -p ${ПОРТ СНАРУЖИ}:${ПОРТ_ВНУТРИ}-v ${ЧЕ_ЗАКИНУТЬ}:${КУДА_ЗАКИНУТЬ}--name=${КАК_НАЗВАТЬ_КОНТЕЙНЕР} openjdk:8 java -jar ${КАКОЙ_ФАЙЛ_ЗАПУСКАТЬ}

docker run -p 8080:8080 -v C:\JavaProjects\my-project\target:/app --name=zdarova2 openjdk:8 java -jar /app/loan-approval-spring-boot-0.0.1-SNAPSHOT.jar
```