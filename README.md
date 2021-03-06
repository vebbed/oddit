# Oddit

Oddit stands for "Odd IT Jobs".

A screenshot of our beta version:
![oddit beta screenshot](http://i.imgur.com/VDob5Cj.png)

A screenshot of the beta admin panel:
![oddit admin beta screenshot](http://i.imgur.com/paEFzTG.png)

### Tell me more...
We started this project out of a need for small jobs we could do.  Take an Electrician for example, they can come around and put in a new light switch for you, you pay them $80 and they go away. Job well done. But why is such a thing uncommon in the Information Technology industry?

There's always someone who:

 - Needs the banner on their Wordpress website replaced
 - Needs their email newsletter system updated
 - Requires maintenance on their PHP website
 - Wants an email system for their business domain
 - Wants a mobile app for their business prototyped
 - Fixing their Shopify/Joomla/Drupal site
 - ... and so on

**However** where do the people/organisations get people for these jobs? They're either gambling on a student, or wasting money on a consultant. **Oddit** is the solution. A place to find people with the skills you need to do one-offs, casual and fixed-term jobs.

### The source code

Oddit is built on the Python Django framework (1.8).

Packages are required, please see requirements.txt:

 - cd to the directory where requirements.txt is located.
 - activate your virtualenv.
 - run: `pip install -r requirements.txt` in your shell.


### Additional requirements

 - Valid ruby environment (http://www.ruby-lang.org/en/downloads/)
 - Valid nodejs environment (https://nodejs.org/en/download/)
 - Valid redis (http://redis.io/topics/quickstart)
 - Install following Packages

 `gem install compass`

 `npm install -g bower`

 `bower install`


### Initial Data load

 - `python manage.py makemigrations`
 - `python manage.py migrate`
 - `python manage.py loaddata job/sql/fixtures.json`
 - `python manage.py rebuild_index` (refer to [haystack documentation](http://django-haystack.readthedocs.io/en/v2.5.0/tutorial.html#installation) for more info.)

We'll be accepting pull requests and fixing issues/bugs posted. We welcome anyone who'd like to join the project.

### Developed by vebnz
- [Mike Mackenzie](https://github.com/veb)
- [Ray Arvin Rimorin](https://github.com/avwave)
- [Jamie Gracie](https://github.com/Kingy)

### Contributors
- [Rob Attfield](https://github.com/rattfieldnz)
