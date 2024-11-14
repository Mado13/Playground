# playground

This is playground repo to test RoR capabilities, esp. turbo and stimulus.

## Prerequisites

* Ruby (version 3.0.0 or higher recommended)
* Rails (version 7.0 or higher recommended)
* PostgreSQL

## Getting Started

Follow these steps to get the application running on your local machine:

1. Clone the repository
```bash
git clone git@github.com:Mado13/playground.git
cd playground
```

2. Install dependencies
```bash
bundle install
```

3. Set up the database
```bash
rails db:create
rails db:migrate
rails db:seed
```

4. Start the development server
```bash
bin/dev
```

The application should now be running at `http://localhost:3000`

## Login Credentials

### Employee Access
```
Email: employee@playground.com
Password: Employee123
```

### Manager Access
```
Email: manager@playground.com
Password: Manager123
```

## Testing

To run the test suite:
```bash
rspec
```
