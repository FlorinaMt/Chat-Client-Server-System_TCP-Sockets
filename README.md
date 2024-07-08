About project:

Simple chat client-server system using sockets. Create account, send text messages to other users or request information from server using commands: "/list", "/number", "/last". The whole conversation is logged in .txt files, one file for each day.

Requirements

The client must be able to 1) send messages, 2) receive messages broadcasted to all clients and 3) request information from the server (not broadcasted to other clients, e.g. number of connected chatters, list of connected chatters or similar).

The application must:

- use Sockets connecting client and server, with the server being multithreaded

- use MVVM with at least two windows.

- use the Observer design pattern.

- use either Singleton or Multiton as a log to the server console and to file(s). It should always be possible to find all the communication for an entire day –text, ip address, date and time.

- use the Factory method, e.g. for different kinds of objects to send between server and client.

Protocol:
![image](https://github.com/betelgeuseBet/Chat-Client-Server_TCP-Sockets/assets/151634373/76c10bfa-7221-424c-b7f7-50a5f58199dd)

Class diagram: 
![image](https://github.com/betelgeuseBet/Chat-Client-Server_TCP-Sockets/assets/151634373/711d3178-8c67-4e60-9812-f5bc7741d1ba)

Diagrams also available as .asta files.
