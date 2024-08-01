![image](https://github.com/user-attachments/assets/39b904b0-8d3e-4252-8cbe-fb1e9917e7db)
![image](https://github.com/user-attachments/assets/a7eaacd9-4cf7-4587-b33a-8bac231353f6)
![image](https://github.com/user-attachments/assets/8ba14b95-7c77-4aaa-9b69-2836dd5147af)
![image](https://github.com/user-attachments/assets/1c957881-d813-4be0-94c1-e7b129edfc9f)
![image](https://github.com/user-attachments/assets/e8839870-3ccb-4af4-a785-3ba8effa9563)
![image](https://github.com/user-attachments/assets/f747d882-1b86-4355-a536-054b0ca4a416)
![image](https://github.com/user-attachments/assets/bee548fd-422b-460a-82cb-c110f9bfb146)
![image](https://github.com/user-attachments/assets/82776589-2989-4500-bdc2-4e3ff8396ad0)

# CREAR CONTENEDOR CON VOLUME SQL SERVER
```bash
docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=yourStrong#Password" -p 1433:1433 --name sqlserver --mount src=db_sqlServer,dst=/var/opt/mssql -d mcr.microsoft.com/mssql/server:2022-latest
```

![image](https://github.com/user-attachments/assets/60e10aa2-9aaf-4754-a293-9c8cece4031b)
![image](https://github.com/user-attachments/assets/0067c29c-3c4e-487d-8847-4df31fe006f2)
![image](https://github.com/user-attachments/assets/24847476-b54e-475e-b35d-357963436104)
![image](https://github.com/user-attachments/assets/b33b11c7-a197-4a4c-ab62-312af6dac70c)
