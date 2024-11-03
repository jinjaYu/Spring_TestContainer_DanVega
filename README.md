# 參考至YT DanVega: spring testContainer
以個人建立CRUD專案後，還需架設資料庫、聯通port設定與匯入資料集...等繁瑣過程，方能開始測試API運作情形。在此提供一快速解決方案，使用spring內建testContainer(docker generating image)實現快速起建，便能與虛擬資料庫溝通，並試做unit test and integration test。

## Danson Placeholder Service - POSTS

This is a service for a project I'm building similar to JsonPlaceholder Service. 

### Getting Started 

To run the project you will need docker desktop running. The `compose.yaml` file is processed by Spring Boot on
startup and automatically runs `docker compose up` for you. 

- There is a test suite in `/src/test/java/`
- There are Swagger Docs at http://localhost:8080/swagger-ui/index.html 
