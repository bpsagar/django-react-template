# django-react-template
A startproject template for Django and React with Postgres database and a docker development environment.

## Usage
To use this template use the following command
```
 django-admin startproject --template=https://github.com/bpsagar/django-react-template/archive/master.zip --extension=py,txt,env,md {{ project_name }}
```

## Post Installation
Run the following commands to completely setup the project

```
# Create the frontend with create react app
npx create-react-app {{ project_name }}-client

# Run docker compose
docker-compose up
```
