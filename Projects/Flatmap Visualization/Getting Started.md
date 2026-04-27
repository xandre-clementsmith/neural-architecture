NOTE: This project utilizes generative AI

https://docs.internationalbrainlab.org/notebooks_external/atlas_swanson_flatmap.html
https://pmc.ncbi.nlm.nih.gov/articles/PMC7721992/

**Python + FastAPI + PostgreSQL + React (with TypeScript)**

**Homebrew** is your starting point on the Mac. It's the equivalent of pacman for macOS — install it first and use it for everything else.

**Git** is what keeps your code in sync between machines. You push from one, pull on the other. You probably already know this but it's worth being deliberate about — commit often, and never have code that only lives on one machine.

**Neovim** installs fine on Mac via Homebrew (`brew install neovim`) and your existing config should transfer directly. Neovim configs are just files, so keeping yours in a dotfiles repo on GitHub means you can pull it onto any machine in minutes. If you don't already have a dotfiles repo that's worth setting up early.

**Docker Desktop** on Mac handles your Postgres and FastAPI containers. The experience is slightly different from Linux — Docker on Mac runs inside a lightweight VM under the hood — but for a project like this you won't notice the difference.

**Pyenv** for managing Python versions. Arch and Mac can have different default Python versions and pyenv lets you pin your project to a specific version on both machines so behavior stays consistent.

The thing to nail down early is that your project has a `requirements.txt` or `pyproject.toml` for Python dependencies and a `package.json` for frontend dependencies, both committed to Git. That way setting up on a new machine is just cloning the repo and running one install command.