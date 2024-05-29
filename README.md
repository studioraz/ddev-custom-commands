### Setup n98-magerun2 Command for DDEV

This script sets up the n98-magerun2 command for use with DDEV in a Magento 2 environment. It ensures that the necessary files and directories are created and configured properly.

#### Prerequisites

- DDEV installed and configured.
- Magento 2 project setup in your local environment.
- `wget` installed on your system.

#### Steps to Execute the Script Remotely

1. **Run the Script Remotely**

   You can execute the script remotely using `curl`. Open your terminal and run the following command:

   ```sh
   curl -s https://raw.githubusercontent.com/studioraz/ddev-custom-commands/master/n98-magerun2-setup | bash
