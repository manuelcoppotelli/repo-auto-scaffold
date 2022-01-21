# Setup

## Create a repository from this template

1. Click the big green button `Use this template` or click [here](../../generate)
1. Enter a Repository name and click `Create repository from template`
1. Head over to the created repository and complete the setup

## Complete the setup

1. In the a new repository, [create a new Initialize Repository issue](../../issues/new?title=Initialize%20repository&assignees=&labels=question&template=init-repo.yaml), fill the form and click `Submit new issue`
1. Wait [Setup Repository Action](../../actions/workflows/setup-repo.yaml) to complete
1. That's it, easy isn't it?

---
# %service_name%

> %service_description%

## Build

To create docker image run the following commands:

``` shell
docker build -t %normalized_service_name% .
```
