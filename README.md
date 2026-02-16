# Sales-and-Profit-Margin-PowerBI-Project
<p>The purpose of this project was to learn how to create reports in PowerBI to visually display data. This is a three page report in which I, designed a report, configured visual fields and formatted properties, synced slicers, and published the report to the PowerBI service. The tables I am using are Targets, Date, Product, Region, Reseller, Sales, Salesperson, Salesperson(Performance)</p>
<div>
<h2>Creating Page 1</h2>
<ul>
<li>I started with naming the page "Overview" then I went onto inserting, formatting, and re-sizing an image to be positioned on the top left of the report.</li>
<li>I inserted a slicer and added the "Year" column from the "Date" table into the visualisation field; I formatted it as a dropdown box.</li>
<li>I added another slicer, added "Region" from the "Region" table and left it as a list.</li>
<li>I added a line and stacked column chart visualisation. I put the "Month" data into the X-axis and the "Sales" into the Y-axis.</li>
<li>I added "Profit Margin" from the "Sales" table to the line Y-axis.</li>
<li>I added a stacked column chart to the report.</li>
<li>I added "Group" from the "Region" table to the X-axis, "Sales" from the "Sales" table to the Y-axis, and "Category" from the "Product" table to the Legend.</li>
<li>I added a stacked bar chart to the page. I added "Category" form the "Product" table and the "Quantity" from the "Sales" table</li>
</ul>
<p>&nbsp;</p>
<p>The final page looks like this:</p>
<img width="1084" height="603" alt="image" src="https://github.com/user-attachments/assets/a5ef059a-33c1-4bfe-a5c0-c300478d3f81" />
<p>The purpose of this is to provide an interactive overview of the performance of this company. It's broken down into sum of sales and profit margins by month, sum of sales by group and category, and sum of quantity by catergory.</p>
</div>

<div>
<h2>Creating Page 2</h2>
<ul>
<li>I started by adding a slicer based on the "Region" column from the "Region Table". I went into slicer setting to enable the "Select all" option</li>
<li>I then added a visual matrix and resized it to cover the rest of the page.</li>
<li>I added the "Fiscal" column from the "Date" table.</li>
<li>Then added "Orders", "Sales", "Cost", "Profit", and "Profit margin" from the "Sales" table.</li>
<li>I added to the filters section and under "filters on this page" I added "Category", "Subcategory", "Product", and "Color" from the "Produc" table</li>
</ul>
<p>&nbsp;</p>
<p>The final page looks like this</p>
<img width="702" height="329" alt="image" src="https://github.com/user-attachments/assets/f326cc0d-b353-4e33-aef0-d6eb17ae7cfb" />
<p>The purpose of this is to look a profits. We can see the orders, sum of sales, and sum of costs and how it relates to the profit and profit margin. It tells them the performance of certain years and it shows some intersting insights. For example, 2020 had the most orders but the difference between the sum of sales and the costs is so thin compared to the other years resulting in a smaller profit despite having the most sales.</p>
</div>
<div>
<h2>Creating Page 3</h2>
<ul>
<li>I started by inserting the "Salesperson" from the "Salesperson(Performance) table into the filters on this page.</li>
<li>I added a dropdown slicer containing the "Year" from the "Date" table</li>
<li>I added a Multi-row Card visual</li>
<li>I added the "Sales" data from the "Sales" table. The "Target", "Variance", and "Variance Margin" from the "Targets" table.</li>
<li>I formatted it to change the text size and background colour of the visual.</li>
<li>I added a Clustered Bar Chart</li>
<li>I added the "Month" from the "Date" table to the Y-axis. As well as "Month" from the "Date" table and "Target" from the "Targets" table to the X-axis</li>
<li>I copied and pasted the visual onto the empty half of the page.</li>
<li>I modified the new chart to a Clustered Column Chart</li>
</ul>
<p>&nbsp;</p>
<p>The final page looks like this</p>
<img width="917" height="515" alt="image" src="https://github.com/user-attachments/assets/f940e663-d053-4c5e-aa61-50fb9ba480f8" />
<p>This last page looks at sales performance for a salesman. This could help the company decide where to dedicate their training resources. The two graphs were added to see the same data expressed by two visualisation types.</p>
</div>

<div>
<h2>Syncing the Slicers</h2>
<p>The purpose of this task was sync all of the slicers across the different pages together.</p>
<img width="170" height="155" alt="image" src="https://github.com/user-attachments/assets/a97d5cea-ae18-403a-91bd-26dd64632d40" />
<img width="178" height="175" alt="image" src="https://github.com/user-attachments/assets/143b684d-1452-4b95-ae50-1e518b72813f" />
</div>

<div>
<h2>Publishing the Report</h2>
<img width="1311" height="109" alt="image" src="https://github.com/user-attachments/assets/a5e1c15c-7d88-441a-9d84-278aae3e379b" />
<img width="1446" height="876" alt="image" src="https://github.com/user-attachments/assets/01e51442-6df7-4d52-aa57-477e552fc7fb" />

<p>This achieves the idea of an interactive report that can breakdown the data by highlighting selected regions and months. On this overview dashboard I can interact with each of the graphs, by clicking on one it will change the rest of them providing me with specfic insights. Because I synced the sliders the same regions are selected when I look at the profit page. The year slider on the "Overview" page and the "My Performance" page also stay the same. </p>

</div>

<div>
<h2>Creating a dashboard</h2>
<img width="842" height="370" alt="image" src="https://github.com/user-attachments/assets/a88a17d0-315b-4d25-8d5d-647f2c0585ed" />
<p>This is a sales monitoring dashboard. This is done by pinning a visual from the report pages, adding a new tile based on an image URL, and using the Q&A feature to ask a question about the data and have PowerBI respond with a visual.</p>
<img width="819" height="376" alt="image" src="https://github.com/user-attachments/assets/4feca99e-4f20-4520-8fdb-7fc98aaca7fd" />
<p>This is a refreshed dashboard after updating the lab database. To do this, I ran a PowerShell script to update the data.</p>


</div>
