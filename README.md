# nodets-express-oop
Nodets Express Oop

In this course you will learn how to generate a complex REST API with NodeJS using `TypeScript` as the core language and `TypeORM` as the SQL ORM.

## Technologies to be applied:

- OOP.
- Docker Compose as a database.
- TypeScript configuration.
- Configuration of routes, controllers, services, and entities.

## List of dependencies for installation:

Required dependencies:

```
npm install class-validator class-transformer cors dotenv express morgan pg typeorm typeorm-naming-strategies typescript
```

Required development dependencies:

```
npm install -D @types/cors @types/express @types/morgan concurrently nodemon
```

# Clases:

METHODS:

- <span style="color: #94fc03">PRACTICAL</span>
- <span style="color: #03d7fc">THEORIST</span>
- <span style="color: #fc7b03">THEORIST / PRACTICAL</span>

| CLASS 1 | Method | Content |
| --------------- | ------------------------------------------------------ | -------------------------------------------- |
| **Start - P1** | <span style="color: #fc7b03">THEORIST / PRACTICAL</span> | Creating `package.json` |
| **Start - P1** | <span style="color: #94fc03">PRACTICAL</span> | Installing necessary dependencies |
| **Start - P1** | <span style="color: #94fc03">PRACTICAL</span> | Adding dependencies to use |
| **Start - P1** | <span style="color: #94fc03">PRACTICAL</span> | Configuring `Express` |
| **Start - P1** | <span style="color: #94fc03">PRACTICAL</span> | Setting up a server through a class |
| **Start - P2** | <span style="color: #fc7b03">THEORIST / PRACTICAL</span> | Applying a global prefix for our API |
| **Start - P2** | <span style="color: #94fc03">PRACTICAL</span> | Generating my first route |
| **Start - P2** | <span style="color: #94fc03">PRACTICAL</span> | Executing what was done in Postman |

| CLASS 2 | Method | Content |
| --------------- | ------------------------------------------------------ | ----------------------------------------------------------- |
| **Routing** | <span style="color: #94fc03">PRACTICAL</span> | Route mode to apply on an OOP-based server |
| **Routing** | <span style="color: #94fc03">PRACTICAL</span> | Generating extended routes from a base route |
| **Controller** | <span style="color: #fc7b03">THEORIST / PRACTICAL</span> | What is a controller? Explained in route |

| CLASS 3 | Method | Content |
| ---------- | ------------------------------------------------------ | -------------------------------------------------------- |
| **Config** | <span style="color: #94fc03">PRACTICAL</span> | Configuring environment variables |
| **Config** | <span style="color: #fc7b03">THEORIST / PRACTICAL</span> | What is a runtime environment? Explained in config |
| **Config** | <span style="color: #94fc03">PRACTICAL</span> | Declaring environment variables in our server.ts |

| CLASS 4 | Method | Content |
| ----------------------- | ------------------------------------------------------ | --------------------------------------------------------- |
| **Docker Compose (DB)** | <span style="color: #94fc03">PRACTICAL</span> | Creating our `docker-compose.yml` |
| **Docker Compose (DB)** | <span style="color: #fc7b03">THEORETICAL / PRACTICAL</span> | Running our docker-compose and checking the connection |
| **TypeORM (DB)** | <span style="color: #94fc03">PRACTICAL</span> | Creating our connection configuration getter |
| **TypeORM (DB)** | <span style="color: #94fc03">PRACTICAL</span> | Execute the connection on our server |
| **TypeORM (DB)** | <span style="color: #94fc03">PRACTICAL</span> | Create our base entity with common data |
| **TypeORM (DB)** | <span style="color: #94fc03">PRACTICAL</span> | Creating our first entity for our database |

| CLASS 5 | Method | Content |
| ----------- | -------------------------------------------- | ------------------------------------------------------------------------------- |
| **Entity** | <span style="color: #03d7fc">THEORIST</span> | Entity architecture proposal |
| **General** | <span style="color: #94fc03">PRACTICAL</span> | Modifying project distribution in a modular way |
| **Entity** | <span style="color: #03d7fc">THEORETICAL</span> | Sample relationships (one-to-many (N:1), one-to-one (1:1), and many-to-many (N:N)) |
| **Entity** | <span style="color: #94fc03">PRACTICAL</span> | Users: User entity modification |
| **Entity** | <span style="color: #94fc03">PRACTICAL</span> | Customer: Entity and relationship creation |
| **Entity** | <span style="color: #94fc03">PRACTICAL</span> | Products: Entity and relationship creation |
| **Entity** | <span style="color: #94fc03">PRACTICAL</span> | Categories: Entity and Relationship Creation |
| **Entity** | <span style="color: #94fc03">PRACTICAL</span> | Purchases: Entity and Relationship Creation |
| **Entity** | <span style="color: #94fc03">PRACTICAL</span> | `purchases_products`: Creating Custom N:N Entities and Relationships |

| CLASS 6 | Method | Content |
| --------------- | ------------------------------------------------------ | ----------------------------------------------------------------------- |
| **Entity** | <span style="color: #94fc03">PRACTICAL</span> | Installing `class-transformer` to exclude data in our entity |
| **Service** | <span style="color: #fc7b03">THEORIST / PRACTICAL</span> | What are services and what are they for? |
| **Service** | <span style="color: #94fc03">PRACTICAL</span> | Instantiating deployed methods with a repository function using TypeORM |
| **Service** | <span style="color: #94fc03">PRACTICAL</span> | Creating `findAll` `findById` `create` `updtae` `delete` |
| **Controller** | <span style="color: #94fc03">PRACTICAL</span> | Integrating methods by instantiating services with controllers |

| CLASS 7 | Method | Content |
| --------------- | -------------------------------------------- | ------------------------------------------------------------ |
| **Controller** | <span style="color: #94fc03">PRACTICAL</span> | Creating our status code enum |
| **Controller** | <span style="color: #94fc03">PRACTICAL</span> | Create our `HttpResponse` class and integrate our enum |
| **Controller** | <span style="color: #94fc03">PRACTICAL</span> | Instantiate our response class in our controller |
| **Controller** | <span style="color: #94fc03">PRACTICAL</span> | Edit our methods in the controller |

| CLASS 8 | Method | Content |
| --------------- | ------------------------------------------------------ | --------------------------------------------------------------------------- |
| **TypeORM** | <span style="color: #94fc03">PRACTICAL</span> | Go from typeORM 0.2 to 0.3 |
| **TypeORM** | <span style="color: #94fc03">PRACTICAL</span> | Create our `Data Source` |
| **TypeORM** | <span style="color: #94fc03">PRACTICAL</span> | Edit our `Data Source` configuration and prepare it for migrations |
| **TypeORM** | <span style="color: #94fc03">PRACTICAL</span> | Edit each of the deprecated methods from the previous version |
| **Service** | <span style="color: #94fc03">PRACTICAL</span> | Modify the methods that are no longer supported in version 0.3 |
| **Migrations** | <span style="color: #fc7b03">THEORIST / PRACTICAL</span> | Why migrations? |
| **Migrations** | <span style="color: #94fc03">PRACTICAL</span> | Creating our `typeform` `migration:generate` and `migration:run` scripts |
| **Migrations** | <span style="color: #94fc03">PRACTICAL</span> | Running migrations and testing our code |
