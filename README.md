<!-- @head-content@ -->
# laplacian/project.base-template

This template generates scripts and other basic files needed for a Laplacian based project.

<!-- @head-content@ -->

<!-- @toc@ -->
## Table of contents
1. [Usage](#usage)


1. [Source list](#source-list)



<!-- @toc@ -->

<!-- @main-content@ -->
## Usage

Add the following entry to your project definition.
```yaml
project:
  templates:
  - group: laplacian
    name: project.base-template
    version: 1.0.0
```




## Source list


[README.md](<./README.md>)

[.editorconfig](<./.editorconfig>)

[.gitattributes](<./.gitattributes>)

[.gitignore](<./.gitignore>)

[model/project/sources.yaml](<./model/project/sources.yaml>)

[model/project.yaml](<./model/project.yaml>)

[src/README.md.hbs](<./src/README.md.hbs>)

[src/.editorconfig.hbs](<./src/.editorconfig.hbs>)

[src/.gitattributes.hbs](<./src/.gitattributes.hbs>)

[src/.gitignore.hbs](<./src/.gitignore.hbs>)

[src/scripts/{each project.subprojects as subproject}{hyphen subproject.group}-{hyphen subproject.name}/publish-local.sh.hbs](<./src/scripts/{each project.subprojects as subproject}{hyphen subproject.group}-{hyphen subproject.name}/publish-local.sh.hbs>)

[src/scripts/{each project.subprojects as subproject}{hyphen subproject.group}-{hyphen subproject.name}/update-project.sh.hbs](<./src/scripts/{each project.subprojects as subproject}{hyphen subproject.group}-{hyphen subproject.name}/update-project.sh.hbs>)

[src/scripts/{if (or project.templates project.template_files)}generate.sh.hbs](<./src/scripts/{if (or project.templates project.template_files)}generate.sh.hbs>)

[src/scripts/{if project.subprojects}git-status-subprojects.sh.hbs](<./src/scripts/{if project.subprojects}git-status-subprojects.sh.hbs>)

[src/scripts/{if project.subprojects}update-subprojects.sh.hbs](<./src/scripts/{if project.subprojects}update-subprojects.sh.hbs>)

[src/scripts/laplacian-generate.sh](<./src/scripts/laplacian-generate.sh>)

[src/scripts/publish-local.sh.hbs](<./src/scripts/publish-local.sh.hbs>)

[src/scripts/update-project.sh](<./src/scripts/update-project.sh>)





<!-- @main-content@ -->