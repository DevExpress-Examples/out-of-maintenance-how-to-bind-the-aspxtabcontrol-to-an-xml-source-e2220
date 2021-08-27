<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128563701/10.1.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E2220)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [TabControlDataSource_manual.xml](./CS/WebSite/App_Data/TabControlDataSource_manual.xml) (VB: [TabControlDataSource_manual.xml](./VB/WebSite/App_Data/TabControlDataSource_manual.xml))
* [Default.aspx](./CS/WebSite/Default.aspx) (VB: [Default.aspx](./VB/WebSite/Default.aspx))
* [Default.aspx.cs](./CS/WebSite/Default.aspx.cs) (VB: [Default.aspx.vb](./VB/WebSite/Default.aspx.vb))
<!-- default file list end -->
# How to bind the ASPxTabControl to an XML source
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/e2220/)**
<!-- run online end -->


<p>This sample demonstrates how to bind the ASPxTabControl to an XML data file. XML data are retrieved from the file via an XmlDataSource component whose XPath property is specifically defined. The XmlDataSource is used as a data source for the ASPxTabControl.</p><p>Based on the source data, the ASPxTabControl populates its Tabs collection with automatically created Tab objects. Tab object characteristics (such as text, image, navigate location, tooltip text, etc) are obtained from the data source's data fields (node attributes).</p><p>In this demo, the required data fields (node attributes) from which to retrieve tab data are indicated using the following specific data-related properties of the ASPxTabControl:<strong> ActiveTabImageUrlField</strong>,<strong> NameField</strong>,<strong> NavigateUrlField</strong>,<strong> TabImageUrlField</strong>, <strong>TextField</strong> and <strong>ToolTipField</strong>.</p>

<br/>


