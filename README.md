<p align="center"><a href="https://lunarphp.io/" target="_blank"><img src="https://raw.githubusercontent.com/lunarphp/art/main/lunar-logo.svg" width="200" alt="Lunar"></a></p>

# Lunar Laravel E-Commerce Starter Kit

This repository serves as a comprehensive reference for utilizing the Lunar Laravel E-Commerce package, offering insights into building a classic e-commerce store.

> **Warning**
> This application is intended solely as an illustrative example of how Lunar headless e-commerce can be implemented with Laravel. It is not suitable for production use and may not be feature-complete.

## Installation

Follow these steps to set up and run the Lunar Laravel E-Commerce Starter Kit:

### 1. Clone the Repository

Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/lunar-ecommerce-starter-kit.git

## step 1:  Copy Environment File
cp .env.example .env

## step 2:  Run Migrations
php artisan migrate

## step 3: Install Lunar Laravel E-Commerce
php artisan lunar:install


## step 4: Setup Account admin in Terminal

## step 5: Run Seeder
php artisan db:seed

## step 6: Run source
php artisan serve

Page admin: http://<yoursite>/hub
