

# item-catalog :trophy:
## About
develop an application that provides a list of items within a variety of categories as well as provide a user registration and authentication system. Registered users will have the ability to post, edit and delete their own items.

## Why This Project? :construction::triangular_flag_on_post:
Modern web applications perform a variety of functions and provide amazing features and utilities to their users; but deep down, it’s really all just creating, reading, updating and deleting data. In this project, you’ll combine your knowledge of building dynamic websites with persistent data storage to create a web application that provides a compelling service to your users.

## Acquired skills :blush:
- Python
- HTML/CSS
- Bootstrap
- Flask
- Jinja2
- SQLAchemy
- OAuth
- Facebook / Google Login

## Requirement :checkered_flag:
- [Vagrant](https://www.vagrantup.com/)
- [Udacity Vagrantfile](https://github.com/udacity/fullstack-nanodegree-vm)
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

## How to run :dart:
Install Vagrant and VirtualBox
Clone the fullstack-nanodegree-vm
Launch the Vagrant VM (vagrant up)
Write your Flask application locally in the vagrant/catalog directory (which will automatically be synced to /vagrant/catalog within the VM).
Run your application within the VM (python /vagrant/catalog/application.py)
Access and test your application by visiting http://localhost:5000 locally

### JSON Endpoints

`/api/v1/catalog.json` - Returns JSON of all items in catalog

`/api/v1/categories/<int:category_id>/item/<int:catalog_item_id>/JSON` - Returns JSON of selected item in catalog

`/api/v1/categories/JSON` - Returns JSON of all categories in catalog

### Login

'/login' - login page


### CRUD for categories

'/' or '/categories' - Returns catalog page with all categories and recently added items

'/categories/new' - Allows user to create new category

'/categories/<int:category_id>/edit/' - Allows user to edit an existing category

'/categories/<int:category_id>/delete/' - Allows user to delete an existing category

### CRUD for category items

'/categories/<int:category_id>/' or `/categories/<int:category_id>/items/` - returns items in category

'/categories/<int:category_id>/item/<int:catalog_item_id>/' - returns category item

'/categories/item/new' - return "This page will be for making a new catalog item

'/categories/<int:category_id>/item/<int:catalog_item_id>/edit' - return "This page will be for making a updating catalog item"

'/categories/<int:category_id>/item/<int:catalog_item_id>/delete' - return "This page will be for deleting a catalog item"




