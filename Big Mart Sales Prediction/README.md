# PROBLEM STATEMENT
## Sales Prediction for Big Mart Outlets
The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and predict the sales of each product at a particular outlet.

Using this model, BigMart will try to understand the properties of products and outlets which play a key role in increasing sales.

Please note that the data may have missing values as some stores might not report all the data due to technical glitches. Hence, it will be required to treat them accordingly. 


<table>
    <tbody>
        <tr>
            <th>Variable</th>
            <th>Description</th>
        </tr>
        <tr>
            <td>Item_Identifier</td>
            <td>Unique product ID</td>
        </tr>
        <tr>
            <td>Item_Weight</td>
            <td>Weight of product</td>
        </tr>
        <tr>
            <td>Item_Fat_Content</td>
            <td>Whether the product is low fat or not</td>
        </tr>
        <tr>
            <td>Item_Visibility</td>
            <td>The % of total display area of all products in a store allocated to the particular product</td>
        </tr>
        <tr>
            <td >Item_Type</td>
            <td>The category to which the product belongs</td>
        </tr>
        <tr>
            <td>Item_MRP</td>
            <td>Maximum Retail Price (list price) of the product</td>
        </tr>
        <tr>
            <td>Outlet_Identifier</td>
            <td>Unique store ID</td>
        </tr>
        <tr>
            <td>Outlet_Establishment_Year</td>
            <td>The year in which store was established</td>
        </tr>
        <tr>
            <td>Outlet_Size</td>
            <td>The size of the store in terms of ground area covered</td>
        </tr>
        <tr>
            <td>Outlet_Location_Type</td>
            <td>The type of city in which the store is located</td>
        </tr>
        <tr>
            <td>Outlet_Type</td>
            <td>Whether the outlet is just a grocery store or some sort of supermarket</td>
        </tr>
        <tr>
            <td>Item_Outlet_Sales</td>
            <td>Sales of the product in the particular store. This is the outcome variable to be predicted.</td>
        </tr>
    </tbody>
</table>
