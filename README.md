## Laravel 5-5 example ##

### Features ###

* Home page
* Custom error pages 403, 404 and 503
* Authentication (registration, login, logout, password reset, mail confirmation, throttle)
* Users roles : administrator (all access), redactor (create and edit post, upload and use medias in personnal directory), and user (create comment in blog)
* Blog with nested comments
* Search in posts
* Tags on posts
* Contact us page
* Admin dashboard with users, posts, articles, medias, settings, notifications and comments
* Multi users medias gestion
* Localization (English, French and Chinese)
* Application tests
* Thumbs creation for images
* Notifications to send emails and notify redactors for new comments

### Tricks ###

To use application the database is seeding with users :

* Administrator : email = admin@la.fr, password = admin
* Redactor : email = redac@la.fr, password = redac
* User : email = walker@la.fr, password = walker
* User : email = slacker@la.fr, password = slacker
