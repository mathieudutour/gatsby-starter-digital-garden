# Starter for the Digital Garden theme

Quickly get started using the Gatsby garden theme! This starter creates a new Gatsby site that is preconfigured to work with the [Gatsby garden theme](https://www.npmjs.com/package/gatsby-theme-garden).

## 🚀 Quick start

1.  **Create a Gatsby site.**

    Use the Gatsby CLI to create a new site, specifying the garden theme starter.

    ```shell
    # create a new Gatsby site using the garden theme starter
    gatsby new my-digital-garden https://github.com/mathieudutour/gatsby-starter-digital-garden
    ```

2.  **Start developing.**

    Navigate into your new site’s directory and start it up.

    ```shell
    cd my-digital-garden/
    gatsby develop
    ```

3.  **Open the code and start customizing!**

    Your site is now running at `http://localhost:8000`!

    To get started, check out the guide to [using a Gatsby theme](https://gatsbyjs.org/docs/themes/using-a-gatsby-theme), or the longer, [more detailed tutorial](https://gatsbyjs.org/tutorial/using-a-theme).

## 🧐 What's inside?

Here are the top-level files and directories you'll see in a site created using the notes theme starter.

```text
gatsby-starter-digital-garden
├── content
│   └── garden
│       ├── example-dir
│       │   └── hi.mdx
│       └── hello.mdx
├── .gitignore
├── .prettierrc
├── gatsby-config.js
├── LICENSE
├── package-lock.json
├── package.json
└── README.md
```

1.  **`/content`**: A content folder holding assets that the theme expects to exist. In this case, you're starting with some example notes! Delete the notes contained in `/content/garden` and start writing your own!

2.  **`.gitignore`**: This file tells git which files it should not track / not maintain a version history for.

3.  **`.prettierrc`**: This file tells [Prettier](https://prettier.io/) which configuration it should use to lint files.

4.  **`gatsby-config.js`**: This is the main configuration file for a Gatsby site. This is where you can specify information about your site (metadata) like the site title and description, which Gatsby plugins you’d like to include, etc. When using themes, it's where you'll include the theme plugin, and any customization options the theme provides.

5.  **`LICENSE`**: This starter is licensed under the MIT license.

6.  **`package-lock.json`** (See `package.json` below, first). This is an automatically generated file based on the exact versions of your npm dependencies that were installed for your project. **(You won’t change this file directly).**

7.  **`package.json`**: A manifest file for Node.js projects, which includes things like metadata (the project’s name, author, etc). This manifest is how npm knows which packages to install for your project.

8.  **`README.md`**: A text file containing useful reference information about your project.

## 🎓 Learning Gatsby

Looking for more guidance? Full documentation for Gatsby lives [on the website](https://www.gatsbyjs.org/).

Here are some places to start:

### Themes

- To learn more about Gatsby themes specifically, we recommend checking out the [theme docs](https://www.gatsbyjs.org/docs/themes/).

### General

- **For most developers, we recommend starting with our [in-depth tutorial for creating a site with Gatsby](https://www.gatsbyjs.org/tutorial/).** It starts with zero assumptions about your level of ability and walks through every step of the process.

- **To dive straight into code samples, head [to our documentation](https://www.gatsbyjs.org/docs/).** In particular, check out the _Reference Guides_ and _Gatsby API_ sections in the sidebar.
