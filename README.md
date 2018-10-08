# App search-IOS Mobile App


A system developed using Swift programming language on XCode. The data will be retrieved from Apple’s iTunes Search API.    
1. Connect Apple’s iTunes APIs to retrieve the search results  
2. Ability run the app on different screen sizes  
3. Use of OOP concepts / design patterns


Develop an iOS app to search and list AppStore content. The app should use a search controller with a table
view or a collection view to list the content.
When launched, the table view / collection view will be empty until the user enter something in the search bar.
Once entered, the data will be retrieved from Apple’s iTunes Search API (https://itunes.apple.com/search). It’s
required to pass the term, limit and entity. Here, term is the search string provided in the search bar. Set the
limit to 200 and entity to software.
Ex: https://itunes.apple.com/search?term=Puzzle&limit=200&entity=software
After loading content, the user should be able to tap on any row / cell. By tapping on a row / cell, the app
should be able to show content in a modal view. 
