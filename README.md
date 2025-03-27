# Quarto Templates

Standard Quarto templates for Displacement Tracking Matrix products.
*Warning: This is a work in progress. The templates are not yet ready for production use and are subject to change*

Supported templates
- **Slides**: HTML presentation slides. *Status: Draft*
- **Documentation**: HTML websites + pdf. *Status: Early draft*
- **Dashboard**: HTML dashboard. *Status: Planned*
- **Webpage**: HTML page. *Status: Planned*
- **Paper**: Single-page HTML + pdf. *Status: Planned*
- **Scrolly**: Single page HTML with scrollytelling elements. *Status: Planned*


## Installing

Choose the [template type] you want and type the following in your terminal:

```bash
quarto use template Displacement-Tracking-Matrix/quarto-templates-DTM/[template type]
```

This will install the extension and create an example .qmd file that you can use as a starting place for your product.

To add the template to an existing Quarto project, type:

```bash
quarto add template Displacement-Tracking-Matrix/quarto-templates-DTM/[template type]
```

## Prerequisites

Before installing a template, ensure you have the Quarto tool installed; a package manager for your code along with the packages you need installed; and a text editor or IDE that supports Quarto.

To set up your development environment using the Pixi tool, run the following:
Install Pixi on Windows:
```powershell
powershell -ExecutionPolicy ByPass -c "irm -useb https://pixi.sh/install.ps1 | iex"
```
Install Pixi on MacOS:
```bash
curl -fsSL https://pixi.sh/install.sh | bash
```
Install Quarto:
```bash
pixi global install quarto
```
In the folder where you want to create you project or you added the template, run the following:
```bashclear
pixi add python
pixi add [the libraries you want to install]
```

## Contributing

We welcome contributions to the Quarto templates. To contribute, please follow these steps:

- Contact bmcdonald@iom.int
- Fork the repository
- Create a new branch
- Make your changes
- Push your changes to your fork
- Create a pull request