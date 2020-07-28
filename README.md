# 📖 StoryBooks &nbsp; ![](https://img.shields.io/github/deployments/iampavangandhi/Storybooks/storybooks-web?color=2648ff&style=flat-square)

> Create public and private stories from your life
> #### WebApp Live at [https://storybooks-web.herokuapp.com/](https://storybooks-web.herokuapp.com/)
> #### Checkout TheNodeCourse at [https://github.com/iampavangandhi/TheNodeCourse](https://github.com/iampavangandhi/TheNodeCourse)

#### This app uses Node.js/Express/MongoDB with Handlebars for templating and Google OAuth for authentication.

## Project Tutorial

### Complete Tutorial (2.5hrs Long) by [Brad Traversy](https://github.com/bradtraversy): ⏩ [**Youtube Link**](https://youtu.be/SBvmnHTQIPY)

<code><img height="50" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png" alt="javascript"></code>
<code><img height="50" src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSTTzPAw-55ssm1Im594xYZ9eRQu2JylrkYLg&usqp=CAU" alt="mongodb"></code>
<code><img height="50" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/nodejs/nodejs.png" alt="nodejs"></code>
<code><img height="50" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/express/express.png" alt="express"></code>
<code><img height="50" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/google/google.png" alt="google"></code>
<code><img height="50" src="https://cdn.glitch.com/project-avatar/0d184ee3-fd8d-4b94-acf4-b4e686e57375.png?2016-11-21T13:18:58.896Z" alt="passport"></code>
<code><img height="50" src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcSCjjrUqDfgOQsyoil76OpCKOnnpmEu71jHFQ&usqp=CAU" alt="heroku"></code>

## Development

#### Add your MongoDB URI and Google OAuth credentials to the config.env file see config.env.example for details or just run <code>npm run postinstall</code>.

```sh
# Install dependencies
npm install

# Run in development
npm run dev

# Run in production
npm start
```

## Folder Structure

    .
    ├── 📁 config                  # Config files
    ├── 📁 helpers                 # Hbs helper files
    ├── 📁 middleware              # Expresss middlewares
    ├── 📁 models                  # Mongoose models
    ├── 📁 public                  # Public folder
    │    └── 📁 css
    ├── 📁 routes                  # Express routes
    ├── 📁 scripts                 # Script files
    └── 📁 views                   # Hbs views
         ├── 📁 error
         ├── 📁 layouts
         ├── 📁 partials
         └── 📁 stories

## Deployment

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Contributing

Feel free to dive in! [Open an issue](https://github.com/iampavangandhi/Storybooks/issues/new) or submit PRs

## License

[MIT](LICENSE) © Pavan Gandhi

## Credit

### [Brad Traversy](https://github.com/bradtraversy)
