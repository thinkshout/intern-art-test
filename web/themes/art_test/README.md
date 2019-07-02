# art_test

art_test can be found in
/new-project-name/web/profiles/contrib/bene/themes/art_test
where new-project-name is your project.

art_test can be found in a project called "new-project-name" here:
/new-project-name/web/profiles/contrib/bene/themes/art_test

## Setup
- Update `Rakefile` to have the correct site path.
  For example, the line in the Rakefile should read
  `system 'browser-sync start --proxy "https://web.bene-test.localhost"
  --files "css/*.css" --no-inject-changes'`
  if your site is named bene-test
- Run `rake install` to install dependencies
- Log in using `drush uli --no-browser`
- Go to `https://localhost:3000/admin/appearance` and remove Bartik.
- Set `art_test` as the default theme.

## Compiling assets
This project uses Browsersync, Sass and Browserify
- Run `rake serve`
- Browser Sync will serve the site at http://localhost:3000.
  This will appear in your console when you run `rake serve`.

## Theme Updates
Update this theme when you want changes to apply to this installation only.
