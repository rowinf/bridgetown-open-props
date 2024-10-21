# Bridgetown Open Props Demo

This is a demo of Open Props. This demo uses bridgetown. Open Props offers a lot of CSS variables for use in your front end development project.

Open props gives you the power of CSS variables right now. It meets you where you are, letting you use as much or as little of it as you want. CSS variables are a new and powerful tool for your front end kit. 

You can add open props to your next Bridgetown project with the command line flag: 

`$ bridgetown new [project-name] -c open-props`

Follow the commits to understand this project

1. initial commit to create the project
2. import normalize.css for base styles
3. add some inline styles to the nav bar
4. add some styles to the main content
5. import buttons.css and create a basic contact form

## Prerequisites

- [Ruby](https://www.ruby-lang.org/en/downloads/)`
- [Node](https://nodejs.org)
  - `>= 12`
- [Yarn](https://yarnpkg.com)

## Install

```sh
bundle install && yarn install
```
> Learn more: [Bridgetown Getting Started Documentation](https://www.bridgetownrb.com/docs/).

## Development

To start development mode, run `bin/bridgetown start` and navigate to [localhost:4000](https://localhost:4000/)!

### Commands

```sh
# running locally
bin/bridgetown start

# build & deploy to production
bin/bridgetown deploy

# load the site up within a Ruby console (IRB)
bin/bridgetown console
```

> Learn more: [Bridgetown CLI Documentation](https://www.bridgetownrb.com/docs/command-line-usage)

## Deployment

You can deploy Bridgetown sites on hosts like Render or Vercel as well as traditional web servers by simply building and copying the output folder to your HTML root.

> Read the [Bridgetown Deployment Documentation](https://www.bridgetownrb.com/docs/deployment) for more information.
