# gppmad.github.io
This is my personal blog, built with Hugo.

## Quick Start

### Run Locally

Start the Hugo development server:

```bash
hugo server
```

Your blog will be available at `http://localhost:1313/`

### Create a New Post

Create a new blog post:

```bash
hugo new content posts/your-post-title.md
```

Then edit the generated file in `content/posts/your-post-title.md` and set `draft = false` when ready to publish.

### Build for Production

Build the static site:

```bash
hugo
```

The generated files will be in the `public/` directory