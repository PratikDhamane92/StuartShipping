# Stuart Shipping Magento 2 Extension

**Stuart Shipping** is Europe’s leading urban logistics company, providing businesses with instant and scheduled same-day delivery solutions. This Magento 2 extension integrates the Stuart Shipping solution into your store, enabling seamless delivery services for restaurants, grocery stores, retail businesses, and eCommerce shops in the UK.

With a few simple configuration steps, you can start delivering your orders using Stuart's powerful shipping platform.

## Features
- Instant and scheduled same-day delivery options
- Real-time order pickup and shipping status updates
- Automated webhook notifications for shipping updates
- Supports restaurant, grocery, retail, and eCommerce deliveries

## Installation and Configuration

### Step 1: Install the Stuart Shipping Module
1. Download the Stuart Shipping Magento 2 extension.
2. Follow standard Magento 2 module installation steps:
   ```bash
   php bin/magento module:enable Codi_StuartShipping
   php bin/magento setup:upgrade
   php bin/magento setup:di:compile
   php bin/magento cache:clean
   ```

### Step 2: Configure Store Information
1. Navigate to **Stores > Settings > Configuration > General > Store Information**.
2. Set the following required fields:
   - Store Name
   - Contact Information
   - Store Address (used as the pickup location)

### Step 3: Configure Stuart Shipping
1. Go to **Stores > Sales > Delivery Methods > Stuart Shipping**.
2. Enter your **Client ID** and **Client Secret** from the Stuart account dashboard.
3. Register a webhook for real-time shipping status updates.
4. Save the configuration.

### Step 4: Enable Shipping at Checkout
Once the configuration is complete, customers will see Stuart shipping options at checkout. The system automatically calculates available delivery methods and displays them for selection.

### Step 5: Create a Shipping Request
1. In the Magento Admin panel, create a new shipping request when processing an order.
2. Stuart will generate a pickup request and initiate the delivery process.

### Step 6: Track Shipping Status
Both administrators and customers receive real-time shipping status notifications via webhook updates.

## Support and Documentation
For detailed API documentation and support, visit the official [Stuart Shipping website](https://stuart.com).

## License
This module is open-source and licensed under the MIT License. See the LICENSE file for more details.

## Contributing
We welcome contributions! Please open an issue or submit a pull request for any improvements or bug fixes.

---

