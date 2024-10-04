Welcome contributors to the DSU website! 
This document will host detailed instructions on working with the quarto repo and using Github Actions to the publish the site. 

# Good to Know
- Always have another team member review your pull request with site changes. 
- They should render the changes on their local machine with `quarto_render("index.qmd")`. 
- Each time the `_quarto.yml` is changed, you will need to run `quarto_render()` to see the changes locally.

# Resources
[Quarto Website Documentation](https://quarto.org/docs/websites/)
[Github Pages](https://quarto.org/docs/publishing/github-pages.html)
[Rendering for CI](https://quarto.org/docs/publishing/ci.html#rendering-for-ci)
