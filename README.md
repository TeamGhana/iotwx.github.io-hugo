# IOTWX Website

- [IOTWX Website](#iotwx-website)
  - [BUILDING THE SITE LOCALlY](#building-the-site-locally)
  - [ADDING CONTENT](#adding-content)

This is the source code for the site [https://iotwx.github.io](https://iotwx.github.io). It uses the static site generator [Hugo](https://gohugo.io).

## BUILDING THE SITE LOCALlY

To build the site follow the following steps:

1. download and install the latest version of [Hugo](https://gohugo.io/getting-started/installing);

2. clone the master branch of [this repository](https://github.com/iotwx/iotwx.github.io-hugo.git);

   ```bash
   git clone --recursive https://github.com/iotwx/iotwx.github.io-hugo.git
   ```

3. from the root of the repository run

   ```bash
   hugo
   ```

   from the command line which will generate the site and put the static files in the the folder called `public`. You will need to check the site to make sure you did not break anything;

4. check in the site all of the site the content lives in `content`;

5. please read the `Hugo` docs to learn about [content management in Hugo](https://gohugo.io/content-management/). Have fun!

## ADDING CONTENT

1. After you have read some of the docs on content management (step 5 above),
   1. make a new branch
   2. add your changes
   3. Submit a pull request when ready

**Note**: the website will be built via a continuous integration service (CircleCI), i.e _you don't need to build your site locally_.

We welcome contributions of all kinds.
