# cookiecutter-tf-module

Cookiecutter template to create Terraform modules.


## Usage

```bash
$ pip install cookiecutter
$ cookiecutter https://github.com/bmacauley/cookiecutter-tf-module.git
```

You will be prompted for basic info (your name, module name, etc.) which will be used in the template.

## Output
Folder structure generated...

```
└── tf-module-name
    ├── CHANGELOG.md
    ├── LICENSE
    ├── README.md
    ├── main.tf
    ├── outputs.tf
    └── variables.tf
```


## Authors
[Brian Macauley](https://github.com/bmacauley) &lt;brian.macauley@gmail.com&gt;  
Based on [DualSpark/cookiecutter-tf-module](https://github.com/DualSpark/cookiecutter-tf-module)

## License
[MIT](/LICENSE)
