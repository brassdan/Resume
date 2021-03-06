# Resume

This is a place to store a markdown format of my resume which gets published and hosted to host your resume using [sinatra][s], [github-pages][gp] or [Heroku][h].

[gp]: http://pages.github.com/
[h]: http://heroku.com/

## Installation

 1. Fork this project
 2. Modify resume.md to be your resume.
 3. Modify config.yaml so that the data represents you, not icco.
 4. Edit views/style.less to make your resume look pretty.
 5. Install the gems [sinatra][s], [github-markup][gm], [git][g], [rack-test][rt], [heroku][h] and [less][l]
   * install the correct parser for [github-markup][gm], such as [rdiscount][r] for [Markdown][md].
 6. type `rake local` or `./resume.rb` to run locally. 
 7. To deploy to Heroku
   * Run `heroku create`
   * `rake deploy` to push your resume to the internet.
 8. To deploy to [github-pages][gp], run `rake github`.

[g]: http://github.com/schacon/ruby-git
[rt]: http://github.com/brynary/rack-test
[s]: http://www.sinatrarb.com/
[r]: http://github.com/rtomayko/rdiscount
[l]: http://lesscss.org/
[gm]: http://github.com/github/markup
[md]: http://en.wikipedia.org/wiki/Markdown


## License

resume.md is property of Daniel Weinstein. You are welcome to use it as a
base structure for your resume, but don't forget, you are not him.

The rest of the code is licensed CC-GPL. Remember sharing is caring.
