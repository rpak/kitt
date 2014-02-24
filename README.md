# KITT
A reference implementation for integrating the design and development teams using tools and process. Your project's KITT is the integration point between your design and development teams. It's okay to realize that your design process does not mesh with your software development process. KITT is both process and digital assets.

## Process Goals
1. Ensure UI components or concepts match the [Ubiquitous Language](http://guide.agilealliance.org/guide/ubiquitous.html) of the project.
2. Assets are part of a living catalog and represent the current state of the UI.
3. CSS and Web Components should represent the production version of code. This will likely require the pairing of designers with developers. Pairing will ensure the practices of the organization are followed.

## Anatomy of your KITT
1. A Kit of Parts, semantic listing of UI components, for your application (example: [Semantic UI](http://semantic-ui.com/))
2. Example pages using UI components that reflect real-world usage
4. Description of HTML Elements with accompanied CSS and required markup
5. CSS file to be used by development teams in production

## Setup

### with GitHub Pages
Create GitHub Project Pages [manually](https://help.github.com/articles/creating-project-pages-manually). Checkout [GitHub Pages](http://pages.github.com/) or [Help](https://help.github.com/categories/20/articles) for more information about authoring options.

1. ```git checkout --orphan gh-pages```
1. ```git rm -rf .```
2. ```echo 'My Project' > index.html```
3. ```git add index.html```
4. ```git commit -a -m 'Create index page'```
5. Within about ten minutes your page should be accessible at http://```$organization_name```.github.io/```$repository_name```


## Additional Information
1. [Nicole Sullivan's Object Oriented CSS](https://www.google.com/search?q=stubbornella+oocss)