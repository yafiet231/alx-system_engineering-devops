# Application server

**Concepts**

[Web Server](https://intranet.alxswe.com/concepts/17 "Web Server")

[Server](https://intranet.alxswe.com/concepts/67 "Server")

[Web stack debugging](https://intranet.alxswe.com/concepts/68 "Web stack debugging")

This was the application deployment project for our AirBnB clone. In this
project, I configured Nginx on the web servers provided to me by Holberton School
to serve a WSGI Flask app running through Gunicorn. Additionally, I set up an
Upstart script to keep the application running on server reboots.

## Tasks :page_with_curl:

* **0. Set up development with Python**
  * In this task, I configured the file `web_flask/0-hello_route.py` from my
  [AirBnB_clone_v2](https://github.com/bdbaraban/AirBnB_clone_v2) to serve content
  on the route `/airbnb-onepage/`, running on port `5000`

# Background Context


- Your web infrastructure is already serving web pages via Nginx that you installed in your [first web stack project](https://intranet.alxswe.com/projects/266 "first web stack project"). 
While a web server can also serve dynamic content, this task is usually given to an application server. In this project you will add this piece to your infrastructure, plug it to
your Nginx and make is serve your Airbnb clone project.

# Resources

**Read or watch:**

[Application server vs web server](https://www.f5.com/glossary "Application server vs web server")

[How to Serve a Flask Application with Gunicorn and Nginx on Ubuntu 16.04 (As mentioned in the video, do not install Gunicorn using virtualenv, just install everything globally)]
(https://www.digitalocean.com/community/tutorials/how-to-serve-flask-applications-with-gunicorn-and-nginx-on-ubuntu-16-04 "How to Serve a Flask Application with Gunicorn and Nginx on Ubuntu 16.04 
(As mentioned in the video, do not install Gunicorn using virtualenv, just install everything globally)")

[Running Gunicorn](https://docs.gunicorn.org/en/latest/run.html "Running Gunicorn")

[Be careful with the way Flask manages slash in route - strict_slashes](https://werkzeug.palletsprojects.com/en/3.0.x/ "Be careful with the way Flask manages slash in route - strict_slashes")

[Upstart documentation](https://doc.ubuntu-fr.org/upstart "Upstart documentation")
