# Microsolft-Power-Bi.
This is a Complete Master Class in Microsoft Power Bi -2022.

### INTRODUCTION.
#### Query Editor.

You can do alot Transformation in the QueryEditor such as , Renaming, cleaning the Null values etc.

-- `unpivoted other columns` changing other columns to  rows


###### mini Project-Creating a data model.
![Creating a data model](https://user-images.githubusercontent.com/42388234/162642154-6929d68e-c381-4911-bd08-40831af6b9ea.png)


## Data Transformation- The Query Editor.

> when connecting the Power Bi to a `website`, Navigate to the top left hand corner and click on `Datasource`,  navigate to website and connect either by adding the URL or adding the `API` of the site as well as the `Key`. 

> The ``Transform` feature in QueryEditor enbles you to do alot of `Data cleaning` such as  `extract` method to extract data from colums, `split` data from columns and so on. 

> `Groupby` can be archieve with `conditional columns` in the `QueryEditor`.

> under `add column` feature in QueryEditor `Creat column from exmample` by `selection` can also be used to Extract values from other columns accurately. 

> Try to understand the difference types of `MergeQuery` before merging any table 


> `Power Query` in Power BI provides very effective functionality to `pivot` and `unpivot` columns. For the pivot functionality you turn `rows` to `columns` and for the unpivot functionality the `inverse` is true where columns are transformed into rows

> To `Group Rows` use the `Apend Quieries` feature .

>  `The Fact table/dimension model` also called the `Star Schema` is used to reduce the amount of data stored in our table. and the reasons for this is to increase the performance of our model. usaully a collection of cleaned other dimensional table that are been compressed in the star schema.
 ## Data Transformation-Advanced.

> Increasing the Query `Performance`, it is better to `Reference`  a Table than `Duplicate`, as the Duplicate will also need to read same Data from the Source.

> Increasing the `Model Performance` can be archive by reducing the number tables being loaded into the model from QueryEditor. This can simply be done by unchecking the `Enable load` button when a schema is rightclicked.
 
> Increasing the `Model Performance` can also be archive by Using the `Groupby` Function in the `Transform` feature. 

> `Parameter`, can be used to transform our data dynamically such as, filtering our data or even using it to create Custom columns.

## Creating Our Model.

> `Cardinality`: `one-to-many`=> table are joined on this bases when one has unique dimension and the other does not. `one-to-one`=> when both of the tables has the same dimension. etc.

> `Cross Filter`: This shows the direction in which our data is going to be filtered, it could be `Single` or `Both`.


## Data Visualization.

> `Conditional Formatting` on Table Visuals can be archieved with `Specific Column` Features and `Cell Elements`. 

> `Tooltips`- This indicate the Hover details, Power BI automathically does this for you. but you can still add more details to it.

> Note: Use `Pie Chart` to visual a data when the total is equal to 100%.

> `Filter-Menu Bar` Feature Supports `Advanced Filtering`-Which you could aggreagte values with certain parameters, `Basic Filtering`-here you could select all or a set of values to be Filtered, `Top N`-here you define a top count value to be filtered. 

> Note: `Cross Filtering and Edit Interaction`-Can be archived by clicking on the a visual then navigating to `Format` Rebin then clicking on `Edit Interactrion` to Turn-Off the Cross Filtering for some Tables and enable you get a a proper visual.

> `Sync Slicer`- Used to Synchronize two pages and Each Action taken by one will be affected by both.

> Add alot of Columns in `X-axis` to Enable `Drill-down` in `Bar-chat`. 

> `Drill Through`: After Drill down- you can drag column to Drill through field and from the first page you can Drill through any connect pages to display the required Output.

> `Decomposition Tree` Another Essential Tool in Data Visualization. 

> `Secondary Values` are inportant to consider because it helps you see the corelation. 

> `Analytics search bar` is mostly available when we are making our forcast. enables features like `Trend line`, `Percentage`, `Forcast` etc.

> `(Q & A) Visual` Helps in answeering all user questions quiclky.. once the schema's are prepared and loaded in the model, the Q&A provides suggested questions as well as the suggested questions visuals provided by the moderator.  

