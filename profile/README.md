<p align="center">
    <img src="https://raw.githubusercontent.com/MoserBlog/.github/main/profile/images/titleimage.png">
</p>


# Pipelines
| CI.MoserBlog.Web | CI.MoserBlog.Styles | CI.MoserBlog.MediaTool
| :--- | :--- | :--- |
| [![Build Status](https://dev.azure.com/philipp-c-moser/MoserBlog/_apis/build/status/CI/CI.MoserBlog.Web?branchName=main)](https://dev.azure.com/philipp-c-moser/MoserBlog/_build/latest?definitionId=72&branchName=main) | [![Build Status](https://dev.azure.com/philipp-c-moser/MoserBlog/_apis/build/status/CI/CI.MoserBlog.Styles?branchName=main)](https://dev.azure.com/philipp-c-moser/MoserBlog/_build/latest?definitionId=70&branchName=main) | [![Build Status](https://dev.azure.com/philipp-c-moser/MoserBlog/_apis/build/status/CI/CI.MoserBlog.MediaTool?branchName=develop)](https://dev.azure.com/philipp-c-moser/MoserBlog/_build/latest?definitionId=73&branchName=develop) |


# System components
## MoserBlog.Web [Docker]
Web application for providing the functionality of the blog to users.

**Manual:** https://github.com/MoserBlog/MoserBlog.Web

**Artifact:** https://hub.docker.com/repository/docker/philippmos/moserblog-web
```
docker pull philippmos/moserblog-web
```

## @philippmos/moserblog-styles [npm]
Client library for defining styling and behavior of client components.

**Manual:** https://github.com/MoserBlog/MoserBlog.Styles

**Artifact:** https://www.npmjs.com/package/@philippmos/moserblog-styles
```
npm i @philippmos/moserblog-styles
```

## MoserBlog.MediaTool [Docker]
Interface for targeted query and management of media files on Azure blob storage.

**Manual:** https://github.com/MoserBlog/MoserBlog.MediaTool

**Artifact:** https://hub.docker.com/repository/docker/philippmos/moserblog-mediatool
```
docker pull philippmos/moserblog-mediatool
```
