### Heroku Toy Project
The bare minimum to run a Python project on Heroku.

### Steps to deploy.
```shell
heroku login # Log to Heroku.
heroku create # Create a remote repository.
git push heroku master # Push to remote repository.
heroku ps:scale web=1 # Attribute ressources to project.
```