# jupyterlab_opencv
JupyterLab with local directories mounted and OpenCV installed

#### Update JupyterLab password:
Generate a new hashed password:

`from notebook.auth import passwd`

`passwd()`

Update the entrypoint in docker-compose.yml.

#### Run JupyterLab
`docker-compose up -d --build`

Navigate your bowser to `http://[your_server]:8888`.  The default password is `test`.

