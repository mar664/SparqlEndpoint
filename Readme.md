npm install -g @comunica/actor-init-sparql

comunica-sparql-http "https://raw.githubusercontent.com/mar664/SparqlEndpoint/main/Values%20Map%20Ontology.owl"

curl -v "http://localhost:3000/sparql?query=CONSTRUCT%20WHERE%20%7B%3Fs%20%3Fp%20%3Fo.%7DLIMIT%20100"
