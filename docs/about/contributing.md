---
outline: deep
---

# Contributing

We welcome contributions in many different forms.
Select the form of contribution to the right that most closely matches your interest.

## Joining the Subcommittee

If you would like to get involved with the Subcommittee,
let us know in the [Discussions](https://github.com/aiaa-deic/computation-ai/discussions) area.
Other good first steps would be joining the [AIAA](https://aiaa.org) as a member.
You can find more information about membership [here](https://www.aiaa.org/membership).

## Contributing to this Website

This website is built and deployed automatically using GitHub Actions
and is created based on the source code found in the repository located <https://github.com/aiaa-deic/computation-ai>.
Updating the source code for this site will be very similar to contributing to other open source projects.
GitHub has a [fantastic article](https://docs.github.com/en/get-started/quickstart/contributing-to-projects)
using the forking method to contribute to a project.
That path is appropriate for external users hoping to make contributions.

For other subcommittee members, you may be able to push changes directly to the main repository.
The best way to get help with contributions is
to raise an [issue](https://github.com/aiaa-deic/computation-ai/issues) in the repository
where someone can answer your questions and provide guidance.

### Formatting on this Website

This website is built using [VitePress,](https://vitepress.vuejs.org/) which is a Vue.js based static site generator.
To add content, you'll need to write markdown files and then add them to the appropriate location in the repository.
If you aren't familiar with Markdown, _markdownguide.org_ has a [useful guide available](https://www.markdownguide.org/basic-syntax/).
There is also a [VitePress specific guide available](https://vitepress.dev/guide/markdown) which lists specific features above and beyond what is available with standard markdown.

As above, if you have any problems, please raise an [issue](https://github.com/aiaa-deic/computation-ai/issues).

### Run this Website Locally

For large changes, it can be very helpful to run the website locally to see how your changes will look.
This lets you try out changes, edit formatting,
and see how the site will look before you push your changes to the repository.
Use the information below to set up your computer for this type of editing.

#### 1. Install Node.js

This website is built using Node.js, so you'll need to install it on your computer.
You can look at <https://nodejs.org/> to get a version of node which you can install on your computer.
If you are successful you'll be able to open a terminal and run `node --version`
and `npm --version` to see the version of node and npm installed on your computer.
If you aren't sure which version to install, the long term support (LTS) version is usually the safest.

#### 2. Clone the Project

You'll need to clone the project to your computer.
The instructions referenced [above](https://docs.github.com/en/get-started/quickstart/contributing-to-projects#cloning-a-fork) have a section
describing how to do this.

#### 3. Install Dependencies

Using a command line terminal, you'll want to navigate to the root of the project.
You'll know you are in the right location and ready to install dependencies when you find a file named `package.json`.
This file is the node.js ecosystem's manifest file.
Once in this location, run the command `npm install`.

If successful, you'll see the dependencies installed with no errors.
Inside the `package.json` file you'll see a section called `scripts`.
This section defines the commands you can run on the project.
The important one here is `dev`.
Running the command `npm run dev` will start a local server and run the website locally.
You'll click the link provided in the terminal to open the website in your browser.
This will be something like `http://localhost:5173`.

Any changes you make to the documentation files will be reflected automatically each time you save a file.
When you are happy with the changes, you can save, commit, and push your changes to the repository.

::: tip Node vs. Other Ecosystems

If you are more familiar with the Python ecosystem, you can think of `package.json` as the `requirements.txt` file.
The node program `npm` is similar to the Python program `pip`.

:::
