# Spaaace

Helper classes for CSS spacing based on [Space in design systems](https://medium.com/eightshapes-llc/space-in-design-systems-188bcbae0d62).

I found this article quite helpful, even though I'm not a designer I still am a frontender and thus sometimes I do have to make decisions related to spacing and other visual elements. This set of guidelines come in handy when a quick padding or margin has to be put in place but instead of trying "random" numbers these sizes are now a sort of go to solution. This is also a project I used to dip my feet on Stylus, even if it really was just a tiny bit.

## Getting Started

There's no real science for getting started with this project.

### Prerequisites

To compile a new version you'll need:
* [Nodejs](https://nodejs.org/en/)
* [Npm](https://www.npmjs.com/)
* [Stylus](http://stylus-lang.com/)

Note: As of NPM v5.2, a new tool to run scripts is included, npx, which let's developers run local binaries from the node_modules folder without having to write the full path to them. The build scripts take advantage of that and thus that's the minimum required version of npm to compile this project.

### Installing

There is no development environment due to the size of the project but get everything needed to compile a new version the steps are:

Install **nodejs** (**npm** is included)

#### Linux

```
curl -sL https://deb.nodesource.com/setup_9.x | sudo -E bash -
sudo apt-get install -y nodejs
```

Next install the project dependencies

```
npm install
```

To test that everything is installed execute `npm run compile` and it should generate a new `style.css` file. 

## Deployment

To use this in a project just import the css file from `node_modules/spaaace/style.css`.

## Built With

* [Stylus](http://stylus-lang.com/)

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Telmo Alves** - *Initial work* - [blugt](https://github.com/blugt)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

