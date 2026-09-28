# Portfolio

A minimal bilingual Hugo portfolio with a blog, RSS feeds, and no JavaScript
or external font dependencies.

## ⚒️ Local development

Install [mise](https://mise.jdx.dev). Start the local preview with:

```shell
mise run dev
```

## 📝 Blog posts

Create a post with:

```shell
mise run post my-post
```

Matching filenames identify translations automatically. Posts may be published
in just one language; the language switch falls back to the other language's
homepage when no translation exists.

RSS feeds are available at `/posts/index.xml` and `/ru/posts/index.xml`.

## 📜 License

Distributed under the MIT License. See [License](/LICENSE) for more information.
