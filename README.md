## To setup the application
- Clone the repository:

```
git clone https://github.com/sainiaditya1/sample-fullstack-application.git
cd sample-fullstack-application

```
- Create a .env file
 ```
 DATABASE_URL=postgresql://username:password@host:port/database
REDIS_URL=redis://username:password@host:port
POSTGRES_DB=your_database_name
POSTGRES_USER=your_postgres_user
POSTGRES_PASSWORD=your_postgres_password
```
- Build and run the containers:
```
   docker-compose up
```
- Access the application:
   - Frontend: http://localhost:3000
   - Backend: http://localhost:3001

