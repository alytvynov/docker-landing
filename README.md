#Docker landing page
Simple docker to deploy landing page without additional backend functionality

Useful commands
```bash
docker image build -t nginx-landing .
docker container run -p 80:80 --rm nginx-landing
```
