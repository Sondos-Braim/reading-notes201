# Read13

## Local Storage

-	User data allows web page to store data of 64 KB. Trusted domains can store more.
-	There was no way to increase the storage available although it was not enough.
-	The, Adobe introduced a new feature that can store 100KB and it was called `flash cookies`.
-	Then, google launched `Gears` that can store an unlimited amount of data per domain.
-	There were so many versions but they wanted to create something unified.
-	HTML5 solves the problem are unifies all of these differences.
-	HTML5 provides a standardized API, implemented natively and consistently in multiple browsers, without having to rely on third-party plugins.
-	HTML5 storage is way in which you can save data locally even when you leave the page or refresh, it’s going to stay there.
-	However, this data will not be sent to a third party server unless you want it to.
-	All the browsers support the HTML5 web storage.
-	From your JavaScript code, you’ll access HTML5 Storage through the `localStorage` object on the global window object.
-	We can use the data storage using the key value method t=so the keys will be stings and the values will be anything. However, when you retrieve the data, the values will be displayed as strings and you need to use some methods to change the type.
-	If you call the method `setItem()` to a key, it will overwrite the previous value.
-	If you call `getItem()` with a non-existent key will return null.
-	Instead of using these methods, you can use square brackets.
-	You can also delete the stored item using another method.
-	You can you enentlistener to track the changes that happen in the storage.
-	The HTML storage is very important for the web page because when you close the browser or maybe accidentally leave the page, it will remember exactly where you were before you closed the browser.
-	Although the HTML storage is very advanced now, however, there is going to be something better in the future.


