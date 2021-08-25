## ***Local Storage***

### “The Past, Present, and Future of Local Storage for Web Applications”
- Local storage is great for native client applications where a majority of the information is held on your local machine
- Cookies were one of the first files that originated from a web application that used local storage, but they are not very big (only 4 KB) and they slow your web application by constantly transmitting data over and over
- Microsoft created userData which allowed up to 64KB of data per domain and trusted domains allowed 10 times that amount (640KB)
- Flash 6 allowed up to 100 KB of data per domain and the proper name was Local Shared Objects
- AMASS and Gears were two other programs created to help with storage
- None of these solutions were uniform across all browsers and ones that were required 3rd part plugins
- HTML5 was finally created that worked across all major browsers and would store data (key/value pairs) locally without the need to transmit to the server unlike cookies
- JS is used to store the key/value pairs and localStorage is treated just like other JS objects
- HTML5 is limited to 5 MBs and this is standard across browsers
- Data from HTML5 is stored as a string in localStorage, so data adds up quickly
- SQL and Indexed Database API are two visions for the future in how data will be stored using localStorage
