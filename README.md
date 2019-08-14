## How to contribute blogs

1. Fork, https://github.com/rtrclubiitj/rtrclubiitj.github.io/
2. Execute `git clone https://github.com/<your-github-username>/rtrclubiitj.github.io`.
3. Go to the directory of the above repository.
4. Execute `git remote add origin_user https://github.com/<your-github-username>/rtrclubiitj.github.io`.
5. Execute `git checkout -b add-blog`.
6. Add your blog entry in `_posts` folder.
7. Execute `git add .`.
8. Execute `git commit -m "added blog entry"`.
9. Execute `git push origin_user add-blog`.
10. Make a PR by comparing `add-blog` of your fork and `master` of ours.

That's all. Your blog is under review.

## Rules for editing

1. **For adding blog entry**: The name of the file should be similar to, `2017-11-14-post_1.md`. Follow the `markdown` syntax. Be sure not to use any language(communicating, not programming :P) that is not accepted by society. Rest depends on the review of the members.
2. **How to push to github**: Once you execute the steps 1 to 4, then after that for submitting new PRs, you have to only start from master, by executing, `git pull origin master` and `git checkout -b "new blog"`.

Currently, only members of the Rotaract Club, IIT Jodhpur can add blog entries to our website.

If you are interested in fixing an issue then just comment on the thread, you will be guided afterwards. Any one can fix the issue, there are no constraints.

The portion below this line was taken from **Massively** README.md. We are thankful to its development team for allowing us to use it.

# Massively
> This is Massively, a text-heavy, article-oriented design built around a huge background
image.

See a preview of the Massively Jekyll Theme here: [https://iwiedenm.github.io/jekyll-theme-massively/](https://iwiedenm.github.io/jekyll-theme-massively/). <br>
Massively was originally designed by HTML5UP and Jekyll was integrated by [JekyllUp: Jekyll Themes](https://jekyllup.com)

## How to Use This Theme
Jekyll consumes themes in two flavors; gem-based or spread across multiple folders
in the site source. This port is of the second type. Concretely, it means that you
can simply grab the [zip][zip] or clone this repository, run `bundle install`
in the new directory and finally `bundle exec jekyll serve`.
You can now access your brand-new Jekyll site on [http://127.0.0.1:4000/][local].
Enjoy!

If you're completely new to Jekyll, check out it's [documentation][jekyll] first.
It's not too hard, we promise!

[zip]: https://github.com/iwiedenm/jekyll-theme-massively-src/archive/master.zip
[local]: http://127.0.0.1:4000/
[jekyll]: https://jekyllrb.com/

## Features

### Slapform.com Integration
[Slapform](https://slapform.com) is supported out of the box! Just add your email to ```_config.yml``` and test the form.
Every time one of your visitors submits the form, you'll get an email straight to your inbox containing the submission so you can get back to them right away. Slapform is very extendable, including AJAX submissions, webhooks, and more.

### Auto-Generating Sitemap
The sitemap is auto generated! Just simply change the sitemap variable in front matter of each page. It looks like so...
```
sitemap:
  priority: 0.7
  lastmod: 2017-11-02
  changefreq: weekly
```

## Credits
### Original README from HTML5 UP
```
Massively by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)


This is Massively, a text-heavy, article-oriented design built around a huge background
image (with a new parallax implementation I'm testing) and scroll effects (powered by
Scrollex). A *slight* departure from all the one-pagers I've been doing lately, but one
that fulfills a few user requests and makes use of some new techniques I've been wanting
to try out. Enjoy it :)

Demo images* courtesy of Unsplash, a radtastic collection of CC0 (public domain) images
you can use for pretty much whatever.

(* = not included)

AJ
aj@lkn.io | @ajlkn


Credits:

	Demo Images:
		Unsplash (unsplash.com)

	Icons:
		Font Awesome (fortawesome.github.com/Font-Awesome)

	Other:
		jQuery (jquery.com)
		Misc. Sass functions (@HugoGiraudel)
		Skel (skel.io)
		Scrollex (github.com/ajlkn/jquery.scrollex)
```
