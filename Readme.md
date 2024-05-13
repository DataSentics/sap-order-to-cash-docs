Generated documentation for the sap-order-to-cash project.

## How to generate documentation:
- clone [sap-order-to-cash-docs](https://github.com/DataSentics/sap-order-to-cash-docs) repository
- clone [sap-order-to-cash](https://github.com/DataSentics/sap-order-to-cash) repository
- in sap-order-to-cash repository
	- change documentation (models/overview.md)
	- generate documentation
		<code>dbt docs generate --target-path \<path to sap-order-to-cash-docs\> </code>
- commit and push changes to both repositories
