# CQRS-ES with Axon Framework

This project describes the steps involves setting an application 

## Getting Started
### Prerequisites
- **Java 8+**
- Docker
- Maven 3.6.x
- Axon Server

### Setting up Environment
Downloading Axon Server from here
https://axoniq.io/product-overview/axon-server
and run this command:
```bash
java -jar axonserver.jar
```

Or simple you can use the docker version for simplicity:
```bash
docker run -d --name axonserver -p 8024:8024 -p 8124:8124 axoniq/axonserver
```

To verify that the server is started correctly, open the page http://localhost:8024.

 
