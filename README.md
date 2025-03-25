# Magento 2 Show/Hide Password Extension

## Introduction
Magento 2 Show/Hide Password Extension enhances user experience by allowing customers to toggle password visibility on login, registration, and checkout pages. This feature reduces login errors and improves accessibility. 

## How It Works
The Magento 2 Show/Hide Password extension adds an eye icon inside password input fields. When clicked, the password visibility toggles between hidden and visible modes. This helps users confirm their password entry, reducing errors. It is compatible with multiple themes and follows Magento 2 security standards.

## Key Features
- Toggle password visibility with a single click.
- Works on login, registration, and checkout pages.
- Fully responsive and compatible with all devices.
- Easy to install and configure without coding knowledge.

## Eye Icon for Password Fields
Adds an intuitive eye icon to password fields. Clicking the icon toggles between visible and hidden password modes.

## Compatibility With All Magento Themes
Seamlessly integrates with any Magento 2 theme, ensuring smooth performance and UI consistency.

## Lightweight and Fast Performance
Designed for minimal impact on website speed, ensuring a smooth user experience.

## Secure and User-Friendly
Maintains Magento 2 security standards while enhancing accessibility for users.

## Extension Installation

### Step 1: Install the Extension Using Composer
```sh
composer require vendor/show-hide-password
```
For a specific version:
```sh
composer require vendor/show-hide-password:version
```
Note: You may need authentication keys from the vendor or Magento Marketplace.

### Step 2: Run Magento Commands
```sh
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy -f
php bin/magento cache:flush
```

## How To Configure Magento 2 Show/Hide Password Extension

### Step 1: Navigate to Admin Panel
Go to **Stores** > **Configuration** > **CodeDecorator** > **Show/Hide Password**.

### Step 2: Enable the Extension
Set **Enable Show/Hide Password** to **Yes**.

### Step 3: Customize Visibility Settings
Adjust where the icon should appear (login, registration, checkout pages).

## Download Our [Magento 2 Show/Hide Password](https://codedecorator.com/magento-2-show-hide-password.html) Extension
