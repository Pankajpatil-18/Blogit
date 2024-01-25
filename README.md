Bloggitt 📝
Bloggitt is a blogging website that allows users to post their thoughts and knowledge with others.

Tech Stack
Frontend: HTML/CSS/Bootstrap
Backend: Django
Quick Start
Fork and Clone the repository using-
git clone https://github.com/VS-DYPIAN/BLOG.git
Create a Branch-
git checkout -b <branch_name>
Create virtual environment-
python -m venv env
env\Scripts\activate
Install dependencies using-
pip install -r requirements.txt
If you have python2 and python3 installed you need to specify python3 by using command:

python3 -m pip install -r requirements.txt
Headover to Project Directory-
cd bloggitt
Make migrations using-
python manage.py makemigrations
If you have python2 and python3 installed you need to specify python3 by using command:

python3 manage.py makemigrations
Migrate Database-
python manage.py migrate
Create a superuser-
python manage.py createsuperuser
Run server using-
python manage.py runserver
Push Changes-
git add .
git commit -m "<your commit message>"
git push --set-upstream origin <branch_name>
Useful Resources to Learn
Django Docs
Bootstrap Docs
Git and GitHub
