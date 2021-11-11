### Charts 
- The chart names from Tableau is shown in “show me” pane.
- If a chart is not in the supported type they will be converted as table .
- Custom visuals will be used if the chart is defaultly  unavailable in Power BI. These are visuals from Power BI Market place.


|Charts	               |    Tableau	               |   Power BI             |
|----------------------|---------------------------|------------------------|
|BAR	               |Horizontal Bar	           | barChart               |
|	                   |Stacked Bar	               | columnChart            |
|	                   |Side by side Bar	       | clusteredColumnChar    |
|AREA	               |Area Chart	               |Area Chart              |
|	                   |Stacked Area	           |Area Chart              |
|LINE	               |Line Chart - Continuous    |Line Chart              |
|	                   |Line Chart - Discrete	   |PBILineChartByAkvelon555E1FCA110843C7A6E66458BA0A3FAD[Custom Visual]|
|	                   |Dual Line	               | Line Chart             |
|PIE	               |Pie	                       |Pie Chart               |
|MAP	               |symbol map	               |map                     |
|DUAL COMBINATION      |Dual combination           |lineClusteredColumnComboChart  |
|TABULARVISUALS        |Text Table	               |table Ex                |
|	                   |Highlighted Tables         |pivotable               |
|CARD	               |text	                   |card                    |
|CUSTOM  CHARTS        |Packed Bubble              |bubbleChartEEDCDFA388784AEEAB47972BC1626196|
|	                   |boxplot	                   | BoxandWhiskerByMAQ1823AD39DT234AB532063E128AX|
|	                   |Heat Map	               |TableHeatMap1443716069308|


### Chart Properties 
- Titles on charts 
- X-axis and Y-axis Titles will be renamed .
- Text Properties like font style, size and color.
- Background color 
- Grid lines.
- Borders for charts.
- Alias name for values.
- Legends will be enabled only if present .
- COLOR OF CHART:
    - If color is applied it will be added else default color is applied to Power BI.
    - If a chart contains multiple color representing its data and if palate is assigned it will be applied to Power BI.

### Dashboard Objects 
- TEXT BOX:
The text box along with its properties [font style, size and color]
- BACKGROUND COLOR:
Background color of the page.
- IMAGES:
Images can be displayed if it is located in current system.

OTHER FEATURES:

- ACTIONS:
    - Only on-select is supported.
    - With Actions from one dashboard to different dashboard power bi interacts with all charts in target dashboard.

- PARAMETERS:

    - Numeric type Parameters:
        - In Allowable options , range and list is supported since specifying range in Power BI is mandatory.

    - Other type Parameters:
        - Other types will be shown as a slicer chart with interactivity among all charts in power bi.

    - TABLE RECORDS COUNT:
        - For each table a record count is calculated as a measure expression in power bi.


