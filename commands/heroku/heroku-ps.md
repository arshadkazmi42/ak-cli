### List running dynos

`heroku ps {{TYPE}} --app {{APP_NAME}}`

- <b>TYPE</b>: Type of dyno.  This is optional. If it is not given then all the dynos are listed.
- <b>APP_NAME</b>: Name of the app.

#### Example:

`heroku ps --app TestApp`

=== run: one-off dyno
run.1: up for 5m: bash

=== web: bundle exec thin start -p $PORT
web.1: created for 30s

##### with type

`heroku ps web --app TestApp`

=== web: bundle exec thin start -p $PORT
web.1: created for 30s