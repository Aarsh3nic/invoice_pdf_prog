# Excel Sheet to PDF Invoice Generator

This Python script `main.py` can be used to generate PDF invoices from Excel spreadsheets. The script uses the `pandas` and `fpdf` libraries to read the Excel files and generate the PDF invoices.

## Requirements
- Python 3.x
- pandas
- fpdf

## How to use
1. Place all the Excel files in the folder `invoices/`.
2. Run the script `main.py` using the command `python main.py`.
3. The generated PDF invoices will be saved in the `PDFs/` folder.

The generated PDF invoice includes the following information:
- Invoice number
- Invoice date
- Product ID
- Product name
- Amount purchased
- Price per unit
- Total price
- Total sum

## Note
- The Excel file must have a sheet named "Sheet 1".
- The Excel file must have the following columns in the order given:
  - `product_id`
  - `product_name`
  - `amount_purchased`
  - `price_per_unit`
  - `total_price`

An example of the working model of this script can be found in the `PDFs/` folder.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
