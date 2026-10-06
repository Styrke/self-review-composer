# Self-Review Composer

A small, self-contained web tool for composing self-review instructions for AI agents.

Choose a preset, adjust the review process, and copy the generated instruction into your agent workflow. Everything runs locally in the browser; there is no build step or backend.

## Run locally

Open [`review-loop-composer.html`](review-loop-composer.html) in a modern browser.

You can also serve the directory locally:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000/review-loop-composer.html>.

## Contributing

Changes can be made directly in `review-loop-composer.html`. Please test the presets, controls, generated instruction, clipboard action, and both light and dark color schemes before submitting a pull request.

## License

No license has been selected yet.
