# How to use filtering expressions 

Filtering expressions can be specified within different navigators' rows to limit the scope of what is being shown. 

If these rows are not visible, you need to enable them by accessing the respective navigator's menu and selecting **Show filter row**.

![picture](pictures/Filtering_expressions_row_25_03.png)

In the filter row of a column that contains data, you can input a variety of filtering expressions. 

For instance, you may input "(today)" in the **Document date** column. By doing so, only items created on the current day will be displayed in the table.

![picture](pictures/Filtering_expressions_today_25_03.png)

## Rules for using filtering expressions 

The expressions have constraints, and their syntax can impact their functionality. It's crucial to ensure their proper formulation to achieve desired results. 

### Relative time expressions 

These expressions refer to time periods relative to the current moment, rather than specifying exact dates. Examples include (yesterday) or (last month). These expressions, enclosed within brackets, are used to define time periods relative to the current date without specifying specific dates.

![picture](pictures/Filtering_expressions_last_month_25_03.png)

### Relative date expressions

These expressions refer to specific dates relative to the current date. For example, "-7d" denotes a date seven days before the current date, while "+2d" represents a date two days ahead of the current date. These expressions, written without brackets, are used to specify exact points in time relative to the present moment.

![picture](pictures/Filtering_expressions_+2d_25_03.png)

### Relative period expressions 

These expressions refer to specific periods relative to the current date. For example, (-1m) denotes the month that was before the current month, while (+2m) represents the month that is ahead of the current month. Enclosed within brackets, these expressions are used to specify time periods relative to the present moment.

![picture](pictures/Filtering_expressions_-1m_25_03.png)

#### Expressions for large relative time periods

These expressions establish time periods relative to specific intervals or divisions within a broader timeframe. For example, "q1," "q2," and "h1" mark these periods. "q1" signifies the first quarter of the year, "q2" represents the second quarter, and "h1" denotes the first half of the year.

 ![picture](pictures/Filtering_expressions_q1_25_03.png)

#### Assign custom time periods

Custom time periods can be designated, for instance, (feb)..(today) representing the timeframe spanning from month February up to and including today. (yesterday) specifically denotes yesterday's date. Additionally, (yesterday)..+2d extends from yesterday to two days ahead, ensuring a comprehensive scope within your data analysis.

![picture](pictures/Filtering_expressions_custom_25_03.png)

> [!NOTE]
> - Zero without brackets represents today as both the beginning and end of the period.
> - If no dimension is specified, the default dimension is days: "-7" is equivalent to "-7d" and "0" represents today.
> - When specifying a period in days, it can be written with or without brackets.




> [!NOTE]
> 
> The screenshots taken for this article are from v24 of the platform.