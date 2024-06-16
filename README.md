# Rails Devcontainer Starter Files

Starter files for a Devcontainer for Rails Development. Contains definitions for a devcontainer as well as containers for PostgreSQL, Redis, Meilisearch and Memcache. The latter two are commented to conserve resources as they are not typically used at the very start of a project. 

## Usage 

1. Get [Rails New](https://github.com/rails/rails-new)
2. Run `rails-new project-name --devcontainer`
3. Copy the `.devcontainer` directory from this repository into the resulting directory of the above step.
4. Modify the `.devcontainer` files to taste. 
5. Use a devcontainer handler to run the project ([VScode](https://code.visualstudio.com), [Devpod](https://devpod.sh), etc.)
   
