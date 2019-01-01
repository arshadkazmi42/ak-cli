### List running dynos

`heroku ps {{TYPE}} --app {{APP_NAME}}`

- <b>TYPE</b>: Type of dyno.  This is optional. If it is not given then all the dynos are listed.
- <b>APP_NAME</b>: Name of the app.

#### Example:

`heroku ps --app TestApp`


##### with type

`heroku ps web --app TestApp`