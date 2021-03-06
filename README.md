# d3-example
This repository contains the code to create a bar chart using D3.js

### Project Organization
```nohighlight
├── data               <- Files containing data for populating the chart
├── README.md          <- The top-level README for developers using this project.
├── index.html         <- HTML file that serves as the homepage of the website
```

### Setup

From GitHub:
```
git clone https://github.com/aravind-sundaresan/d3-example.git
cd d3-example
```

The instructions to run the application from the project folder are listed below.

### Instructions to launch the application

- Open command prompt (Windows) / terminal (macOS/Linux)

- Inorder to launch the application, the user must run a local HTTP server from the project folder. We can use Python 
to run the server. 

  If the Python version installed in the system is 3.X, the server can be launched with the following command:
  ```
  python -m http.server 8000
  ```
  While the default port used for the server is 8000, the user can change the port number if needed.

  If the Python version is 2.X, the command to launch the server is:
  ```
  python -m SimpleHTTPServer
  ```

- Once the server is launched, open a web browser of your choice to access this URL: http://localhost:8000/ and the dashboard should be up and running. The port number would vary depending on the value passed while launching the server.
