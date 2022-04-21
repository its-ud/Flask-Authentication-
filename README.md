# Flask-Authentication-
Login SignUp by user in Flask

## User Functions
1. Register (Sign Up)
2. Login
3. After Authentication (Enters to the Dashboard)

## To Run The App
### setting up the environment
```
pip install flask
```

### install all nessesary modues in the import list by pip
```
from flask import Flask, render_template, url_for, redirect, flash
from flask_sqlalchemy import SQLAlchemy
from flask_login import UserMixin, login_user, LoginManager, login_required, logout_user, current_user
from flask_wtf import FlaskForm
from wtforms import StringField, PasswordField, SubmitField
from wtforms.validators import InputRequired, Length, ValidationError
from flask_bcrypt import Bcrypt
```

### then enter the command
```
python3 app.py
```

### Encryption of Password is done using -- Bcrypt hashing
### Database used -- Sqlite3
