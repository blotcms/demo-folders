# Demo folders

The material Blot's bundled templates are previewed on. Each directory here becomes a public demo blog (`<name>.blot.im`) and a ZIP people can download from the templates pages on blot.im.

This repository is a submodule of [blotcms/blot](https://github.com/blotcms/blot) at `app/templates/folders`. The code that syncs these folders into the demo blogs, and each blog's settings (`config.js`: title, template, menu, plugins), live in that repository under `app/templates/demo/`. See the README there for adding a folder and for how a deploy publishes changes.

To publish a change, commit and push it here, then commit the new submodule pointer in blotcms/blot and deploy.
