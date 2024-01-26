# Room and Machine Management with Hibernate, RMI, and Swing

This project is designed to manage rooms and machines using a Swing graphical user interface. It utilizes Hibernate for the persistence layer and RMI (Remote Method Invocation) for client-server communication. The project is divided into two parts: the RMI server and the RMI client.

## Screenshot
### Main menu
<img width="960" alt="image" src="https://github.com/MaskedFezz/tpRMI/assets/130797834/8fc00778-6c2b-4d21-9ae7-504ff6968e82">

### Rooms
<img width="607" alt="image" src="https://github.com/MaskedFezz/tpRMI/assets/130797834/7ad4c097-9077-43c7-936e-9779cca4db47">
<img width="605" alt="image" src="https://github.com/MaskedFezz/tpRMI/assets/130797834/b55aa420-879f-4181-9a74-629f082cfeaf">
<img width="609" alt="image" src="https://github.com/MaskedFezz/tpRMI/assets/130797834/49520a75-5bb0-4b57-baf3-facb919e4234">
<img width="605" alt="image" src="https://github.com/MaskedFezz/tpRMI/assets/130797834/f368273f-7d54-4d88-a1b8-bfdd9e78c258">
<img width="604" alt="image" src="https://github.com/MaskedFezz/tpRMI/assets/130797834/c19c2445-6d18-40a4-9d11-572e49057aec">
<img width="656" alt="image" src="https://github.com/MaskedFezz/tpRMI/assets/130797834/ac716947-1157-4ab7-886b-e4fcadfca141">

### Machines
<img width="656" alt="image" src="https://github.com/MaskedFezz/tpRMI/assets/130797834/da83381a-6258-491b-9a1b-2d5f6315f4e6">
<img width="654" alt="image" src="https://github.com/MaskedFezz/tpRMI/assets/130797834/c166ce52-2218-4f09-9aa2-453f3d6d673b">
<img width="657" alt="image" src="https://github.com/MaskedFezz/tpRMI/assets/130797834/924a5348-6ddc-43c4-8244-19579aa4c7f0">
<img width="599" alt="image" src="https://github.com/MaskedFezz/tpRMI/assets/130797834/719a70ca-0119-4149-ac29-6e46daf885a2">

### Search
<img width="739" alt="image" src="https://github.com/MaskedFezz/tpRMI/assets/130797834/a27a11db-725b-4190-b33b-4b756441af7c">


## Technologies Used
- Java
- MySQL (for the database)
- Hibernate (for the persistence layer)
- RMI (for client-server communication)

## Project Features
1. CRUD (Create, Read, Update, Delete) operations for machines.
2. CRUD operations for rooms.
3. Searching for available machines in each room.

## Project Structure
The project is divided into two parts:

### ServerRMI Project
- `src/main/java/entities`: Entity classes for machines and rooms.
- `src/main/java/util`: `HibernateUtil` class for managing the SessionFactory.
- `src/main/java/service`: `MachineService` and `RoomService` classes for service operations.
- `src/main/java/config`: `hibernate.cfg.xml` file for Hibernate configuration.
- `src/main/java/dao`: `IDao` interface for CRUD operations.
- `src/main/java/server`: `Server` class to start the RMI server.

### ClientRMI Project
- `src/main/java/entities`: Entity classes for machines and rooms.
- `src/main/java/dao`: `IDao` interface for CRUD operations.
- `src/main/java/config`: `Config` class for RMI configuration (IP address and port).
- `src/main/resources`: `configuration.properties` file to specify the server's IP address and port.
- `src/main/java/ui`: Swing graphical user interface for room and machine management.

## System Requirements
- Java 8 or higher
- MySQL Server
- Hibernate
- Network connection for RMI communication

## How to Run the Project
1. Clone this project to your computer.
2. Start the RMI server using the `Server` class from the ServerRMI project.
3. Run the Swing application using the main class from the ClientRMI project.
4. Use the graphical interface to perform CRUD operations on machines and rooms.
5. Conduct searches to find available machines in each room.

## Author
- Mohamed Fezzazi

This project is intended for room and machine management, using advanced Java technologies. For questions or comments, please contact me.
