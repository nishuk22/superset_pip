## Setup
- Install requirements.txt and activate venv
- Required envs `export FLASK_APP=superset && export SUPERSET_CONFIG_PATH="$(pwd)/superset_config.py" && export SUPERSET_HOME=$(pwd)`
- To create default roles, permissions and all required tables `superset db upgrade && superset init`
- Create default admin user `superset fab create-admin --username admin --firstname Superset --lastname Admin --email admin@gmail.com --password admin`
- Command to start `superset run -p 8080 --with-threads --reload --debugger`
