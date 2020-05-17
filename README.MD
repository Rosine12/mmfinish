# API End Points:

- baseURL: http://mymoneyrw.herokuapp.com/api/


## Auth

1. http://mymoneyrw.herokuapp.com/api/auth/users/ : get, list registered user and add new ones.

2. http://mymoneyrw.herokuapp.com/api/auth/users/me/: get & update loggedin user

3. http://mymoneyrw.herokuapp.com/api/auth/users/

4. http://mymoneyrw.herokuapp.com/api/auth/users/confirm/

5. http://mymoneyrw.herokuapp.com/api/auth/users/resend_activation/
6. http://mymoneyrw.herokuapp.com/api/auth/users/set_password/
7. http://mymoneyrw.herokuapp.com/api/auth/users/reset_password/
8. http://mymoneyrw.herokuapp.com/api/auth/users/reset_password_confirm/
8. http://mymoneyrw.herokuapp.com/api/auth/users/set_username/
8. http://mymoneyrw.herokuapp.com/api/auth/users/reset_username/
8. http://mymoneyrw.herokuapp.com/api/auth/users/reset_username_confirm/
8. http://mymoneyrw.herokuapp.com/api/articles/
8. http://mymoneyrw.herokuapp.com/api/businessplans/
8. http://mymoneyrw.herokuapp.com/api/testimonies/
8. http://mymoneyrw.herokuapp.com/api/feedback/



## Translations

1. create pull request or clone the this repo

2. edit translate strings in fr.po for french

3. edit rw.po for Kinyarwanda translations

expample: to translate "current position" into kinyarwanda
open rw.po and look for ***msgstr***

```
msgid "Current position"
msgstr ""

```
change into:

````
msgid "Current position"
msgstr "umwanya ubu"

```