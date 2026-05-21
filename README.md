# mars blog

Microblog by Amarah Boulanger. Lives at [1800mars.github.io/blog](https://1800mars.github.io/blog/).

Built with Jekyll, hosted on GitHub Pages.

## How to add a new post

1. Create a new file in `_posts/` named `YYYY-MM-DD-your-title.md`
2. Add the front matter at the top:
   ```
   ---
   layout: post
   title: "Your Post Title"
   date: YYYY-MM-DD
   tags: [tag1, tag2]
   summary: "One sentence summary."
   ---
   ```
3. Write your post in Markdown below the front matter.
4. Commit and push. GitHub builds it automatically.

## How to add images

1. Put image files in `assets/images/`
2. Link them in your post: `![description]({{ site.baseurl }}/assets/images/filename.jpg)`

## RSS

Feed is at [1800mars.github.io/blog/feed.xml](https://1800mars.github.io/blog/feed.xml)
