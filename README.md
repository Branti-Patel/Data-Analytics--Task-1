This project involves cleaning and preprocessing a Marketing campaign dataset to prepare it for analysis. The original dataset contained information about Customer with various attributes like ID, Income, year_birth, date of purchase,buying data and more.

Cleaning Steps Performed Missing Values Analysis:

Identified missing values in dataset Maintained as-is since these represent legitimate missing data Text Cleaning:

Removed leading/trailing spaces from all text fields Fixed malformed special characters (dashes and apostrophes) Standardized country names to use only the first listed country Date Standardization:

Converted date_added to datetime format One invalid date record was set to NaT Duration Column Processing:

Split into numeric duration and unit (minutes or seasons) Created two new columns: duration_num and duration_unit Data Type Conversion:

Ensured proper data types for all columns Created separate numeric duration column for analysis Duplicate Check:

Verified no complete duplicate rows existed
