# karanb23.github.io

This repository hosts the personal website for karanb23 and is served via GitHub Pages.

Live site
-------

- https://karanb23.github.io

Quick setup (local)
-------------------

1. Clone the repository:

   git clone https://github.com/karanb23/karanb23.github.io.git
   cd karanb23.github.io

2. If the site is static (HTML/CSS/JS only):

   - Open `index.html` directly in your browser, or
   - Run a simple local server and visit http://localhost:8000
     - Python 3: `python3 -m http.server 8000`
     - Node (http-server): `npx http-server -c-1 .`
     - VS Code: Use the "Live Server" extension.

3. If the site uses Jekyll (Ruby):

   - Install Ruby and Bundler (see https://jekyllrb.com/docs/installation/)
   - Install dependencies: `bundle install`
   - Run locally: `bundle exec jekyll serve --watch --incremental --host 127.0.0.1`

Deployment / GitHub Pages
-------------------------

- Because this repository is named `karanb23.github.io`, GitHub Pages will serve the site from the default branch (usually `main`) at https://karanb23.github.io.
- After pushing changes, allow a minute for Pages to build and then refresh the site. Clear your browser cache if you don't see updates.

Contributing
------------

Contributions are welcome. To contribute:

1. Fork the repo
2. Create a branch for your changes: `git checkout -b my-feature`
3. Make changes and commit them
4. Push and open a pull request

Contact
-------

- GitHub: https://github.com/karanb23
