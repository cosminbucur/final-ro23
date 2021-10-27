# mapping conventions
/ /index - landing page
/register - register form
/login - login form
/home - home page for user
/admin - home page for admin

/pets               GET     -> show pets page   |   pet/pets.html

/pets/add           POST  -> add pet

/pets/{id}/edit     GET     -> showEditPetForm  |   pet/pet-edit.html
/pets/{id}/edit     POST    -> updatePet

/pets/{id}          DELETE  -> updatePet

# thymeleaf conventions
- add button
    - create page (html)
    - add thymeleaf tags
    - add page to security config
    - create mapping in controller
    - add method in controller
