https://www.theodinproject.com/lessons/ruby-on-rails-forms

## Connect the database
- Boot the app `docker compose up -d`
- To create the database `docker compose run web rake db:create`

## Rebuild the app.
- Full rebuild requires a re-run of `docker compose run app bundle install` to sync changes in the `Gemfile.lock` to the host.
- Followed by `docker compose up --build`.