Application Server


Window 1
ubuntu@154887-web-01:~/AirBnB_clone_v2$ python3 -m web_flask.0-hello_route
 * Serving Flask app '0-hello_route'
 * Debug mode: off
WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on all addresses (0.0.0.0)
 * Running on http://127.0.0.1:5000
 * Running on http://10.247.167.62:5000
Press CTRL+C to quit
127.0.0.1 - - [17/May/2023 23:47:13] "GET /airbnb-onepage HTTP/1.1" 200 -

Window 2
ubuntu@154887-web-01:~/AirBnB_clone_v2$ curl 127.0.0.1:5000/airbnb-onepage
Hello HBNB!ubuntu@154887-web-01:~/AirBnB_clone_v2$
