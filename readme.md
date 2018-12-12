## Purpose
This is a test of evaluating [Hexo](https://hexo.io/) - a static site generating tool, mainly for blogging - to be used as the framework for new church web site.

## Try locally
1. Install nodejs from https://nodejs.org/en/ if not installed yet.

2. Install git from https://git-scm.com/downloads if not installed yet.

3. Install hexo using command line bellow
```
npm install -g hexo-cli
```

4. Clone this repository.
```
git clone https://github.com/gallen/cimnewsite-hexo
```

5. Goto the cloned folder and install required packages.
```
cd cimnewsite-hexo
npm install
```

6. Run hexo local server
```
hexo serve
```
You'll be able to see you local site on http://localhost:4000

## Write post
Either follow hexo document https://hexo.io/docs/writing or just create markdown file anywhere under folder 'source/_posts'. Use any .md file under 'source/_posts' as example.

## Hosting, CI and CMS
* Hosting: The generated site is just static files, any hosting provider is fine. Github/Gitlab page, google firebase, zeit now, netlify all provide generous free hosting option.

* CI(continuous build): there're quite a lot online CI options there. Travis is quite popular. By far netlify is most easy one and has good integration with github as well.

* CMS: provide option for non-tech writer to update the content. No need to know git/github etc. Netlify provides an out of box template for hexo, amazing :)

Netlify hosting: https://cimnewsite.netlify.com/


Netlify cms: https://cimnewsite.netlify.com/admin (try login with your google account)

