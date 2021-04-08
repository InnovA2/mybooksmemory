<h1 align="center">
  <img src="https://user-images.githubusercontent.com/39911545/114070007-dffc2d80-989f-11eb-9145-49164893b311.png" alt="MyBooksMemory" width="25%"/>
  <br>
  <i>MyBooksMemory</i>
</h1>

Mobile application to manage owned books, desires, to share books and discover actualities.

> **Note: MyBooksMemory** is a project carried out in a private repository on Gitlab.

- [Modules](#gear-modules)
  - [MyBooksMemory](#mybooksmemory)
  - [MyBooksMemoryFront](#mybooksmemoryfront)
  - [MyBooksMemoryApi](#mybooksmemoryapi)
  - [MyBooksMemoryBOT](#mybooksmemorybot)
- [Public links](#link-public-links)
- [Authors](#busts_in_silhouette-authors)

## :gear: Modules
### MyBooksMemory
It is a mobile application whose objective is to offer a book manager to the user. He therefore has the possibility of adding the books he has in his virtual library or these desires. He can also indicate the books he has read.

But also, the user can share his books with his family, his friends, ... via a group sharing system.

In addition, MyBooksMemory references French bookstores so that users can discover bookstores that are nearby.

Technologies used:
- Ionic
- Angular
- Capacitor

### MyBooksMemoryFront
MyBooksMemoryFront is a showcase site whose objective is to present the concepts of the application.

Technologies used:
- Angular
- Angular Material UI

### MyBooksMemoryApi
MyBooksMemoryApi is a web service using the web service [BooksMemoryApi](https://github.com/InnovA2/booksmemory#booksmemoryapi).

This service is used by the application and the Discord bot.

This allows to:
- register / authenticate and manage the user profile information
- retrieve books from the BooksMemoryApi web service to add them to its lists (virtual libraries)
- indicate the books read and put notes
- create sharing groups
- discover the bookstores sorted by city
- access statistics

Technologies used:
- NestJS
- TypeScript


### MyBooksMemoryBOT
MyBooksMemoryBOT is a bot on Discord for retrieving information from books.

Technologies used:
- Node.js
- TypeScript
- Discord.js

## :link: Public links

<img src="https://user-images.githubusercontent.com/39911545/114082419-01fcac80-98ae-11eb-8272-7a60cff4af0e.png" alt="MyBooksMemory" width="25%"/>

- MyBooksMemoryFront: [https://my.booksmemory.net](https://my.booksmemory.net)
- Discord de MyBooksMemory: [https://discord.gg/NpfbyG3](https://discord.gg/NpfbyG3)

## :busts_in_silhouette: Authors
- [Adrien MARTINEAU](https://github.com/WaZeR-Adrien)
- [Angéline TOUSSAINT](https://github.com/AngelineToussaint)


