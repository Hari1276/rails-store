# Rails Store Project

A Ruby on Rails learning project, featuring product management, stock notifications, and email subscriptions.


## Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/rails-store.git
cd rails-store
```

### 2. Install dependencies
```bash
bundle install
yarn install
```

### 3. Set up the database
```bash
bin/rails db:create
bin/rails db:migrate
```

### 4. Create admin user (required for authentication)
```bash
bin/rails runner "User.create!(email: 'admin@example.com', password: 'password')"
```

### 5. Start the server
```bash
bin/rails server
```

Visit [http://localhost:3000](http://localhost:3000) in your browser.

#### For more information on the project, visit [https://guides.rubyonrails.org/getting_started.html#introduction](https://guides.rubyonrails.org/getting_started.html#introduction)
