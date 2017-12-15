hexo-theme-mirror
=================

A hexo theme for creating a mirror's website, used by [BJTU Free and Open Source Software Mirror](https://mirror.bjtu.edu.cn/).

# Usage

1. Use hexo to create a website, use npm to remove `hexo-generator-index`, because we will have a custom index. Install `hexo-renderer-nunjucks` and `hexo-renderer-stylus`.

2. Clone this repo to `YOURSITE/themes/mirror`.

3. Edit `YOURSITE/themes/mirror/_config.yml`, `YOURSITE/_config.yml`.

4. Create different page as you `menu` sector in `YOURSITE/themes/mirror/_config.yml`, if you want to have a mirror table, add `layout: indexTable` to `YOURSITE/source/index.html` (or markdown file).

5. Added your json files, one is `YOURSITE/source/status/task_status.json`, use [mirror](https://github.com/ideal/mirror/) to generate it. Another is `YOURSITE/source/help/desc_help.json`, you can get a example [here](https://mirror.bjtu.edu.cn/help/desc_help.json).
