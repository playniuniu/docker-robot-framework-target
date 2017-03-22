# Docker for playniuniu/robot-framework target

### Intro

This docker is used for playniuniu/robot-framework testing target

Please see [playniuniu/robot-framework](https://github.com/playniuniu/docker-robot-framework) for detail

### RUN

If you want to run this single docker, please use the command:

```bash
docker run -d --rm -p 8000:80 -v YOUR_HTML_FOLDER:/opt/web --name robot-framework-target playniuniu/robot-framework-target
```

