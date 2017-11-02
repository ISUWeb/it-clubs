# ISU IT Clubs

The goal of this project is to provide a website where students can obtain more information about the IT clubs at Illinois State University. 

# Run the project locally

First clone the project. If you are not familiar with Git, take a look at the documentation https://git-scm.com/book/en/v2. Another good resource is the Odin Project. See the lessons on Git. Here's the first one: https://www.theodinproject.com/courses/web-development-101/lessons/introduction-to-git.

Also, if you are using Windows, and are fed up with the Windows command line, check out http://cmder.net/.

Next, setup a local environment. All you really need is [Jekyll](https://jekyllrb.com/), the static site generator used in this project. There are two ways to set up your development environment:

1. Intall Jekyll on your computer. This should be easy enough on a Mac or Linux machine. Simply follow the steps on the [Jekyll Documentation](https://jekyllrb.com/docs/installation/). Windows is a little more tedious, but if you want to give it a shot you might find this website useful [Run Jekyll on Windows](http://jekyll-windows.juthilo.com/). Once you have Jekyll installed, navigate to the root of the project and run `jekyll serve`.

2. Skip Jekyll entirely and run our project with [Docker](https://www.docker.com/). Docker will load a Linux container with a Jekyll environment already set up. Simply navigate to the root folder of the project using your terminal (where the docker-compose.yml file is) and run `docker-compose up`.

In either case, navigate to http://localhost:4000 to see the project. When you change any of the files, Jekyll will detect changes and automatically rebuild the project, so no need to restart the server once its up, simply refresh your browser. Note that there are a few exceptions, however, like changes to the `_config.yml` file. 