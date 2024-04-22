Why use the flask to criate an api?
Flask has a basic architecture for criating an API, which is why it ends up being the ideal choice for creating APIs with Python.

app = Flask(__name__) - Criate app
@app.route('/name_url') - Criate url acess
app.run(port=5000,host='',debug=True) - Inicializa aplication