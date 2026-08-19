---
title: Weiyuan Chen's homepage
feature_text: |
  ## Weiyuan Chen
  Striving to produce high-quality research and also keep an open mind for critical ideas and collaboration.
feature_image: "https://picsum.photos/1300/400?image=989"
excerpt: "Homepage of Weiyuan Chen, PhD student in Computer Science at Virginia Tech."
---

- My name is Weiyuan Chen. I am a second year PhD student researching advanced reasoning methods in LLMs advised by [Prof. Tu Vu](https://tuvllms.github.io/). Previously I achieved a Bachelor's degree in Computer Science at Zhejiang University. I'm fortunate to have worked with [Prof. Arman Cohan](https://armancohan.com/), and [Prof. Ningyu Zhang](https://x.com/zxlzr?lang=en).

{% include button.html text="Github" icon="github" link="https://github.com/katie-chen2" color="#0366d6" %} {% include button.html text="LinkedIn ☕️" link="https://www.linkedin.com/in/weiyuan-chen-273b03388/" color="#f68140" %} {% include button.html text="X" icon="twitter" link="https://x.com/WeiyuanChen01" color="#0d94e7" %} {% include button.html text="Install Alembic ⚗️" link="https://github.com/daviddarnes/alembic#installation" %}

## Recent News
- <span class="news-date">Aug, 2025.</span> Joined Virginia Tech as a Computer Science PhD student.
- <span class="news-date">Jun, 2025.</span> Graduated from Zhejiang University with a Bachelor's degree in Computer Science.

## Highlighed Publications

{% include publication-item.html
  title="Prism: Pushing the Frontier of Deep Think via Process Reward Model-Guided Inference"
  url="https://arxiv.org/abs/2603.02479"
  authors="Rituraj Sharma, <strong>Weiyuan Chen</strong>, Noah Provenzano, Tu Vu"
  paper_url="https://arxiv.org/abs/2603.02479"
  huggingface_url="https://huggingface.co/papers/2603.02479"
  code_url="https://github.com/Rituraj003/PRISM/"
%}

{% include publication-item.html
  title="AbGen: Evaluating Large Language Models in Ablation Study Design and Evaluation for Scientific Research"
  url="https://aclanthology.org/2025.acl-long.611/"
  authors="Yilun Zhao, <strong>Weiyuan Chen</strong>, Zhijian Xu, Manasi Patwardan, Chengye Wang, Yixin Liu, Lovekesh Vig, Arman Cohan"
  paper_url="https://aclanthology.org/2025.acl-long.611/"
  huggingface_url="https://huggingface.co/papers/2507.13300"
  code_url="https://github.com/yale-nlp/AbGen"
%}

## Examples

Here are a few examples of Alembic out in the wild being used in a variety of ways:

- [bawejakunal.github.io](https://bawejakunal.github.io/)
- [case2111.github.io](https://case2111.github.io/)
- [karateca.org](https://www.karateca.org/)

## Installation

### Quick setup

To give you a running start I've put together some starter kits that you can download, fork or even deploy immediately:

- ⚗️🍨 Vanilla Jekyll starter kit  
  [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/daviddarnes/alembic-kit){:style="background: none"}
- ⚗️🌲 Forestry starter kit  
  [![Deploy to Forestry](https://assets.forestry.io/import-to-forestry.svg)](https://app.forestry.io/quick-start?repo=daviddarnes/alembic-forestry-kit&engine=jekyll){:style="background: none"}  
  [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/daviddarnes/alembic-forestry-kit){:style="background: none"}
- ⚗️💠 Netlify CMS starter kit  
  [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/daviddarnes/alembic-netlifycms-kit&stack=cms){:style="background: none"}

- ⚗️:octocat: GitHub Pages with remote theme kit  
  {% include button.html text="Download kit" link="https://github.com/daviddarnes/alembic-kit/archive/remote-theme.zip" color="#24292e" %}
- ⚗️🚀 Stackbit starter kit  
  [![Create with Stackbit](https://assets.stackbit.com/badge/create-with-stackbit.svg)](https://app.stackbit.com/create?theme=https://github.com/daviddarnes/alembic-stackbit-kit){:style="background: none"}

### As a Jekyll theme

1. Add `gem "alembic-jekyll-theme"` to your `Gemfile` to add the theme as a dependancy
2. Run the command `bundle install` in the root of project to install the theme and its dependancies
3. Add `theme: alembic-jekyll-theme` to your `_config.yml` file to set the site theme
4. Run `bundle exec jekyll serve` to build and serve your site
5. Done! Use the [configuration](#configuration) documentation and the example [`_config.yml`](https://github.com/daviddarnes/alembic/blob/master/_config.yml) file to set things like the navigation, contact form and social sharing buttons

### As a GitHub Pages remote theme

1. Add `gem "jekyll-remote-theme"` to your `Gemfile` to add the theme as a dependancy
2. Run the command `bundle install` in the root of project to install the jekyll remote theme gem as a dependancy
3. Add `jekyll-remote-theme` to the list of `plugins` in your `_config.yml` file
4. Add `remote_theme: daviddarnes/alembic@main` to your `_config.yml` file to set the site theme
5. Run `bundle exec jekyll serve` to build and serve your site
6. Done! Use the [configuration](#configuration) documentation and the example [`_config.yml`](https://github.com/daviddarnes/alembic/blob/master/_config.yml) file to set things like the navigation, contact form and social sharing buttons

### As a Boilerplate / Fork

_(deprecated, not recommended)_

1. [Fork the repo](https://github.com/daviddarnes/alembic#fork-destination-box)
2. Replace the `Gemfile` with one stating all the gems used in your project
3. Delete the following unnecessary files/folders: `.github`, `LICENSE`, `screenshot.png`, `CNAME` and `alembic-jekyll-theme.gemspec`
4. Run the command `bundle install` in the root of project to install the jekyll remote theme gem as a dependancy
5. Run `bundle exec jekyll serve` to build and serve your site
6. Done! Use the [configuration](#configuration) documentation and the example [`_config.yml`](https://github.com/daviddarnes/alembic/blob/master/_config.yml) file to set things like the navigation, contact form and social sharing buttons

## Customising

When using Alembic as a theme means you can take advantage of the file overriding method. This allows you to overwrite any file in this theme with your own custom file, by matching the file name and path. The most common example of this would be if you want to add your own styles or change the core style settings.

To add your own styles copy the [`styles.scss`](https://github.com/daviddarnes/alembic/blob/master/assets/styles.scss) into your own project with the same file path (`assets/styles.scss`). From there you can add your own styles, you can even optionally ignore the theme styles by removing the `@import "alembic";` line.

If you're looking to set your own colours and fonts you can overwrite them by matching the variable names from the [`_settings.scss`](https://github.com/daviddarnes/alembic/blob/master/_sass/_settings.scss) file in your own `styles.scss`, make sure to state them before the `@import "alembic";` line so they take effect. The settings are a mixture of custom variables and settings from [Sassline](https://medium.com/@jakegiltsoff/sassline-v2-0-e424b2881e7e) - follow the link to find out how to configure the typographic settings.
