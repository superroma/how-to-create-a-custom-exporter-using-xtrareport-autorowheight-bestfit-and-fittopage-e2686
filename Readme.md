

# How to create a custom exporter using XtraReport (AutoRowHeight, BestFit and FitToPage)

<p>This is an ASP version of the <a href="https://www.devexpress.com/Support/Center/p/E2231">How to create a custom exporter for the PivotGridControl by using the XtraReport suite</a> example that implements following suggestions:<br /><a href="https://www.devexpress.com/Support/Center/p/S130430">S130430: Support word wrap when printing and exporting</a><br /><a href="https://www.devexpress.com/Support/Center/p/S91257">S91257: Utilize a Line color when printing</a><br /><a href="https://www.devexpress.com/Support/Center/p/AS9011">AS9011: Print row headers on every page on export/printing</a><br />and the <a href="https://www.devexpress.com/Support/Center/p/S18650">S18650: Add an event that allows to provide custom size for field values (MeasureFieldValue, or so)</a>  suggestion for printing facilities.</p>

<br/>

<!--- Autogenerated footer --->
*Files to look at*:

* [Default.aspx](./CS/WebSite/Default.aspx) ([VB](./VB/WebSite/Default.aspx))
* [Default.aspx.cs](./CS/WebSite/Default.aspx.cs#L43-L56) ([VB](./VB/WebSite/Default.aspx.vb))
* [Error.aspx](./CS/WebSite/Error.aspx) ([VB](./VB/WebSite/Error.aspx))
* [Error.aspx.cs](./CS/WebSite/Error.aspx.cs) ([VB](./VB/WebSite/Error.aspx.vb))
* **[PivotReportGenerator.cs](./CS/WebSite/App_Code/PivotReportGenerator.cs)** **([VB](./VB/WebSite/App_Code/PivotReportGenerator.vb))**


[DevExpress, Inc](https://www.devexpress.com)
![Analytics](https://ga-beacon.appspot.com/UA-118635726-1/e2686?pixel)
