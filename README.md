# NovaSQL

### Supported databases:
- [MySQL](https://github.com/NovaSQL/MySQL-Driver)
- [PostgresSQL](https://github.com/NovaSQL/PostgresSQL-Driver)
- [Microsoft SQL Server](https://github.com/NovaSQL/MSSQL-Driver)
- [SQLite](https://github.com/NovaSQL/SQLite-Driver)

## Getting Started
1. Install the core dependency together with the desired driver:  
   **Maven:**
   ```xml
     <dependency>
       <groupId>io.novasql</groupId>
       <artifactId>Core</artifactId>
       <version>{{VERSION}}</version>
     </dependency>
   ```
   ```xml
     <dependency>
       <groupId>io.novasql</groupId>
       <artifactId>{{DRIVER}}</artifactId>
       <version>{{VERSION}}</version>
     </dependency>
   ```
   **Gradle**
   ```groovy
     implementation 'io.novasql:Core:{{VERSION}}'
   ```
   ```groovy
     implementation 'io.novasql:{{DRIVER}}:{{VERSION}}'
   ```

## Contributing
   1. Clone the project:  
      **All modules**  
      - `git clone --recursive https://github.com/NovaSQL/NovaSQL`
      
      **Selected module**
       - [API](https://github.com/NovaSQL/API)
       - [Core](https://github.com/NovaSQL/Core)
       - [MySQL Driver](https://github.com/NovaSQL/MySQL-Driver)
       - [PostgresSQL Driver](https://github.com/NovaSQL/PostresSQL-Driver)
       - [Microsoft SQL Driver](https://github.com/NovaSQL/MSSQL-Driver)
       - [SQLite Driver](https://github.com/NovaSQL/SQLite-Driver)
  2. Make your changes.
  3. Submit a pull-request with your changes. (Optional)

## License
This project is licensed under the [GNU GPLv3 license](https://github.com/NovaSQL/NovaSQL/LICENSE.md).

## Contact
You can reach us on:
- Website: https://novasql.io
- E-mail: info@novasql.io
- Discord: https://discord.novasql.io
- Twitter: [NovaSQL](https://twitter.com/NovaSQL)
- Facebook: [NovaSQL](https://facebook.com/NovaSQL)
- Reddit: [NovaSQL](https://reddit.com/r/NovaSQL)
