# tasksToDo
## Run
* Add venv
```sh
python3 -m venv venv
```
* Activate venv
```sh
. venv/bin/activate
```
* Necessary facilities
```sh
pip3 install Flask mysql-connector-python Werkzeug
```
* Add neovim if used
```sh
pip3 install neovim pylint
```
* Environment Variables
``` sh
export FLASK_DATABASE_USER='user' &&
export FLASK_DATABASE_PASSWORD='' &&
export FLASK_DATABASE='todo'
```
* Export for development
```sh
export FLASK_APP=todo && export FLASK_ENV=development
```
* Flask run
```sh
flask run
```
* Initialize databases
```sh
flask init-db
```
[![logoN1-w.png](https://i.postimg.cc/bvwkKP8Y/logoN1-w.png)](https://github.com/Hec98)
