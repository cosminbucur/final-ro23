# thymeleaf implementation steps
- create template (html)
- add thymeleaf tags
- add page to security config
- create mapping in controller
- add/change method in controller
- add/change method in service
- add/change method in repository
- add/change dto
- add/change entity

# mapping conventions

## common pages
```
/ /index - landing page
/register - register form
/login - login form
/home - home page for user
/admin - home page for admin
```

## feature pages
```
/pets               GET     -> show pets page   |   pet/pets.html

/pets/add           POST    -> add pet

/pets/{id}/edit     GET     -> showEditPetForm  |   pet/pet-edit.html
/pets/{id}/edit     POST    -> updatePet

/pets/{id}          DELETE  -> updatePet
```
