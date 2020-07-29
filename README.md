# notebooks-collection-opendata
A set of simple notebooks 13 TeV ATLAS Open Data datasets

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/atlas-outreach-data-tools/notebooks-collection-opendata/master)

### Docker
Docker allows you to run notebooks on your local computer, without internet connection.
1. Download Docker Desktop from [here](https://www.docker.com/products/docker-desktop)
2. Once you have Docker Desktop running, in a terminal, enter
```
docker pull meevans/atlasopendata-notebooks:latest
```

3. You can now run the image as a container and execute commands you normally would whilst being connected to the internet!

```
docker run --rm -it -p 8888:8888 meevans/atlasopendata-notebooks:latest
```

4. Copy and paste the following with the generated token from the server as <token> into your web browser on your local host machine

```
http://localhost:8888/?token=<token>
```

You now have access to Jupyter running on your Docker container.

@2020
