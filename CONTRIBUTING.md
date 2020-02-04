

## What Type of Contributions Are Welcome?
All contributions welcome! 

## Code of Conduct
<a href="CODE_OF_CONDUCT.md">Code of Conduct</a>

## How I'm Keeping Things In Sync During Development.
The way I'm developing is to do changes in Observable notebook first. For this type of work, it has been a faster way to write working code. Because all the code is automatically executed in each cell when code changes, it allows me to catch bugs earlier than I would otherwise. I can have multiple plots of different types built in the same notebook and make sure they all still build as I change code! 

The active notebook is noted in the README. 

<i>I try to sync changes to the index.js file in this code repository after each work session.</i> 

Potential code to keep in sync is in several locations: 
- An Observable notebook
- This code repository, particularly in the index.js file in the dist directory. 
- Documentation as found in the docs folder in this code repository.
- The demo page found in the docs folder in this code repository.

#### Index.js & Observable notebook are almost always kept in sync. When they aren't, I'll let people know and put it in the README.
#### The demo page is not kept in sync and will only be updated occasionally. 
#### The docs are updated gradually. Sometimes there will be new or changing functions that aren't populated yet.



## Ways to Contribute!

### Documentation
Anything confusing or absent in documentation as well. Inline documentation, documentation built with documentation.js, tests, example incoming data jsons, and code changes are all welcome. Briefly check issues to see if your issue already exists.

#### How to Edit & Generate the Docs
There is Documentation on how to make the docs in the docs folder<a href="https://github.com/JustinGOSSES/wellioviz/blob/master/docs/MakingDocs.md"> here</a>

### Contributing Code
Code contributions are always welcome, whether it be small modifications or entire features. 

As the project gains momentum, check the <a href="https://github.com/JustinGOSSES/wellioviz/issues">Issues</a> for outstanding issues & features under development. There is an attempt at organizing the issues using the project board <a href="https://github.com/JustinGOSSES/wellioviz/projects/1">here</a>. For the most part, the issues board contains all the issues.. just in an organization to make it clear what is being worked on now.

If you’d like to contribute, but you’re not so experienced with JavaScript, look for good first issue tags or email the maintainer for suggestions.

### Issues, Features, and Bug Reports

Add a feature request or bug report issue <a href="https://github.com/JustinGOSSES/wellioviz/issues/new/choose">here</a> When you add an issue, there will be two choices for issues templates to use, one for bug reports and another for feature requests.

### Pull Requests
If you've fixed an issue in the code, please consider submitting a pull request, which is basically a fork or branch of this repository submitted back to it with a specific change. 
1. State why you are proposing this change. 
2. When you make a pull request, please try to keep the changes to one feature at a time if possible (not always possible). 
3. We don't have tests yet, so in lieu of that, please fork the active Observable notebook noted in the README add in your changed functions and make sure everything still works with your changes. If there are changes needed to be made to get things to work that are not in index.js but only in the Observable notebook, please note that in your pull request. This is unlikely but theoretically possible.
- Please consider other use-cases and make sure your code changes aren't narrowing the scope of wellioviz to only your use case.
- Follow the PUll REQUEST template <a href="https://github.com/JustinGOSSES/wellioviz/blob/master/.github/pull_request_template.md">here</a>

If anything is confusing, open an issue.
