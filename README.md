# Games Design and Development: Year 2
# Internetworking CA

## Joe O'Regan
## K00203642
## 10/04/2016

---

Take Home Assignment for 2nd year Internetworking module of Games Design and Development - BSc (Honours) in Computing (Level 8) course. 

2 Perl Client and Server socket applications, originally created as part of a group assigment.

---

**Client-Server 1:** The Client receives a question from the Server "What is your name?". The Client sends a reply string to the Server with the users name. The Server then sends a reply to the Client, depending on if the name matches the name 
stored by the Server the Client can receive a different greeting

![Client/Server 1](https://raw.githubusercontent.com/joeaoregan/Yr2-Internetworking-CA/master/Screenshots/ClientServer1.png "Client/Server 1")
###### Client / Server 1

---

**Client-Server 2:** This utility includes a separate client and server socket that extends the first listing. The Client socket receives a question from the Server socket "What is your name?". The Client sends a reply string to the Server with the name. The Server then sends a reply to he Client, depending on if the name matches the name stored by the Server.  If the name is Joe the Server returns a greeting, otherwise the Client must enter a password. If the password is correct the Client receives a positive response, otherwise the user must guess the password until it guesses one of the answers in the array of passwords stored by the Server socket

![Client/Server 2](https://raw.githubusercontent.com/joeaoregan/Yr2-Internetworking-CA/master/Screenshots/ClientServer1.png "Client/Server 2")
###### Client / Server 2