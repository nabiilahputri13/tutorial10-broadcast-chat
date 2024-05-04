# Tutorial 10 🩰𓈒⋆⑅˚₊୨୧₊˚⑅⋆𓈒🩰
## Nabiilah Putri Safa
----------------------

## 2.1. Original code of broadcast chat

![Screenshot 2024-05-04 124517](https://github.com/nabiilahputri13/my-first-repob/assets/124870275/6ffb23d8-0047-4662-b98f-f9d3f7d86bca)

![Screenshot 2024-05-04 124459](https://github.com/nabiilahputri13/my-first-repob/assets/124870275/4674237e-df00-45ac-b3c5-b6d4b801328e)

![Screenshot 2024-05-04 124448](https://github.com/nabiilahputri13/my-first-repob/assets/124870275/249e445c-d872-4f95-b04f-933d1134e406)

![Screenshot 2024-05-04 124305](https://github.com/nabiilahputri13/my-first-repob/assets/124870275/9b4554f7-626d-4e3a-a5bc-18c38b624af0)

After running the server with the command "cargo run --bin server" and each client with the command "cargo run --bin client", the output above shows that each client and the server receive broadcasted chats from each client. Every time a client types a message in the command line, that string will be sent to the server, and the server will then proceed to send it to all connected clients.

## 2.2. Modifying port

When the client and server have the same port, the application will run smoothly just like before. However, if, for instance, we only change one port, say the client port, an error will occur on the client because, according to the client, that port doesn't have a connection, and the program will crash when given the command "cargo run --bin client".