# Set up files
A typical .gitignore file for TTI wpengine website repos, and theme directory's .gitignore and .wpegitignore files for Github Actions deploy

>  Examples:
>  [i35wacocams](https://github.com/ttitamu/i35wacocams-wpengine) and [harleyandhobbit](https://github.com/ttitamu/harleyandhobbit-wpengine)

## How to use the files

### .gitignore
`/.gitignore`
- Add this [.gitignore file](https://github.com/himeylo/gitignore/blob/master/.gitignore) to your website's local parent directory for pushing to git
- Uncomment Theme section rows and edit to add theme name in place of <theme> for both rows
	https://github.com/himeylo/gitignore/blob/13009d9600587c45e4e62661a2b33808cf45d598/.gitignore#L23-L24
- Uncomment Plugin section rows and edit to add plugin name in place of <plugin> for both rows, if applicable
	https://github.com/himeylo/gitignore/blob/13009d9600587c45e4e62661a2b33808cf45d598/.gitignore#L27-L28

### theme's .gitignore
`/wp-content/themes/THEMENAME/.gitignore`
- Add this [.gitignore file](https://github.com/himeylo/gitignore/blob/master/wp-content/themes/THEMENAME/.gitignore) to your website's theme directory for Github Actions auto-deploy to production functionality

### theme's .wpegitignore
`/wp-content/themes/THEMENAME/.wpegitignore`
- Add this [.wpegitignore file](https://github.com/himeylo/gitignore/blob/master/wp-content/themes/THEMENAME/.wpegitignore) to your website's theme directory for Github Actions auto-deploy to production functionality

