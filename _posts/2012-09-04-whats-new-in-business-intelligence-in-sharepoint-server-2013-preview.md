---
layout: post
title: What's new in business intelligence in SharePoint Server 2013 Preview
date: 2012-09-04 19:32
author: techforumugm
comments: true
categories: [SharePoint Server]
---
<h1 class="heading"><span>Excel BI</span></h1><div class="heading"> </div><span>Excel BI provides the capabilities to analyze and visually explore data of  any size, and to integrate and show interactive solutions. In SharePoint Server  2013 Preview, Excel BI offers certain new features to support business  intelligence applications. </span><span>These include the following:</span><br /><div class="section"><span></span></div><div class="unordered"><span><b>In-Memory BI Engine (IMBI):</b> The In Memory multidimensional data  analysis engine (IMBI), also known as the Vertipaq engine, allows for almost  instant analysis of millions of rows and is a fully integrated feature in the  Excel client.</span></div><div class="unordered"><span></span><span></span></div><div class="unordered"><span><b>Power View Add-in for Excel:</b> Power View ("Crescent") enables users to  visualize and interact with modeled data by using highly interactive  visualizations, animations and smart querying.. Users can present and share  insights with others through rich storyboard presentation capabilities.  PowerView is powered by the BI Semantic Model and the VertiPaq engine.</span></div><div class="unordered"><span></span><span></span><span><b>Decoupled PivotChart and PivotTable reports:</b> Users can now create  PivotChart reports without having to include a PivotTable report on the same  page.</span></div><div class="unordered"><span></span><span><b>Trend analysis:</b> Excel Services supports the ability to conduct trend  analysis from cells in PivotTable reports that use OLAP data, such as Analysis  Services cubes or PowerPivot data models.</span></div><a href="http://www.blogger.com/null" name="ExcelServices"></a><span></span><br /><span style="font-family:Trebuchet MS;"></span><br /><div class="separator" style="clear:both;text-align:center;"><a href="https://techforumugm.files.wordpress.com/2012/09/3eb03-bi-bmp.jpg" style="margin-left:1em;margin-right:1em;"><img border="0" height="189" src="https://techforumugm.files.wordpress.com/2012/09/3eb03-bi-bmp.jpg?w=300" width="320" /></a></div><br /><span style="font-family:Trebuchet MS;"></span><br /><span style="font-family:Trebuchet MS;"></span><br /><span>Excel Services</span><br /><span></span><span>Excel Services enables people to view and interact with Excel workbooks that  have been published to SharePoint sites. Users are able to explore data and  conduct analysis in a browser window just as they would by using the Excel  client. For more information about Excel Services in Microsoft SharePoint Server  2010, see Excel Services overview (SharePoint Server 2010) on Microsoft  TechNet.In SharePoint Server 2013 Preview, Excel Services offers certain new  features to support business intelligence applications. These include the  following:</span><span></span><br /><span>Data exploration improvements: People can more easily explore data and  conduct analysis in Excel Services reports that use SQL Server Analysis Services  data or PowerPivot data models. For example, users can point to a value in a  PivotChart or PivotTable report and see suggested ways to view additional  information. Users can also use commands such as Drill Down To to conduct  analysis. Users can also apply the Drill Down command by using a single mouse  click.</span><br /><div class="unordered"><span></span><span>Field list and field well support: Excel Services enables people to easily  view and change which items are displayed in rows, columns, values, and filters  in PivotChart reports and PivotTable reports that have been published to Excel  Services.</span></div><div class="unordered"><span>Calculated measures and members: Excel Services supports calculated measures  and calculated members that are created in Excel.</span><span></span></div><div class="unordered"><span>Enhanced timeline controls: Excel Services supports timeline controls that  render and behave as they do in the Excel client.</span></div><div class="unordered"><span>Application BI Servers: Administrators can specify SQL Server Analysis  Services servers to support more advanced analytic capabilities in Excel  Services.</span><span></span></div><div class="unordered"><span>Business Intelligence Center update: The Business Intelligence Center site  template has been streamlined. It not only has a new look, it is easier to  use.</span></div><a href="http://www.blogger.com/null" name="PerfPt"></a><span></span><br /><span><strong>PerformancePoint Services</strong></span><br /><span></span><br /><div class="section"><span>PerformancePoint Services enables users to create interactive dashboards that  display key performance indicators (KPIs) and data visualizations in the form of  scorecards, reports, and filters. For more information about PerformancePoint  Services in SharePoint Server 2010, see PerformancePoint Services overview  (SharePoint Server 2010) on Microsoft TechNet.In SharePoint Server 2013 Preview,  PerformancePoint Services offers certain new features to support business  intelligence applications. These include the following:</span></div><div class="section"><span></span><span><b>Dashboard Migration:</b> Users will be able to copy entire dashboards and  dependencies, including the .aspx file, to other users, servers, or site  collections. This feature also allows the ability to migrate single items to  other environments and migrate content by using Windows PowerShell commands.</span><span></span></div><div class="section"><span><b>Filter Enhancements &amp; Filter Search:</b> The UI has been enhanced to  allow users to easily view and manage filters including giving users the ability  to search for items within filters without having to navigate through the  tree.</span></div><div class="section"><span><b>BI Center Update:</b> The new BI Center is cleaner, and easier to use with  folders and libraries configured for easy use.</span><span></span></div><div class="section"><span><b>Support for Analysis Services Effective User:</b> This new feature  eliminates the need for Kerberos delegation when per-user authentication is used  for Analysis Services data sources. By supporting Analysis Services Effective  User feature, authorization checks will be based on the user specified by the  EffectiveUserName property instead of using the currently authenticated  user.</span></div><div class="section"><span><b>PerformancePoint Support on iPad:</b> PerformancePoint dashboards can now  be viewed and interacted with on iPad devices using the Safari web  browser.</span></div><a href="http://www.blogger.com/null" name="VisioSvcs"></a><span></span><br /><span><strong>Visio Services</strong></span><br /><strong><span style="font-family:Trebuchet MS;"></span></strong><br /><span></span><span>Visio Services is a service application that lets users share and view  Microsoft Visio Drawing (*.vsdx) and Visio 2010 Web drawing (*.vdw) files. The  service also enables data-connected Visio Drawing (*.vsdx) and Visio 2010 Web  drawing (*.vdw) files.to be refreshed and updated from various data sources.  </span><br /><span><b>Maximum Cache Size:</b> A new service parameter, it is located on the  Central Admininstration Visio Graphics Service Application Global Settings page.  The default value is 5120 MB.</span><span></span><br /><span><b>Health Analyzer rules:</b> New corresponding Health Analyzer rules have  been added to reflect the new Maximum Cache Size parameter.</span><br /><span><b>Updated Windows PowerShell cmdlets, Set-SPVisioPerformance:</b> This  cmdlet has been updated to include the new Maximum Cache Size parameter.</span><span></span><br /><span><b>Commenting on drawings supported:</b> Users can add meaningful comments to  a Visio Drawing (*.vsdx) collaboratively on the web via Visio Services in full  page rendering mode.</span>