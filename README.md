# RandomBlogSnippets 🚀

Get random blog posts from your personal blog and update your Github README.md with them.

## Features ✨

- Scrape random blog posts and update your Github README.md.
- Easy to set up and use.

## Setting up ⚙️

1. Fork or clone this repository.
2. Remember to replace the `URL` and `CSS_SELECTOR` environment variables within the `env` section of `get_post.yml` file.
3. Replace the links inside `README.md` and `update_readme.py` with your own blog URL and CSS selector.
4. Update the README_template.md file with your desired content and placeholders.
5. Set up a GitHub Actions secret (`BLOG_POSTS`) containing a personal access token with `repo` scope. To create a new personal access token, go to your GitHub account settings -> Developer settings -> Personal access tokens, and generate a new one. Make sure to check the 'repo' scope before generating it. Finally, go to your repository's Settings -> Secrets and add a new secret with the name 'BLOG_POSTS' and the value as your generated token.
6. Enable the GitHub Actions workflow on your forked or cloned repository.
7. I've commented out areas where you might want to consider further modifications, so check them out!

Now, the blog posts will be automatically updated on your Github README.md!

## Contributions Welcome! 🌟

Feel free to contribute by adding new features, enhancing existing code, or fixing bugs! Pull requests are appreciated.
