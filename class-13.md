# Reading 13 Local Storage

Why would a developer use local storage for a web application?

To store the state of their interface.

What information should not be stored in local storage?
personal information that you would care if it were exploited.

Local storage can store what type of data? How would you convert it to that type before storing?

Local storage can only store string date. You can use JSON.stringify() and JSON.parse() methods to convert them.