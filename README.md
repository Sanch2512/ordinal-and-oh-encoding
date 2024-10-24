Ordinal Encoding Function
Function to perform ordinal encoding on a categorical column.
    
    Parameters:
    column (pd.Series): The categorical column to encode.
    order (list): Optional predefined order of categories.
    
    Returns:
    pd.Series: The column with ordinal encoding applied.
One-Hot Encoding Function
 Function to perform one-hot encoding on a categorical column.
    
    Parameters:
    column (pd.Series): The categorical column to encode.
    
    Returns:
    pd.DataFrame: A new DataFrame with one-hot encoded columns.
Perform ordinal encoding on 'Size' column (custom order)
Perform one-hot encoding on 'Color' column
Concatenate the original DataFrame with the one-hot encoded columns
