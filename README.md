# TinyApp

TinyApp is a full stack web app built with Node and Express that lets users shorten long URLs (similar to bit.ly).

## Screenshots

List of URLs created by a logged in user. A short url (randomly generated 6 digit code) is available for sharing, as well as the long url (for eg. http://www.nytimes.com). Edit and Delete features also available.

!["Screenshot of urls page"](https://github.com/richmondwong/tinyapp/blob/master/docs/urls.png)

Edit page. Here the user can change the long URL to something else (for eg. from http://www.nytimes.com to http://www.wsj.com). After the long URL is changed, the short URL will remain the same.

!["Screenshot of URL edit page"](https://github.com/richmondwong/tinyapp/blob/master/docs/edit_url.png)

## Dependencies

- Node.js
- Express
- EJS
- bcrypt
- body-parser
- cookie-session

## Getting Started

- Install all dependencies (using 'npm install')
- Run the development web server using the 'node express_server.js' command

