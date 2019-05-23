[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen.svg)](LICENSE)

# Scala Tutorials

Scala tutorials by way of an interactive (Jupyter) notebook.

## Getting Started

### Dependencies

Ensure the following dependencies are installed and configured:

  - [Docker and Docker Compose]

### Setup Steps

  - Run `docker-compose up` to run the Jupyter notebook

The app is now accessible from [`localhost:8888`](http://localhost:8888) (take note of the access token value to allow access to open the notebook).

## Contributing

We follow the "[feature-branch]" Git workflow.

  1. Commit changes to a branch in your fork (use `snake_case` convention):
     - For technical chores, use `chore/` prefix followed by the short description, e.g. `chore/do_this_chore`
     - For new features, use `feature/` prefix followed by the feature name, e.g. `feature/feature_name`
     - For bug fixes, use `bug/` prefix followed by the short description, e.g. `bug/fix_this_bug`
  1. Rebase or merge from "upstream"
  1. Submit a PR "upstream" to `develop` branch with your changes

Please read [CONTRIBUTING] for more details.


## License

```
    Copyright (c) 2019 Herdy Handoko

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
```

`scala-tutorials` is released under the Apache Version 2.0 License. See the [LICENSE] file for further details.


[CONTRIBUTING]: https://github.com/hhandoko/scala-tutorials/blob/master/CONTRIBUTING.md
[Docker and Docker Compose]: https://docs.docker.com/compose/
[feature-branch]: http://nvie.com/posts/a-successful-git-branching-model/
[LICENSE]: https://github.com/hhandoko/scala-tutorials/blob/master/LICENSE
