# Copy Book

Copy book is a collection of texts that are commonly used around the web.

## Development

You need [Hugo](https://gohugo.io/) to run the dev server. If you have [Homebrew](https://brew.sh/) you can do the following:

```sh
brew install hugo
```

Check this [Hugo installation page](https://gohugo.io/getting-started/installing/) for installing on other systems.

Then clone the repo, install dependencies, and start the server locally.

```sh
git clone https://github.com/praveenjuge/copybook.git
cd copybook
npm install
npm run dev
```

Open [`http://localhost:1313`](http://localhost:1313) in your browser.

| Scripts         | Description                                     |
| --------------- | ----------------------------------------------- |
| `npm run dev`   | Starts a local Hugo server and Tailwind Watcher |
| `npm run build` | For generating production files                 |

## License

See the [LICENSE](https://github.com/praveenjuge/copybook/blob/main/LICENSE) file.
