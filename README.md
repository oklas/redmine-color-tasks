# redmine-color-tasks

This is Redmine theme with tasks colours like Mantis tasks colors.

The two additional task status is provided. You may be want
to add task **Acknowledged** (7) and **Confirmed** (8)
in "Adminstration" > "Issue statuses".

This simple theme conceived as overloading of existing theme.
By default it overload the standart **classic** Redmine theme.
It's look like this:

![Overview Classic Theme Screenshot](https://raw.github.com/oklas/redmine-color-tasks/master/screenshots/classic.png
 "Classic")

It is possible to overload any other theme by edition 
application.css file of that theme. Simple add inclusion of
color_tasks.css to application.css file of your favorite theme.


For example to enable colours for NYSenate
[Gitlab-looking](https://github.com/nysenate/nyss-gitlab-redmine-theme)
theme, add to application.css:

    @import url(../../redmine-color-tasks/stylesheets/color-tasks.css);

The result will be like so:

![Overview Gitlab Theme Screenshot](https://raw.github.com/oklas/redmine-color-tasks/master/screenshots/gitlab.png
 "Gitlab")


License MIT

Serguei Okladnikov <oklaspec@gmail.com>