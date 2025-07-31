# E-Commerce Rails

A modern, flexible, and scalable e-commerce platform built with Ruby on Rails.

## Features
- User authentication and authorization
- Product catalog with categories and variants
- Shopping cart and checkout process
- Order management
- Payment integration (Stripe, PayPal, etc.)
- Admin dashboard for managing products, orders, and users
- Responsive storefront for customers
- Email notifications for orders and account activity
- Extensible architecture for custom features

## Getting Started

### Prerequisites

- Ruby (version 3.0+ recommended)
- Rails (version 6.1+ recommended)
- PostgreSQL
- Node.js & Yarn

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/mirkodev93/E-Commerce-Rails.git
   cd E-Commerce-Rails
   ```

2. **Install dependencies:**
   ```bash
   bundle install
   yarn install
   ```

3. **Set up the database:**
   ```bash
   rails db:create db:migrate db:seed
   ```

4. **Start the server:**
   ```bash
   rails server
   ```

5. **Visit the app:**
   Open [http://localhost:3000](http://localhost:3000) in your browser.

## Configuration

- Copy `.env.example` to `.env` and set your environment variables.
- Configure payment gateways and email settings in `config/initializers`.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b my-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin my-feature`)
5. Create a new Pull Request

## License

This project is licensed under the BSD-3-Clause License. See the [LICENSE](license.md) file for details.

## Acknowledgements

- [Ruby on Rails](https://rubyonrails.org/)
- [Spree Commerce](https://spreecommerce.org/)
- [Stripe](https://stripe.com/)
- [PostgreSQL](https://www.postgresql.org/)

---

Thank you for supporting open-source e-commerce!
