# zephyr-vscode-workspace
A VS Code Workspace for developing Zephyr Projects.

It opens a Docker container from the official [Zephyr Docker images](https://github.com/zephyrproject-rtos/docker-image) which has everything you need to get started developing a Zephyr project.

Use this template to quickly set up a dev enviroment on any machine with Docker and VSCode :)

https://user-images.githubusercontent.com/2559382/233291862-37514c50-0c57-4d46-82f3-a3f49b57402a.mp4

## How to use

You should already have Docker and VSCode with the remote containers plugin installed on your system.

* [docker](https://docs.docker.com/engine/install/)
* [vscode](https://code.visualstudio.com/)
* [vscode remote containers plugin](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

### Get the template

Click on "use this template" in the top right corner of this repo on the Github site.

### Create your repository

On the next dialog, name the repository you would like to start and decide if you want all of the branches, or just the main.

Github will then create a new repository with the contents of this one in your account.  It grabs the latest changes as "initial commit".

### Clone your repo

Now you can clone your repo as normal

### Open it in vscode

Now that you've cloned your repo onto your computer, you can open it in VSCode (File->Open Folder). 

When you open it for the first time, you should see a little popup that asks you if you would like to open it in a container.  Say yes!

If you don't see the pop-up, click on the little green square in the bottom left corner, which should bring up the container dialog

In the dialog, select "Remote Containers: Reopen in container"

VSCode will build the dockerfile inside of `.devcontainer` for you.  If you open a terminal inside VSCode (Terminal->New Terminal), you should see that your username has been changed to `user`, and the bottom left green corner should say "Dev Container"

### Author

[Keenan Johnson](https://www.keenanjohnson.com/) is an electrical and software engineer with experience building IoT fleets of all shapes and sizes.

[Reach out](https://www.keenanjohnson.com/consulting) if you need help or are interested in hiring me as a consultant for your project.
