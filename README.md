git clone YOUR_GITHUB_REPOSITORY_URL
cd YOUR_PROJECT_FOLDER

python3 -m venv venv
pip install -r requirements.txt

cp .env.example .env

python main.py --dry-run "test"

python main.py "My crop leaves are turning yellow. What should I do?"

