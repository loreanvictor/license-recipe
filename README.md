```
┓ ┳┏┓┏┓┳┓┏┓┏┓
┃ ┃┃ ┣ ┃┃┗┓┣ 
┗┛┻┗┛┗┛┛┗┗┛┗┛
```

A [tmplr](https://github.com/loreanvictor/tmplr) recipe to add license to your project. Provides a wide range of licenses to choose from, sourced from [choosealicense.com](https://choosealicense.com).

## Usage

This recipe should be used by some other [tmplr recipe](https://github.com/loreanvictor/tmplr):

```yml
# .tmplr.yml
steps:
  # ...

  - use: loreanvictor/license-recipe

  # ...
```

<br>

This recipe requires the following arguments (based on picked license). It will prompt the user if they are not provided:

- `owner`: The full name of the license owner.
- `project_name`: The name of the project. _Required by some licenses (not all)._
- `project_url`: The url of the project. _Required by some licenses (not all)._
- `email`: The email of the license owner. _Required by some licenses (not all)._

<br><br>
