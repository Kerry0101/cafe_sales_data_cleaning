[1]   The first major problem that I encountered is the Missing and Inconsistent Values.
      The dataset had missing values, empty strings, and inconsistent representations like "UNKNOWN" and "ERROR" to some columns.
      I removed those rows with missing critical information and standardized categorical values.

Second woyld be the Data Type Issues. Several numerical columns contained string values like "ERROR" instead of numbers, and the dates needed proper formatting.
So I converted all columns to appropriate data types.

The 3rd one would be Invalid Data. I discovered and removed rows with invalid values such as negative or zero quantities/prices, and rows where the Total Spent
didn't match the calculation of Quantity × Price Per Unit.
