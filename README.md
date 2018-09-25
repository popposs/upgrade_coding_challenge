Upgrade Take-home Assignment

Created with Postgres, Nginx, Flask + Gunicorn.

Routes:
`/` for registration page
`/cancel/<uid>` to cancel by unique registration id
`/modify/<uid>/mmddyy/mmddyy` to modify registration arrival and departure dates

1. `make bootstrap-db` to initialize Postgres tables
2. `make all` to run the rest of the containers (nginx, flask app)
3. `localhost:8080` to test the app
