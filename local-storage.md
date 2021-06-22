# The pas , present and future of local storage
* THE HISTORY OF LOCAL storage

* * The most famous utility for doing this storage thing relied on something called cookies, but they relied on sending data over and over to the server, thus using the internet, and they also had some limitations like the limited storage capacity, and slowing down web pages and web applications.

* * Before HTML came about userData allows web pages to store up to 64 KB of data per domain.
## HTML5

* It’s a way for web pages to store named key/value pairs locally.
* HTML5 is accessed through the localStorage object on the global window object, you can check on your browser if it supports it using the in operator, you can use Modernizr for the same purpose.
*  HTML5  stored BY : named key/ value pairs in your local machine, an  example :

` {userName: ‘Albert’, age: 26} `


![HTML storage](https://www.codeproject.com/KB/HTML/Web-Storage-In-Essence/localStorageShare.jpg)


***the storage of HTML5 is support the folowing browsers:***

1. IE 8.0+
2. Firefox 3.5+
3. Safari 4.0+
4. Chrome 4.0+
5. Opera 10.5+
6. Iphone 2.0+
7. Android 2.0+

* *** HTML web storage provides two objects for storing data on the client:***
1. ((localStorage)) 

- stores data with no expiration date.Where the data will not be deleted when the browser is closed, and will be available the next day, week, or year.


2. ((SessionStorage ))

- It is equal to the localStorage object, except that it stores the data for only one session. The data is deleted when the user closes the specific browser tab.



## HTML5 STORAGE IN ACTION
* Unfortunatly , if  you close the browser window mid-game, you’ll lose your progress. But with HTML5 Storage, we can save the progress locally, within the browser itself. Here is a live demonstration. Make a few moves, then close the browser tab, then re-open it. If your browser supports HTML5 Storage, the demonstration page should magically remember your exact position within the game, including the number of moves you’ve made, the position of each of the pieces on the board, and even whether a particular piece is selected.

![HTML5 STORAGE IN ACTION with games](https://res.cloudinary.com/keystone-demo/image/upload/c_fit,f_auto,h_450,w_750/v1548345971/html5-games-developer.png)