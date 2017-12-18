- forwarded URL, http://people.lis.illinois.edu/~bzelip/

2017-12-18
- jekyllized this site for balancing local development workflow and retaining the easyness of github pages
  - using jekyll isn't ideal, but this way minimizes the storage/duplication-of-files overhead for local development and web hosting
  - excluding as many files as possible via _config.yml helps with this balancing act
    - things like dev_notes.md are kept in git, but are not built and stored locally via jekyll
- updated css workflow
  - one script using postcss-cli for concatenating through minimizing -- this is my modern/contemporary/most recent postcss/npm workflow -- notice not even using `css/src/x.css` and `css/dist/x.css`, but rather building `css/x.min.css` from `css/x.css`. 