# Gatsby_Hello_World
Simple beginner Static App using Gatsby

# Installing and using Gatsby
Gatsby is available via the gatsby-cli JavaScript package. You have two ways you can use it:

Global install, run:
```npm install gatsby-cli -g```, this will install the executable gatsby on your machine. You can now use Gatsby like so in your terminal: ```gatsby <command>```.
Use npx, npx is a tool that makes it possible to run executable files without first installing them on your machine. If you use this way of installing you need to prefix your calls to Gatsby like so ```npx gatsby <command>```.

# These three commands will get you started working with a new Gatsby app:

```gatsby new <project name> <optional GitHub URL>```: Use this command to generate a new project. It takes a name as a mandatory argument and optionally a GitHub URL as the second argument. Using the latter argument will create a Gatsby project based on an existing Gatsby project on GitHub.

```gatsby develop```: Start a development server where your project can be accessed. A development server is an HTTP server able to host your files so you can access them from your browser. You will find your Gatsby app running at http://localhost:8000. It will also start an instance of GraphQL, which is a graphical development tool you can use to explore the data available to your app and build queries. You can use GraphQL by browsing to http://localhost:8000/___graphql.

```gatsby build```: Create a deployable static representation of your app. All the resulting HTML, JavaScript, and CSS will end up in the sub-directory public.
