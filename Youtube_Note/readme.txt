Questions i want to get answered : 
    1. How these file communicate with each other? ::checked
        -> chrome.runtime.sendMessage() || for background.js , popup.js , option.js
            chrome.runtime.onMessage()
        -> chrome.tab.sendMessage() || for foreground.js
            chrome.runtime.onMessage()


    2. How to save the bookmarks, considering got the video ID?
        2.1 How to query local storage?
            
