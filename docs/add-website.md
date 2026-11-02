In order to add to the website:

- Fork this project
- Add `.md` file you would like to add into the `docs` folder
  - Additionally, you must follow the specific syntax as follows:
    - simple page: `- Adding to the Website: add-website.md)`
    - dropdown: you must have this nested system (refer to the example below)
- Add file(s) or new directory into the `mkdocs.yml` folder so it's visible for the public.
- Done!

```
- nav:
  - Home: index.md
  [...]
  - Technical:
      - Logging into SSH: ssh.md
  - Adding to the Website: add-website.md)
```
