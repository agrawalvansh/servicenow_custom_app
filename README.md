
# ServiceNow Custom App

ServiceNow Custom App is a tailored application designed to extend and enhance ServiceNow platform capabilities for your organization. This repository contains the source code, configuration files, and update sets for deploying and managing the custom app within your ServiceNow instance.

## Features

- Custom tables and fields for device management
- Automated workflows and catalog items
- Security ACLs and role-based access
- Data import/export utilities
- Modular structure for easy updates and maintenance

## Getting Started

1. **Clone the repository:**
	```
	git clone https://gitlab.com/agrawalvansh-group/servicenow_custom_app.git
	```
2. **Review the update sets and XML files** in the `update/` and `dictionary/` folders.
3. **Import update sets** into your ServiceNow instance using the Update Set feature.
4. **Verify and test** the application modules and catalog items.

## Requirements

- ServiceNow instance (Orlando or later recommended)
- Admin access to import update sets

## Installation

1. Log in to your ServiceNow instance as an admin.
2. Navigate to **System Update Sets > Retrieved Update Sets**.
3. Import the XML files from the `update/` directory.
4. Preview and commit the update sets.
5. Configure any additional settings as needed.

## Usage

- Access the app modules from the ServiceNow application navigator.
- Use the catalog items to request or manage devices.
- Review and modify security roles as required for your organization.

## Contributing

Contributions are welcome! Please fork the repository and submit a merge request. For major changes, open an issue first to discuss your proposed changes.

## Support

For questions or support, please open an issue in this repository or contact the maintainer.

## License

This project is licensed under the MIT License.
