# Giscus Comments for My Website

This repository hosts the Giscus comment system configuration for my website. Giscus is a GitHub Discussions-based comment system that allows visitors to leave feedback using their GitHub accounts.

## Features

- **GitHub Login**: Secure authentication for commenting.
- **VuePress Integration**: Seamless setup with static site generators.
- **Customizable**: Tailor appearance and behavior to fit your site.
- **Multi-language Support**: Accessible for a global audience.
- **Emoji Reactions**: Users can react to comments with emojis.

## Configuration
Update your VuePress config.js:
```
plugins: [
  [
    "giscus",
    {
      repo: "yourusername/your-repo",
      repoId: "your-repo-id",
      category: "Announcements",
      categoryId: "your-category-id",
      mapping: "pathname",
      strict: false,
      reactionsEnabled: true,
      emitMetadata: false,
      inputPosition: "top",
      theme: "preferred_color_scheme",
      lang: "zh-CN",
    },
  ],
],
```
