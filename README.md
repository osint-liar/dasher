# OSINT LIAR Templates
A set of templates that complement OSINT LIAR's data analysis, data visualization and reporting functionality. 

Development typically happens locally and pushes are deployed to github

From Github To Local

sed 's,https://osint-liar.github.io/osint-liar-templates,http://127.0.0.1/static/osint-liar-templates,g' reports/json/index.json
sed 's,https://osint-liar.github.io/osint-liar-templates,http://127.0.0.1/static/osint-liar-templates,g' analysis-tools/json/index.json

From Local to Github

sed 's,http://127.0.0.1/static/osint-liar-templates,https://osint-liar.github.io/osint-liar-templates,g' reports/json/index.json
sed 's,http://127.0.0.1/static/osint-liar-templates,https://osint-liar.github.io/osint-liar-templates,g' analysis-tools/json/index.json