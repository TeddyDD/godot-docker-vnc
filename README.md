# Godot Engine editor in Docker container

Adapted [docker-unity-3d](https://github.com/nenadg/docker-unity3d) to work
with [Godot Engine](https://godotengine.org/). I used [nanodeath/godot](https://hub.docker.com/r/nanodeath/godot/)
as reference how to put Godot into container.

Created for **fun**, for CI you should use headless container with Godot server
for example [nanodeath/godot](https://hub.docker.com/r/nanodeath/godot/)

I think audio is not working.

## Usage

``` sh
docker-compose up
````

Connect to container using any VNC viewer: `172.16.250.10:5900`. `/context` is mounted volume.
