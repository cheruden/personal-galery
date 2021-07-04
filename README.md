# The Unchained Gallery  https://gallery-Theunchained.herokuapp.com/
A personal gallery application to display great photos by categories and locations from around the world.

### Author
[cheruden](https://github.com/cheruden)

### Screenshots
<img src="/static/images/django-gallery.PNG">

<img src="/static/images/django-gallery-2.PNG">

### User Stories
+ [x] View different photos that interest me.
+ [x] Click on a single photo to expand it and also view the details of the photo. The photo details must appear on a modal within the same route as the main page.
+ [x] Search for different categories of photos. (ie. Travel, Food)
+ [x] Copy a link to the photo to share with my friends.
+ [x] View photos based on the location they were taken.

### Technologies
* BackEnd:
      * Python
      * Django
* FontEnd:
      * HTML
      * CSS
      * JavaScript
      * Bootstrap
* Database
      * PostgreSQL
* Deployment
      * Heroku     

### Live Link
https://gallery-Theunchained.herokuapp.com/


### Installation Requirements

```
git clone https://github.com/cheruden/personal-gallery.git

virtualenv virtual

source virtual/bin/activate

pip3 install -r requirements.txt

psql CREATE DATABASE galleryz

python3.8 manage.py runserver

python manage.py migrate

python manage.py test
```
### BDD
| Input              | Output                     |
|---------------     |---------------             |
| Click on a photo   | Display images in Fancybox with details |
| Click copy Link button| Copy Link to Clipboard      |
| Search image in a certain category| View photos matching search term|

### Known bugs
No known bugs

### Support and contact details
cheruden25@gmail.com

Copyright (c) 2021 **[cheruden](https://github.com/cheruden)
**
