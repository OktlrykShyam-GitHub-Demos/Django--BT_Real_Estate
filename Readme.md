Django Demo App
=
Bt Real Estate
-

This app demonstrates basic to intermediate DJango technique and usage. I wrote it as part of a Django course I did over on Packt. It's a good app to learn Django from - I am quite good now. It comes with prebuilt HTML and I worked through the materials and converted it into Django - and coded the views and models and routing with the urls.

*Dockerfiles included* *The docker-compose may loop a little before it stabilizes - I need to include a wait for db function.*

The data is seeded using fixtures, if running from the command line use

  - python manage.py migrate &&
  - python manage.py loaddata seed.json &&
  - python manage.py runserver


create a db named btredb, and edit settings.py to set up the database server


*ps: My Web Page will be available soon*
