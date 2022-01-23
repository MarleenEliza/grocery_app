# grocery_app

Personal project for practicing full stack development / design

# setup in docker

```
# create docker image
$ docker build -t grocery_app .

# set up container for client with nginx server at port 8000
$ docker run -it -p 8000:80 --name grocery-app-container grocery_app
```

# Skills I want to improve via this project:
* Adobe XD
* Adobe Illustrator
* Vue3
* Typescript
* Docker
* Python
* MySQL

# Environment
Front-End: Vue3 with TypeScript
Back-end: Python with Flask, MySQL
Design: Adobe XD
Logo-design: Adobe Illustrator

Usage of Python:
Try Flask framework for first time to integrate it with Vue JS
Connect Python to a MySQL DB which contains the supermarkt and ingredient information
I am not very proficient in Python so instead of using a fancy AI to calculate an efficient route through the supermarket, I will just be using categories in order to create an ordered list

# Idea
I dislike spending a lot of time at the supermarket, so I decided to try making an app that will generate a grocery list that will help me navigate the supermarket in an efficient way.

# Functions (to be finalized)
1. Create a grocery list
→ User can input the groceries that they want to buy from a list. They can search both by keywords as well as picking an item from a category (eg. Strawberry from category fruit)
→ Memo function for each ingredient so you can add brand name or how many grams etc.

2. Add a recipe to the grocery list
→　Users can add select a recipe and all items needed for that recipe will be added to the grocery list. Before adding, the user can decide to leave out certain items if they don’t need to buy it.

3. Create a new recipe
→ Users can create their own recipe with ingredients available in the DB.
Order the grocery list (main function)
→ Order the groceries put in by the user and generates an ordered list which provides an efficient way to walk tough the supermarket
Other functions such as adding your own supermarket, or ingredients will be added if I have time
