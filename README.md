# SGF Code for ERPNext: Barcode Generation and Warehouse Management

## Overview
This custom code is designed for ERPNext to facilitate the generation of multiple barcodes and QR codes for products within the system. The tool enhances inventory management by integrating features that allow users to search product databases across multiple companies, select warehouses, and view available quantities. It supports the generation of Code 128 barcodes and QR codes, ensuring compatibility with various universal label printers.

## Features

1. **Bulk Barcode Generation**: 
   - Generate over 100 barcodes at once for different products.
   - Supports both Code 128 and QR code formats.

2. **Database Search Functionality**: 
   - Search the product database by product name or company name.
   - Works seamlessly for multiple companies, enhancing flexibility for users managing diverse inventories.

3. **Warehouse Selection**:
   - Users can select a specific warehouse from which to generate barcodes.
   - View available quantities of products across selected warehouses.

4. **Dynamic Warehouse Filtering**:
   - The warehouse list is dynamically filtered based on the currently selected company, ensuring users only see relevant warehouses.

5. **Compatibility**:
   - Developed for ERPNext version 15 or later.
   - Compatible with Universal Label Printers, tested specifically on the following models:
     - TSVE LP46Lite
     - TSC TE Series
     - TTP Series

## Implementation 

To implement this custom code in your ERPNext environment:

1. **Installation**:
   - Follow the included installation guide to integrate the barcode generation tool.
   - Ensure you have the required printer drivers for the supported universal label printers.

2. **Configuration**:
   - Access the settings to configure company profiles and warehouse options.
   - Set up your printer preferences for optimal barcode printing.

3. **Usage**:
   - Navigate to the custom barcode generation interface within ERPNext.
   - Use the search functionality to locate products or companies.
   - Select your desired warehouse, review available quantities, and proceed to generate barcodes.

## Conclusion

This custom code for ERPNext significantly simplifies barcode generation and inventory management. By providing bulk generation capabilities and essential search features, it enhances operational efficiency for businesses managing multiple products and warehouses. Enjoy seamless integration with universal label printers for effective label printing solutions.
