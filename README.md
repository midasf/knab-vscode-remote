## knab-vscode-remote

# how to use.
git clone this repo. build your container: ` docker build --pull --rm -f "DockerFile.dockerfile" -t knabvscoderemote:latest "." `
then run it and mount your aws secrets `docker run -it -v c:\Users\.aws:/root/.aws knabvscoderemote:latest`

in VScode install the extention ms-vscode-remote.remote-containers:
 `code --install-extension ms-vscode-remote.remote-containers` 