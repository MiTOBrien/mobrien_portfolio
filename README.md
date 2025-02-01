# Michael O'Brien Portfolio

This is my personal portfolio site built using [Jekyll](https://jekyllrb.com/) and hosted on [Netlify](https://mobrienportfolio.netlify.app/).

If you would like to use this as a template to create your own portfolio site follow the steps below.

## Prerequisites

Before you begin, ensure you have the following:

- A GitHub account
- Basic knowledge of Git and GitHub
- Ruby and Bundler installed on your local machine

## Getting Started

1. **Fork the Repository**
   - Click the "Fork" button at the top right of this page to create a copy of this repository in your GitHub account.
   - Remove "`-template`" from your new repo name so that the repo name is just "`portfolio`", or whatever you'd like to name it.

2. **Clone Your Fork**
   - Open your terminal and run the following command, replacing `YOUR_USERNAME` with your GitHub username and `YOUR_REPO_NAME` with your chosen repo name:
     ```
     git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
     ```

3. **Navigate to the Project Directory**
   ```
   cd YOUR_REPO_NAME
   ```

4. **Install Dependencies**
   - Run the following command to install the required gems:
     ```
     bundle install
     ```

## Customizing Your Site

1. **Modify the Configuration Files**
   - Open the `_config.yml` file in your favorite text editor.
   - Update the fields with your own personal info.

2. **Add Your Content**
   - You can add your own new sections in the `_data` directory, and/or modify the existing ones.

3. **Run the Site Locally**
   - Use the following command to serve your site locally and see the changes:
     ```bash
     jekyll serve
     ```
   - If you get an error run:
     ```bash
     bundle exec jekyll serve
     ```

## Deploying Your Site

1. **Push Your Changes to GitHub**
   - After making your changes, commit and push them to your forked repository:
   ```bash
    git add .
    git commit -m "Customize site"
    git push origin main
    ```

2. **Create a Netlify account or log into your account**
- I recommend logging in with your Github account
- On the left hand menu bar click on "Sites"
- On the right hand site click on "Add new site" and select "Import an existing project"
- Select "GitHub"
- It will ask you to 'authorize' your account
- Choose your portfolio project from the list of repositories
- I recommend giving it a meaningful site name or it will assign something random that will make your page harder to find.  i.e. yourname_portfolio
- Make sure your 'main' branch is selected to deploy (It should be by default)
- Scroll to the bottom and choose deploy


2. **Visit Your Site**
   - Your site should be live at `https://YOURSITENAME.netlify.app`.
   - You can check your deployed status under the sites tab to confirm when your site is deployed and live.

## (Optional) Choosing a Different Jekyll Theme

By default this repo uses this theme: [https://github.com/byanko55/jekyll-professional-resume](https://github.com/byanko55/jekyll-professional-resume)

If you want to use a different Jekyll theme, follow these steps:

1. **Find a Jekyll Theme**
   - Browse [Jekyll Themes](http://jekyllthemes.org/) or [GitHub Pages Themes](https://pages.github.com/themes/) to find a theme you like.

2. **Update the Gemfile**
   - Open the `Gemfile` and replace the existing theme with your chosen theme. For example:
     ```
     gem "your-chosen-theme"
     ```

3. **Update the Configuration**
   - Modify the `_config.yml` file to include the new theme name