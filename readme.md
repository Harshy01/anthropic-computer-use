Hey,
this repo is focused on experimenting with the new anthropic computer use api, which gives ai the power to use computer using tools to interact and replace human actions with, without any further delay let's directly get into it:

i'm referring to this right now:

![Anthropic Computer Use Docs](https://github.com/anthropics/anthropic-quickstarts/tree/main/computer-use-demo)

so the docs start with a few warnings which i'm ofc gonna ignore(not really, i'm using a vm which is flashed in a pen-drive inside docker)
it suggests to use docker:

```
export ANTHROPIC_API_KEY=%your_api_key%
docker run \
    -e ANTHROPIC_API_KEY=$ANTHROPIC_API_KEY \
    -v $HOME/.anthropic:/home/computeruse/.anthropic \
    -p 5900:5900 \
    -p 8501:8501 \
    -p 6080:6080 \
    -p 8080:8080 \
    -it ghcr.io/anthropics/anthropic-quickstarts:computer-use-demo-latest
```

