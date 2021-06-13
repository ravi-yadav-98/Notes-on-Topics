read: https://blog.paperspace.com/deploying-deep-learning-models-flask-web-python/
## Flask Notes
### Introduction:
- Flask is a web framework that provides libraries to build lightweight web applications in python.
- Flask is considered as a micro framework. based on WSGI  toolkit and jinja2 
- WSGI: web server gateway interface, which is a standard for python web application development.
- Jinja2 is a web template engine which combines a template with a certain data source to render the dynamic web pages.
- ---------------------------------------------------------------
 ### Create pip virtual environment:
- pip install virtualenv
- virtualenv myenv
- myenv\scripts\activate
- ----------------------------------------------------------------
### Hello World in Flask
- app  = Flask(__Name__)   # create flask object
- @app.route('/')   ## The route() function of the Flask class defines the URL mapping of the associated function. The syntax is given below.
- @app.route('/home/<name>'), 
  @app.route('/home/<int:age>)
- app.run(host, port, debug, options)  
- host	The default hostname is 127.0.0.1, i.e. localhost
- port	The port number to which the server is listening to. The default port number is 5000.
- debug	The default is false. It provides debug information if it is set to true.
- options	It contains the information to be forwarded to the server.

  
  ### add_url_rule() function
  
  ### flask URL Binding:
  - 
