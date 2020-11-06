---
layout: post
title: How can we set Unique column in SharePoint 2010 list ?
date: 2012-09-03 18:09
author: techforumugm
comments: true
categories: [SharePoint Server]
---
<span> </span><span><span>In SharePoint 2010, we have the built in functionality to enforce the uniqueness of the field. But yes do remember that the field must be indexed first before you want to set it as a primary key.Create a list in SharePoint 2010 site and then create a field that you want to have a primary key. Go to list settings. Go to indexed columns and choose that column to be indexed.You can index up to 20 fields per list as you can see in the screen shot. I have already created one index which is on Customer_ID field in the list.<br /></span><span>                            </span></span><span><span>At the time of creating a field then we have an option to enforce the unique value. This can be set only when you have made that column indexed. So if you have not indexed this column, SP 2010 will ask you to do it.<br /></span></span><br /><div class="separator" style="clear:both;text-align:center;"><a href="https://techforumugm.files.wordpress.com/2012/09/b747d-u1-bmp.jpg" style="margin-left:1em;margin-right:1em;"><img border="0" src="https://techforumugm.files.wordpress.com/2012/09/b747d-u1-bmp.jpg" /></a></div><span><span></span></span><br /><span><span>After setting this field as unique key, then go ahead and add one value and try to add another with the same. It will not allow you to do following <span> </span>message.</span></span><br /><span></span><span> </span><br /><span style="font-family:Trebuchet MS;"></span><br /><div class="separator" style="clear:both;text-align:center;"><a href="https://techforumugm.files.wordpress.com/2012/09/68bf4-uc2-bmp.jpg" style="margin-left:1em;margin-right:1em;"><img border="0" height="130" src="https://techforumugm.files.wordpress.com/2012/09/68bf4-uc2-bmp.jpg?w=300" width="320" /></a></div><span></span><span><span></span></span><br /><div class="MsoNormal" style="line-height:normal;margin:0 0 10pt;"><span>Unique field is case insensitive. So if you have Leads and LEADS, it means same to the field. It is unique.it won’t allow you to save. Same is enforced even when you update the item.<br />Supported Column Types<br />• Single line of text<br />• Choice field (but not multichoice)<br />• Number<br />• Currency<br />• Date/ Time<br />• Lookup (but not multivalve)<br />• Person or Group (but not multivalve)<br />• Title (but not in a document library)</span></div>