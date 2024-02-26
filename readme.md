<h1 align="center">Hugo + Tailwind CSS Starter and Boilerplate</h1>

<p align="center">Hugoplate is a free starter template built with Hugo, and TailwindCSS, providing everything you need to jumpstart your Hugo project and save valuable time.</p>

<p align="center">Made with ♥ by <a href="https://zeon.studio/"> Zeon Studio</a></p>
<p align=center> If you find this project useful, please give it a ⭐ to show your support.</p>

<h2 align="center"> <a target="_blank" href="https://hugoplate.netlify.app/" rel="nofollow">👀 Demo</a> | <a  target="_blank" href="https://pagespeed.web.dev/analysis/https-hugoplate-netlify-app/6lyxjw6t4r?form_factor=desktop">Page Speed (95+)🚀</a>
</h2>

<p align="center">
  <a href="https://github.com/gohugoio/hugo/releases/tag/v0.121.2" alt="Contributors">
    <img src="https://img.shields.io/static/v1?label=min-HUGO-version&message=0.121.2&color=f00&logo=hugo" />
  </a>

  <a href="https://github.com/zeon-studio/hugoplate/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/zeon-studio/hugoplate" alt="license">
  </a>

  <a href="https://github.com/zeon-studio/hugoplate">
    <img src="https://img.shields.io/github/languages/code-size/zeon-studio/hugoplate" alt="code size">
  </a>

  <a href="https://github.com/zeon-studio/hugoplate/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/zeon-studio/hugoplate" alt="contributors">
  </a>
</p>

## 🎁 What's Included

We have included almost everything you need to start your Hugo project. Let's see what's included in this template:

### 📌 Key Features

- 👥 Multi-Authors
- 🎯 Similar Posts Suggestion
- 🔍 Search Functionality
- 🌑 Dark Mode
- 🏷️ Tags & Categories
- 🔗 Netlify setting pre-configured
- 📞 Support contact form
- 📱 Fully responsive
- 📝 Write and update content in Markdown
- 💬 Disqus Comment
- 🔳 Syntax Highlighting

### 📄 15+ Pre-designed Pages

- 🏠 Homepage
- 👤 About
- 📞 Contact
- 👥 Authors
- 👤 Author Single
- 📝 Blog
- 📝 Blog Single
- 🚫 Custom 404
- 💡 Elements
- 📄 Privacy Policy
- 🏷️ Tags
- 🏷️ Tag Single
- 🗂️ Categories
- 🗂️ Category Single
- 🔍 Search

### 📦 Tech Stack

- [Hugo](https://gohugo.io/)
- [Tailwind CSS](https://tailwindcss.com/)
- [PostCSS](https://postcss.org/)
- [PurgeCSS](https://purgecss.com/)
- [AutoPrefixer](https://autoprefixer.github.io/)
- [Hugo Modules](https://gohugo.io/hugo-modules/)
- [Markdown](https://markdownguide.org/)
- [Prettier](https://prettier.io/)
- [Jshint](https://jshint.com/)
- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)
- [Github Actions](https://github.com/features/actions)
- [Gitlab Ci](https://docs.gitlab.com/ee/ci/)
- [AWS Amplify](https://aws.amazon.com/amplify/)

---

## 🚀 Getting Started

First you need to [clone](https://github.com/zeon-studio/hugoplate) or [download](https://github.com/zeon-studio/hugoplate/archive/refs/heads/main.zip) the template repository, and then let's get started with the following process:

### ⚙️ Prerequisites

To start using this template, you need to have some prerequisites installed on your machine.

- [Hugo Extended v0.115+](https://gohugo.io/installation/)
- [Node v18+](https://nodejs.org/en/download/)
- [Go v1.20+](https://go.dev/doc/install)

### 👉 Project Setup

We build this custom script to make your project setup easier. It will create a new Hugo theme folder, and clone the Hugoplate theme into it. Then move the exampleSite folder into the root directory. So that you can start your Hugo server without going into the exampleSite folder. Use the following command to setup your project.

```bash
npm run project-setup
```

### 👉 Install Dependencies

Install all the dependencies using the following command.

```bash
npm install
```

### 👉 Development Command

Start the development server using the following command.

```bash
npm run dev
```

### 🎬 Still Confused? Watch a Quick Video

https://github.com/zeon-studio/hugoplate/assets/58769763/c260c0ae-91be-42ce-b8db-aa7f11f777bd

---

## 📝 Customization

This template has been designed with a lot of customization options in mind. You can customize almost anything you want, including:

### 👉 Site Config

You can change the site title, base URL, language, theme, plugins, and more from the `hugo.toml` file.

### 👉 Site Params

You can customize all the parameters from the `config/_default/params.toml` file. This includes the logo, favicon, search, SEO metadata, and more.

### 👉 Colors and Fonts

You can change the colors and fonts from the `data/theme.json` file. This includes the primary color, secondary color, font family, and font size.

### 👉 Social Links

You can change the social links from the `data/social.json` file. Add your social links here, and they will automatically be displayed on the site.

---

## 🛠 Advanced Usage

We have added some custom scripts to make your life easier. You can use these scripts to help you with your development.

### 👉 Update Theme

If you want to update the theme, then you can use the following command. It will update the theme to the latest version.

```bash
npm run update-theme
```

> **Note:** This command will work after running `project-setup` script.

### 👉 Update Modules

We have added a lot of modules to this template. You can update all the modules using the following command.

```bash
npm run update-modules
```

### 👉 Remove Dark Mode

If you want to remove dark mode from your project, then you have to do it manually from everywhere. So we build a custom script to do it for you. you can use the following command to remove dark mode from your project.

```bash
npm run remove-darkmode
```

> **Note:** This command will work before running `project-setup` script. If you already run the `project-setup` command, then you have to run `npm run theme-setup` first, and then you can run this command. afterward, you can run `npm run project-setup` again.

---

## 🚀 Build And Deploy

After you finish your development, you can build or deploy your project almost everywhere. Let's see the process:

### 👉 Build Command

To build your project locally, you can use the following command. It will purge all the unused CSS and minify all the files.

```bash
npm run build
```

### 👉 Deploy Site

We have provided 5 different deploy platform configurations with this template, so you can deploy easily.

- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)
- [Github Actions](https://github.com/features/actions)
- [Gitlab Ci](https://docs.gitlab.com/ee/ci/)
- [AWS Amplify](https://aws.amazon.com/amplify/)

And if you want to Host some other hosting platforms. then you can build your project, and you will get a `public` folder. that you can copy and paste on your hosting platform.

> **Note:** You must change the `baseURL` in the `hugo.toml` file. Otherwise, your site will not work properly.

---

## 🔒 Guide to Staying Compliant

### 🐞 Reporting Issues

We use GitHub Issues as the official bug tracker for this Template. Please Search [existing issues](https://github.com/zeon-studio/hugoplate/issues). It’s possible someone has already reported the same problem.
If your problem or idea has not been addressed yet, feel free to [open a new issue](https://github.com/zeon-studio/hugoplate/issues).

### 📝 License

Copyright (c) 2023 - Present, Designed & Developed by [Zeon Studio](https://zeon.studio/)

**Code License:** Released under the [MIT](https://github.com/zeon-studio/hugoplate/blob/main/LICENSE) license.

**Image license:** The images are only for demonstration purposes. They have their license, we don't have permission to share those images.

---

## 🖼️ Showcase

List of projects people are building with **Hugoplate**! Have you built a project with Hugoplate? Submit it by creating a pull request and we'll feature it here!

| [![Open Neuromorphic](https://tinyurl.com/hp7avtje)](https://open-neuromorphic.org/) | [![AI Models](https://tinyurl.com/mu4p7dhb)](https://aimodels.org/) | [![Hugobricks](https://tinyurl.com/4x3uwhm9)](https://www.hugobricks.preview.usecue.com/) |
|:---:|:---:|:---:|
| **Open Neuromorphic** | **AI Models** | **Hugobricks** |

```
hugoplate
├─ .devcontainer
│  ├─ Dockerfile
│  └─ devcontainer.json
├─ .editorconfig
├─ .git
│  ├─ HEAD
│  ├─ config
│  ├─ description
│  ├─ hooks
│  │  ├─ applypatch-msg.sample
│  │  ├─ commit-msg.sample
│  │  ├─ fsmonitor-watchman.sample
│  │  ├─ post-update.sample
│  │  ├─ pre-applypatch.sample
│  │  ├─ pre-commit.sample
│  │  ├─ pre-merge-commit.sample
│  │  ├─ pre-push.sample
│  │  ├─ pre-rebase.sample
│  │  ├─ pre-receive.sample
│  │  ├─ prepare-commit-msg.sample
│  │  ├─ push-to-checkout.sample
│  │  └─ update.sample
│  ├─ index
│  ├─ info
│  │  └─ exclude
│  ├─ logs
│  │  ├─ HEAD
│  │  └─ refs
│  │     ├─ heads
│  │     │  └─ main
│  │     └─ remotes
│  │        └─ origin
│  │           └─ HEAD
│  ├─ objects
│  │  ├─ info
│  │  └─ pack
│  │     ├─ pack-7faf376e7ca2000f9d46ad3797efdf7c074ef2c4.idx
│  │     └─ pack-7faf376e7ca2000f9d46ad3797efdf7c074ef2c4.pack
│  ├─ packed-refs
│  └─ refs
│     ├─ heads
│     │  └─ main
│     ├─ remotes
│     │  └─ origin
│     │     └─ HEAD
│     └─ tags
├─ .github
│  ├─ ISSUE_TEMPLATE
│  │  └─ bug_report.yml
│  └─ workflows
│     └─ main.yml
├─ .gitignore
├─ .gitlab-ci.yml
├─ .jshintrc
├─ .markdownlint.json
├─ .prettierrc
├─ .vscode
│  ├─ extensions.json
│  └─ tasks.json
├─ LICENSE
├─ amplify.yml
├─ assets
│  ├─ images
│  │  ├─ avatar-sm.png
│  │  ├─ avatar.png
│  │  ├─ banner.png
│  │  ├─ call-to-action.png
│  │  ├─ favicon.png
│  │  ├─ gallery
│  │  │  ├─ 01.jpg
│  │  │  ├─ 02.jpg
│  │  │  ├─ 03.jpg
│  │  │  ├─ 04.jpg
│  │  │  ├─ 05.jpg
│  │  │  └─ 06.jpg
│  │  ├─ image-placeholder.png
│  │  ├─ logo-darkmode.png
│  │  ├─ logo.png
│  │  ├─ no-search-found.png
│  │  ├─ og-image.png
│  │  ├─ service-1.png
│  │  ├─ service-2.png
│  │  └─ service-3.png
│  └─ scss
│     └─ custom.scss
├─ config
│  └─ _default
│     ├─ languages.toml
│     ├─ menus.en.toml
│     ├─ module.toml
│     └─ params.toml
├─ content
│  └─ english
│     ├─ _index.md
│     ├─ about
│     │  └─ _index.md
│     ├─ authors
│     │  ├─ _index.md
│     │  ├─ john-doe.md
│     │  ├─ sam-wilson.md
│     │  └─ william-jacob.md
│     ├─ blog
│     │  ├─ _index.md
│     │  ├─ post-1.md
│     │  ├─ post-2.md
│     │  ├─ post-3.md
│     │  └─ post-4.md
│     ├─ contact
│     │  └─ _index.md
│     ├─ pages
│     │  ├─ elements.md
│     │  └─ privacy-policy.md
│     └─ sections
│        ├─ call-to-action.md
│        └─ testimonial.md
├─ data
│  ├─ social.json
│  └─ theme.json
├─ go.mod
├─ hugo.toml
├─ i18n
│  └─ en.yaml
├─ images
│  ├─ screenshot.png
│  └─ tn.png
├─ netlify.toml
├─ package.json
├─ postcss.config.js
├─ readme.md
├─ scripts
│  ├─ clearModules.js
│  ├─ projectSetup.js
│  ├─ removeDarkmode.js
│  ├─ themeSetup.js
│  └─ themeUpdate.js
├─ tailwind.config.js
├─ theme.toml
├─ themes
│  └─ hugoplate
│     ├─ assets
│     │  ├─ js
│     │  │  └─ main.js
│     │  ├─ plugins
│     │  │  ├─ maps
│     │  │  │  └─ google-map.js
│     │  │  └─ swiper
│     │  │     ├─ swiper-bundle.css
│     │  │     └─ swiper-bundle.js
│     │  └─ scss
│     │     ├─ base.scss
│     │     ├─ buttons.scss
│     │     ├─ components.scss
│     │     ├─ custom.scss
│     │     ├─ main.scss
│     │     ├─ module-overrides.scss
│     │     ├─ navigation.scss
│     │     └─ utilities.scss
│     └─ layouts
│        ├─ 404.html
│        ├─ _default
│        │  ├─ baseof.html
│        │  ├─ list.html
│        │  ├─ single.html
│        │  ├─ taxonomy.html
│        │  └─ terms.html
│        ├─ about
│        │  └─ list.html
│        ├─ authors
│        │  ├─ list.html
│        │  └─ single.html
│        ├─ blog
│        │  ├─ list.html
│        │  └─ single.html
│        ├─ contact
│        │  └─ list.html
│        ├─ index.html
│        └─ partials
│           ├─ call-to-action.html
│           ├─ components
│           │  ├─ author-card.html
│           │  ├─ blog-card.html
│           │  ├─ breadcrumb.html
│           │  ├─ language-switcher.html
│           │  ├─ pagination.html
│           │  ├─ theme-switcher.html
│           │  └─ tw-size-indicator.html
│           ├─ essentials
│           │  ├─ footer.html
│           │  ├─ head.html
│           │  ├─ header.html
│           │  ├─ script.html
│           │  └─ style.html
│           ├─ page-header.html
│           └─ widgets
│              ├─ categories.html
│              ├─ tags.html
│              └─ widget-wrapper.html
├─ vercel-build.sh
└─ vercel.json

```