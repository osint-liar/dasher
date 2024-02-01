# Dasher an OSINT LIAR Templates Library
A set of templates that complement OSINT LIAR's data analysis, data visualization and reporting functionality. 

Development typically happens locally and pushes are deployed to github


### Local Development
```bash
git clone git@github.com:osint-liar/dasher.git
cd dasher
python -m http.server 8000 # start a web server to host the template files locally
```

You will need to set the "http://127.0.0.1:8000/reports/json/index.json"

# Important
You will need to edit the tool you are testing to make sure it is in fact using the correct url. 