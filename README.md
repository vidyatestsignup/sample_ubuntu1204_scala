sample_ubuntu1204_scala
=======================

This sample helps you create a shippable.yml file for your Scala project on Shippable. Please refer to our [language specific documentation on Scala](http://docs.shippable.com/languages/#scala) for more details.

### Build Image

The sample uses a Scala specific build image that's available for public use:
[shippableimages/ubuntu1204_scala](https://registry.hub.docker.com/u/shippableimages/ubuntu1204_scala)  ([Dockerfile](https://github.com/shippableImages/ubuntu1204_scala/blob/master/Dockerfile)).

The scala version available in the image is 2.11.2

To set your build image in Shippable:
- Login to [Shippable](https://www.shippable.com) 
- Navigate to your project page by clicking on the project link
- Click on **Settings** and choose the following option:

`Pull Image from : shippableimages/ubuntu1204_scala`

For more details on project settings, you can refer our docs on  [Build and Project Settings](http://docs.shippable.com/project_settings).
