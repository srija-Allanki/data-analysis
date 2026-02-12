# data-analysis
Steps I Performed
1️⃣ Checked Missing Values

Used df.isnull().sum() to identify null values.

Handled missing data using:

dropna() to remove rows

fillna() to replace with mean/mode

2️⃣ Removed Duplicate Records

Identified duplicates using df.duplicated().sum()

Removed them using df.drop_duplicates()

3️⃣ Standardized Text Data

Converted text to lowercase

Removed extra spaces using .str.strip()

Standardized categories (e.g., M → Male, F → Female)

4️⃣ Converted Date Format

Used pd.to_datetime() to convert inconsistent date formats

Formatted dates to dd-mm-yyyy

5️⃣ Renamed Column Headers

Converted column names to lowercase

Replaced spaces with underscores

6️⃣ Fixed Data Types

Converted numerical columns to int/float

Converted date columns to datetime

Verified using df.dtypes

📊 Tools Used

Python

Pandas
