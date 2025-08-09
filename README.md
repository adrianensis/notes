# Notes reader (markdown notes)

1. Clone [https://github.com/adrianensis/static-site](https://github.com/adrianensis/static-site) repo in project root folder
   1. `git clone git@github.com:adrianensis/static-site.git`
2. Run `static-site/scripts/user/build.dekstop`
2. Run `static-site/scripts/user/run.dekstop` to run the app locally in your browser
3. Or read `static-site/README.md` usage section
4. Put your notes inside `content`, like `content/Notes`.
5. Specify `content` variable in `content/config.json` so the system can find your files.
   1. Example: `"content":"content/Notes"`
6. Fill `content/paths.json` with your folder/files structure.
7. Refresh the app.