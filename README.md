# get_docker_package_version
Example app to extract the versions of python packages out of a 'oggm/bokeh' docker image.

You can run the app with an desired image (here 'oggm/bokeh:20191210') with the comment: `docker run -e BOKEH_ALLOW_WS_ORIGIN=127.0.0.1 -p 8085:8080 ghcr.io/oggm/bokeh:20221229 git+https://github.com/pat-schmitt/get_docker_package_version.git app.ipynb`

The app can be found in your browser at the adress `http://127.0.0.1:8085/app`
