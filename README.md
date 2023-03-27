## create_doc

Generate angular project documentation using GPT and dependency-cruiser.

- Free software: MIT license

### Features

- Create documentation for your project using GPT. Analyze html files or other file types and generate a markdown file with the documentation.

- Create module dependency documentation using dependency-cruiser static code analysis.

### Usage

- Initialize a project with the following command:

        create_doc init

- Check the configuration file `.create_doc.json` created in the root of your project and adjust it to your needs. You can define multiple processors for gpt and dependencies.

- Create documentation for your project the following command:

        create_doc process_gpt

- You can also run the specific gpt processors with the following commands:

        create_doc process_gpt processor_name

- for example

        create_doc process_gpt forms

- Create documentation for your project dependencies with the following command:

        create_doc process_dependencies

- To run the specific dependency processors use the following commands:

        create_doc process_dependencies processor_name

### Credits

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

- Cookiecutter: https://github.com/audreyr/cookiecutter
- `audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage

Example angular form from https://github.com/gothinkster/angular-realworld-example-app
