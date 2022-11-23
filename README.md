# Ml_Basic_EDA
Machine language basic exploratory data analysis


#
def basic_eda(x):
    print("DATASET_SHAPE_____________________________________________________________________")
    print(x.shape)
    print(" ")
    print("DATASET_INFO______________________________________________________________________")
    print(x.info())
    print(" ")
    print("DESCRIPTIVE_STATISTICS____________________________________________________________")
    print(x.describe())
    print(" ")
    print("SUM_OF_NA_ROWS_IN_COLUMNS_________________________________________________________")
    print(x.isna().sum())
    print(" ")
    print("DATA_TYPES________________________________________________________________________")
    print(x.dtypes)
    print(" ")
