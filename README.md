# adamfriswell.com (My personal portolio website)

## Info
- Hosting: GitHub pages
- Domain registrar: GoDaddy
- Framework: Jekyll
- CI/CD: GitHub Actions

## Background
During the first lockdown in 2020 I thought I'd make good use of the time and develop a personal portfolio site. I'd been told by senior devs that every web dev should have one, and knew it would be a good asset to have moving forwards. I also wanted to use it as an opportunity to learn some new tech.

The first issue I wanted to address was hosting. I had experience using Azure and was intersted in learning about AWS, but both seemd very involved (and expensive) for what I wanted to produce, which is essentially a static site. I found GitHub lets you host a site for free with [GitHub Pages](https://pages.github.com/), which was perfect for what I was looking for, given I use it for my personal version control anyway. I went ahead and purchased my first domain from [GoDaddy](https://www.godaddy.com/en-uk). 

The next question was to address which framework I wanted to use, I have experience in MVC and Angular from work, but again wanted to use this as an opportunity to learn something new. I was keen to learn React or Vue but again seemed overkill for what I wanted. I looked at static site generators like [Jekyll](https://jekyllrb.com/) and Hugo, before deciding to go with Jekyll. I went with this mainly because GitHub pages is powered by Jekyll, so seemed a natural fit, and also because it uses Ruby which I had no prior experience in using.

Using Jekyll with GitHub pages means that once you push some commits it will kick off a GitHub action workflow with a build and deploy step, automatically making my changes live - very easy!

I've found this experience both valuable and fun, I had no prior experience of making a live site from scratch or managing DNS records and such (as the Ops team manage this at work). It also helped me hone my HTML and CSS skills, as well as learning new skills in: Jekyll, GitHub pages + actions, Ruby (Gems, Bundler) and [Liquid](https://shopify.github.io/liquid/).
