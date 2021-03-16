## Deploy Flutter App on DigitalOcean App Platform using Docker.

### Getting Started
Fork the repository and make the following changes: 

- Change ``GIT_USERNAME`` and ``REPO_NAME`` to your desired Flutter repository. (Line **23 and 24**)

- Within your Flutter project, open ``.gitignore`` and remove ``/build`` and then run ``flutter build apk``, uploading your APK release file.

- Configure the testing for your Flutter project. You can read more about this [here](https://flutter.dev/docs/testing). 

- Also, replace ``REPO_NAME`` on the Caddy installation as well. (Line **28**)

- Deploy the modified Dockerfile to DigitalOcean App Platform. Read more about [App Platform deployment](https://www.digitalocean.com/products/app-platform/).