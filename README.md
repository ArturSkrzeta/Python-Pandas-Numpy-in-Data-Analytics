<h2>Data Warehouse: CSV flat files -> Python -> Tableau -> Server -> Business Analysis -> New data</h2>
<h3>Intro</h3>
<img src="images/schema.JPG">
<h3>Data Warehousing consists of following steps:</h3>
<ol>
  <li>CSV as dasta extracts from different systems,</li>
  <li>Python for ETL (extract, transform, load),</li>
  <li>Tableau for data visualization dasboards,</li>
  <li>Server to get dasboard published for stakeholders,</li>
  <li>Busines Analysis,</li>
  <li>New data coming in from systems to storage,</li>
  <li>Go to step 1.</li>
</ol>
<h3>Demo with conclusions</h3>
<ul>
  <li>Python script combines flat files into one Tableau input.</li>
  <li>In this case I use static source  which is CSV flat files <b>(batch processing)</b>.</li>
  <li>However data pipelines are built also for real-time sources where target system requires constant data update <b>(stream processing)</b>.</li>
  <li>The example shows that ultimate destination of data pipelines doesn't have to be a data warehouse.</li>
  <li>Data pipeline can route the processed data into another applications like Tableu for building dashboards.</li>
  <li>Once dashboard built, there is the Tableau option for sending it into server.</li>
  <li>Once published, we can perfrom Business Analysis</li>
  <li>Making decisions based on BA leads to process improvements</li>
  <li>Process improvements generates new data that can undergo the Data Warehousing process all over again.</li>
  <li>Data Warehouse is a great tool for monitoring business processes and continuous improvement impementation.</li>
</ul>

<h3>Tableau Dashboard</h3>
<img src="images/dashboard.JPG">
<br>
<br>
<img src="images/dashboard2.JPG">
<h3>Business Analysis</h3>
<ul>
  <li>Taking conclusions from the analysis that can improve business perfomance.</li>
  <li>Conclusions based on the Tableau dashboard (data generated randomnly so the analysis is purely hypothetic):</li>
    <ul>
      <li>Only one country has positive cashflow as opposed to other countries. That means clients form Italy pay the money into their accounts.</li>
      <li>...</li>
    </ul>
<ul>
