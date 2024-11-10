# File Format Converter
File Format Converter is a simple and efficient tool designed to convert CSV files into JSON format. 

## How to run
- Create your data in CSV format. Provide the metadata about those CSV files in schemas.json file.
- Create environment variables `SRC_BASE_DIR` and `TGT_BASE_DIR`.
- Run the following python command: `python3 app.py`
- If you want to convert only specific datasets into JSON format: `python3 app.py '["orders", "products", "departments"]'`
