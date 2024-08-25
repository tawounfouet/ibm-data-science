


https://author-ide.skills.network/render?token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJtZF9pbnN0cnVjdGlvbnNfdXJsIjoiaHR0cHM6Ly9jZi1jb3Vyc2VzLWRhdGEuczMudXMuY2xvdWQtb2JqZWN0LXN0b3JhZ2UuYXBwZG9tYWluLmNsb3VkL0lCTVNraWxsc05ldHdvcmstRFYwMTAxRU4tQ291cnNlcmEvbGFicy92NC9QcmFjdGljZV9Bc3NpZ25tZW50X1BhcnQyLm1kIiwidG9vbF90eXBlIjoidGhlaWFvcGVuc2hpZnQiLCJhZG1pbiI6ZmFsc2UsImlhdCI6MTcyMDA4MjczOH0.PN8U-pZ3zGNRFdPo7L_MzVR8rElbZVobg5GIVjQZJdg 

```sh
python3.10 -m venv _venv

source _venv/bin/activate

pip install --upgrade pip

pip install setuptools

pip install packaging

pip install pandas dash

pip install httpx==0.20 dash plotly

# create requirements.txt file
pip freeze > requirements.txt

# run dash app
python Dash_wildfire.py