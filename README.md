# This is a simple windows desktop TODO application

## Environment
* [Windows host setup](https://crosswalk-project.org/documentation/windows/windows_host_setup.html)
* Python

### Setup Python
Download [Python](https://www.python.org/ftp/python/3.5.1/python-3.5.1-embed-amd64.zip), unzip and put the folder on the PATH.

```
npm install
```

## How to run
Download newest [CrossWalk](https://download.01.org/crosswalk/releases/crosswalk/windows/canary/latest/),
unzip and put the folder on your PATH.

```python
python -m http.server 8000;
```

    xwalk http://localhost:8080

To enable debugging remotely:

    xwalk http://localhost:8080 --remote-debugging-port=9222

Then navigate to the the url [http://localhost:9222](http://localhost:9222) in Chrome.

### Technology stack
For running the application:
* CrossWalk
* Python

For development:
* Typescript
* RequireJS
* AngularJS
* Bootstrap
* Karma