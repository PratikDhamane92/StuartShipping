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
     
This screenshot demonstrates the store information section.

![Screenshot from 2025-01-08 19-48-00](https://github.com/user-attachments/assets/1a0a4b43-41b5-4280-8e10-ac4dba26bb97)

### Step 3: Configure Stuart Shipping
1. Go to **Stores > Sales > Delivery Methods > Stuart Shipping**.
2. Enter your **Client ID** and **Client Secret** from the Stuart account dashboard.
3. Register a webhook for real-time shipping status updates.
4. Save the configuration.

This screenshot demonstrates the Stuart Shipping configuration section.

![Screenshot from 2025-01-08 17-13-06](https://github.com/user-attachments/assets/50a0511b-36f8-4401-bb03-a8be6722a460)

### Step 4: Enable Shipping at Checkout
Once the configuration is complete, customers will see Stuart shipping options at checkout. The system automatically calculates available delivery methods and displays them for selection.

This screenshot demonstrates the Stuart Shipping options available on the checkout step.

![Screenshot from 2025-01-08 17-23-17](https://github.com/user-attachments/assets/af3b32de-9b09-44bb-9cb9-cb97931937e6)

### Step 5: Create a Shipping Request
1. In the Magento Admin panel, create a new shipping request when processing an order.
2. Stuart will generate a pickup request and initiate the delivery process.

This screenshot demonstrates the Stuart Shipping process that was initiated.

![Screenshot from 2025-01-08 17-42-38](https://github.com/user-attachments/assets/d3290d99-8463-480a-ac5d-3d3797efe178)

![Screenshot from 2025-01-09 14-24-16](https://github.com/user-attachments/assets/3430e3db-d92d-404e-9cc7-87feed766b27)

### Step 6: Track Shipping Status
Both administrators and customers receive real-time shipping status notifications via webhook updates.

This screenshot demonstrates the admin order section showing shipping status updates.

![Screenshot from 2025-01-09 14-40-24](https://github.com/user-attachments/assets/324f232d-139f-4bc7-a379-55c32749e274)

This screenshot demonstrates the customer-facing order section showing shipping status updates.

![Screenshot from 2025-01-09 14-41-10](https://github.com/user-attachments/assets/468d5933-6845-4170-836f-1013953bc04b)

![Screenshot from 2025-01-09 14-31-16](https://github.com/user-attachments/assets/1805bc6a-d017-4d4c-98be-79474ce2dc6f)

## Support and Documentation
For detailed API documentation and support, visit the official [Stuart Shipping website](https://stuart.com).

## License
This module is open-source and licensed under the MIT License.
## Contributing
We welcome contributions! Please open an issue or submit a pull request for any improvements or bug fixes.

---

