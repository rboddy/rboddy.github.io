# This is Documentation on Github
> "Can you look in to how they do documentation on Github. Internally Confluence is a great tool, but I want to know how all these Github repos have this awesome public facing documentation."
> -Ray Flowers 2017

## So How do we Document on Github?

There are two main ways to document on Github. They are:
* Create a README.md
* Create a Wiki

But wait! That's stuff we know right? As users of Github, we check out READMEs and Wikis all the time. But how do we make it look readable for the public (like this one)? And then how do we turn it into a public facing website for the every day non-github user?

## Github Markdown

Oh sick, there's markdown. I can dig it. I like style. Click [here](https://guides.github.com/features/mastering-markdown/) to learn all about that markdown. It's pretty generic stuff. It does, however, offer some pretty neat features for documentation. Such as:

### Syntax Highlighting:

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
That's pretty neat.

### Task Lists:

- [x] This is a complete item
- [ ] This is an incomplete item

We can populate these with all kinds of fun features.

### Images:

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

Yeah, that's Yaktocat. I don't know his relation to Octocat, but he seems pretty sweet.

## Github Pages

So you have this super cool README.md file and maybe you have a repo that you want to be able to throw some web based documentation together for. The perfect solution is a Github Page. Click [here](https://rboddy.github.io) to see the page I created for these Docs. How do you do this? Well you can find the easy 3 step solution [here](https://pages.github.com/). That covers most of what you need to know. If you want to give an existing repo a custom domain to host your README.md file, just add a custom domain to an existing repo by going to "Settings" and finding the custom domain input field. It's that easy! I know, super cool stuff.

