# What is the difference between a library and a framework?
![N|Solid](https://i.stack.imgur.com/DqCkT.png)



----------------------------
# REACT

[![N|Solid](https://upload.wikimedia.org/wikipedia/en/thumb/a/a7/React-icon.svg/320px-React-icon.svg.png)](https://facebook.github.io/react/)

React is an open source javascript library is used for building user interfaces(UI). 
React enables developers to be able to create web pages that can change data without the need to reload the page. React handles the view in (MVC)

#### Sample code for react
![N|Solid](https://dab1nmslvvntp.cloudfront.net/wp-content/uploads/2016/02/1454509910getting-started-with-react01-hello-world-demo-1024x640.png)

If you are building a web app where the data changes frequently, you will ideally want your view to be a function of the data. When the data changes, the view should be able to update itself and reflect the changes. For example, when you are on Hashnode, you may see a lot of changes triggered by various parts of the app. Some of these changes are :

- The app detects that there are new items in your feed. So, we need to show "New Updates" label on the top of the feed.
- New notifications are generated for you and you need to see the "count" in the top right notification icon.
- When you click on the "New Updates" button your feed needs to be refreshed.

These are a few instances where the data changes quickly and we need to reflect that in the view. Unless your UI is a function of the data, it'll be difficult for you to manage the application. This is where React helps. You will build your app in terms of small reusable components and React will make sure that your view reflects the latest data. It's like hitting a refresh button automatically whenever the underlying data changes. Furthermore, by building well encapsulated components you are essentially making a testable app with good separation of concerns and maximum code reuse. It is also worth mentioning that React maintains a virtual DOM and only updates those parts of the view where underlying data has been changed (which results in improved performance).

## ratings 5/5
![N|Solid](http://www.courierhacker.com/wp-content/uploads/2016/01/5-star-rating.png)


  

# HOWLER.JS

![N|Solid](https://camo.githubusercontent.com/98b571ff7230cf5d95e1d41d5d8ea0620c20a79d/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f686f776c65722e6a732f686f776c65722d6c6f676f2e706e67)

Howler.js is an audio library for the modern web. It defaults to Web Audio API and falls back to HTML5 Audio. This makes working with audio in JavaScript easy and reliable across all platforms.


#### sample code for howlerjs
 
 
 ```javascript
function play_audio(file_names) {
    sound = new Howl({
        src: [audio_url+file_names[0]],
        volume: 0.5,
        onend: function() {
            file_names.shift();
            if (file_names.length > 0) {
                play_audio(file_names);
            }
        }
    });      
    sound.play();
}
```

## rating 3/5
![N|Solid](https://unputdownablebookclub.files.wordpress.com/2013/10/3-stars-out-of-5.png)

# JQUERY

![N|Solid](http://www.softsciencewebmedia.com/images/CodingPlatforms_jQuery.png)

jQuery is a JavaScript library that allows web developers to add extra functionality to their websites and it is open source. It is used to simplify event handling, HTML document traversing, Ajax interactions and animation for speedy website development.

 ```
 $(document).ready(function(){
    $("p").click(function(){
        $(this).hide();
    });
});
```
# rating 5/5
![N|Solid](http://www.courierhacker.com/wp-content/uploads/2016/01/5-star-rating.png)






