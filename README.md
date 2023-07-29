```
┓ ┳┏┓┏┓┳┓┏┓┏┓
┃ ┃┃ ┣ ┃┃┗┓┣ 
┗┛┻┗┛┗┛┛┗┗┛┗┛
```

A [tmplr](https://github.com/loreanvictor/tmplr) recipe to add license to your project. Provides a wide range of licenses to choose from, sourced from [choosealicense.com](https://choosealicense.com).

## Usage

👉 Use it directly on your project:

```bash
npx tmplr use loreanvictor/license-recipe
```

<br>

👉 Or use it as part of some other [tmplr recipe](https://github.com/loreanvictor/tmplr):

```yml
# .tmplr.yml
steps:
  # ...

  - use: loreanvictor/license-recipe

  # ...
```

<br>

If the following arguments are provided, the recipe won't prompt the user for them:

- `owner`: The full name of the license owner.
- `project_name`: The name of the project. _Required by some licenses (not all)._
- `project_url`: The url of the project. _Required by some licenses (not all)._
- `email`: The email of the license owner. _Required by some licenses (not all)._

```yml
# .tmplr.yml
steps:
  - use: loreanvictor/license-recipe
    args:
      owner: "Lorean Victor"
      project_name: "My Project"
      project_url: "https://github.com/loreanvictor/my-project"
```

<br><br>
