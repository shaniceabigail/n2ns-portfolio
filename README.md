<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h1 align="center">New2NonStop Home Page - Forked project</h1>

  <p align="center">
    It is a personal static website/portfolio template hosted with GitHub Pages, built forked and edited for New2NonStop
    <br />
    <strong>Author </strong>
    <a href="https://hashirshoaeb.github.io/portfolio"> hashirshoaeb.github.io/portfolio</a>
    <br />
    <br />
    
  </p>
</p>


<!-- ABOUT THE PROJECT -->

**Built with** [Nextjs](https://nextjs.org/) & [Bootstrap5](https://getbootstrap.com).



<!-- GETTING STARTED -->
# Getting Started

Follow the setup instructions below. Please feel free to reach out to me by filing an [issue](https://github.com/hashirshoaeb/portfolio/issues) or emailing me at hashirshoaeb@gmail.com for help configuring your project.

## Prerequisites

You should have [Nodejs](https://nodejs.org/en/) and [Git](https://git-scm.com/downloads) installed on your PC. You should also own a GitHub account.

## Setup

1. Fork this repoistory and clone it to your local machine.
    ```sh
      git clone https://github.com/<your-username>/portfolio.git
    ``` 

2. Edit the [config/config.js](https://github.com/hashirshoaeb/portfolio/blob/main/config/config.js) file. Replace [config/profile.png](https://github.com/hashirshoaeb/portfolio/blob/main/config/profile.png) with your image. 
    >Note: You need to rename your image file as `profile.png`.

3. Run following scripts in terminal/command prompt to install dependencies.
    ```sh
      npm install
      npm run build
    ```
## Testing

1. To test on your local server, run the following command:
    ```sh
      npm run dev
    ```

2. Open the browser to http://localhost:3000/

## Deployment

If it works locally, you can deploy your project to GitHub Pages. GitHub Pages provides two types of free domains, `<username>.github.io` and `<username>.github.io/<repository>`. You can choose the one that suits your needs. You can learn more about domain types from [here](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages#types-of-github-pages-sites).

### Deploy to \<your-username>.github.io/portfolio

Simply you just need to commit and push your changes to github. And [GitHub Actions](https://docs.github.com/en/actions/learn-github-actions/introduction-to-github-actions#overview) will take care of the deployment. Your site will be available at `https://<your-username>.github.io/portfolio`

### Deploy to \<your-username>.github.io

Create a new repository with your username as `<your-username>.github.io`. And let the following command do the job for you.

```sh
  npm run predeploy
  node scripts/pages.js <your-username> master
```

Your site will be available at `https://<your-username>.github.io`

<!-- CONTRIBUTING -->
# Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contribution you make would be **appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
# License

Distributed under the `MIT` License. See [LICENSE](https://github.com/hashirshoaeb/portfolio/blob/main/LICENSE) for more information.
