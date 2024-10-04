# Data Stewardship Website

This website serves as a resource for Fisheries and Oceans Canada employees working in the Pacific Region Science Branch, providing support for their data stewardship and management responsibilities.

## Project Structure

The project has the following files and directories:

- `_quarto.yml`: The configuration file for the Quarto package.
- `index.qmd`: The home page of the website.
- `training-resources.qmd`: A page with our list of training resources. 
- `about.qmd`: The About page describing the Data Stewardship Unit serving the Pacific Region Science Branch.
- `perspectives/`: Directory containing pages related to different perspectives on data stewardship.
- `images/icons/`: Directory containing image icons for the pages.
- `styles/custom.css`: Custom CSS styles for the website.
- `README.md`: Documentation for the project.

## Getting Started

To run the website locally, follow these steps:

1. Clone the repository with git by running `git clone https://github.com/pbs-assess/data-stewardship-unit.git` in terminal. 
2. Install the required dependencies: `R -e "install.packages('quarto')"`
3. Preview the website: `R -e "quarto::quarto_render("index.qmd")"`

## Contributing

If you would like to contribute to this project, please follow the guidelines in [CONTRIBUTING.md](CONTRIBUTING.md).

## License

This project is licensed under the [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/).

