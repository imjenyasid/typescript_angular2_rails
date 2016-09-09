##Rails + Typescript + Angular2

###Setup
    bundle install
    npm install
    typings install

###Use foreman to start dev server

    bundle exec foreman start

#####Why use foreman?
Because tsc needs to run in conjunction with the rails server. Tsc will watch your .ts files and will recompile when there is a file change.
