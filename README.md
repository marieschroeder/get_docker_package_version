# get_docker_package_version
Example app to extract the versions of python packages out of a 'oggm/bokeh' docker image.

You can run the app with an desired image (here 'oggm/bokeh:20191210') with the comment: `docker run -e BOKEH_ALLOW_WS_ORIGIN=0.0.0.0:8080 -p 8080:8080 oggm/bokeh:20191210 git+https://github.com/pat-schmitt/get_docker_package_version.git app.ipynb`

The app can be found in your browser at the adress `http://0.0.0.0:8080/app`
