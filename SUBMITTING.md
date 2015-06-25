This document contains detailed instructions on how to write and submit drafts. Use these links to navigate to other parts of the documentation:

- [Introduction](http://www.sitepoint.com/introduction-to-sitepoints-peer-review/)
- Submitting Drafts
- [Joining as a Reviewer](http://www.sitepoint.com/becoming-sitepoints-peer-reviewer-how-and-why/)
- [FAQ](http://sitepoint.com/sitepoints-peer-review-faq)

---

## Before writing

This guide will contain best practices for submitting quality work. Quality work is reviewed faster, paid for faster, and scores you higher on the "regular authors" list, meaning you can get paid more per article, eventually. Related content: [SitePoint's Writing Guide](http://www.sitepoint.com/writing-guidelines/).

### MarkDown

The only accepted format is MarkDown. Do **not** submit in any other form. Do **not** include HTML in MarkDown. If you are not familiar with MD, please see the basics [here](http://markdowntutorial.com/) and/or [here](https://guides.github.com/features/mastering-markdown).

If you have no idea about which editor to use, the recommended MD editor is [Stackedit](https://stackedit.io/editor). It supports syntax highlight and [Github Flavored Markdown](https://help.github.com/articles/github-flavored-markdown/), which you should become familiar with.

### English Language

Make sure your English is good. Watch out for lowercase "i", missing commas, missing dots, typos. Use a spell checker - every modern browser has one. The better your English, the faster I review. It's best if you have someone who speaks good English pre-read your article. Please don't expect reviewers to fix your language - some will do it, but that's not what they're there for. Your English should be good enough to allow people to immediately dive into the content of your post - that is what leads to the best reviews and ultimately, the best posts.

### Titles and Subtitles

The post's title will be H1 (`#`) when published. This means you should never use anything higher than `##` (H2) in your draft. Keep your main section headings at `##`. Sub-sections are `###`, and so on.

Keep your headings short and effective - try for under 6 words.

Capitalize. Use [TitleCapitalization](http://titlecapitalization.com) to capitalize your headings properly. Use this on ALL headings, not just H2.

### Article Length

Try not to exceed 2000 words. Try not to be under 800 words. Word count **does not** include code.

## Submitting

To submit, you need to be familiar with the basics of Github. Please go through [this tutorial](https://guides.github.com/activities/hello-world) before continuing.

Step by step:

1. [Fork](https://guides.github.com/activities/forking) the peer review repo you've joined. If you have a fork already, synchronize it with the original version (in case the original was updated with other people's posts since you forked it, for example) as per [this post](https://help.github.com/articles/syncing-a-fork/).

	<img data-gifffer="http://www.sitepoint.com/wp-content/uploads/2015/06/1434739145peers-forking.gif" />

2. Create a **new branch for every article you intend to write** - this is very important. Make sure every new branch is based **off of the master branch of your fork**. A common error is branching when already on another branch, which will cause your pull requests to be turned into a single pull request if you commit that way. All draft pull requests submitted on the `master` branch will be rejected.

	<script type="text/javascript" src="https://asciinema.org/a/21683.js" id="asciicast-21683" async></script>

2. If there is no folder matching your name yet **under the Authors folder**, please make one. Make it your full name, but remove local characters. For example, Bruno Škvorc will have the folder "Bruno Skvorc" or "Bruno-Skvorc".

	<img data-gifffer="http://www.sitepoint.com/wp-content/uploads/2015/06/1434742814peers-author-folder.gif" />

3. Make a sub-folder for your post. Prefix the name with the number of posts in your folder. For example, if this is your first post in this repository, prefix with 01. If you already have three posts in this new system, prefix with 04. Keep the name short, but descriptive. For example, if your tutorial is called "How to set up ACL with Sentry in Laravel", a good **folder** name is "01 - Sentry ACL in Laravel" and a bad name is "01 - sentrylar". For articles of several parts, see below.

	<img data-gifffer="http://www.sitepoint.com/wp-content/uploads/2015/06/1434742805peers-article-folder.gif" />

4. Inside that folder, put the draft in MarkDown format (the file name doesn't matter as long as it ends in `.md`) and related images (if you wish to include any in the post).

	<img data-gifffer="http://www.sitepoint.com/wp-content/uploads/2015/06/1434742797peers-article-draft.gif" />

5. Send a [pull request](https://help.github.com/articles/using-pull-requests/).

	<img data-gifffer="http://www.sitepoint.com/wp-content/uploads/2015/06/1434743210peers-example-pr.gif" />

## Multi-part articles

If you got approval from the editor to submit a multi-part post, then put each part in its own folder. See [Rafie Younes](http://www.sitepoint.com/author/yrafie/)' folder as an example:

![](http://www.sitepoint.com/wp-content/uploads/2015/05/1433237933Screenshot-2015-06-02-11.38.22.png)

## After Submitting

Once a draft PR is submitted, it will be given a label of `peer review`:

![](http://www.sitepoint.com/wp-content/uploads/2015/06/1433238647Screenshot-2015-06-02-11.50.35.png)

It will then have to be in `peer review` mode for a specific amount of time **or** reviewed by a specific number of people before moving into `editor review` stage:

![](http://www.sitepoint.com/wp-content/uploads/2015/06/1433238787Screenshot-2015-06-02-11.52.48.png)

The duration and number of needed reviews will vary per channel.

Wait for feedback from other authors, or for feedback from the channel editor. People will comment on your PR directly. Fix errors when issues are raised concerning your post, try to be actively engaged in discussions about it. The ultimate goal is to iron it out to perfection. 

Please do not take critique personally - obvious trolls will be banned, of course, but everyone in the repo will try to help you improve, and it is expected that you do the same.
<script src="http://dab1nmslvvntp.cloudfront.net/wp-content/uploads/2015/06/1434812097gifffer.min_.js"></script><script>window.onload=function() {Gifffer();}</script>
