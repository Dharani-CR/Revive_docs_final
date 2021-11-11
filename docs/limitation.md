## Frontend 

1. Scaling: 

    - The Y axis Scaling cannot be changed .[Power BI Limitation] 

2. Color: 

    - If palette is not assigned default color in power BI will be applied [Power BI Limitation]. 

3. Sorting: 

    - Columns containing derivations from date columns [e.g. month name: April ,may etc] will be considered as text columns in Power BI. They will be hence sorted  based on alphabetical order and not month wise.[Power BI Limitation] 

4. Filters: 

    - Applying filters for a Text Column in Power BI requires all the values filtered out. Tableau provides only the start and end value in the metadata. [Power BI Limitation].	 

5. Actions: 

    - Run Action on hover and menu is not supported. 

    - With Actions from one dashboard to different dashboard restriction on particular chart interaction among different dashboard is not supported 

6.  Parameters: 

    - Numeric type Parameters: 

        - If allowable option all is selected parameter is not supported since specifying range is mandatory in power bi. 

    - Other type Parameters: 

        - Only numeric type parameters are supported in power bi 

        - If string or date parameters are included the slicer will be created but the expression is not supported. 

 

 

## Backend 

- In Multiple DataSource modelled separately with blend relationships, relationship will not be migrated to Power BI 

- If table name is not unique within single workbook, power bi throws up an error 

- Transformations: 

    - Teradata database with Live connection in tableau is not supported in power bi(direct query mode)  

    - Spaces between keywords in an expression is required else expression will not be migrated. 

    - Calculated fields with dimension columns from different tables.  

    - Cannot perform date difference between date and datetime column the column type should be same. 

    - In tableau the values rounds to specific decimal values on calculated columns by default. 

    - If Storage mode is Live in tableau  Power BI(direct query) does not does not support all the transformations.