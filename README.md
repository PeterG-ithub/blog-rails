# Simple Blog App

This is a basic Ruby on Rails application for creating and viewing articles. It includes a basic list of articles with links to view individual articles and create new ones. There is no styling (CSS) applied to the application.

## Installation
To set up this project locally, follow these steps:

### Prerequisites
Ensure you have the following installed on your machine:

- **Ruby**: The programming language used by Rails. 

### Windows

1. Ensure you have Ruby installed. If not, download and install it from [here](https://www.ruby-lang.org/en/downloads/).
2. With Ruby installed, you can now install Rails:
    ```bash
        gem install rails
3. Clone this repository to your local machine.

        git clone https://github.com/PeterG-ithub/blog-rails.git
        cd blog-rails
4. Install the required Ruby gems using Bundler.If you encounter Ruby version errors here, change the version of ruby in the Gemfile

        bundle install
5. Set up the database by running the following commands:

        rails db:create
        rails db:migrate
        rails db:seed
6. Start the Rails server to run the application locally:

        rails server
### Linux

1. Open a terminal.
2. Ensure you have Ruby installed by running `ruby --version`. 

        ruby --version
If not, install Ruby using your package manager.

        sudo apt update
        sudo apt-get install ruby-full

3. With Ruby installed, you can now install Rails:

        gem install rails
4. Clone this repository to your local machine.

        git clone https://github.com/PeterG-ithub/blog-rails.git
        cd blog-rails
5. Install the required Ruby gems using Bundler. If you encounter Ruby version errors here, change the version of ruby in the Gemfile

        bundle install
6. Set up the database by running the following commands:

        rails db:create
        rails db:migrate
        rails db:seed
7. Start the Rails server to run the application locally:

        rails server
## Features

- **Article Listing**: List all articles on the homepage.
- **View Article**: View individual articles by clicking on their titles.
- **Create Article**: Form to create a new article.
- **Edit Article**: Ability to edit existing articles.
- **Delete Article**: Ability to delete articles.
- **Article Validations**: Validations for article title and content.
- **Comment on Articles**: Add comments to articles.
- **Basic Navigation**: Links to navigate between different pages.

## Credits
This Ruby Project is part of the curriculum provided by The Odin Project, an open-source online platform that offers free resources to learn web development.
- **Website**: [The Odin Project](https://www.theodinproject.com/)
- **Project**: [Blog App Project](https://www.theodinproject.com/lessons/ruby-on-rails-blog-app)
