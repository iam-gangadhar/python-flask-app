#### SIMPLE PYTHON DYNAMIC PLASK WEBSITE 
Project File structure
your_project/
├── app.py
├── templates/
│   └── index.html
└── static/
    └── ocean.jpg


### To Run this Application we just need one python container.
1.Build the Docker Image:
```sh
docker build -t dynamic-flask-app .
```

2. Run the Docker Container:
```sh
docker run -p 5000:5000 dynamic-flask-app
```

