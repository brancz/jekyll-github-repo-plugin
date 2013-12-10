Jekyll GitHub Repo Tag
======================

A liquid tag to display a GitHub repository in an organized clean way.

##Dependencies & Installation

###Dependencies

You will need the following dependencies to build your Jekyll project with
this plugin:

```
gem install json
gem install open-uri
```

You will also need to have bootstrap 3 and font-awesome 4 for the default
style.

```
<link rel="stylesheet" href="http://netdna.bootstrapcdn.com/bootstrap/3.0.3/css/bootstrap.min.css">
<link rel="stylesheet" href="http://netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css">
```

###Installation

Copy `github_repo_tag.rb` into your `_plugins` folder of your Jekyll project.

##Usage

Syntax: `{% render_github_repo [user/repo] %}`

Feel free to modify the html and style as you desire.

##Examples

```
{% render_github_repo flower-pot/jekyll-github-repo-plugin %}
```

Would generate a box as it is in this
[article](http://flowerpot.io/2013/12/10/jekyll-github-repo-plugin/).
