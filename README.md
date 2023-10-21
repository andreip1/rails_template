# Rails Template Project

A readily available Rails 7 application template pre-configured with a curated list of gems and tools to jump-start your Rails development.

## Features

- **Rails 7**: Using the latest version with the new `importmap-rails` for managing JavaScript.
- **Authentication**: Using `devise` for secure user registration and session management.
- **Authorization**: Using `pundit` to provide a robust, granular system for permissions.
- **Styling**: Integrated with `tailwindcss-rails` for utility-first CSS.
- **Hotwire**: Included `turbo-rails` and `stimulus-rails` for fast, SPA-like navigation without JavaScript bundles.
- **Testing**: `RSpec`, `FactoryBot`, and `shoulda-matchers` for writing and managing tests easily.
- **Linting**: `rubocop-rails` for enforcing Rails best practices and coding standards.
- **Performance**: `bullet` to help detect and improve N+1 queries.
- **Security**: `brakeman` for analyzing code and ensuring no vulnerabilities.
- **Background Jobs**: `sidekiq` for processing background jobs efficiently.
- **Redis**: Configured for caching and background job processing.
- **Developer Tools**: Includes `pry-rails`, `letter_opener`, and `listen` for debugging, email previewing, and development conveniences.
- **Forms**: `simple_form` for easier form markup and integration.

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/andreip1/rails-template.git
```

2. Change directory:
```bash
cd rails-template
```

3. Install dependencies:
```bash
bundle install
```

4. Setup database:
```bash
rails db:create db:migrate
```

5. Start the Rails server:
```bash
./bin/dev
```

Visit `http://localhost:3000` in your browser to see the application running.

## Configuration

Remember to:

- Configure your Redis URL in the development and production environment files.
- Adjust any other configurations as per your requirements.

## Contributing

Feel free to open issues, submit pull requests, or even fork the repository to suit your custom needs. All contributions are welcome!
