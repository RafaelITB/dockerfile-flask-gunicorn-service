## Dockerfiile for a flask gunicorn setup

### Default Credentials

- **User**: `rgs`
- **Password**: `sjo`
- 
### Building the Docker Image

Download the `Dockerfile` and run the following command in the same directory:
```
sudo docker build -t my_container -f dfFlask.
```
### Running the Container

To start the container, use:
```
sudo docker run -it -p 5000:5000 my_container
```
