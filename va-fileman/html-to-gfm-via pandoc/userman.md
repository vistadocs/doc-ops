---
Generator: Microsoft Word 15 (filtered)
lang: EN-US
title: VA FileMan User Guide
---

<div class="WordSection1">

VA FileMan 22.2

User Manual

<img src="user-manual.fld/image001.png" id="Picture 41" width="180"
height="180" alt="Title: VA Seal - Description: VA Seal" />

October 2018

 

Department of Veterans Affairs (VA)

Office of Information and Technology (OIT)

Enterprise Program Management Office (EPMO)

 

</div>

<span style="font-size:12.0pt;font-family:&quot;Times New Roman&quot;,serif;color:black">  
</span>

<div class="WordSection2">

<span id="_Toc446123251"></span><span id="_Toc41989686"></span><span id="_Toc83811830"></span><span id="_Toc90375053"></span><span id="_Toc527389037">Revision
History</span>

<table class="MsoNormalTable" data-border="1" data-cellspacing="0"
data-cellpadding="0"
data-summary="Table details the revision history including the date, revision number, description of changes, and the author."
width="628"
style="margin-left:7.15pt;border-collapse:collapse;border:none">
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th width="94" data-valign="top"
style="width: 70.25pt; border: solid windowtext 1.0pt; background: #DFDFDF; padding: 0in 5.4pt 0in 5.4pt"><p><span
id="COL001_TBL001"></span>Date</p></th>
<th width="78" data-valign="top"
style="width: 58.5pt; border: solid windowtext 1.0pt; border-left: none; background: #DFDFDF; padding: 0in 5.4pt 0in 5.4pt"><p>Revision</p></th>
<th width="270" data-valign="top"
style="width: 202.5pt; border: solid windowtext 1.0pt; border-left: none; background: #DFDFDF; padding: 0in 5.4pt 0in 5.4pt"><p>Description</p></th>
<th width="186" data-valign="top"
style="width: 139.5pt; border: solid windowtext 1.0pt; border-left: none; background: #DFDFDF; padding: 0in 5.4pt 0in 5.4pt"><p>Author</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td width="94" data-valign="top"
style="width: 70.25pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 5.4pt 0in 5.4pt"><p>10/15/2018</p></td>
<td width="78" data-valign="top"
style="width: 58.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 5.4pt 0in 5.4pt"><p>1.3</p></td>
<td width="270" data-valign="top"
style="width: 202.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 5.4pt 0in 5.4pt"><p>Tech
Edits:</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>Updated styles and formatting throughout.</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">       </span></span>Made
format and content updates throughout this document related to HTML and
Word document synchronization project.</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>Changed all references from “OI&amp;T” to “OIT”
throughout.</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>Updated all references throughout to Kernel manuals to the
current, correct title:</p>
<p><span style="font-family:&quot;Courier New&quot;">o<span
style="font:7.0pt &quot;Times New Roman&quot;">  
</span></span><em>Kernel 8.0 &amp; Kernel Toolkit 7.3 Systems Management
Guide</em></p>
<p><span style="font-family:&quot;Courier New&quot;">o<span
style="font:7.0pt &quot;Times New Roman&quot;">  
</span></span><em>Kernel 8.0 &amp; Kernel Toolkit 7.3 Developer’s
Guide</em></p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>Reformatted display of file and field names throughout;
moved file/field number immediataly following the file/field
name.</p></td>
<td width="186" data-valign="top"
style="width: 139.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 5.4pt 0in 5.4pt"><p>REDACTED</p></td>
</tr>
<tr class="even">
<td width="94" data-valign="top"
style="width: 70.25pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 5.4pt 0in 5.4pt"><p>01/17/2017</p></td>
<td width="78" data-valign="top"
style="width: 58.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 5.4pt 0in 5.4pt"><p>1.2</p></td>
<td width="270" data-valign="top"
style="width: 202.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 5.4pt 0in 5.4pt"><p>Changes
for patch DI*22.2*2:</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>Updated Section <u><span style="color:blue">7</span></u>,
adding eight field types to the list.</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>Added Sections <u><span
style="color:blue">7.10</span></u><span style="color:blue"> </span>–
<u><span style="color:blue">7.17</span></u><span
style="color:blue">.</span></p></td>
<td width="186" data-valign="top"
style="width: 139.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 5.4pt 0in 5.4pt"><p>REDACTED</p></td>
</tr>
<tr class="odd">
<td width="94" data-valign="top"
style="width: 70.25pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 5.4pt 0in 5.4pt"><p>11/30/2016</p></td>
<td width="78" data-valign="top"
style="width: 58.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 5.4pt 0in 5.4pt"><p>1.1</p></td>
<td width="270" data-valign="top"
style="width: 202.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 5.4pt 0in 5.4pt"><p>Updates
for Patch DI*22.2*4:</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>Updated Section <u><span
style="color:blue">4.3.3</span></u> (Internal vs. External Field Values
for Search Conditions) for the search conditions for a COMPUTED type
fields that evaluate to a date.</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>Added line to <u><span style="color:blue">Table
3</span></u> for :B Print Qualifier.</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>Updated <u><span style="color:blue">Table 31</span></u> to
revise wording about exiting Screen Editor.</p></td>
<td width="186" data-valign="top"
style="width: 139.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 5.4pt 0in 5.4pt"><p>REDACTED</p></td>
</tr>
<tr class="even">
<td width="94" data-valign="top"
style="width: 70.25pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 5.4pt 0in 5.4pt"><p>08/03/2016</p></td>
<td width="78" data-valign="top"
style="width: 58.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 5.4pt 0in 5.4pt"><p>1.0</p></td>
<td width="270" data-valign="top"
style="width: 202.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 5.4pt 0in 5.4pt"><p>Initial
release of VA FileMan 22.2 User Manual.</p></td>
<td width="186" data-valign="top"
style="width: 139.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 5.4pt 0in 5.4pt"><p>VA
FileMan 22.2 Development Team</p></td>
</tr>
</tbody>
</table>

 

<img src="user-manual.fld/image002.png" id="Picture 2" width="22"
height="22" alt="Note" />     **REF:** For the current patch history
related to this software, see the Patch Module (i.e., Patch User Menu
\[A1AE USER\]) on FORUM.

 

<span style="font-size:12.0pt;font-family:&quot;Times New Roman&quot;,serif;color:black">  
</span>

<span id="_Toc446123253"> </span>

Table of Contents

[Revision History<span style="color:black;display:none;
text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">ii</span>](#_Toc527389037)

[List of
Figures<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">ix</span>](#_Toc527389038)

[List of Tables<span style="color:
black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">xiv</span>](#_Toc527389039)

[Orientation<span style="color:black;
display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">xvi</span>](#_Toc527389040)

[1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;font-weight:normal;
text-decoration:none">    </span>Introduction<span style="color:black;
display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">1</span>](#_Toc527389041)

[1.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Fields, Records, and
Files<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">1</span>](#_Toc527389042)

[1.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Files and the
Database<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">2</span>](#_Toc527389043)

[1.3<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Printing Records from
Files<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">3</span>](#_Toc527389044)

[1.4<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Adding and Editing
Records<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">3</span>](#_Toc527389045)

[1.5<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>LAYGO File
Access<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">4</span>](#_Toc527389046)

[1.6<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Scrolling Mode vs. Screen
Mode<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">4</span>](#_Toc527389047)

[2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;font-weight:normal;
text-decoration:none">   
</span>Inquire<span style="color:black;display:none;
text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">5</span>](#_Toc527389048)

[2.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Overview<span style="color:black;display:none;text-decoration:none">..
</span><span style="color:black;display:none;text-decoration:none">5</span>](#_Toc527389049)

[2.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Inquire to File Entries
Option<span style="color:black;display:none;text-decoration:
none">.
</span><span style="color:black;display:none;text-decoration:none">6</span>](#_Toc527389050)

[2.2.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Standard Caption
Output<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">7</span>](#_Toc527389051)

[2.3<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>SORT
Templates<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">8</span>](#_Toc527389052)

[2.4<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Choose Your Own Print
Fields<span style="color:black;display:none;text-decoration:
none">.
</span><span style="color:black;display:none;text-decoration:none">9</span>](#_Toc527389053)

[2.5<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Choose Your Own
Device<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">10</span>](#_Toc527389054)

[3<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;font-weight:normal;
text-decoration:none">   
</span>Print<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">11</span>](#_Toc527389055)

[3.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>How to Print Reports from
Files<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">11</span>](#_Toc527389056)

[3.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>VA FileMan’s Print
Capabilities<span style="color:black;display:none;text-decoration:
none">.
</span><span style="color:black;display:none;text-decoration:none">11</span>](#_Toc527389057)

[3.3<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Standard Column Format for VA FileMan
Prints<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">12</span>](#_Toc527389058)

[3.4<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Sorting<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">13</span>](#_Toc527389059)

[3.4.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Specifying SORT BY
Fields<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">13</span>](#_Toc527389060)

[3.4.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Sorting
Order<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">14</span>](#_Toc527389061)

[3.4.3<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Choosing Print
Fields<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">22</span>](#_Toc527389062)

[3.4.4<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Other Print
Features<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">30</span>](#_Toc527389063)

[4<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;font-weight:normal;
text-decoration:none">   
</span>Search<span style="color:black;display:none;
text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">35</span>](#_Toc527389064)

[4.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>How to
Search<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">35</span>](#_Toc527389065)

[4.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Search
Steps<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">35</span>](#_Toc527389066)

[4.2.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Enter
Conditions<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">35</span>](#_Toc527389067)

[4.2.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Combine
Conditions<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">38</span>](#_Toc527389068)

[4.2.3<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Format
Output<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">40</span>](#_Toc527389069)

[4.3<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Details and
Features<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">41</span>](#_Toc527389070)

[4.3.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Sorting and
Searching<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">41</span>](#_Toc527389071)

[4.3.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>SEARCH
Templates<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">41</span>](#_Toc527389072)

[4.3.3<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Internal vs. External Field Values for Search
Conditions<span style="color:black;
display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">43</span>](#_Toc527389073)

[4.3.4<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Print Number of Matches
Found<span style="color:black;display:none;text-decoration:
none">.
</span><span style="color:black;display:none;text-decoration:none">43</span>](#_Toc527389074)

[4.3.5<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Searching
Multiples<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">43</span>](#_Toc527389075)

[5<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;font-weight:normal;
text-decoration:none">   
</span>Browser<span style="color:black;display:none;
text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">46</span>](#_Toc527389076)

[5.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Browser
Screen<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">47</span>](#_Toc527389077)

[5.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Browser
Features<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">48</span>](#_Toc527389078)

[5.2.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Navigation
Keystrokes<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">48</span>](#_Toc527389079)

[5.2.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Clipboard<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">49</span>](#_Toc527389080)

[5.2.3<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Search<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">50</span>](#_Toc527389081)

[5.2.4<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Online
Help<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">50</span>](#_Toc527389082)

[5.2.5<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Other
Features<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">51</span>](#_Toc527389083)

[5.2.6<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Browser as an
Option<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">52</span>](#_Toc527389084)

[6<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;font-weight:normal;
text-decoration:none">    </span>VA FileMan
Prompts<span style="color:black;
display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">52</span>](#_Toc527389085)

[6.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>The \<Enter\>
Key<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">53</span>](#_Toc527389086)

[6.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Standard Prompt
Structure<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">54</span>](#_Toc527389087)

[6.3<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Responding to
Prompts<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">54</span>](#_Toc527389088)

[6.4<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Getting Online Help at Any Prompt (Enter ? or
??)<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">55</span>](#_Toc527389089)

[6.5<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Incorrect
Responses<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">55</span>](#_Toc527389090)

[6.6<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Partial
Responses<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">56</span>](#_Toc527389091)

[6.7<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Default
Responses<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">56</span>](#_Toc527389092)

[6.8<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Longer Default Responses and the “Replace…With”
Editor<span style="color:black;
display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">57</span>](#_Toc527389093)

[6.8.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>“Replace...” Prompt
Shortcuts<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">58</span>](#_Toc527389094)

[6.9<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Prompts with a List of
Choices<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">58</span>](#_Toc527389095)

[6.10<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Key
Fields<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">60</span>](#_Toc527389096)

[6.11<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Special Responses to Field
Prompts<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">60</span>](#_Toc527389097)

[6.11.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Deleting a Field’s Value
(@)<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">60</span>](#_Toc527389098)

[6.11.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Jumping to another Field with the Caret
(^)<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">61</span>](#_Toc527389099)

[6.11.3<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Exiting with the Single Caret
(^)<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">61</span>](#_Toc527389100)

[6.11.4<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Exiting with the Double Caret
(^^)<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">62</span>](#_Toc527389101)

[6.11.5<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Mandatory (Required)
Fields<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">62</span>](#_Toc527389102)

[6.11.6<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Spacebar
Recall<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">62</span>](#_Toc527389103)

[6.11.7<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Typical Data Entry
Session<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">63</span>](#_Toc527389104)

[7<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;font-weight:normal;
text-decoration:none">    </span>Field Types<span style="color:black;
display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">64</span>](#_Toc527389105)

[7.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Introduction<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">64</span>](#_Toc527389106)

[7.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>DATE/TIME
Fields<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">65</span>](#_Toc527389107)

[7.2.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Acceptable Formats for Entering
Dates<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">65</span>](#_Toc527389108)

[7.2.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Abbreviations for
Dates<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">66</span>](#_Toc527389109)

[7.2.3<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Times in DATE/TIME
Fields<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">66</span>](#_Toc527389110)

[7.2.4<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Abbreviations for
Times<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">67</span>](#_Toc527389111)

[7.3<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>NUMERIC
Fields<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">67</span>](#_Toc527389112)

[7.4<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>SET OF CODES
Fields<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">68</span>](#_Toc527389113)

[7.4.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Internal vs. External Values for SET OF CODES
Fields<span style="color:black;display:
none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">68</span>](#_Toc527389114)

[7.5<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>FREE TEXT
Fields<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">69</span>](#_Toc527389115)

[7.6<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>WORD-PROCESSING
Fields<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">69</span>](#_Toc527389116)

[7.7<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>COMPUTED
Fields<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">71</span>](#_Toc527389117)

[7.8<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>POINTER TO A FILE
Fields<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">72</span>](#_Toc527389118)

[7.9<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>VARIABLE-POINTER
Fields<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">73</span>](#_Toc527389119)

[7.10<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>BOOLEAN
Fields<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">75</span>](#_Toc527389120)

[7.11<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>LABEL REFERENCE
Fields<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">75</span>](#_Toc527389121)

[7.12<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>TIME
Fields<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">76</span>](#_Toc527389122)

[7.13<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>YEAR
Fields<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">76</span>](#_Toc527389123)

[7.14<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>UNIVERSAL TIME
Fields<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">76</span>](#_Toc527389124)

[7.15<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>FT POINTER
Fields<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">77</span>](#_Toc527389125)

[7.16<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>FT DATE
Fields<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">77</span>](#_Toc527389126)

[7.17<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>RATIO
Fields<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">77</span>](#_Toc527389127)

[7.18<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Subfiles
(Multiples)<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">78</span>](#_Toc527389128)

[8<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;font-weight:normal;
text-decoration:none">    </span>Adding and Deleting
Records<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">79</span>](#_Toc527389129)

[8.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>.01
Field<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">79</span>](#_Toc527389130)

[8.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>How to Add a
Record<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">79</span>](#_Toc527389131)

[8.3<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Adding a Duplicate Record (Use
Quotes)<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">80</span>](#_Toc527389132)

[8.4<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>How to Delete a
Record<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">81</span>](#_Toc527389133)

[8.5<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Repointing When Deleting
Records<span style="color:black;display:none;text-decoration:
none">.
</span><span style="color:black;display:none;text-decoration:none">81</span>](#_Toc527389134)

[8.6<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Adding Records to a POINTER TO A FILE
Field<span style="color:black;display:none;
text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">84</span>](#_Toc527389135)

[8.6.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Adding Duplicate-Named
Entries<span style="color:black;display:none;text-decoration:
none">.
</span><span style="color:black;display:none;text-decoration:none">85</span>](#_Toc527389136)

[8.7<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Adding and Deleting from
Multiples<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">86</span>](#_Toc527389137)

[8.8<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Enter or Edit File Entries
Option<span style="color:black;display:none;text-decoration:
none">.
</span><span style="color:black;display:none;text-decoration:none">87</span>](#_Toc527389138)

[9<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;font-weight:normal;
text-decoration:none">   
</span>ScreenMan<span style="color:black;display:
none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">89</span>](#_Toc527389139)

[9.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Scrolling Mode Editing vs. Screen Mode
Editing<span style="color:black;display:none;
text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">89</span>](#_Toc527389140)

[9.1.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Similarities<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">89</span>](#_Toc527389141)

[9.1.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Differences<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">90</span>](#_Toc527389142)

[9.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>ScreenMan
Screen<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">91</span>](#_Toc527389143)

[9.3<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Navigation Keystrokes (Cursor
Movement)<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">92</span>](#_Toc527389144)

[9.3.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>How to Navigate between
Fields<span style="color:black;display:none;text-decoration:
none">.
</span><span style="color:black;display:none;text-decoration:none">92</span>](#_Toc527389145)

[9.3.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>How to Navigate between
Pages<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">93</span>](#_Toc527389146)

[9.3.3<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Saving and
Exiting<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">93</span>](#_Toc527389147)

[9.3.4<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Command Line Options (SAVE, EXIT,
etc.)<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">94</span>](#_Toc527389148)

[9.4<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Editing<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">95</span>](#_Toc527389149)

[9.4.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>How to Edit
Fields<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">95</span>](#_Toc527389150)

[9.4.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Long Fields (and the Zoom
Editor)<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">96</span>](#_Toc527389151)

[9.4.3<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>WORD-PROCESSING
Fields<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">96</span>](#_Toc527389152)

[9.4.4<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Multiples<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">97</span>](#_Toc527389153)

[9.4.5<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Navigational Keys for Repeating
Blocks<span style="color:black;display:none;text-decoration:
none">.
</span><span style="color:black;display:none;text-decoration:none">101</span>](#_Toc527389154)

[9.5<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Details<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">101</span>](#_Toc527389155)

[9.5.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>How to File
Edits<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">101</span>](#_Toc527389156)

[9.5.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">      
</span>Troubleshooting<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">102</span>](#_Toc527389157)

[10<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;font-weight:normal;
text-decoration:none">  </span>Word-Processing
Fields<span style="color:black;
display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">102</span>](#_Toc527389158)

[10.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Word-Processing
Editors<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">102</span>](#_Toc527389159)

[10.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Choosing a Preferred
Editor<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">102</span>](#_Toc527389160)

[10.3<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Switching to another Editor While
Editing<span style="color:black;display:none;
text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">103</span>](#_Toc527389161)

[11<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;font-weight:normal;
text-decoration:none">  </span>Screen Editor<span style="color:black;
display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">103</span>](#_Toc527389162)

[11.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Screen Editor
Screen<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">105</span>](#_Toc527389163)

[11.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Entering
Text<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">105</span>](#_Toc527389164)

[11.3<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Entering
Commands<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">105</span>](#_Toc527389165)

[11.4<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Navigation Keystrokes (Cursor
Movement)<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">106</span>](#_Toc527389166)

[11.5<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Saving, Printing, and
Exiting<span style="color:black;display:none;text-decoration:
none">.
</span><span style="color:black;display:none;text-decoration:none">107</span>](#_Toc527389167)

[11.6<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Finding
Text<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">107</span>](#_Toc527389168)

[11.7<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Formatting
Paragraphs<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">108</span>](#_Toc527389169)

[11.8<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Cutting and
Pasting<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">108</span>](#_Toc527389170)

[11.9<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Deleting<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">109</span>](#_Toc527389171)

[11.10<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">  
</span>Settings/Modes<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">110</span>](#_Toc527389172)

[11.11<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">  
</span>Troubleshooting<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">110</span>](#_Toc527389173)

[11.11.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">  
</span>Terminal Type
Setting<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">110</span>](#_Toc527389174)

[11.11.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">  
</span>\<PF\> Keys Not Working: How to
Exit<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">111</span>](#_Toc527389175)

[11.12<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">  
</span>Screen Editor and Personal
Computers<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">111</span>](#_Toc527389176)

[11.12.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">  
</span>Pasting and
Uploading<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">111</span>](#_Toc527389177)

[11.12.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">  
</span>Symbol
Characters<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">111</span>](#_Toc527389178)

[11.12.3<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">  
</span>Files: Save as
Text<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">111</span>](#_Toc527389179)

[11.12.4<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">  
</span>Wrap Vs. No
Wrap<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">111</span>](#_Toc527389180)

[11.12.5<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">  
</span>Avoiding Lost
Characters<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">112</span>](#_Toc527389181)

[12<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;font-weight:normal;
text-decoration:none">  </span>Line
Editor<span style="color:black;display:
none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">113</span>](#_Toc527389182)

[12.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Recognizing the Line
Editor<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">113</span>](#_Toc527389183)

[12.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>How to Enter Text in the Line
Editor<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">113</span>](#_Toc527389184)

[12.3<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Revising Existing
Text<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">114</span>](#_Toc527389185)

[12.3.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Shortcut: Enter Line Number to Edit at “EDIT Option:”
Prompt<span style="color:black;
display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">114</span>](#_Toc527389186)

[12.4<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>“Replace...With” Edits: Be
Careful<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">115</span>](#_Toc527389187)

[12.4.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Shortcuts at the “Replace...With”
Prompt<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">115</span>](#_Toc527389188)

[12.4.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>“Replace...” Prompt
Shortcuts<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">116</span>](#_Toc527389189)

[12.5<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Commands<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">117</span>](#_Toc527389190)

[12.5.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Available
Commands<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">117</span>](#_Toc527389191)

[12.5.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>LIST: List the
Message<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">117</span>](#_Toc527389192)

[12.5.3<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>ADD: Append More
Text<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">118</span>](#_Toc527389193)

[12.5.4<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>JOIN: Combine Two Lines of
Text<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">118</span>](#_Toc527389194)

[12.5.5<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>INSERT: Insert New Lines of Text between Existing
Ones<span style="color:black;
display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">118</span>](#_Toc527389195)

[12.5.6<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>DELETE: Delete a Line or
Lines<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">119</span>](#_Toc527389196)

[12.6<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Advanced
Features<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">119</span>](#_Toc527389197)

[12.6.1<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>File Transfer (Use When Uploading ASCII
Text)<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">119</span>](#_Toc527389198)

[12.6.2<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Text Terminator-String
Change<span style="color:black;display:none;text-decoration:
none">.
</span><span style="color:black;display:none;text-decoration:none">120</span>](#_Toc527389199)

[12.6.3<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Programmer Edit (Edit Lines with M
Commands)<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">121</span>](#_Toc527389200)

[12.6.4<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Editor Change: Switch
Editors<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">121</span>](#_Toc527389201)

[12.6.5<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,sans-serif;color:windowtext;text-decoration:none">    
</span>Transfer Text (from another WORD-PROCESSING
Field)<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">121</span>](#_Toc527389202)

[Glossary<span style="color:black;
display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">124</span>](#_Toc527389203)

[Index<span style="color:black;
display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">131</span>](#_Toc527389204)

**<span style="font-family:&quot;Times New Roman Bold&quot;,serif"> </span>**

<span id="_Toc527389038">List of Figures</span>

[Figure 1: Example Showing Several Patient
Records<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">1</span>](#_Toc527389205)

[Figure 2: Representation of a
Database<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">2</span>](#_Toc527389206)

[Figure 3: Example of a Printed
Report<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">3</span>](#_Toc527389207)

[Figure 4: Inquire—Dialogue Using the Inquire to File Entries Option:
Sample User Entries at Prompts and Sample
Report<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">6</span>](#_Toc527389208)

[Figure 5: Inquire—Prompt to Store Entries into a
Template<span style="color:black;display:none;text-decoration:
none">.
</span><span style="color:black;display:none;text-decoration:none">8</span>](#_Toc527389209)

[Figure 6: Inquire—Dialogue for Choosing Your Own Print Fields: Sample
User Entries at
Prompts<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">9</span>](#_Toc527389210)

[Figure 7: Inquire—Dialogue for Choosing a Device *and* Getting STANDARD
CAPTIONED OUTPUT: Sample User Entries at
Prompts<span style="color:black;display:none;text-decoration:none"> 
</span><span style="color:black;display:none;text-decoration:none">10</span>](#_Toc527389211)

[Figure 8: Print—Example of a Standard
Printout<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">12</span>](#_Toc527389212)

[Figure 9: Print—Dialogue for Creating a Printed Report: Sample User
Entries at Prompts<span style="color:black;
display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">12</span>](#_Toc527389213)

[Figure 10: Print—Dialogue for Specifying a Sort Order for a Printed
Report: Sample User Entries at
Prompts<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">13</span>](#_Toc527389214)

[Figure 11: Print—Example of a Printed Report in a Specific
Order<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">13</span>](#_Toc527389215)

[Figure 12: Print—Sorting Canonic and Non-Canonic
Numbers<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">14</span>](#_Toc527389216)

[Figure 13: Print—Specifying a Sort
Range<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">15</span>](#_Toc527389217)

[Figure 14: Print—Choosing Entries with a Specific
Value<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">15</span>](#_Toc527389218)

[Figure 15: Print—Dialogue to Include Records with NULL Values: Sample
User Entries at Prompts<span style="color:
black;display:none;text-decoration:none"> 
</span><span style="color:black;display:none;text-decoration:none">16</span>](#_Toc527389219)

[Figure 16: Print—Sample Report Displaying Fields with NULL
Values<span style="color:black;display:none;
text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">17</span>](#_Toc527389220)

[Figure 17: Print—Dialogue to Create a Sort Template: Sample User
Entries at Prompts<span style="color:black;
display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">21</span>](#_Toc527389221)

[Figure 18: Print—Forcing the Creation of a Sort
Template<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">22</span>](#_Toc527389222)

[Figure 19: Print—Reusing a Sort
Template<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">22</span>](#_Toc527389223)

[Figure 20: Print—Confirmation Message to Print All
Fields<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">22</span>](#_Toc527389224)

[Figure 21: Print—Stringing Several Print Qualifiers
Together<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">26</span>](#_Toc527389225)

[Figure 22: Print—Obtaining a List of All Print Templates for a
File<span style="color:black;display:none;text-decoration:
none">.
</span><span style="color:black;display:none;text-decoration:none">27</span>](#_Toc527389226)

[Figure 23: Print—Creating a Print
Template<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">27</span>](#_Toc527389227)

[Figure 24: Print—Forcing the Creation of a Print
Template<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">27</span>](#_Toc527389228)

[Figure 25: Print—Reusing a Print
Template<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">28</span>](#_Toc527389229)

[Figure 26: Print—Inserting a New Print
Field<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">28</span>](#_Toc527389230)

[Figure 27: Print—Inserting a Multiple Print
Field<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">28</span>](#_Toc527389231)

[Figure 28: Print—Choosing a Captioned Print
Template<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">29</span>](#_Toc527389232)

[Figure 29: Print—Dialogue Encountered when Creating a Captioned Print
Report<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">29</span>](#_Toc527389233)

[Figure 30: Print—Generating Multiple Copies of a
Report<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">30</span>](#_Toc527389234)

[Figure 31: Print—Example of a Report
Heading<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">31</span>](#_Toc527389235)

[Figure 32: Print—Dialogue to Customize Report Headings: Sample User
Entries at Prompts<span style="color:black;
display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">31</span>](#_Toc527389236)

[Figure 33: Print—Suppressing Headings on a
Report<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">32</span>](#_Toc527389237)

[Figure 34: Print—Confirming the Suppression of Headings in a Print
Template<span style="color:black;display:
none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">32</span>](#_Toc527389238)

[Figure 35: Print—Creating a Print Template with a Custom
Header<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">32</span>](#_Toc527389239)

[Figure 36: Print—Selecting an Existing Print Template with a Custom
Header<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">33</span>](#_Toc527389240)

[Figure 37: Print—Including a Custom Footer in a Print
Template<span style="color:black;display:none;text-decoration:
none">.
</span><span style="color:black;display:none;text-decoration:none">33</span>](#_Toc527389241)

[Figure 38: Print—Including a Custom Header and Footer in a Print
Template<span style="color:black;display:none;
text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">33</span>](#_Toc527389242)

[Figure 39: Search—Example of a Search
Condition<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">37</span>](#_Toc527389243)

[Figure 40: Search—Example of Two Truth
Tests<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">38</span>](#_Toc527389244)

[Figure 41: Search—Example of a Single Search Condition Using a Truth
Test<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">39</span>](#_Toc527389245)

[Figure 42: Search—Example of a Multiple Search Condition Using Truth
Tests<span style="color:black;display:none;
text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">39</span>](#_Toc527389246)

[Figure 43. Search—Dialogue to a Completed Search: Sample User Entries
at Prompts and Sample
Report<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">40</span>](#_Toc527389247)

[Figure 44: Search—Creating a Search
Template<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">42</span>](#_Toc527389248)

[Figure 45: Search—Reusing a Search Template at the “SEARCH FOR FIELD”
Prompt<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">42</span>](#_Toc527389249)

[Figure 46: Search—Reusing a Search Template at the “SORT BY”
Prompt<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">42</span>](#_Toc527389250)

[Figure 47: Search—Dialogue of a Search on a Multiple Field: Sample User
Entries at Prompts<span style="color:black;
display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">44</span>](#_Toc527389251)

[Figure 48: Search—Prompts Encountered when Searching on a Multiple
Field<span style="color:black;display:none;
text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">45</span>](#_Toc527389252)

[Figure 49: Search—Additional Prompts Encountered when Searching on a
Multiple Field<span style="color:black;
display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">45</span>](#_Toc527389253)

[Figure 50: Browser—Sample Screen Component
Parts<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">47</span>](#_Toc527389254)

[Figure 51: VA FileMan Prompts—Sample Component Parts of a
Prompt<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">54</span>](#_Toc527389255)

[Figure 52: VA FileMan Prompts—Asking for a
Response<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">54</span>](#_Toc527389256)

[Figure 53: VA FileMan Prompts—“Select-type” Prompts, Offering a
Choice<span style="color:black;
display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">54</span>](#_Toc527389257)

[Figure 54: VA FileMan Prompts—“Yes/No-type”
Prompts<span style="color:black;display:none;text-decoration:
none">.
</span><span style="color:black;display:none;text-decoration:none">55</span>](#_Toc527389258)

[Figure 55: VA FileMan Prompts—Dialogue to Choose from a List in VA
FileMan: Sample User Entries at
Prompts<span style="color:black;display:none;text-decoration:none"> 
</span><span style="color:black;display:none;text-decoration:none">56</span>](#_Toc527389259)

[Figure 56: VA FileMan Prompts—Prompts with Default
Responses<span style="color:black;display:none;text-decoration:
none">.
</span><span style="color:black;display:none;text-decoration:none">56</span>](#_Toc527389260)

[Figure 57: VA FileMan Prompts—Overriding the Default Response to a
Prompt<span style="color:black;
display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">56</span>](#_Toc527389261)

[Figure 58: VA FileMan Prompts—Long Responses Employing the
“Replace...With” Editor<span style="color:black;
display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">57</span>](#_Toc527389262)

[Figure 59: VA FileMan Prompts—Changing a Long Response Using the
“Replace...With” Editor<span style="color:black;
display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">57</span>](#_Toc527389263)

[Figure 60: VA FileMan Prompts—Replacing an Entire Entry Using the
Ellipsis
(...)<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">57</span>](#_Toc527389264)

[Figure 61: VA FileMan Prompts—Deleting an Entire Entry Using the
At-Sign (@)<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">57</span>](#_Toc527389265)

[Figure 62: VA FileMan Prompts—Displaying a List of
Choices<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">58</span>](#_Toc527389266)

[Figure 63: VA FileMan Prompts—Displaying a Subset of Choices from a
List<span style="color:black;
display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">59</span>](#_Toc527389267)

[Figure 64: VA FileMan Prompts—Entering a Duplicate Compound
Key<span style="color:black;display:none;text-decoration:
none">.
</span><span style="color:black;display:none;text-decoration:none">60</span>](#_Toc527389268)

[Figure 65: VA FileMan Prompts—Deleting a Field
Entry<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">60</span>](#_Toc527389269)

[Figure 66: VA FileMan Prompts—Using the Caret (^) Key to “Jump” to a
Specific Field<span style="color:black;
display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">61</span>](#_Toc527389270)

[Figure 67: VA FileMan Prompts—Using the Caret (^) Key to Exit a
Prompt<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">61</span>](#_Toc527389271)

[Figure 68: VA FileMan Prompts—Using the “Spacebar Recall”
Functionality<span style="color:black;display:none;
text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">62</span>](#_Toc527389272)

[Figure 69: VA FileMan Prompts—Example of a Typical Data Entry
Session<span style="color:black;display:none;
text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">63</span>](#_Toc527389273)

[Figure 70: Field Types—Entering a Date at a DATE/TIME
Field<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">65</span>](#_Toc527389274)

[Figure 71: Field Types—Entering a Date and
Time<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">66</span>](#_Toc527389275)

[Figure 72: Field Types—Example of a NUMERIC
Field<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">67</span>](#_Toc527389276)

[Figure 73: Field Types—Example of a SET OF CODES
Field<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">68</span>](#_Toc527389277)

[Figure 74: Field Types—Example of a FREE TEXT
Field<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">69</span>](#_Toc527389278)

[Figure 75: Field Types—Example of a FREE TEXT Field with
Validation<span style="color:black;display:none;
text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">69</span>](#_Toc527389279)

[Figure 76: Field Types—Example of a WORD-PROCESSING Field, Using the
Screen Editor<span style="color:black;
display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">70</span>](#_Toc527389280)

[Figure 77: Field Types—Example of a WORD-PROCESSING Field, Using the
Line Editor<span style="color:black;
display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">70</span>](#_Toc527389281)

[Figure 78: Field Types—Dialogue to Choose a COMPUTED Field: Sample User
Entries at Prompts<span style="color:black;
display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">71</span>](#_Toc527389282)

[Figure 79: Field Types—Sample of a POINTER TO A FILE Field (1 of
2)<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">72</span>](#_Toc527389283)

[Figure 80. Field Types—Sample of a POINTER TO A FILE Field (2 of
2)<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">72</span>](#_Toc527389284)

[Figure 81: Field Types—Dialogue Showing Help for Entries in a
VARIABLE-POINTER Field: Sample User Entries at
Prompts<span style="color:black;display:none;text-decoration:none"> 
</span><span style="color:black;display:none;text-decoration:none">73</span>](#_Toc527389285)

[Figure 82: Field Types—Using the PREFIX and a Question Mark to Get a
List of Entries in a Pointed-To
File<span style="color:black;display:none;text-decoration:none"> 
</span><span style="color:black;display:none;text-decoration:none">74</span>](#_Toc527389286)

[Figure 83: Field Types—Searching for an Entry in a Pointed-To
File<span style="color:black;display:none;text-decoration:
none">.
</span><span style="color:black;display:none;text-decoration:none">74</span>](#_Toc527389287)

[Figure 84: Field Types—Adding a New Entry to a Pointed-To
File<span style="color:black;display:none;text-decoration:
none">.
</span><span style="color:black;display:none;text-decoration:none">75</span>](#_Toc527389288)

[Figure 85: Field Types—Sample Subfile (Multiple)
Field<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">78</span>](#_Toc527389289)

[Figure 86: Field Types—Example of a Multiple Field
Prompt<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">78</span>](#_Toc527389290)

[Figure 87: Records—Dialogue to Add a Record: Sample User Entries at
Prompts<span style="color:black;display:none;
text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">79</span>](#_Toc527389291)

[Figure 88: Records—Dialogue to Add a Duplicate Record: Sample User
Entries at Prompts<span style="color:black;
display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">80</span>](#_Toc527389292)

[Figure 89: Records—Dialogue to Delete a Record: Sample User Entries at
Prompts<span style="color:black;display:none;
text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">81</span>](#_Toc527389293)

[Figure 90: Records—Dialogue to Delete a Record and Re-Point to a
Different Record: Sample User Entries at
Prompts<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">82</span>](#_Toc527389294)

[Figure 91: Records—Dialogue Showing a Report of Changed Entries: Sample
Report<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">83</span>](#_Toc527389295)

[Figure 92: Records—Dialogue to Add a New Entry to a Pointed-To File:
Sample User Entries at
Prompts<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">84</span>](#_Toc527389296)

[Figure 93: Records—Adding a Duplicate-Named Entry to a Pointed-To
File<span style="color:black;display:
none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">85</span>](#_Toc527389297)

[Figure 94: Records—Adding an Entry to Both the Current File and to a
Pointed-To File<span style="color:black;
display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">85</span>](#_Toc527389298)

[Figure 95: Records—Dialogue Showing Entries to a Multiple Field: Sample
User Entries at
Prompts<span style="color:black;display:none;text-decoration:none"> 
</span><span style="color:black;display:none;text-decoration:none">86</span>](#_Toc527389299)

[Figure 96: Records—Choosing a File to
Edit<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">87</span>](#_Toc527389300)

[Figure 97: Records—Choosing the File Fields to
Edit<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">87</span>](#_Toc527389301)

[Figure 98: Records—Choosing Specific File Fields to
Edit<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">87</span>](#_Toc527389302)

[Figure 99: Records—Dialogue Using the Enter or Edit File Entries
Option: Sample User Entries at
Prompts<span style="color:black;display:none;text-decoration:none"> 
</span><span style="color:black;display:none;text-decoration:none">88</span>](#_Toc527389303)

[Figure 100: ScreenMan—Sample Screen Component Parts and Field
Values<span style="color:black;display:none;
text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">91</span>](#_Toc527389304)

[Figure 101: ScreenMan—A “Popup” Subpage for a Multiple: Sample
Component Parts and Field
Values<span style="color:black;display:none;text-decoration:none"> 
</span><span style="color:black;display:none;text-decoration:none">98</span>](#_Toc527389305)

[Figure 102: ScreenMan—Dialogue Showing a Repeating Block in a Multiple:
Sample ScreenMan Fields and Field
Values<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">100</span>](#_Toc527389306)

[Figure 103: Screen Editor—Sample WORD-PROCESSING Field in the Screen
Editor: Sample Component
Parts<span style="color:black;display:none;text-decoration:none"> 
</span><span style="color:black;display:none;text-decoration:none">105</span>](#_Toc527389307)

[Figure 104: Screen Editor—Dialogue to Do a “FIND” while Using the
Screen Editor<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">108</span>](#_Toc527389308)

[Figure 105: Line Editor—Example of a WORD-PROCESSING Field in the Line
Editor<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">113</span>](#_Toc527389309)

[Figure 106: Line Editor—Prompts for Entering Word-Processing
Text<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">113</span>](#_Toc527389310)

[Figure 107: Line Editor—Completing Your Edits in the Line
Editor<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">114</span>](#_Toc527389311)

[Figure 108: Line Editor—Shortcut to Edit a Specific Line Using the Line
Editor<span style="color:black;display:
none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">114</span>](#_Toc527389312)

[Figure 109: Line Editor—Example of an *Incorrect* Edit with the
“Replace...With” Editor<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">115</span>](#_Toc527389313)

[Figure 110: Line Editor—Using the Ellipsis (…) to Replace an Entire
Line<span style="color:black;display:none;
text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">115</span>](#_Toc527389314)

[Figure 111: Line Editor—Edit Options Available with the Line
Editor<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">117</span>](#_Toc527389315)

[Figure 112: Line Editor—Example Using the List a Range of Lines
Option<span style="color:black;display:none;
text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">117</span>](#_Toc527389316)

[Figure 113: Line Editor—Example Using the Add Lines to End of Text
Option<span style="color:black;display:none;
text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">118</span>](#_Toc527389317)

[Figure 114: Line Editor—Example Using the Join Line to the One
Following Option<span style="color:black;display:none;
text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">118</span>](#_Toc527389318)

[Figure 115: Line Editor—Example Using the Insert Lines after an
Existing Line Option<span style="color:black;
display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">118</span>](#_Toc527389319)

[Figure 116: Line Editor—Example Using the Delete Line(s)
Option<span style="color:black;display:none;text-decoration:
none">.
</span><span style="color:black;display:none;text-decoration:none">119</span>](#_Toc527389320)

[Figure 117: Line Editor—Example of Entering M Code while Using the
Y-Programmer Edit Option<span style="color:
black;display:none;text-decoration:none"> 
</span><span style="color:black;display:none;text-decoration:none">121</span>](#_Toc527389321)

[Figure 118: Line Editor—Dialogue of the Extended Pointer Syntax while
Using the Transfer Lines From Another Document Option: Sample User
Entries at Prompts (Example
\#1)<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">122</span>](#_Toc527389322)

[Figure 119: Line Editor—Dialogue of the Extended Pointer Syntax while
Using the Transfer Lines From Another Document Option: Sample User
Entries at Prompts (Example
\#2)<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">122</span>](#_Toc527389323)

[Figure 120: Line Editor—Example of a Possible Warning Message when
Using the Transfer Lines From Another Document
Option<span style="color:black;display:none;text-decoration:none"> 
</span><span style="color:black;display:none;text-decoration:none">123</span>](#_Toc527389324)

 

**<span style="font-size:14.0pt;font-family:&quot;Arial&quot;,sans-serif;color:black">  
</span>**

<span id="_Toc527389039">List of Tables</span>

[Table 1: Documentation Symbol
Descriptions<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">xix</span>](#_Toc527389325)

[Table 2: Print—Sort
Qualifiers<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">18</span>](#_Toc527389326)

[Table 3: Print—Print
Qualifiers<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">23</span>](#_Toc527389327)

[Table 4: Search—Condition
Tests<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">36</span>](#_Toc527389328)

[Table 5: Search—Condition
Operators<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">38</span>](#_Toc527389329)

[Table 6: Browser—Navigation
Keystrokes<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">48</span>](#_Toc527389330)

[Table 7: Browser—Using the Browser
Clipboard<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">49</span>](#_Toc527389331)

[Table 8: Browser—Searching in the
Browser<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">50</span>](#_Toc527389332)

[Table 9: Browser—Online
Help<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">50</span>](#_Toc527389333)

[Table 10: Browser—Other
Features<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">51</span>](#_Toc527389334)

[Table 11: VA FileMan Prompts—Getting Online Help at any Prompts Using
Question Marks<span style="color:black;
display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">55</span>](#_Toc527389335)

[Table 12: VA FileMan Prompts—“Replace” Prompt
Shortcuts<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">58</span>](#_Toc527389336)

[Table 13: Field Types—Abbreviations for
Dates<span style="color:black;display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">66</span>](#_Toc527389337)

[Table 14: Field Types—Abbreviations for
Times<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">67</span>](#_Toc527389338)

[Table 15: BOOLEAN Data Type
Example<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">75</span>](#_Toc527389339)

[Table 16: LABEL REFERENCE Data Type
Example<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">75</span>](#_Toc527389340)

[Table 17: TIME Data Type
Example<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">76</span>](#_Toc527389341)

[Table 18: YEAR Data Type
Example<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">76</span>](#_Toc527389342)

[Table 19: UNIVERSAL TIME Data Type
Example<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">76</span>](#_Toc527389343)

[Table 20: FT POINTER Data Type
Example<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">77</span>](#_Toc527389344)

[Table 21: FT DATE Data Type
Example<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">77</span>](#_Toc527389345)

[Table 22: RATIO Data Type
Example<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">77</span>](#_Toc527389346)

[Table 23: ScreenMan—Keystrokes to Navigate between Fields in a
ScreenMan Form<span style="color:black;display:
none;text-decoration:none">..
</span><span style="color:black;display:none;text-decoration:none">92</span>](#_Toc527389347)

[Table 24: ScreenMan—Keystrokes to Navigate between Pages in a ScreenMan
Form<span style="color:black;display:
none;text-decoration:none">..
</span><span style="color:black;display:none;text-decoration:none">93</span>](#_Toc527389348)

[Table 25: ScreenMan—Command Line Options and Shortcut Keystrokes in a
ScreenMan  
Form<span style="color:black;display:none;text-decoration:none">..
</span><span style="color:black;display:none;text-decoration:none">94</span>](#_Toc527389349)

[Table 26: ScreenMan—Keystrokes to Move the Cursor in a ScreenMan
Form<span style="color:black;display:none;text-decoration:
none">..
</span><span style="color:black;display:none;text-decoration:none">95</span>](#_Toc527389350)

[Table 27: ScreenMan—Keystrokes to Delete Characters in a ScreenMan
Form<span style="color:black;display:none;
text-decoration:none">..
</span><span style="color:black;display:none;text-decoration:none">95</span>](#_Toc527389351)

[Table 28: ScreenMan—Keystrokes to Switch Modes in a ScreenMan
Form<span style="color:black;display:none;
text-decoration:none">..
</span><span style="color:black;display:none;text-decoration:none">96</span>](#_Toc527389352)

[Table 29: ScreenMan—Keystrokes to Navigate Repeating Blocks in a
ScreenMan Form<span style="color:black;
display:none;text-decoration:none">..
</span><span style="color:black;display:none;text-decoration:none">101</span>](#_Toc527389353)

[Table 30: Screen Editor—Keystrokes to Navigate in the Screen
Editor<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">106</span>](#_Toc527389354)

[Table 31: Screen Editor—Keystrokes to Exit and Save Text in the Screen
Editor<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">107</span>](#_Toc527389355)

[Table 32: Screen Editor—Keystrokes to Find Text in the Screen
Editor<span style="color:black;display:none;text-decoration:
none">
</span><span style="color:black;display:none;text-decoration:none">107</span>](#_Toc527389356)

[Table 33: Screen Editor—Keystrokes to Format Paragraphs in the Screen
Editor<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">108</span>](#_Toc527389357)

[Table 34: Screen Editor—Keystrokes to Cut and Paste Text in the Screen
Editor<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">108</span>](#_Toc527389358)

[Table 35: Screen Editor—Keystrokes to Delete Text in the Screen
Editor<span style="color:black;display:none;
text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">109</span>](#_Toc527389359)

[Table 36: Screen Editor—Keystrokes to Change the Settings and Mode in
the Screen Editor<span style="color:black;
display:none;text-decoration:none">
</span><span style="color:black;display:none;text-decoration:none">110</span>](#_Toc527389360)

[Table 37: Line Editor—”Replace” Prompt
Shortcuts<span style="color:black;display:none;text-decoration:none">.
</span><span style="color:black;display:none;text-decoration:none">116</span>](#_Toc527389361)

 

 

</div>

<span style="font-size:12.0pt;font-family:&quot;Times New Roman&quot;,serif;color:black">  
</span>

<div class="WordSection3">

<span id="_Toc445622720"></span><span id="_Toc446123504"></span><span id="Orientation"></span><span id="_Toc527389040"></span><span id="_Hlt446130591"></span>Orientation

<span id="_Hlt451239317"></span><span id="what_is_va_fileman">What is VA
FileMan?</span>

VA FileMan is the database management system for the Veterans Health
Information Systems and Technology Architecture user (VistA)
environment. VA FileMan creates and maintains a database management
system that includes features such as:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>A report writer

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>A data dictionary manager

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Scrolling and screen-oriented data entry

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Text editors

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Programming utilities

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Tools for sending data to other systems

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>File archiving

VA FileMan can be used as a:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Standalone database

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Set of interactive or “silent” routines

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Set of application utilities

In all modes, it is used to define, enter, and retrieve information from
a set of computer-stored files, each of which is described by a data
dictionary.

VA FileMan is a public domain software package that is developed and
maintained by the Department of Veterans Affairs (VA). It is widely used
by VA medical centers and in clinical, administrative, and business
settings in this country and abroad.

<img src="user-manual.fld/image003.png" width="37" height="37"
alt="Caution" />   CAUTION: Programmer access in VistA is defined as
DUZ(0)=“@”. It grants the privilege to become a developer in VistA.
Programmer access allows you to work outside many of the security
controls enforced by VA FileMan, enables access to all VA FileMan files,
access to modify data dictionaries, etc. It is important to proceed with
caution when having access to the system in this way.

<span id="how_to_use_this_manual">How to Use this Manual</span>

The VA FileMan User Manual is comprised of two separate documents that
describe the VA FileMan functionality of VistA’s database management
system:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>The *VA FileMan User Manual* (this manual) introduces
basic VA FileMan concepts, and shows you how to use VA FileMan’s basic
tools for displaying and editing data. It shows you how to use VA
FileMan features that are used throughout most VistA applications and
used by *all* VistA users.

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>The *VA FileMan Advanced User Manual* shows how to use the
features of VA FileMan that are likely to be used by experienced VistA
users. It introduces advanced VA FileMan concepts, and shows you how to
use VA FileMan’s advanced tools. It describes features that are more
likely to be used by:

<span style="font-family:
&quot;Courier New&quot;">o<span style="font:7.0pt &quot;Times New Roman&quot;">  
</span></span>Automated Data Processing Application Coordinators
(ADPACs)

<span style="font-family:&quot;Courier New&quot;">o<span style="font:7.0pt &quot;Times New Roman&quot;">  
</span></span>System Administrators

<span style="font-family:&quot;Courier New&quot;">o<span style="font:7.0pt &quot;Times New Roman&quot;">  
</span></span>Other technical users

<img src="user-manual.fld/image004.png" id="Picture 4" width="23"
height="23" alt="Note" />    **NOTE:** These documents are available in
Microsoft Word (.docx), Adobe Acrobat Portable Document Format (PDF),
and Hypertext Markup Language (HTML) format (see the “[HTML
Manuals](#html_manuals)” section).

In this manual, the following major features of VA FileMan are
introduced along with a description on how to use them:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Inquire</span></u>

<span style="font-family:Symbol;color:black">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Print</span></u>

<span style="font-family:Symbol;color:black">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Search</span></u>

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Browser</span></u>

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">VA FileMan Prompts</span></u>

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Field Types</span></u>

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Adding and Deleting
Records</span></u>

<span style="font-family:Symbol;color:black">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">ScreenMan</span></u>

<span style="font-family:Symbol;color:black">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Word-Processing
Fields</span></u>

<span style="font-family:Symbol;color:black">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Screen Editor</span></u>

<span style="font-family:Symbol;color:black">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Line Editor</span></u>

<img src="user-manual.fld/image002.png" id="Picture 6" data-border="0"
width="22" height="22" alt="Note" />     **REF:** For VA FileMan
installation instructions in the VistA environment see the *VA FileMan
Installation Guide* and any national patch description of the patch
being released.

<span id="html_manuals">HTML Manuals</span>

Why produce an HTML (Hypertext Markup Language) edition of the VA
FileMan manuals?

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>The HTML versions of the VA FileMan manuals are useful as
online documentation support as you use VA FileMan. HTML manuals allow
you to instantly jump (link) to specific sections, other documents, or
references online.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>The VA FileMan HTML manuals are “living” documents that
are continuously updated with the most current VA FileMan information
(unlike paper or printed documentation). They are updated based on new
versions, patches, or enhancements to VA FileMan.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Presenting manuals in an HTML format online also gives new
opportunities, such as accessing embedded multimedia training material
(e.g., movies, audio recordings, etc.) directly in the manuals.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Manuals are accessible over the VA Intranet network.

<span id="intended_audience">Intended Audience</span>

The intended audience of this manual is all key stakeholders. The
stakeholders include the following:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>General users of the VA FileMan database.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Automated Data Processing Application Coordinators
(ADPACs)

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>System Administrators—Personnel at Department of Veterans
Affairs (VA) sites who are responsible for computer management and
system security on the VistA M Servers.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Enterprise Program Management Office (EPMO)—VistA legacy
development teams.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Product Support (PS).

Disclaimers

<span id="software_disclaimer">Software Disclaimer</span>

This software was developed at the Department of Veterans Affairs (VA)
by employees of the Federal Government in the course of their official
duties. Pursuant to title 17 Section 105 of the United States Code this
software is *not* subject to copyright protection and is in the public
domain. VA assumes no responsibility whatsoever for its use by other
parties, and makes no guarantees, expressed or implied, about its
quality, reliability, or any other characteristic. We would appreciate
acknowledgement if the software is used. This software can be
redistributed and/or modified freely provided that any derivative works
bear some notice that they are derived from it, and any modified
versions bear some notice that they have been modified.

<img src="user-manual.fld/image003.png" data-border="0" width="32"
height="32" alt="Caution" />    CAUTION: To protect the security of
VistA systems, distribution of this software for use on any other
computer system by VistA sites is prohibited. All requests for copies of
Kernel for *non*-VistA use should be referred to the VistA site’s local
Office of Information Field Office (OIFO).

<span id="documentation_disclaimer">Documentation Disclaimer</span>

This manual provides an overall explanation of VA FileMan and the
functionality contained in VA FileMan 22.2; however, no attempt is made
to explain how the overall VistA programming system is integrated and
maintained. Such methods and procedures are documented elsewhere. We
suggest you look at the various VA Internet and Intranet Websites for a
general orientation to VistA. For example, visit the Office of
Information and Technology (OIT) VistA Development Intranet website.

<img src="user-manual.fld/image005.png" id="Picture 39" data-border="0"
width="33" height="33" alt="Title: Caution - Description: Caution" />   
DISCLAIMER: The appearance of any external hyperlink references in this
manual does *not* constitute endorsement by the Department of Veterans
Affairs (VA) of this Website or the information, products, or services
contained therein. The VA does *not* exercise any editorial control over
the information you find at these locations. Such links are provided and
are consistent with the stated purpose of this VA Intranet Service.

<span id="documentation_conventions">Documentation Conventions</span>

This manual uses several methods to highlight different aspects of the
material:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Various symbols are used throughout the documentation to
alert the reader to special information.
<u><span style="color:blue">Table 1</span></u> gives a description of
each of these symbols:

<span id="_Toc527389325"></span><span id="_Ref386466666">Table</span> 1:
Documentation Symbol Descriptions

| <span id="COL001_TBL002"></span>Symbol                                                                                         | Description                                                                                                           |
|--------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| <img src="user-manual.fld/image002.png" id="Picture 8" data-border="0"                                                         
 width="22" height="22" alt="Note" />                                                                                            | **NOTE / REF:** Used to inform the reader of general information including references to additional reading material. |
| <img src="user-manual.fld/image003.png" id="Picture 9" data-border="0"                                                         
 width="33" height="33" alt="Caution" />                                                                                         | **CAUTION / RECOMMENDATION / DISCLAIMER:** Used to caution the reader to take special notice of critical information. |
| <span style="font-family:&quot;Times New Roman&quot;,serif"><img src="user-manual.fld/image006.png" data-border="0" width="12" 
 height="41" alt="Tip" /></span>                                                                                                 | **TIP:** Used to inform the reader of helpful tips or tricks they can use when working with VA FileMan.               |

 

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Descriptive text is presented in a proportional font (as
represented by this font).

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Conventions for displaying TEST data in this document are
as follows:

<span style="font-family:&quot;Courier New&quot;">o<span style="font:7.0pt &quot;Times New Roman&quot;">  
</span></span>The first three digits (prefix) of any Social Security
Numbers (SSN) begin with either “**000**” or “**666**”.

<span style="font-family:&quot;Courier New&quot;">o<span style="font:7.0pt &quot;Times New Roman&quot;">  
</span></span>Patient and user names are formatted as follows:
\<*Application Name/Abbreviation/Namespace*\>PATIENT,\[*N*\] and
\<*Application Name/Abbreviation/Namespace*\>USER,\[*N*\] respectively,
where “\<*Application Name/Abbreviation/Namespace*\>” is defined in the
Approved Application Abbreviations document and “*N*” represents the
first name as a number spelled out and incremented with each new entry.
For example, in VA FileMan (FM) test patient and user names would be
documented as follows: FMPATIENT,ONE; FMPATIENT,TWO; FMPATIENT,THREE;
FMUSER,14, etc.

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>“Snapshots” of computer online displays (i.e., screen
captures/dialogues) and computer source code, if any, are shown in a
*non*-proportional font and usually enclosed within a box:

<span style="font-family:
&quot;Courier New&quot;">o<span style="font:7.0pt &quot;Times New Roman&quot;">  
</span></span>User’s responses to online prompts are **bold** typeface
and highlighted in yellow
(e.g., **<span style="background:yellow">\<Enter\></span>**).

<span style="font-family:&quot;Courier New&quot;">o<span style="font:7.0pt &quot;Times New Roman&quot;">  
</span></span>Emphasis within a dialogue box is **bold** typeface and
highlighted in blue (e.g.,<span style="background:aqua"> STANDARD
LISTENER: RUNNING</span>).

<span style="font-family:&quot;Courier New&quot;">o<span style="font:7.0pt &quot;Times New Roman&quot;">  
</span></span>Some software code reserved/key words are **bold**
typeface with alternate color font.

<span style="font-family:&quot;Courier New&quot;">o<span style="font:7.0pt &quot;Times New Roman&quot;">  
</span></span>References to “**\<Enter\>**” within these snapshots
indicate that the user should press the **Enter** key on the keyboard.
Other special keys are represented within **\< \>** angle brackets. For
example, pressing the **PF1** key can be represented as pressing
**\<PF1\>**.

<span style="font-family:
&quot;Courier New&quot;">o<span style="font:7.0pt &quot;Times New Roman&quot;">  
</span></span>Author’s comments are displayed in italics or as “callout”
boxes.

<img src="user-manual.fld/image002.png" id="Picture 11" data-border="0"
width="22" height="22" alt="Note" />     **NOTE:** Callout boxes refer
to labels or descriptions usually enclosed within a box, which point to
specific areas of a displayed image.

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>All uppercase is reserved for the representation of M
code, variable names, or the formal name of options, field/file names,
and security keys (e.g., DIEXTRACT).

<img src="user-manual.fld/image002.png" id="Picture 12" data-border="0"
width="22" height="22" alt="Note" />     **NOTE:** Other software code
(e.g., Delphi/Pascal and Java) variable names and file/folder names can
be written in lower or mixed case (e.g., CamelCase).

<span id="navigation"></span><span id="_Toc321921658">Documentation
Navigation</span>

This document uses Microsoft<sup>®</sup> Word’s built-in navigation for
internal hyperlinks. To add **Back** and **Forward** navigation buttons
to your toolbar, do the following:

1.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Right-click anywhere on the customizable Toolbar in Word (*not*
the Ribbon section).

2.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Select **Customize Quick Access Toolbar** from the secondary
menu.

3.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Select the drop-down arrow in the “Choose commands from:” box.

4.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Select **All Commands** from the displayed list.

5.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Scroll through the command list in the left column until you see
the **Back** command (green circle with arrow pointing left).

6.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Select/Highlight the **Back** command and select **Add** to add
it to your customized toolbar.

7.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Scroll through the command list in the left column until you see
the **Forward** command (green circle with arrow pointing right).

8.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Select/Highlight the Forward command and select **Add** to add it
to your customized toolbar.

9.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Select **OK**.

You can now use these **Back** and **Forward** command buttons in your
Toolbar to navigate back and forth in your Word document when selecting
hyperlinks within the document.

<img src="user-manual.fld/image002.png" id="Picture 13" data-border="0"
width="22" height="22" alt="Note" />     **NOTE:** This is a one-time
setup and is automatically available in any other Word document once you
install it on the Toolbar.

<span id="_Toc397138030"></span><span id="_Toc485620882"></span><span id="_Toc4315558"></span><span id="_Toc8096545"></span><span id="_Toc15257683"></span><span id="_Toc18284795"></span><span id="Obtain_Technical_Information_Online">How
to Obtain Technical Information Online</span>

Exported VistA M Server-based software file, routine, and global
documentation can be generated through the use of Kernel, MailMan, and
VA FileMan utilities.

<img src="user-manual.fld/image002.png" id="Picture 14" data-border="0"
width="22" height="22" alt="Note" />     **NOTE:** Methods of obtaining
specific technical information online is indicated where applicable
under the appropriate section.  
  
**REF:** For further information, see the *VA FileMan Technical Manual*.

<span id="Help_at_Prompts">Help at Prompts</span>

VistA M Server-based software provides online help and commonly used
system default prompts. Users are encouraged to enter question marks at
any response prompt. At the end of the help display, you are immediately
returned to the point from which you started. This is an easy way to
learn about any aspect of the software.

<span id="Obtaining_Data_Dictionary_Listings">Obtaining Data Dictionary
Listings</span>

Technical information about VistA M Server-based files and the fields in
files is stored in data dictionaries (DD). You can use the **List File
Attributes** \[DILIST\] option on the **Data Dictionary Utilities** \[DI
DDU\] menu in VA FileMan to print formatted data dictionaries.

<img src="user-manual.fld/image002.png" id="Picture 16" data-border="0"
width="22" height="22" alt="Note" />     **REF:** For details about
obtaining data dictionaries and about the formats available, see the
“List File Attributes” section in the “File Management” section in the
*VA FileMan Advanced User Manual*.

<span id="Assumptions_about_the_Reader">Assumptions</span>

This manual is written with the assumption that the reader is familiar
with the following:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>VistA computing environment:

<span style="font-family:
&quot;Courier New&quot;">o<span style="font:7.0pt &quot;Times New Roman&quot;">  
</span></span>Kernel—VistA M Server software

<span style="font-family:
&quot;Courier New&quot;">o<span style="font:7.0pt &quot;Times New Roman&quot;">  
</span></span>VA FileMan data structures and terminology—VistA M Server
software

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Microsoft<sup>®</sup> Windows environment

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>M programming language

<span id="_Toc4315560"></span><span id="_Toc8096547"></span><span id="_Toc15257685"></span><span id="_Toc18284796"></span><span id="Reference_Materials"></span><span id="_Toc485620884">Reference</span>
Materials

Readers who wish to learn more about VA FileMan should consult the
following:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>*VA FileMan Release Notes*

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>*VA FileMan Installation Guide*

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>*VA FileMan Technical Manual*

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>*VA FileMan User Manual* (this manual; PDF and HTML
format)

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>*VA FileMan Advanced User Manual* (PDF and HTML format)

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>*VA FileMan Developer’s Guide* (PDF and HTML format)

<img src="user-manual.fld/image002.png" id="Picture 17" data-border="0"
width="22" height="22" alt="Note" />     **REF:** Zip files of the VA
FileMan documentation in HTML format are located on the VA FileMan
Intranet product website and VDL at:
<http://www.va.gov/vdl/application.asp?appid=5>.  
  
Using a web browser, open the **HTML** documents “table of contents”
page (i.e., index.html). The *VA FileMan User Manual*, *VA FileMan
Advanced User Manual*, and *VA FileMan Developer’s Guide* are all linked
together.

VistA documentation is made available online in Microsoft<sup>®</sup>
Word format and in Adobe<sup>®</sup> Acrobat Portable Document Format
(PDF). The PDF documents *must* be read using the Adobe<sup>®</sup>
Acrobat Reader, which is freely distributed by Adobe<sup>®</sup> Systems
Incorporated at: <http://www.adobe.com/>

VistA software documentation can be downloaded from the VA Software
Document Library (VDL) at: <http://www.va.gov/vdl/>

<img src="user-manual.fld/image002.png" id="Picture 18" data-border="0"
width="22" height="22" alt="Note" />     **REF:** VA FileMan manuals are
located on the VDL at: <http://www.va.gov/vdl/application.asp?appid=5>

VistA documentation and software can also be downloaded from the Product
Support (PS) Anonymous Directories.

 

</div>

<span style="font-size:12.0pt;font-family:&quot;Times New Roman&quot;,serif;color:black">  
</span>

<div class="WordSection4">

# <span id="_Toc446204351"></span><span id="_Ref387304718"></span><span id="_Toc527389041">1<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Introduction</span>

## <span id="_Toc446204353"></span><span id="_Toc446217124"></span><span id="_Toc527389042">1.1<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Fields, Records, and Files</span>

A computer database, such as VA FileMan, organizes your data, storing it
in fields, records, and files, much as you might arrange and preserve
information on paper.

A *record* is a group of fields of data. Each record has a name (e.g., a
patient name for a patient record). You can use the record name to
recall the record for editing or for printing out. Records are also
known as file *entries*.

For example, a record for a patient might have various fields
(e.g., NAME, AGE, ADMISSION DATE, etc.) for a single patient. Each
record for a patient would contain the same set of fields (places to
fill in information):

<span id="_Toc527389205">Figure</span> 1: Example Showing Several
Patient Records

<img src="user-manual.fld/image007.png" id="Picture 19" data-border="0"
width="421" height="252"
alt="Title: Example Showing Several Patient Records - Description: Example showing several patient records. Image shows: Box: Individual fields within a record --&gt; pointint to multiple (3) boxes representing patient records." />

 

Each *field* in a record functions just like a blank on a form. When you
are editing a record on a terminal, for each field, you get a prompt
that tells you what type of data to enter.

VA FileMan uses **16** basic [field types](#field_types). These fields
allow you to enter only certain kinds of information, just as a blank on
a form might require you to enter only numbers. For example:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>A DATE OF BIRTH field could be set up to record
dates/times.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>A SOCIAL SECURITY NUMBER field could be set up to record a
**nine**-digit number.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>An ADDRESS field could be set up to hold the text of an
address.

These three fields are different from one another because of the type of
data they store.

All of the records that contain like data are collected and stored in
the same *file*. For example, all patient records are stored in the
PATIENT (#2) file and all computer user records are stored in the NEW
PERSON (#200) file. This way, to look up a patient, you know that the
file to go to is the PATIENT (#2) file. Also, to do a report on all
patients, you would generate the report from the PATIENT (#2) file.

## <span id="Database"></span><span id="_Toc446204354"></span><span id="_Toc446217125"></span><span id="_Toc527389043">1.2<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Files and the Database</span>

The *database* contains all the data files on your computer system:

<span id="_Toc527389206">Figure</span> 2: Representation of a Database

<img src="user-manual.fld/image008.png" id="Picture 20" data-border="0"
width="447" height="429"
alt="Title: Representation of a Database - Description: Representation of a database. Circle with &quot;Database&quot; at the top. within the circle are several boxes representing files: Patinet File, Prescription File, Blood Bank File, Order File, Scheduling File, Provider File, Hospital Locations File, Employee File" />

 

<img src="user-manual.fld/image002.png" id="Picture 21" data-border="0"
width="22" height="22" alt="Note" />     **NOTE:** There are many more
files than this in VistA databases!

## <span id="Printing"></span><span id="_Toc446204355"></span><span id="_Toc446217126"></span><span id="_Toc527389044">1.3<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Printing Records from Files</span>

One way of getting at the information stored in a database is to
generate reports that print out selected records. You do *not* have to
print *every* field in a record; you can just choose a subset of fields
to print out. Nor do you have to print *every* record in a file; there
are ways to limit and select what records to print out.

The report in <u><span style="color:blue">Figure
3</span><span style="color:blue"> </span></u>displays four records, with
one line of output per record, from the HOSPITAL LOCATION (#44) file:

<span id="_Toc527389207"></span><span id="_Ref389660359">Figure</span>
3: Example of a Printed Report

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

  Internal Entry

  Number         Name        Title

  -------------  ----------  -------------------

  1              ICU         Intensive Care Unit

  2              CCU         Critical Care Unit

  5              OR          Operating Room

  25             1EAST       Ward on 1 East

</div>

 

Most applications that use VA FileMan provide a number of already-set-up
reports you can quickly choose and print out. In addition, there are
options in VA FileMan that allow you to generate your own reports.

This manual contains the following sections on print records from the
database:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Inquire</span></u>

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Print</span></u>

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Search</span></u>

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Browser</span></u>

## <span id="Adding"></span><span id="_Toc446204356"></span><span id="_Toc446217127"></span><span id="_Toc527389045">1.4<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Adding and Editing Records</span>

As well as printing records from the database, you can *add* new records
and *edit* existing records. When you work on the computer system with
VistA applications (e.g., Laboratory) most of what you are doing is
adding new records and editing existing ones. For example, each new lab
result would get stored in a new record; when you make a status change
it would be an edit to a field or fields in a patient’s existing record.

Since the bulk of the work you do on the computer system involves
working with records, the more you know about using the underlying
database system (VA FileMan), the easier it is to do all of your work on
the computer system.

This manual contains the following sections on how to edit information
in records:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">VA FileMan Prompts</span></u>

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Field Types</span></u>

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Adding and Deleting
Records</span></u>

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">ScreenMan</span></u> (editing
via forms)

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Word-Processing
Fields</span></u>

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Screen Editor</span></u>
(WORD-PROCESSING fields)

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Line Editor</span></u>
(WORD-PROCESSING fields)

## <span id="_Toc446204357"></span><span id="_Toc446217128"></span><span id="_Toc527389046"></span><span id="Laygo">1.5<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>LAYGO</span> File Access

In VistA applications, you *not* only display and edit existing records,
but also add and delete records from files. For example, you might need
to add a new patient to the PATIENT (#2) file. The access to add and
delete records can be controlled; however, each VA FileMan file can be
set to either allow or *not* allow adding and deleting of new records.

If a file allows records to be added or deleted, it is said to have
**Learn-As-You-Go** (**LAYGO**) access. To add or delete records, your
user account *must* also be set to allow **LAYGO** access to the file in
question. For example, there are certain conditions when you need to
specify a particular physician. At that point, you can enter a new
physician name, rather than choosing one that already is on file. If you
are allowed to add new entries to the file (i.e., you have **LAYGO**
access), the new entry is added to a file of physicians.

## <span id="Modes"></span><span id="_Toc446204358"></span><span id="_Toc446217129"></span><span id="_Toc527389047">1.6<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Scrolling Mode vs. Screen Mode</span>

Many VA VistA application packages have a *Scrolling Mode* interface.
Scrolling Mode works as follows:

1.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Computer puts a prompt on the screen.

2.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>Users
enter a response to the prompt.

3.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Computer places another prompt on the screen, scrolling down one
line. Previous prompts move up and eventually off of the screen.

In Scrolling Mode, prompting occurs in the same predetermined order, in
a sequence designed by the developer of the application. The user
enters, and the computer stores, the responses one at a time. Unless the
user is familiar with a few timesaving Scrolling Mode techniques, the
user has to step through each prompt in a record before he/she can
finish editing the record.

<img src="user-manual.fld/image002.png" id="Picture 22" data-border="0"
width="22" height="22" alt="Note" />     **REF:** For more information
on editing records in Scrolling Mode, see the
“<u><span style="color:blue">VA FileMan Prompts</span></u>” section.

Recently developed VistA applications, on the other hand, often use a
*Screen Mode* interface for editing data. In the Screen Mode approach,
each field occupies a fixed position on the screen. The user can see
many data fields at once and use simple key combinations to edit data
and move from field to field on a screen. The user can also move from
one screen to another like turning through the pages of a book. VA
FileMan’s screen-oriented data entry tool is called
<u><span style="color:blue">ScreenMan</span></u>.

In comparing Scrolling Mode with Screen Mode, an area in particular
where Screen Mode is much more convenient than Scrolling Mode is text
editing. VA FileMan’s Scrolling Mode text editor is the
<u><span style="color:blue">Line Editor</span></u>. A better choice for
editing text is VA FileMan’s Screen Mode editor, the
<u><span style="color:blue">Screen Editor</span></u>.

<img src="user-manual.fld/image002.png" id="Picture 23" data-border="0"
width="22" height="22" alt="Note" />     **REF:** For more information
on the Line Editor, see the “<u><span style="color:blue">Line
Editor</span></u>” section. For more information on the Screen Editor,
see the “<u><span style="color:blue">Screen Editor</span></u>” section.

 

# <span id="_Ref446306799"></span><span id="_Ref446309865"></span><span id="_Ref446310561"></span><span id="_Toc527389048">2<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Inquire</span><span id="_Hlt446232432"></span>

## <span id="_Toc527389049">2.1<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Overview</span>

Many reports that you print from applications are pre-designed
(i.e., the selection of records) and the fields that print for each
record are pre-determined by the application developer. You simply
choose the report you would like to print from a menu option, choose an
output device, and the selected report prints.

You can also create your own reports, however, if you have either VA
FileMan’s print options, or custom-designed application options that
take advantage of the same VA FileMan features. This section introduces
one of VA FileMan’s print options, **Inquire to File
Entries** \[<span style="color:windowtext">DIINQUIRE</span>\] option.

There are two ways you have an opportunity to use VA FileMan’s inquiry
capabilities:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>An option that has been set up already to allow you to
inquire to entries from a particular file.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>VA FileMan’s **Inquire to File
Entries** \[<span style="color:windowtext">DIINQUIRE</span>\] option,
which lets you inquire to any file to which you have access.

In either case, use of VA FileMan’s inquire feature is very similar. In
most cases, the only difference is that with the **Inquire to File
Entries** \[<span style="color:windowtext">DIINQUIRE</span>\] option,
you have to choose which file to inquire.

## <span id="_Toc527389050">2.2<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Inquire to File Entries Option</span>

The quickest way to display the data for one file entry or for a small
number of entries is to use the **Inquire to File
Entries** \[<span style="color:windowtext">DIINQUIRE</span>\] option.
This option lets you choose a set of entries to display, and choose the
fields that you want to see for each entry. For example:

<span id="_Toc527389208">Figure</span> 4: Inquire—Dialogue Using the
Inquire to File Entries Option: Sample User Entries at Prompts and
Sample Report

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

Select VA FileMan Option: **<span style="background:yellow">INQ
\<Enter\></span>** uire to File Entries

 

<img src="user-manual.fld/image009.png" data-border="0" width="190"
height="25"
alt="1. Choose the file. - Title: 1. Choose the file. - Description: 1. Choose the file." />

OUTPUT FROM WHAT FILE: PATIENT//
**<span style="background:yellow">\<Enter\></span>**

<img src="user-manual.fld/image010.png" data-border="0" width="221"
height="35"
alt="2. Choose entries to display from the file. - Title: 2. Choose entries to display from the file. - Description: 2. Choose entries to display from the file." />

Select PATIENT NAME: **<span style="background:yellow">FMPATIENT,
ONE</span>**

ANOTHER ONE: **<span style="background:yellow">FMPATIENT, TWO</span>**

ANOTHER ONE: **<span style="background:yellow">FMPATIENT, THREE</span>**

ANOTHER ONE: **<span style="background:yellow">\<Enter\></span>**

 

<img src="user-manual.fld/image011.png" data-border="0" width="288"
height="72"
alt="3. Choose output fields. Captioned Output is the easiest (displays all fields that contain data for each entry). - Title: 3. Choose output fields. Captioned Output is the easiest (displays all fields that contain data for each entry). - Description: 3. Choose output fields. Captioned Output is the easiest (displays all fields that contain data for each entry)." />

STANDARD CAPTIONED OUTPUT? Yes//
**<span style="background:yellow">\<Enter\></span>** (Yes)

Include COMPUTED fields:  (N/Y/R/B): NO//
**<span style="background:yellow">?</span>**

<img src="user-manual.fld/image012.png" data-border="0" width="321"
height="58"
alt="4. For Captioned Output, choose whether to display record numbers and computed fields. - Title: 4. For Captioned Output, choose whether to display record numbers and computed fields. - Description: 4. For Captioned Output, choose whether to display record numbers and computed fields." />

Enter a code from the list.

     Select one of the following:

 

          N         NO - No record number (IEN), no Computed Fields

          Y         Computed Fields

          R         Record Number (IEN)

          B         BOTH Computed Fields and Record Number (IEN)

 

 

Include COMPUTED fields:  (N/Y/R/B): NO//
**<span style="background:yellow">B \<Enter\></span>** OTH Computed
Fields and Record Number (IEN)

DISPLAY AUDIT TRAIL? No//
**<span style="background:yellow">\<Enter\></span>** NO

 

 

 

 

 

 

<img src="user-manual.fld/image013.png" data-border="0" width="253"
height="62"
alt="5. Review the selected entries that are displayed on the report (sample list abbreviated). - Title: 5. Review the selected entries that are displayed on the report (sample list abbreviated). - Description: 5. Review the selected entries that are displayed on the report (sample list abbreviated)." />

 

NUMBER: 180                             NAME: FMPATIENT, ONE

  SEX: MALE                             DATE OF BIRTH: 04/04/1944

.

.

.

NUMBER: 229                             NAME: FMPATIENT, TWO

  SEX: MALE                             DATE OF BIRTH: 01/01/1962

.

.

.

NUMBER: 229                             NAME: FMPATIENT, THREE

  SEX: FEMALE                           DATE OF BIRTH: 01/25/1952

.

.

.

</div>

 

### <span id="Captioned"></span><span id="_Toc527389051"></span><span id="_Hlt446381186"></span>2.2.1<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Standard Caption Output

Choosing Standard Captioned Output can be very useful; it prints out
*all* fields (that contain data) for each entry in the report. Use it is
a quick way to select all the fields for each entry in the report.
Otherwise, you need to select each field to print individually, from the
list of fields available to print in the file. Answering **YES** to use
STANDARD CAPTIONED OUTPUT is the fastest way to choose what fields to
print.

#### 2.2.1.1<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Computed Fields

When using Standard Captioned Output, you can choose from the following
at the “Include COMPUTED Fields: (N/Y/R/B): NO//” prompt:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**N (default)—**NO - No record number (IEN), no Computed
Fields

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**Y—**Computed Fields

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**R—**Record Number (IEN)

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**B—**BOTH Computed Fields and Record Number (IEN)

The default is to display neither. Enter two question marks (**??**) for
detailed help about responding to this prompt.

#### 2.2.1.2<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Audit Trails

If one or more of the fields have been audited, the system displays the
“DISPLAY AUDIT TRAIL?” prompt. If you answer **YES**, then you see the
changes that have been recorded for the various fields in the AUDIT
(#1.1) file, along with the current values of the fields.

## <span id="Templates"></span><span id="_Toc527389052">2.3<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>SORT Templates</span>

When you choose several entries to display, you are prompted with the
following:

<span id="_Toc527389209">Figure</span> 5: Inquire—Prompt to Store
Entries into a Template

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

STORE THESE ENTRY ID’s IN A TEMPLATE:

</div>

 

You can *save* your list of selected entries in a SORT template by
entering a template name at this prompt. Your list of entries is then
saved in a SORT template. You can then *reuse* the list of selected
entries in the template when you do additional printing from this file
in the future.

<img src="user-manual.fld/image002.png" id="Picture 29" data-border="0"
width="22" height="22" alt="Note" />     **REF:** For more information
on using SORT templates, see the “<u><span style="color:blue">Saving
Sort Criteria (SORT Templates)</span></u>” section.

## <span id="Print_fields"></span><span id="_Toc527389053"></span><span id="_Hlt446147681"></span>2.4<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Choose Your Own Print Fields

<img src="user-manual.fld/image003.png" data-border="0" width="32"
height="32" alt="Caution" />    CAUTION: Do *not* use STANDARD CAPTIONED
OUTPUT.

To choose your own fields to output for each entry, answer **NO** to the
“STANDARD CAPTIONED OUTPUT?” prompt. You can then choose your own output
fields. For example, if you only need NAME, DATE OF BIRTH, and PROVIDER
information about a selected patient, you could request it, as shown in
<u><span style="color:blue">Figure 6</span></u>:

<span id="_Toc527389210"></span><span id="_Ref345588305">Figure</span>
6: Inquire—Dialogue for Choosing Your Own Print Fields: Sample User
Entries at Prompts

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

Select VA FileMan Option: **<span style="background:yellow">INQ
\<Enter\></span>** uire to File Entries

 

OUTPUT FROM WHAT FILE: PATIENT//
**<span style="background:yellow">\<Enter\></span>**

Select PATIENT NAME: **<span style="background:yellow">FMPATIENT,
ONE</span>**

ANOTHER ONE: **<span style="background:yellow">\<Enter\></span>**

<img src="user-manual.fld/image014.png" data-border="0" width="172"
height="37"
alt="1. Answer NO here. - Title: 1. Answer NO here. - Description: 1. Answer NO here." />

STANDARD CAPTIONED OUTPUT? Yes// **<span style="background:yellow">NO
\<Enter\></span>** (No)

<img src="user-manual.fld/image015.png" data-border="0" width="140"
height="46"
alt="2. Choose output fields. - Title: 2. Choose output fields. - Description: 2. Choose output fields." />

FIRST PRINT FIELD: **<span style="background:yellow">NAME</span>**

     1   NAME

     2   NAME COMPONENTS

     3   NAME ORDER

CHOOSE 1-3: **<span style="background:yellow">1 \<Enter\></span>** NAME

THEN PRINT FIELD: **<span style="background:yellow">DATE OF
BIRTH</span>**

THEN PRINT FIELD: **<span style="background:yellow">PROVIDER</span>**

THEN PRINT FIELD: **<span style="background:yellow">\<Enter\></span>**

Heading (S/C): PATIENT LIST//
**<span style="background:yellow">\<Enter\></span>**

<img src="user-manual.fld/image016.png" data-border="0" width="163"
height="35"
alt="3. Choose an output device. - Title: 3. Choose an output device. - Description: 3. Choose an output device." />

DEVICE: **<span style="background:yellow">\<Enter\></span>** SSH VIRTUAL
TERMINAL Right Margin: 80//
**<span style="background:yellow">\<Enter\></span>**

 

PATIENT LIST                                   FEB 12,2013  18:41   
PAGE 1

NAME                            DATE OF BIRTH

  PROVIDER

--------------------------------------------------------------------------------

 

FMPATIENT,ONE                   11/20/1950

</div>

 

<img src="user-manual.fld/image002.png" id="Picture 34" data-border="0"
width="22" height="22" alt="Note" />     **REF:** For more information
on customizing output print fields, see the
“<u><span style="color:blue">Print</span></u>” section. It provides
detailed information about the different choices you can make at the
“PRINT FIELD:” prompt to display your information in different ways.

## <span id="Device"></span><span id="_Toc527389054">2.5<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Choose Your Own Device</span>

<img src="user-manual.fld/image003.png" data-border="0" width="32"
height="32" alt="Caution" />    CAUTION: Do *not*
u<span id="_Hlt446292327"></span>se STANDARD CAPTIONED OUTPUT.

If you enter **YES** at the “STANDARD CAPTIONED OUTPUT?” prompt, output
is sent to the **HOME** device, which ordinarily is the terminal you are
using. To send output to a printer, you need to answer **NO** at the
“STANDARD CAPTIONED OUTPUT?” prompt. This means you *must* choose
y<span id="_Hlt457018626">o</span>ur ow<span id="_Hlt446147679">n</span>
print fields, as described in Section
<u><span style="color:blue">2.4</span></u>,
“<u><span style="color:blue">Choose Your Own Print Fields</span></u>.”
Doing this allows you to select the output device, however.

If you answer **NO** to the “STANDARD CAPTIONED OUTPUT?” prompt, you can
still get CAPTIONED output, however. To do this, choose the CAPTIONED
PRINT template at the first “PRINT FIELD:” prompt, as shown in
<u><span style="color:blue">Figure 7</span></u>.

Enter a left bracket “**\[**” and the word **CAPTIONED**. CAPTIONED
OUTPUT from the template works exactly as if you had answered **YES** at
the “STANDARD CAPTIONED OUTPUT?” prompt to request CAPTIONED OUTPUT.

<span id="_Toc527389211"></span><span id="_Ref345588311">Figure</span>
7: Inquire—Dialogue for Choosing a Device *and* Getting STANDARD
CAPTIONED OUTPUT: Sample User Entries at Prompts

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

STANDARD CAPTIONED OUTPUT? Yes// **<span style="background:yellow">N
\<Enter\></span>** (No)

FIRST PRINT FIELD:
**<span style="background:yellow">\[CAPTIONED</span>**

<img src="user-manual.fld/image017.png" data-border="0" width="363"
height="54"
alt="Even though you do not choose “Standard Caption Output,” you can still use the CAPTIONED Print Template for the same effect. - Title: Even though you do not choose “Standard Caption Output,” you can still use the CAPTIONED Print Template for the same effect. - Description: Even though you do not choose “Standard Caption Output,” you can still use the CAPTIONED Print Template for the same effect." />

 

Include COMPUTED fields:  (N/Y/R/B): NO//
**<span style="background:yellow">\<Enter\></span>** - No record number
(IEN), no Computed Fields

DISPLAY AUDIT TRAIL? No//
**<span style="background:yellow">\<Enter\></span>** NO

Heading (S/C): PATIENT LIST//
**<span style="background:yellow">\<Enter\></span>**

 

<img src="user-manual.fld/image018.png" data-border="0" width="388"
height="48"
alt="By not choosing “Standard Caption Output,” you can then choose the output device. - Title: By not choosing “Standard Caption Output,” you can then choose the output device. - Description: By not choosing “Standard Caption Output,” you can then choose the output device." />

DEVICE:

</div>

 

<span style="font-size:12.0pt;font-family:&quot;Times New Roman&quot;,serif;color:black">  
</span>

<span id="_Ref446306809"></span><span id="_Ref446308851"></span><span id="_Ref446308911"></span><span id="_Ref446309126"></span><span id="_Ref446309734"></span><span id="_Ref446309874"></span><span id="_Ref446310572"></span><span id="_Hlt446217640"></span> 

# <span id="_Ref524020377"></span><span id="_Ref524020422"></span><span id="_Ref524020448"></span><span id="_Ref524021090"></span><span id="_Ref524021616"></span><span id="_Ref524022235"></span><span id="_Ref524022757"></span><span id="_Toc527389055">3<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Print</span>

## <span id="_Toc527389056"></span><span id="_Hlt446233744"></span><span id="_Hlt446232311"></span>3.1<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>How to Print Reports from Fi<span id="_Hlt446233759"></span>les

With the **Inquire to File
Entries** \[<span style="color:windowtext">DIINQUIRE</span>\] option,
you can:

1.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Select entries from a file, one by one.

2.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Choose a format for displaying the selected entries.

3.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Output the selected entries.

VA FileMan’s print capabilities, on the other hand, allow you to select
entries, *not* one by one, but instead by choosing a range of entries
based on the sorting order. You can choose all entries in a file, for
example, and sort them in alphabetical order for the printout.
Alternatively, you can choose all entries sorting between **E** and
**F** and sort them in alphabetical order for the printout.

## <span id="_Toc527389057">3.2<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>VA FileMan’s Print Capabilities</span>

There are two ways in which you have an opportunity to use VA FileMan’s
print capabilities:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>An option that has been set up already to allow you to
print from a particular file.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>VA FileMan’s **Print File Entries** \[DIPRINT\] option,
which lets you print from any file to which you have access.

In either case, use of VA FileMan’s print features is very similar. In
most cases, the only difference is that with the **Print File
Entries** \[DIPRINT\], you have to choose from which file to print.

Unlike the **Inquire to File
Entries** \[<span style="color:windowtext">DIINQUIRE</span>\] option,
which displays individual records, VA FileMan’s print can list all
records in a file. Thus, the focus of the **Inquire to File
Entries** \[<span style="color:windowtext">DIINQUIRE</span>\] option is
a single or small group of entries while VA FileMan’s prints are
concerned with the entire file.

VA FileMan’s print features allow considerable flexibility in:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Selecting entries.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Ordering (or sorting) the entries selected.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Choosing which fields to display.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Formatting the output.

The following two basic components can be used to create a report:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>“S<span id="_Hlt457018605">O</span>RT
<span id="_Hlt446147706">B</span>Y:” dialogue. Used to sort (and
sometimes narrow down) the entries that you want displayed.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>“PRINT F<span id="_Hlt446147709">I</span>ELD:” dialogue.
Used to choose the fields you want and the format of their display.

The choices you can make at these two prompts are discussed in detail
later in this section.

## <span id="standard"></span><span id="_Toc527389058">3.3<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Standard Column Format for VA FileMan Prints</span>

VA FileMan has a standard, columnar format for print output. The file
name, current date/time, and page number appear at the top of each
report page, followed by column headings that correspond to the labels
of selected fields. There are many ways to customize the format, as
shown in <u><span style="color:blue">Figure 8</span></u>:

<span id="_Toc527389212"></span><span id="_Ref446146148">Figure</span>
8: Print—Example of a Standard Printout

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    PATIENT LIST                          NOV 28, 1996     11:32   PAGE
1

    NAME                    SEX

   
---------------------------------------------------------------------

    FMPATIENT,SEVEN         MALE

    FMPATIENT,EIGHT         MALE

    FMPATIENT,NINE          MALE

    FMPATIENT,10            FEMALE

</div>

 

This simple example of a report (<u><span style="color:blue">Figure
8</span></u>) is generated by the dialogue in
<u><span style="color:blue">Figure 9</span></u>. It prints information
from all the entries in the PATIENT (#2) file, ordered by NAME (#.01)
field. Only data from the NAME and SEX fields are printed, as requested
at the “PRINT FIELD:” prompts:

<span id="_Toc527389213"></span><span id="_Ref345588318">Figure</span>
9: Print—Dialogue for Creating a Printed Report: Sample User Entries at
Prompts

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

Select VA FileMan Option: **<span style="background:yellow">PRINT
\<Enter\></span>** File Entries

 

OUTPUT FROM WHAT FILE: PATIENT//
**<span style="background:yellow">\<Enter\></span>**

<img src="user-manual.fld/image019.png" data-border="0" width="175"
height="40"
alt="Sort output by record name. - Title: Sort output by record name. - Description: Sort output by record name." />

SORT BY: NAME// **<span style="background:yellow">\<Enter\></span>**

START WITH NAME: FIRST//
**<span style="background:yellow">\<Enter\></span>**

<img src="user-manual.fld/image020.png" data-border="0" width="149"
height="40"
alt="Choose print fields. - Title: Choose print fields. - Description: Choose print fields." />

FIRST PRINT FIELD: **<span style="background:yellow">NAME</span>**

     1   NAME

     2   NAME COMPONENTS

     3   NAME ORDER

CHOOSE 1-3: **<span style="background:yellow">1 \<Enter\></span>** NAME

THEN PRINT FIELD: **<span style="background:yellow">SEX</span>**

THEN PRINT FIELD:

Heading (S/C): PATIENT LIST//
**<span style="background:yellow">\<Enter\></span>**

DEVICE:

</div>

 

<img src="user-manual.fld/image002.png" id="Picture 85" data-border="0"
width="22" height="22" alt="Note" />**     NOTE:** You would have
received information about every patient in the file, *not* just these
four. You could have asked for several more fields to be printed. They
would appear as columns of output, left to right, in the order
specified.

## <span id="specifying_sort"></span><span id="_Toc527389059"></span><span id="_Hlt446144465"></span>3.4<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Sorting

### <span id="_Toc527389060">3.4.1<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Specifying SORT BY Fields</span>

Sorting determines the *order* that records are printed in your reports.
You can accept the default order (by the **.01** field), or you can
specify your own sorting order. The sort can be a simple sort, based on
only one field, or you can sort based on the values of several fields.

For example, if you want to print the entries in order from oldest to
youngest patient, you could sort the report by date of birth (the DATE
OF BIRTH field in the PATIENT \[#2\] file), as shown in
<u><span style="color:blue">Figure 10</span></u>:

<span id="_Toc527389214"></span><span id="_Ref345588324">Figure</span>
10: Print—Dialogue for Specifying a Sort Order for a Printed Report:
Sample User Entries at Prompts

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

Select VA FileMan Option: **<span style="background:yellow">PRINT
\<Enter\></span>** File Entries

 

OUTPUT FROM WHAT FILE: PATIENT//
**<span style="background:yellow">\<Enter\></span>**

<img src="user-manual.fld/image021.png" data-border="0" width="150"
height="42"
alt="Sort by DATE OF BIRTH. - Title: Sort by DATE OF BIRTH. - Description: Sort by DATE OF BIRTH." />

SORT BY: NAME// **<span style="background:yellow">DATE OF BIRTH</span>**

START WITH DATE OF BIRTH: FIRST//
**<span style="background:yellow">\<Enter\></span>**

  WITHIN DATE OF BIRTH, SORT BY:
**<span style="background:yellow">\<Enter\></span>**

FIRST PRINT FIELD: **<span style="background:yellow">NAME</span>**

     1   NAME 

     2   NAME COMPONENTS 

     3   NAME ORDER 

CHOOSE 1-3: **<span style="background:yellow">1 \<Enter\></span>** NAME

THEN PRINT FIELD: **<span style="background:yellow">SEX</span>**

THEN PRINT FIELD: **<span style="background:yellow">\<Enter\></span>**

<img src="user-manual.fld/image022.png" data-border="0" width="251"
height="34"
alt="NOTE: DATE OF BIRTH is not a print field. - Title: NOTE: DATE OF BIRTH is not a print field. - Description: NOTE: DATE OF BIRTH is not a print field." />

Heading (S/C): PATIENT LIST//
**<span style="background:yellow">\<Enter\></span>**

DEVICE: **<span style="background:yellow">\<Enter\></span>** SSH VIRTUAL
TERMINAL Right Margin: 80//
**<span style="background:yellow">\<Enter\></span>**

</div>

 

The output then prints in the following order (by DATE OF BIRTH), as
shown in <u><span style="color:blue">Figure 11</span></u>:

<span id="_Toc527389215"></span><span id="_Ref490833751">Figure</span>
11: Print—Example of a Printed Report in a Specific Order

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

PATIENT LIST                                 FEB 12, 2013   19:11       
PAGE 1

NAME                        SEX

-------------------------------------------------------------------------------

 

         DATE OF BIRTH: OCT 14, 1877

FMPATIENT,12                FEMALE

         DATE OF BIRTH: NOV 3, 1922

FMPATIENT,13                MALE

         DATE OF BIRTH: APR 4, 1933

FMPATIENT,NINE              MALE

</div>

 

If you sort by a field that is *not* a print field, then it is displayed
as a subheader. In <u><span style="color:blue">Figure 11</span></u>, the
sort criterion (DATE OF BIRTH) is printed as a subheader with every
change in sort value.

To suppress the printing of sort values (subheaders) in the body of your
report, you can either:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Add the field you are sorting by to the print field list.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Place an <span id="_Hlt446149706">at-sign</span> (**@**)
in front of the field label at the “SORT BY:” prompt. In the previous
example (<u><span style="color:blue">Figure 11</span></u>), you would
sort by **@DATE OF BIRTH** instead of **DATE OF BIRTH**.

### <span id="order"></span><span id="_Toc527389061">3.4.2<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Sorting Order</span>

The ordering of entries within a sort is generally from low value to
high value. Some special cases for specific data type field values
include:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**SET OF CO<span id="_Hlt446136683">D</span>ES—**Field
values are sorted by the internally stored code, *not* the value that is
output.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**FREE TEXT—**Field values usually sort from lowest value
to highest value following the ASCII sorting sequence. Digits sort
before uppercase letters, which sort before lowercase letters
(e.g., **M1** sorts before **MC** which sorts before **Mc**).

#### 3.4.2.1<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Sorting Canonic Numbers and *Non*-Canonic Strings, and the ;TXT Sort Qualifier

Canonic numbers are pure numbers that do *not* have leading **zeroes**
before or trailing **zeroes** after a decimal point. Thus, **1.1** is a
canonic number but **01.1** and **1.10** are *not*. A *non*-canonic
string is everything else. For example, **“8C”** is a *non*-canonic
string.

This distinction is important when sorting, because in all VA FileMan
sorting, *canonic numbers sort first*, and everything else sorts second.
Usually, this works very well. But in a few cases where sort fields
contain a mix of canonic numbers and *non*-canonic strings, unexpected
sort orders result. Classic cases include sorting on Social Security
Numbers and on ward locations.

Consider Social Security Numbers (SSNs). The SSNs **666333333** and
**666999900** are canonic numbers. But the SSN **000769000** is *not* a
canonic number, because of its leading **zeroes**. When you use the
default sort based on SSN, you get output that looks like
<u><span style="color:blue">Figure 12</span></u>:

<span id="_Toc527389216"></span><span id="_Ref523989248">Figure</span>
12: Print—Sorting Canonic and Non-Canonic Numbers

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

PATIENT LIST                              JUL 19,1996   11:36       
PAGE 1

SSN              NAME

-------------------------------------------------------------------------------

 

666333333        FMPATIENT,13

666999900        FMPATIENT,14

000769000        FMPATIENT,15

</div>

 

In this example (<u><span style="color:blue">Figure 12</span></u>), you
see that SSN **000769000** is *non*-canonic due to its leading
**zeroes**, so it sorts *after* SSN **666999900**, which is canonic.

A similar situation occurs when you sort on ward locations. Suppose you
have wards **8**, **8C**, and **9**. Wards **8** and **9** are canonic
numbers, while ward **8C** is a *non*-canonic string. Thus, if you sort
on ward location, your output comes out in this order: **8**, **9**,
**8C**.

To avoid this problem, use the sort qualifier “**;TXT**” on your sort
field. This forces all field values to be *non*-canonic, with the result
that a group of strings like **8**, **8C**, and **9** sort in the
expected order.

<img src="user-manual.fld/image002.png" id="Picture 86" data-border="0"
width="22" height="22" alt="Note" />     **REF:** For more information
on the “**;TXT**” sort qualifier, see the list of Sort
Qu<span id="_Hlt446136963">a</span><span id="_Hlt446147784">l</span>ifiers
in <u><span style="color:blue">Table 2</span></u>.

#### <span id="select"></span><span id="_Hlt446304954"></span>3.4.2.2<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Sorting to Select Entries for Printing

Besides using sorting to determine the *order* of entries printed, you
can also use the “START WITH ...:” prompt to restrict what entries are
printed to a range. For example, if you accept the default sort range
(from first to last), you can get a report with every item in the file
listed. You can cut this list down to a subset of the entries in the
file by how you sort (e.g., entries that sort from **FMPATIENT**,A to
**FMPATIENT**,Z only).

To specify a sort range, enter the range starting point at the “START
WITH...:” prompt, and the range end point at the “GO TO...:” prompt. For
example:

<span id="_Toc527389217">Figure</span> 13: Print—Specifying a Sort Range

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    SORT BY: NAME// **<span style="background:yellow">\<Enter\></span>**

      START WITH NAME: FIRST//
**<span style="background:yellow">FMPATIENT,A</span>**

      GO TO NAME:  LAST//
**<span style="background:yellow">FMPATIENT,Z</span>**

</div>

 

#### 3.4.2.3<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Selecting All Entries with the Same Value for One Field

A simple kind of selecting can be done to choose only those entries that
have a particular value for a field. For example, to list only those
patients who have a DIAGNOSIS equal to **CANCER**, you can sort as in
the example in <u><span style="color:blue">Figure 14</span></u>:

<span id="_Toc527389218"></span><span id="_Ref472422752">Figure</span>
14: Print—Choosing Entries with a Specific Value

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    START WITH DIAGNOSIS: FIRST//
**<span style="background:yellow">CANCER</span>**

    GO TO DIAGNOSIS: LAST//
**<span style="background:yellow">CANCER</span>**

</div>

 

#### 3.4.2.4<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Other Ways of Selecting Entries

The “START WITH ... GO TO ...” dialogue can be used to do sophisticated
selecting from a file. Computed expressions can be entered at the
prompts to filter the entries to be printed.

<img src="user-manual.fld/image002.png" id="Picture 87" data-border="0"
width="22" height="22" alt="Note" />     **REF:** These powerful
techniques are discussed in the
“Co<span id="_Hlt446137129">m</span>puted Expressions” section in the
*VA FileMan Advanced User Manual*.

You can also use VA FileMan’s search functions to select entries for
printing.

<img src="user-manual.fld/image002.png" id="Picture 88" data-border="0"
width="22" height="22" alt="Note" /><span style="font-size:10.0pt">    
</span>**REF:** For more information on VA FileMan’s search functions,
see the “<u><span style="color:blue">Search</span></u>” section.

#### <span id="null">3.4.2.5<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Including Entries with NULL Fields in Your Sort (Start with @)</span>

When you sort a report on a particular field, if any record in the file
has *no value* in that field (i.e., **NULL**) that record is *skipped*
and *not printed*, if you accept the default sort start value (FIRST).
In other words, in a print from the PATIENT (#2) file, if you sort on
the PROVIDER field, start sorting from the default of FIRST, and there
are some patients with nothing in their PROVIDER field (i.e., **NULL**),
those patients are *left off of the report entirely*.

If you want to include records in your report, even if they have no
value in the field on which you are sorting (i.e., **NULL**), sort from
**@** instead of accepting the default of FIRST. As in
<u><span style="color:blue">Figure 15</span></u>, enter an
at-sign (**@**) at the “START WITH:” prompt:

<span id="_Toc527389219"></span><span id="_Ref345588331">Figure</span>
15: Print—Dialogue to Include Records with NULL Values: Sample User
Entries at Prompts

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

Select VA FileMan Option: **<span style="background:yellow">PRINT
\<Enter\></span>** File Entries

 

OUTPUT FROM WHAT FILE: PATIENT//
**<span style="background:yellow">\<Enter\></span>**

SORT BY: NAME// **<span style="background:yellow">PROVIDER</span>**

<img src="user-manual.fld/image023.png" data-border="0" width="377"
height="50"
alt="Start with an at-sign (@) instead of FIRST to force inclusion of all entries in the printout, even those whose value for this field is NULL. - Title: Start with an at-sign (@) instead of FIRST to force inclusion of all entries in the printout, even those whose value for this field is NULL. - Description: Start with an at-sign (@) instead of FIRST to force inclusion of all entries in the printout, even those whose value for this field is NULL." />

START WITH PROVIDER: FIRST//
**<span style="background:yellow">@</span>**

GO TO PROVIDER: LAST//
**<span style="background:yellow">\<Enter\></span>**

  WITHIN PROVIDER, SORT BY:
**<span style="background:yellow">\<Enter\></span>**

FIRST PRINT FIELD: **<span style="background:yellow">NAME</span>**

     1   NAME

     2   NAME COMPONENTS

     3   NAME ORDER

CHOOSE 1-3: **<span style="background:yellow">1 \<Enter\></span>** NAME

THEN PRINT FIELD: **<span style="background:yellow">DATE OF
BIRTH</span>**

THEN PRINT FIELD: **<span style="background:yellow">\<Enter\></span>**

Heading (S/C): PATIENT LIST//
**<span style="background:yellow">\<Enter\></span>**

<img src="user-manual.fld/image024.png" data-border="0" width="381"
height="51"
alt="Whenever you specify any sort criteria at the “SORT BY:” prompt, you are prompted for what page to start at. - Title: Whenever you specify any sort criteria at the “SORT BY:” prompt, you are prompted for what page to start at. - Description: Whenever you specify any sort criteria at the “SORT BY:” prompt, you are prompted for what page to start at." />

START AT PAGE: 1// **<span style="background:yellow">\<Enter\></span>**

 

<span style="font-size:10.0pt">...SORRY, THIS MAY TAKE A FEW
MOMENTS...</span>

</div>

 

The output of this sort would then include all records, even those with
no value in their PROVIDER fields:

<span id="_Toc527389220"></span><span id="_Ref345588339">Figure</span>
16: Print—Sample Report Displaying Fields with NULL Values

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

PATIENT LIST                                   FEB 13,2013  16:22   
PAGE 1

NAME                                DATE OF BIRTH

--------------------------------------------------------------------------------

 

<img src="user-manual.fld/image025.png" data-border="0" width="436"
height="67"
alt="FMPATIENT,ONE does not have a provider. If the @ had not been entered at the “START WITH PROVIDER:” prompt, the entry would not have been printed. - Title: FMPATIENT,ONE does not have a provider. If the @ had not been entered at the “START WITH PROVIDER:” prompt, the entry would not have been printed. - Description: FMPATIENT,ONE does not have a provider. If the @ had not been entered at the “START WITH PROVIDER:” prompt, the entry would not have been printed." />

 

        PROVIDER:   <span style="background:aqua">EMPTY</span>

FMPATIENT,ONE                       03/01/1940

        PROVIDER:   FMPROVIDER,2

FMPATIENT,TWO                       03/04/1933

        PROVIDER:   FMPROVIDER,2

FMPATIENT,THREE                     09/25/1949

        PROVIDER:   FMPROVIDER,2

FMPATIENT,FOUR                      01/31/1921

        PROVIDER:   FMPROVIDER,3

FMPATIENT,FIVE                      05/24/1931

        PROVIDER:   FMPROVIDER,3

FMPATIENT,SIX                       04/03/1935

        PROVIDER:   FMPROVIDER,3

FMPATIENT,SEVEN                     10/22/1925

</div>

 

#### <span id="sort_reference"></span><span id="_Hlt446136964"></span>3.4.2.6<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Sort Qualifier Reference

As well as entering fields to sort by, you can also enter formatting
controls in the “SORT BY:” dialogue. Add these qualifiers to the field
label or to the computed expression you are entering at the “SORT BY:”
prompt.

##### 3.4.2.6.1<span style="font:7.0pt &quot;Times New Roman&quot;">    </span>Sort Qualifiers to Use at “SORT BY:” Prompts

<u><span style="color:blue">Table 2</span></u> lists the sort qualifiers
you can use at the “SORT BY:” prompts:

<span id="_Toc527389326"></span><span id="_Ref446138135">Table</span> 2:
Print—Sort Qualifiers

<table class="MsoNormalTable" data-border="1" data-cellspacing="0"
data-cellpadding="0" width="668"
style="margin-left:1.15pt;border-collapse:collapse;border:none">
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th width="102"
style="width: 76.5pt; border: solid windowtext 1.0pt; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="COL001_TBL003"></span>Qualifier</p></th>
<th width="144"
style="width: 1.5in; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Action</p></th>
<th width="422"
style="width: 316.5pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Discussion</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>!</strong>field</p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Number
entries by sort value</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Entries
having the same value for the SORT BY field are numbered sequentially
starting at one.</p></td>
</tr>
<tr class="even">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>#</strong>field</p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Page
break when sort value changes</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Starts
a new page every time the value of the sorted field changes.</p></td>
</tr>
<tr class="odd">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>‘</strong>field</p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Specify
a range for output without sorting</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>This
lets you <em>select</em> entries based on this field in the “START WITH
. . . GO TO . . .” dialogue, but <em>not sort</em> based on the
field.</p>
<p><img src="user-manual.fld/image002.png" id="Picture 89"
data-border="0" width="22" height="22"
alt="Note" /> <strong>NOTE:</strong> Since sorting requires substantial
system resources, do <em>not</em> sort entries unnecessarily.</p></td>
</tr>
<tr class="even">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>+</strong>field</p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Subtotal
within a SORT BY field</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>When
subtotaling, you indicate in the “PRINT FIELD” dialogue the fields to be
enumerated. All requested numeric operations (sum, count, etc.) are done
as a subtotal when the SORT BY field changes in addition to the grand
totals at the end.</p>
<p>You can sub-subtotal by adding a prefix of <strong>+</strong> to
<strong>two</strong> fields in the “SORT BY:” dialogue. For example:</p>
<p><span style="font-size:6.0pt"> </span></p>
<p>SORT BY: <strong>+REGION</strong></p>
<p>WITHIN REGION, SORT BY: <strong>+STORE</strong></p>
<p><span style="font-size:6.0pt"> </span></p>
<p>This produces subtotals for each STORE within the subtotals for each
REGION.</p></td>
</tr>
<tr class="odd">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><span
style="font-size:11.0pt;
  font-family:&quot;Arial&quot;,sans-serif;color:black"><br />
</span>
<p><strong> -</strong>field</p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Reverse
sort order</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Only
effective for NUMERIC and DATE/TIME valued fields:</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>DATE/TIME values—Prints from most recent to earliest.</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>NUMERIC values—Prints from largest to smallest.</p></td>
</tr>
<tr class="even">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>@</strong>field</p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Suppress
the printing of subheader</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Normally,
a subheader with the value of the SORT BY field name is printed for SORT
BY fields, if the field is <em>not</em> also specified as a print field.
Using an at-sign (<strong>@</strong>) suppresses those
subheaders.</p></td>
</tr>
<tr class="odd">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>field<strong>;C<em>n</em></strong></p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Set
column of subheader</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>The
number (<strong><em>n</em></strong>) indicates the column to begin the
subheader.</p></td>
</tr>
<tr class="even">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>field<strong>;L<em>n</em></strong></p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Use
less than the entire sort field for sorting</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>The
<strong>;L</strong> suffix lets you specify that only the first
“<strong><em>n</em></strong>” characters of the field used to sort.
Thus, if you specify:</p>
<p><span style="font-size:6.0pt"> </span></p>
<p>SORT BY: <strong>NAME;L2</strong></p>
<p><span style="font-size:6.0pt"> </span></p>
<p>Only the first <strong>two</strong> letters of the name field are
used for sorting: the order of “<strong>FMEMPLOYEE,TWENTY</strong>” and
“<strong>FMEMPLOYEE,ONE</strong>”, for example, is unpredictable in your
output.</p></td>
</tr>
<tr class="odd">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>field<strong>;<span
id="pa_b"></span><span
id="_Hlt446145184"></span>P<em>a</em>-<em>b</em></strong></p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Store
sort range for display</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>The
<strong>;P</strong> suffix saves the “START WITH” and “GO TO” sort range
for <em>one</em> level of sort fields, for later reference at a “PRINT
FIELD” prompt. You can substitute any string (up to <strong>60</strong>
characters in length) for “<strong><em>a</em></strong>” and
“<strong><em>b</em></strong>” in
“<strong>;P<em>a</em>-<em>b</em></strong>”. Whatever strings you use as
“<strong><em>a</em></strong>” and “<strong><em>b</em></strong>”
(e.g.,<span
style="font-family:&quot;Times New Roman&quot;,serif"> </span>FROM and
TO) become subscripts of the PARAM() array:</p>
<p><span style="font-size:6.0pt"> </span></p>
<p>SORT BY: <strong>NAME;PFROM-TO</strong></p>
<p>START WITH NAME: FIRST// <strong>C</strong></p>
<p>GO TO NAME: LAST// <strong>D<em>zzzzz</em></strong></p>
<p><span style="font-size:6.0pt"> </span></p>
<p>Then at a “PRINT FIELD” prompt, you can reference the saved values by
using <strong>PARAM(“<em>a-string</em>”)</strong> and
<strong>PARAM(“<em>b-string</em>”)</strong>. Thus, in this case:</p>
<p><span style="font-size:6.0pt"> </span></p>
<p>THEN PRINT FIELD: <strong>PARAM(“FROM”)</strong></p>
<p>THEN PRINT FIELD: <strong>PARAM(“TO”)</strong></p>
<p><span style="font-size:6.0pt"> </span></p>
<p>The sort-from and sort-to values of “<strong>C</strong>” and
“<strong>D<em>zzzzz</em></strong>” in the report would then print in the
appropriate location. The typical reason to save sort values, and then
retrieve them from the <strong>PARAM</strong> array in a print field, is
for custom report headers (which are created as PRINT templates). It is
one method to print sort criteria in the report header.</p>
<p>If you need to sort on <em>two or more</em> fields, you need to use a
different string for “<strong><em>a</em></strong>” and
“<strong><em>b</em></strong>” at each level, or else the values
overwrite each other.</p>
<p><img src="user-manual.fld/image002.png" id="Picture 90"
data-border="0" width="22" height="22"
alt="Note" /> <strong>NOTE:</strong> No value is saved in the
<strong>PARAM</strong> array if the user accepts “FIRST” or “LAST” as
the “START WITH” or “GO TO” sort values; the PARAM array is
<strong>NULL</strong>.</p></td>
</tr>
<tr class="even">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>field<strong>;S<em>n</em></strong></p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Skip
lines when sort value changes</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>The
<strong>;S</strong> suffix skips one line between sort field values, if
no number is added. If you specify a number
(“<strong><em>n</em></strong>”), <em>n</em>-lines are skipped. You can
use this qualifier to skip lines after subtotals are printed by
inserting the following after the last subtotaled field:</p>
<p><span style="font-size:6.0pt"> </span></p>
<p>WITHIN X, SORT BY: <strong>@“”;S</strong></p>
<p>START WITH ““: FIRST// <strong>@</strong></p>
<p>GO TO “<strong>”</strong>: LAST// <strong>@</strong></p></td>
</tr>
<tr class="odd">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>field<strong>;TXT</strong></p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Sort
numbers as text</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>The
<strong>;TXT</strong> sort qualifier forces digits to be sorted as
alphanumeric strings, <em>not</em> as numbers (“<strong>22</strong>”
sorts before “<strong>3</strong>”). Use this to correctly sort mixed
canonic and <em>non</em>-canonic numbers.</p></td>
</tr>
<tr class="even">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>field<strong>;”xxx”</strong></p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Replace
caption in subheader and sort dialogue</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>The
default subheader is the field label or expression entered at the “SORT
BY:” prompt. The same string is used within the sort dialogue. You can
substitute a string of your choosing by adding a semicolon
(<strong>;</strong>) and text enclosed in quotation marks. For
example:</p>
<p><span style="font-size:6.0pt"> </span></p>
<p>SORT BY: DATE OF BIRTH;“Birthdate: <strong>”</strong></p>
<p><span style="font-size:6.0pt"> </span></p>
<p>To suppress the caption in the subheader, enter <strong>two</strong>
double quotes after the semicolon:<br />
<br />
</p>
<p>SORT BY: DATE OF BIRTH;“”</p>
<p><span style="font-size:6.0pt"> </span></p>
<p>The specified caption is also used in the subsequent sort dialogue.
This is useful in simplifying the sort dialogue when a field label is
confusing, is concatenated, or is an extended pointer. For example:</p>
<p><span style="font-size:6.0pt"> </span></p>
<p>SORT BY: <strong>STORE:REGION;”Location:”</strong></p>
<p>START WITH Location: FIRST// <strong>&lt;Enter&gt;</strong></p>
<p>WITHIN Location, SORT BY: <strong>&lt;Enter&gt;</strong></p>
<p>PRINT FIELD: <strong>STORE</strong></p>
<p>THEN PRINT FIELD: <strong>&lt;Enter&gt;</strong></p>
<p><span style="font-size:6.0pt"> </span></p>
<p>“<strong>Location:</strong>” is substituted for
“<strong>STORE:REGION</strong>”.</p></td>
</tr>
</tbody>
</table>

<span id="sort_templates"> </span>

#### <span id="_Ref524021044">3.4.2.7<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Saving Sort Criteria (SORT Templates)</span>

You can save your sort criteria in a SORT template. This lets you reuse
the same sorting instructions in future prints from the current file.
SORT templates are stored in the SORT TEMPLATE (#.401) file. If you sort
by more than **three** fields, you are asked whether you want to store
your sort criteria in a SORT template, as shown in
<u><span style="color:blue">Figure 17</span></u>.

<span id="_Toc527389221"></span><span id="_Ref345588347">Figure</span>
17: Print—Dialogue to Create a Sort Template: Sample User Entries at
Prompts

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

Select VA FileMan Option: **<span style="background:yellow">PRINT
\<Enter\></span>** File Entries

 

OUTPUT FROM WHAT FILE: PATIENT//
**<span style="background:yellow">\<Enter\></span>**

<img src="user-manual.fld/image026.png" data-border="0" width="169"
height="44"
alt="Sort by at least three fields. - Title: Sort by at least three fields. - Description: Sort by at least three fields." />

SORT BY: NAME// **<span style="background:yellow">ZIP CODE</span>**

START WITH ZIP CODE: FIRST//
**<span style="background:yellow">\<Enter\></span>**

  WITHIN ZIP CODE, SORT BY:
**<span style="background:yellow">CITY</span>**

     1   CITY 

     2   CITY (CIVIL)

     3   CITY (VA)

CHOOSE 1-3: **<span style="background:yellow">1 \<Enter\></span>** CITY

  START WITH CITY: FIRST//
**<span style="background:yellow">\<Enter\></span>**

    WITHIN CITY, SORT BY:
**<span style="background:yellow">NAME</span>**

     1   NAME 

     2   NAME COMPONENTS 

     3   NAME ORDER 

CHOOSE 1-3: **<span style="background:yellow">1 \<Enter\></span>**  NAME

    START WITH NAME: FIRST//
**<span style="background:yellow">\<Enter\></span>**

      WITHIN NAME, SORT BY:
**<span style="background:yellow">\<Enter\></span>**

<img src="user-manual.fld/image027.png" data-border="0" width="376"
height="48"
alt="To save the sort criteria for a future use, enter a SORT template name. - Title: To save the sort criteria for a future use, enter a SORT template name. - Description: To save the sort criteria for a future use, enter a SORT template name." />

STORE IN ‘SORT’ TEMPLATE: **<span style="background:yellow">ADDRESS
LIST</span>**

  Are you adding ‘ADDRESS LIST’ as a new SORT TEMPLATE? No//
**<span style="background:yellow">Y \<Enter\></span>** (Yes)

DESCRIPTION:

  No existing text

  Edit? NO// **<span style="background:yellow">YES</span>**

<img src="user-manual.fld/image028.png" data-border="0" width="353"
height="46"
alt="Optionally, enter a description for the SORT template. - Title: Optionally, enter a description for the SORT template. - Description: Optionally, enter a description for the SORT template." />

==\[ WRAP \]==\[ INSERT \]=============\< DESCRIPTION \>===========\[
\<PF1\>H=Help \]====

**<span style="background:yellow">Template for address listing.</span>**

 

 

\<=======T=======T=======T=======T=======T=======T=======T=======T=======T\>======

 

 

FIRST PRINT FIELD:

</div>

 

##### 3.4.2.7.1<span style="font:7.0pt &quot;Times New Roman&quot;">    </span>Forcing Creation of a SORT Template

Ordinarily, you are only asked whether to save your sort criteria in a
SORT template if you enter **three** or more fields at the “SORT BY:”
prompts. However, to force this question to be asked, enter a right
bracket ( **\]** ) by itself at one “SORT BY:” prompt. No matter how few
fields you sort by, you are still prompted to save your sort criteria in
a SORT template.

<span id="_Toc527389222">Figure</span> 18: Print—Forcing the Creation of
a Sort Template

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    SORT BY: NAME// **<span style="background:yellow">\]</span>**

    SORT BY: NAME//

</div>

 

##### 3.4.2.7.2<span style="font:7.0pt &quot;Times New Roman&quot;">    </span>Reusing Sort Criteria in New Reports

The reason to save sort criteria in a SORT template is so that you can
*reuse* your sort criteria in a new report from the same file.

To reuse a SORT template as the sort criteria in a new report, at the
“SORT BY:” prompt in the new report, enter a left bracket ( **\[** )
plus the template name:

<span id="_Toc527389223">Figure</span> 19: Print—Reusing a Sort Template

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    OUTPUT FROM WHAT FILE: NEW PERSON//
**<span style="background:yellow">\<Enter\></span>**

    SORT BY: NAME// **<span style="background:yellow">\[ADDRESS LIST
\<Enter\></span>**

                                    (Dec 08, 1995@07:53) User \#34 File
\#200 

    WANT TO EDIT ‘ADDRESS LIST’ TEMPLATE? NO//
**<span style="background:yellow">\<Enter\></span>**

    FIRST PRINT FIELD:

</div>

 

### <span id="specifying_print"></span><span id="_Toc527389062"></span><span id="_Hlt446147711"></span>3.4.3<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Choosing Print Fields

#### 3.4.3.1<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Specifying Fields to Print

After you have specified the order in which the output should occur, you
are asked to list the fields you want displayed for each file entry. In
the simplest case, fields are identified by their label. If you enter a
single question mark (**?**) at the prompt, a list of all the fields in
the file is displayed. If you enter the name of a Multiple, you are
asked for the subfields you want printed. A subfield *must* be specified
even if the Multiple has only one subfield.

To print all fields in the file, enter **ALL** (uppercase) at the “FIRST
PRINT FIELD:” prompt. You are then prompted:

<span id="_Toc527389224">Figure</span> 20: Print—Confirmation Message to
Print All Fields

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    Do you mean ALL the fields in the file? NO//

</div>

 

Enter **YES** to indicate all fields; otherwise, the file is searched
for field labels beginning with the letters “**ALL**”.

<img src="user-manual.fld/image002.png" id="Picture 91" data-border="0"
width="22" height="22" alt="Note" />     **NOTE:** Fields from other
files can also be printed using extended pointers. This technique is
described in the “Using Co<span id="_Hlt446140124">m</span>puted
Expressions in COMPUTED Fields” section in the “Computed Expressions”
section in the *VA FileMan Advanced User Manual*. You can also enter
other computed expressions, which are also described in that section.

#### <span id="print_qualifiers"></span><span id="_Hlt446143573"></span>3.4.3.2<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Print Qualifier Reference

VA FileMan’s print capabilities provide many ways to format a report. If
you do *not* specify any formatting controls, a format is constructed
automatically. The width of each field’s print area is computed using
information from the field’s definition. The default width is the larger
of the following in the print dialogue:

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Maximum number of characters allowed for the field.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Length of the longest word of the field’s label (or other
specification).

**Two** inter-column spaces are added to separate fields.

By using print qualifiers at the “PRINT FIELD:” prompt, for each field,
you can indicate:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>How long the field’s print area should be.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Where it should start.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>How many lines to skip before printing the field.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Column title for the field.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Insert literal strings within the output.

For fields that have numeric values, you can call for several arithmetic
calculations and indicate the number of decimal digits of accuracy. If
you have requested subtotals in the sort dialogue (by preceding the
field with a **+**), calculations are done at the subtotal level as
well.

##### 3.4.3.2.1<span style="font:7.0pt &quot;Times New Roman&quot;">    </span>Print Qualifiers to use at “PRINT FIELD:” Prompts

<u><span style="color:blue">Table 3</span></u> lists the print
qualifiers you can use at the “PRINT FIELD:” prompts:

<span id="_Toc527389327"></span><span id="_Ref446141407"></span><span id="_Hlt446381292"></span>Table
3: Print—Print Qualifiers

<table class="MsoNormalTable" data-border="1" data-cellspacing="0"
data-cellpadding="0" width="668"
style="margin-left:1.15pt;border-collapse:collapse;border:none">
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th width="102"
style="width: 76.5pt; border: solid windowtext 1.0pt; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="COL001_TBL004"></span>Qualifier</p></th>
<th width="144"
style="width: 1.5in; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Action</p></th>
<th width="422"
style="width: 316.5pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Discussion</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>!</strong>field</p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Count</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>The
number of entries with <em>non</em>-<strong>NULL</strong> values in this
field is counted.</p></td>
</tr>
<tr class="even">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>#</strong>field</p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>All
statistics</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Use
with NUMERIC fields only. <strong>Six</strong> lines of statistical
output are generated for the selected field:</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>Total</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>Count</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>Mean</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>Maximum</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>Minimum</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>Standard Deviation</p></td>
</tr>
<tr class="odd">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&amp;</strong>field</p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Total</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Use
for NUMERIC fields only. The values of all occurrences of this field are
summed.</p></td>
</tr>
<tr class="even">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>+</strong>field</p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Total,
count and mean</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Use
for NUMERIC fields only. The sum, count of <em>non</em>-
<strong>NULL</strong> values, and the arithmetic mean of the
<em>non</em>- <strong>NULL</strong> values are printed.</p></td>
</tr>
<tr class="odd">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>field<strong>;B</strong></p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Multiples
in sorted order</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Typically,
entries in a Multiple are printed in order by Internal Entry Number
(IEN). The <strong>;B</strong> print specifier ensures that subentries
are displayed in order by the value of the <strong>.01</strong>
field.</p></td>
</tr>
<tr class="even">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>field<strong>;C<em>n</em></strong></p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Set
start column position</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>You
can specify the starting column of a field’s display. If the number
(<strong><em>n</em></strong>) is a positive number, the field prints in
that column counting from the left margin. If it is negative, the field
starts in that column as subtracted from the right margin. If there is
<em>not</em> enough room on a line for the field to display properly, it
is moved to the line below. Adding <strong>;C1</strong> always starts a
field’s display at the beginning of a line.</p></td>
</tr>
<tr class="odd">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>field<strong>;D<em>n</em></strong></p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Round
decimal fractions</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Specify
the number of decimal digits of accuracy with a number,
“<strong><em>n</em></strong>”. If <strong><em>n</em>=0</strong>, the
number is rounded to a whole number. The number
(<strong><em>n</em></strong>) <em>must be</em> <strong>&gt; 0</strong>
<em>or</em> <strong>= 0</strong>.</p></td>
</tr>
<tr class="even">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="_Hlt446141836"></span>field<strong>;L<em>n</em></strong></p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Left
justify and truncate</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>To
left justify within a field width of “<strong><em>n</em></strong>”
characters, follow the <strong>;L</strong> with the number of column
positions you want the field to occupy. If necessary, the data is
truncated to fit into this length. Since <em>non</em>-numeric fields are
left justified by default, the only effect of <strong>;L</strong> on
those fields is truncation. This qualifier does <em>not</em> affect
DATE/TIME-valued fields.</p></td>
</tr>
<tr class="odd">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>field<strong>;N</strong></p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Suppress
consecutive duplicate values</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>If
you do <em>not</em> want the same value for a field printed on
consecutive rows of a report, add <strong>;N</strong> to the field
specification.</p></td>
</tr>
<tr class="even">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>field<strong>;R<em>n</em></strong></p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Right
justify text</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>To
right justify within a field of “<strong><em>n</em></strong>”
characters, follow the <strong>;R</strong> with that number.
Right-justified data is <em>not</em> truncated; if
“<strong><em>n</em></strong>” is <em>not</em> large enough; data spills
into the next field’s area causing confusing output. DATA TYPE field
values of NUMERIC are right justified by default. However, COMPUTED
expressions with numeric results are <em>not</em> right justified
automatically.</p></td>
</tr>
<tr class="odd">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>field<strong>;S<em>n</em></strong></p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Skip
lines between fields</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>You
can indicate a number of lines to skip before printing a field by using
<strong>;S<em>n</em></strong>. Without a number, <strong>;S</strong>
skips a single line. If your field has a <strong>NULL</strong> value,
“<strong><em>n</em></strong>” lines are skipped anyway. You
<em>cannot</em> use <strong>;S</strong> with a WORD-PROCESSING-type
field. To skip one line before a WORD-PROCESSING field, precede the
field with an additional print specification like this:<br />
<br />
</p>
<p>THEN PRINT FIELD: <strong>“”;S</strong></p></td>
</tr>
<tr class="even">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>field<strong>;T</strong></p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Use
field TITLE as header</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>If
you want to use the field’s TITLE, as defined in the data dictionary,
instead of its LABEL in the header, add <strong>;T</strong>.</p></td>
</tr>
<tr class="odd">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>field<strong>;W<em>n</em></strong></p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Wrap
text</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>The
<strong>;W</strong> suffix splits a field that is too long for its field
column width at word boundaries (spaces) and prints it out fully on
<strong>two</strong> or more rows. You can optionally follow the
<strong>;W</strong> with the number of column positions to be occupied
by each line of output. If the field’s data dictionary definition says
to always print in word-wrap mode, DATA TYPE field values of
WORD-PROCESSING are automatically wrapped. The <strong>;W</strong>
suffix overrides the <strong>;R</strong> or <strong>;L</strong>
suffixes; <em>do not use them together</em>.</p></td>
</tr>
<tr class="even">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>field<strong>;X</strong></p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Suppress
header and inter-column spaces</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Follow
the field specification with <strong>;X</strong> to suppress the
<strong>two spaces</strong> normally inserted before a field and the
column header for the field. The result is concatenation of the field
with the field that came before it. The <strong>;X</strong> suffix is
often used to add a literal caption to a field.</p></td>
</tr>
<tr class="odd">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>field<strong>;”<em>xxx</em>”</strong></p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Customize
header</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>The
default header for columns of a report is the field label (for fields)
or a COMPUTED expression (for “on-the-fly” COMPUTED expressions). To
change the header, follow the field label with a semicolon
(<strong>;</strong>) and the column header you want. Enclose the header
in quotes. When possible, spaces wrap the substitute header within a
print width obtained from the field’s data definition. For example:</p>
<p><span style="font-size:6.0pt"> </span></p>
<p>THEN PRINT FIELD: <strong>DOB;”Date of Birth”</strong></p>
<p>THEN PRINT FIELD: <strong>DOB;”Date_of_Birth”</strong></p>
<p><span style="font-size:6.0pt"> </span></p>
<p>The first specification prints the header on <strong>two</strong>
lines; the second prints it on <strong>one</strong> line (with
underscores). To suppress the header, add <strong>; “”</strong> to the
field.</p>
<p><img src="user-manual.fld/image002.png" id="Picture 92"
data-border="0" width="22" height="22"
alt="Note" /><strong> NOTE:</strong> The tilde (<strong>~</strong>)
character should <em>never</em> be used within a customized header,
because this character has a special meaning to VA FileMan.</p></td>
</tr>
<tr class="even">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>field<strong>;Y<em>n</em></strong></p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Set
start row position</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>You
can start printing a field on any line on the page. If
“<strong><em>n</em></strong>” is:</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span><strong>Positive—</strong>The field is printed on that
line as counted from the top of the page.</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span><strong>Negative—</strong>The field is printed on that
line as counted from the bottom.</p>
<p>When specifying <strong>;Y<em>n</em></strong>, you <em>must</em>
account for any page header that is displayed.</p></td>
</tr>
<tr class="odd">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>“<em>xxx</em>”</strong></p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Insert
a literal</p></td>
<td width="422" data-valign="top"
style="width: 316.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>At
the “PRINT FIELD:” prompt enclose a FREE TEXT literal in quotes. The
literal is inserted into the body of the report. For example, the
following specifications begin each entry’s display with a caption and
NAME:</p>
<p><span style="font-size:6.0pt"> </span></p>
<p>FIRST PRINT FIELD: <strong>“Patient’s name:”</strong></p>
<p>THEN PRINT FIELD: <strong>NAME;“”</strong></p>
<p><strong>Or</strong></p>
<p>FIRST PRINT FIELD: <strong>“Patient’s name:”</strong></p>
<p>THEN PRINT FIELD: <strong>NAME;X</strong></p>
<p><span style="font-size:6.0pt"> </span></p>
<p><img src="user-manual.fld/image002.png" id="Picture 93"
data-border="0" width="22" height="22"
alt="Note" /> <strong>NOTE:</strong> The header for the NAME field is
suppressed in both examples.</p></td>
</tr>
</tbody>
</table>

 

You can string together several of these print qualifiers at the “PRINT
FIELD:” prompt. For example:

<span id="_Toc527389225">Figure</span> 21: Print—Stringing Several Print
Qualifiers Together

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    THEN PRINT FIELD: **+WEIGHT;S1;C3;L6;”Patient Weight”**

</div>

 

These specifications translate to: total, count, and give the mean for
all values of the WEIGHT field, which *must* be a NUMERIC valued field.
Skip one line before printing the values. Start the output in column
three, left justify and truncate it to **six** character positions, and
print the column heading “Patient Weight” on **two** lines.

#### <span id="print_templates">3.4.3.3<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Saving Print Criteria (PRINT Templates)</span>

PRINT templates let you store your print field specifications for use at
a later time. You can retrieve the template at a later time by using the
template name surrounded by square brackets ( **\[ \]** ). Template
names *must* be unique with respect to any other PRINT template created
for the same file. VA FileMan notifies you if you try to create a
template with a template name that already exists for a file. PRINT
templates are stored in the PRINT TEMPLATE (#.4) file.

To see a list of all existing templates that pertain to the file you are
dealing with, enter a left bracket and a question mark (**\[?**) at the
prompt where you can retrieve templates. For example:

<span id="_Toc527389226">Figure</span> 22: Print—Obtaining a List of All
Print Templates for a File

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    FIRST PRINT FIELD: **\[?**

</div>

 

This gives you a list of the PRINT templates available for your use with
the file.

You are automatically prompted for a template name when it is determined
that a considerable amount of information has been specified. If you
choose **five** or more print fields, or if some of your print fields
have special formatting specifications, you are prompted to store your
print field specification in a PRINT template, as follows:

<span id="_Toc527389227">Figure</span> 23: Print—Creating a Print
Template

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    STORE PRINT LOGIC IN TEMPLATE:

</div>

 

If you do *not* want to store your specifications in a template, simply
press the **Enter** key. If you do want to save these print
specifications for future reuse, however, respond to this prompt with
the name of a template (either new or existing). Do *not* enclose the
name in brackets; use brackets only to invoke a template, *not* to name
one.

##### 3.4.3.3.1<span style="font:7.0pt &quot;Times New Roman&quot;">    </span>Forcing Creation of a PRINT Template

Ordinarily, you are only asked whether you want to save your PRINT
template if you enter **five** or more fields at the “PRINT FIELD:”
prompt, or enter complex print specifications. However, by entering a
right bracket ( **\]** ) by itself at one of your field prompts, you can
force the prompt that asks you for a template name, no matter how few
fields you specify. You *must* designate at least one field to be
printed to receive the template prompt, though.

For example:

<span id="_Toc527389228">Figure</span> 24: Print—Forcing the Creation of
a Print Template

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    PRINT FIELD: **<span style="background:yellow">\] \<Enter\></span>**

    PRINT FIELD: **<span style="background:yellow">NAME</span>**

    THEN PRINT FIELD:
**<span style="background:yellow">\<Enter\></span>**

    HEADING: **<span style="background:yellow">\<Enter\></span>**

    STORE PRINT LOGIC IN TEMPLATE: **<span style="background:yellow">ID
PRINT</span>**

</div>

 

##### 3.4.3.3.2<span style="font:7.0pt &quot;Times New Roman&quot;">    </span>Using and Editing PRINT Templates

If a PRINT template has already been defined for a file, you can answer
the “FIRST PRINT FIELD:” prompt with the template name, enclosed within
square brackets ( **\[ \]** ). For example:

<span id="_Toc527389229"></span><span id="_Ref490837427">Figure</span>
25: Print—Reusing a Print Template

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    FIRST PRINT FIELD: **<span style="background:yellow">\[PATIENT
DATA\]</span>**

    WANT TO EDIT ‘PATIENT DATA’ TEMPLATE? NO//
**<span style="background:yellow">Y \<Enter\></span>** (YES)

    NAME: PATIENT DATA//
**<span style="background:yellow">\<Enter\></span>**

    READ ACCESS: **<span style="background:yellow">\<Enter\></span>**

    WRITE ACCESS: **<span style="background:yellow">\<Enter\></span>**

</div>

 

After you retrieve a template, you are asked if you want to edit the
template. If you answer **YES** (as shown in
<u><span style="color:blue">Figure 25</span></u>), you are allowed to
edit the template name. To delete the template, enter an
at-sign (**@**). After the “NAME:” prompt, you can edit the template
security codes for **READ** and **WRITE** access.

Next, you are prompted to edit each “PRINT FIELD:” value, containing
each print field stored in the template. You can leave each print field
as is, edit it, or delete it with the at-sign character (**@**).

To insert a new print field ahead of the print field being displayed in
your template, precede the print field you want to insert with a caret
(**^**). See the example in <u><span style="color:blue">Figure
26</span></u> of adding to a PRINT template (INPUT and SORT templates
have this feature also):

<span id="_Toc527389230"></span><span id="_Ref389661454">Figure</span>
26: Print—Inserting a New Print Field

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    FIRST PRINT FIELD: FIELD1//
**<span style="background:yellow">\<Enter\></span>**

    THEN PRINT FIELD: FIELD2//
**<span style="background:yellow">\<Enter\></span>**

    THEN PRINT FIELD: FIELD4//
**<span style="background:yellow">^FIELD3</span>**

    THEN PRINT FIELD: FIELD4//
**<span style="background:yellow">\<Enter\></span>**

</div>

 

To insert a Multiple field and its subfields ahead of the field
currently displayed in the template, do the following:

1.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>Enter
a caret (**^**) followed by the name of the Multiple field.

2.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Ignore the default presented at the “THEN PRINT FIELD:” prompt
and insert each subfield by entering a caret (**^**) followed by the
name of that subfield.

3.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>After
all subfields have been added, enter a caret (**^**) and a right bracket
(**^\]**).

For example:

<span id="_Toc527389231">Figure</span> 27: Print—Inserting a Multiple
Print Field

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

FIRST PRINT FIELD: FIELD1//
**<span style="background:yellow">\<Enter\></span>**

    THEN PRINT FIELD: FIELD2//
**<span style="background:yellow">\<Enter\></span>**

    THEN PRINT FIELD: FIELD3//
**<span style="background:yellow">^MultField \<Enter\></span>**
(multiple)

    THEN PRINT MultField SUB-FIELD: FIELD3//
**<span style="background:yellow">^SubField1</span>**

    THEN PRINT MultField SUB-FIELD: FIELD3//
**<span style="background:yellow">^SubField2</span>**

    THEN PRINT MultField SUB-FIELD: FIELD3//
**<span style="background:yellow">^\]</span>**

    THEN PRINT FIELD: FIELD3//

</div>

 

#### 3.4.3.4<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>CAPTIONED PRINT Template: \[CAPTIONED

Every file has a pre-defined CAPTIONED PRINT template that you can
select at the “PRINT FIELD:” prompt. The CAPTIONED PRINT template can be
very useful; it prints out all fields for each entry in your report. Use
it is a quick way to get all the fields for each entry in your report
(much quicker than entering each field individually)!

Use it as follows:

<span id="_Toc527389232">Figure</span> 28: Print—Choosing a Captioned
Print Template

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    FIRST PRINT FIELD:
**<span style="background:yellow">\[CAPTIONED</span>**

</div>

 

##### 3.4.3.4.1<span style="font:7.0pt &quot;Times New Roman&quot;">    </span>COMPUTED Fields and Record Numbers in CAPTIONED OUTPUT

When you choose the CAPTIONED PRINT template, you are prompted with
“Include COMPUTED fields”. At this prompt, you can decide whether to
include COMPUTED-type fields in the output for each record, as well as
record numbers.

<img src="user-manual.fld/image002.png" id="Picture 94" data-border="0"
width="22" height="22" alt="Note" />     **REF:** For more information
on COMPUTED fields, see the “COMPUTED Data
<span id="_Hlt446143283">T</span>ype” section in the *VA FileMan
Advanced User Manual*.

<span id="_Toc527389233">Figure</span> 29: Print—Dialogue Encountered
when Creating a Captioned Print Report

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    FIRST PRINT FIELD:
**<span style="background:yellow">\[CAPTIONED</span>**

 

    Include COMPUTED fields: (N/Y/R/B): NO//
**<span style="background:yellow">?</span>**

 

    Enter a code from the list.

         Select one of the following:

 

              N         NO - No record number (IEN), no Computed Fields

              Y         Computed Fields

              R         Record Number (IEN)

              B         BOTH Computed Fields and Record Number (IEN)

 

   

    Include COMPUTED fields:  (N/Y/R/B): NO//
**<span style="background:yellow">BOTH \<Enter\></span>** Computed
Fields and Record Number (IEN)

 

      \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

    Heading (S/C): NEW PERSON LIST//
**<span style="background:yellow">\<Enter\></span>**

    DEVICE: **<span style="background:yellow">\<Enter\></span>**

</div>

 

#### <span id="statistics">3.4.3.5<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Printing Statistics Only (Totals, Counts, etc.)</span>

If you precede *all* of the fields that you choose for printing at the
“PRINT FIELD:” prompts with a **+**, **&**, **!**, or **\#**, the
individual field values are *not* printed in your report. Instead, you
only get the requested statistics, which (depending on the print
qualifiers and fields used) can be the total, count, mean, maximum,
minimum, and/or standard deviation.

<img src="user-manual.fld/image002.png" id="Picture 95" data-border="0"
width="22" height="22" alt="Note" />     **REF:** For more information
about print qualifiers, see the “[Print Qualifier
Reference](#print_qualifiers)<span id="_Hlt446143571"></span><span id="_Hlt446143767"></span>”
section.

### <span id="other"></span><span id="_Toc527389063">3.4.4<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Other Print Features</span>

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>[Multiple Copies of a
Print](#multiple_copies)<span id="_Hlt446143623"></span><span id="_Hlt446147865"></span><span id="_Hlt446143708"></span><span id="_Hlt446143598"></span><span id="_Hlt446143696"></span>

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>[Report
Headings](#headings)<span id="_Hlt446143620"></span><span id="_Hlt446147868"></span>

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>[Suppressing Report Headings (and Page
Feeds)](#suppressing)<span id="_Hlt446147870"></span><span id="_Hlt446143617"></span>

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>[Custom Headings and
Footers](#custom)<span id="_Hlt446147872"></span><span id="_Hlt446143613"></span>

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>[Printing Sort Criteria in Header or
Footer](#criteria)<span id="_Hlt446147874"></span><span id="_Hlt446143610"></span>

#### <span id="multiple_copies"></span><span id="_Hlt446143710"></span>3.4.4.1<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Multiple Copies of a Print

To generate more than one copy of a report, you *must* have an output
device on your system (e.g., a spool device or a sequential disk
processor \[SDP\]), which stores data in a linear format. If you choose
to send the output to such a device at the “DEVICE:” prompt, the system
prompts you as shown in <u><span style="color:blue">Figure
30</span></u>:

<span id="_Toc527389234"></span><span id="_Ref490837707">Figure</span>
30: Print—Generating Multiple Copies of a Report

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    ENTER NUMBER OF COPIES: **<span style="background:yellow">4</span>**

    OUTPUT COPIES TO DEVICE:
**<span style="background:yellow">PRINTER</span>**

</div>

 

In this example (<u><span style="color:blue">Figure 30</span></u>), you
are asking to print **four** copies to the device called **PRINTER**.

You *must* be using VA FileMan with Kernel or with a device handler
similar to Kernel’s to produce multiple copies. If you exceed the
maximum spool lines allowed, as defined in the KERNEL SYSTEM PARAMETERS
(#8989.3) file, your report is stopped.

#### <span id="headings"></span><span id="_Hlt446143622"></span>3.4.4.2<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Report Headings

The heading in a report is what is printed at the top of each report
page. Ordinarily, it includes the following, as shown in
<u><span style="color:blue">Figure 31</span></u>:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Heading (report title)

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Date of report

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Time of report

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Page number

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Column headers (field titles for fields in the output)

<span id="_Toc527389235"></span><span id="_Ref490837828">Figure</span>
31: Print—Example of a Report Heading

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    PATIENT LIST                       JUL 19,1996  14:49    PAGE 1

    SSN        NAME

    -------------------------------------------------------------------

</div>

 

You can customize the report heading when you print. If you ask for help
at the “Heading (S/C):...” prompt, VA FileMan displays the instructions
shown in <u><span style="color:blue">Figure 32</span></u>:

<span id="_Toc527389236"></span><span id="_Ref345588354">Figure</span>
32: Print—Dialogue to Customize Report Headings: Sample User Entries at
Prompts

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

Heading (S/C): PATIENT LIST//
**<span style="background:yellow">?</span>**

 

There are two different options:

 

1\) Accept the default heading or enter a custom heading.

 For no heading at all, type @.

 To use a Print Template for the heading, type \[TEMPLATE NAME\].

 

2\) Replace the default heading with:

 S  to Suppress the heading when there are no records to print, and/or

 C  to print sort Criteria in the heading.

 

If S and/or C is entered, the heading prompt will re-appear.

<img src="user-manual.fld/image029.png" data-border="0" width="179"
height="42"
alt="Default heading for the report. - Title: Default heading for the report. - Description: Default heading for the report." />

Heading (S/C): PATIENT LIST//
**<span style="background:yellow">CS</span>**

<img src="user-manual.fld/image030.png" data-border="0" width="438"
height="75"
alt="“C” prints sort criteria on the heading of the first page. “S” tells VA FileMan not to print anything if there are no records to print. - Title: “C” prints sort criteria on the heading of the first page. - Description: “C” prints sort criteria on the heading of the first page. “S” tells VA FileMan not to print anything if there are no records to print." />

 

  \*\* Suppress the heading when there are no records to print.

  \*\* print sort Criteria in heading.

 

 

Heading: PATIENT LIST//

</div>

 

Thus, at the “Heading (S/C):” prompt, you can:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Enter **S** to *not* print the heading (i.e., *not* print
anything), if no records are found to print.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Enter **C** to print sort criteria in the report heading
on the first page.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Enter a new heading to replace the default heading or
press the **Enter** key to accept the default heading.

#### <span id="suppressing"></span><span id="_Hlt446143619"></span>3.4.4.3<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Suppressing Report Headings (and Page Feeds)

If you do *not* want headings to be printed in your output, enter an
at-sign (**@**) at the “HEADING:” prompt:

<span id="_Toc527389237">Figure</span> 33: Print—Suppressing Headings on
a Report

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    HEADING: PATIENT LIST// **<span style="background:yellow">@</span>**

</div>

 

If you want neither headings nor page feeds in your output, enter
**two** at-signs (**@@**) at the “HEADING:” prompt.

If you suppress the headings in your output and also save your print
criteria in a PRINT template, you are asked:

<span id="_Toc527389238">Figure</span> 34: Print—Confirming the
Suppression of Headings in a Print Template

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    DO YOU ALWAYS WANT TO SUPPRESS SUBHEADERS WHEN PRINTING TEMPLATE?

</div>

 

Subheaders are the names of SORT BY fields you see in the body of your
report, when you do *not* include those SORT BY fields as print fields.
To automatically suppress all subheaders, answer **YES** at this prompt.

<img src="user-manual.fld/image002.png" id="Picture 96" data-border="0"
width="22" height="22" alt="Note" /><span style="font-size:10.0pt">    
</span>**NOTE:** When you are sorting, you can suppress subheaders
individually at each sort level by entering an at-sign (**@**) in front
of the field on which you are sorting.  
  
**REF:** For more information, see the
“[Sorting](#specifying_sort)<span id="_Hlt446147885"></span><span id="_Hlt446144464"></span>”
section.

#### <span id="custom"></span><span id="_Hlt446143615"></span>3.4.4.4<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Custom Headings and Footers

You can print complex, multi-line headings by using a PRINT template to
hold your heading format. For example, suppose that you want the
patient’s name and date of birth to appear as the heading at every page
break. You could first create a PATIENT HEADER template as follows:

<span id="_Toc527389239">Figure</span> 35: Print—Creating a Print
Template with a Custom Header

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    SORT BY: **<span style="background:yellow">NAME</span>**

    START WITH NAME:  FIRST//
**<span style="background:yellow">\<Enter\></span>**

    FIRST PRINT FIELD: **<span style="background:yellow">“PATIENT NAME: 
”</span>**

    THEN PRINT FIELD: **<span style="background:yellow">NAME</span>**

    THEN PRINT FIELD: **<span style="background:yellow">“DATE OF BIRTH: 
”;C50</span>**

    THEN PRINT FIELD: **<span style="background:yellow">DATE OF
BIRTH</span>**

    THEN PRINT FIELD:
**<span style="background:yellow">\<Enter\></span>**

      \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

    Heading (S/C): PATIENT LIST//
**<span style="background:yellow">\<Enter\></span>**

    STORE PRINT LOGIC IN TEMPLATE:
**<span style="background:yellow">PATIENT HEADER</span>**

      Are you adding ‘PATIENT HEADER’ as a new PRINT TEMPLATE?  No//
**<span style="background:
yellow">YES \<Enter\></span>** (Yes) 

    DEVICE:

</div>

 

Then, at a later time, when you do another print, at the heading prompt,
enter the template name:

<span id="_Toc527389240">Figure</span> 36: Print—Selecting an Existing
Print Template with a Custom Header

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    Heading (S/C): PATIENT LIST//
**<span style="background:yellow">\[PATIENT HEADER\]</span>**

</div>

 

When you enter a PRINT template name such as PATIENT HEADER at the
“Heading (S/C):...” prompt, the format of the template is used as a
replacement for the full normal report heading on each page of your
report. It replaces the full default heading, including:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Title

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Time

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Date

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Page number

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Field names

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Separator line

Thus, the header, as defined above, would contain *no* column headings
and would *not* be separated from the body of the report by a horizontal
line or even a blank line. You can add these in yourself as print fields
in the template, if you so desire.

##### 3.4.4.4.1<span style="font:7.0pt &quot;Times New Roman&quot;">    </span>Custom Footers

You can also add custom footers to the bottom of each page of a report.
First, save the contents of the footer in a template as you do to create
a custom heading. Then, use the template at the “HEADING:” prompt with a
dash (-) before the first square bracket, as shown in
<u><span style="color:blue">Figure 37</span></u>:

<span id="_Toc527389241"></span><span id="_Ref523996613">Figure</span>
37: Print—Including a Custom Footer in a Print Template

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

Heading (S/C): PATIENT LIST//
**<span style="background:yellow">-\[PATIENT FOOTER\]</span>**

</div>

 

You can specify both a heading and footer like this:

<span id="_Toc527389242">Figure</span> 38: Print—Including a Custom
Header and Footer in a Print Template

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    Heading (S/C): PATIENT LIST//
**<span style="background:yellow">\[PATIENT HEADER\]-\[PATIENT
FOOTER\]</span>**

</div>

 

<img src="user-manual.fld/image002.png" id="Picture 97" data-border="0"
width="22" height="22" alt="Note" />**     NOTE:** Specifying only a
footer at the “Heading (S/C):” prompt suppresses the default heading. If
you need a header as well as footer, you *must* use custom templates for
both.

#### <span id="criteria"></span><span id="_Hlt446143612"></span>3.4.4.5<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Printing Sort Criteria in the Heading or the Footer

<span id="_Hlt446381331"></span>You can print the sort criteria (values
used to sort the report) in the header in two different ways:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>At the “Heading (S/C):” prompt, entering **C** prints the
sort criteria in the automatically generated report heading.

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Use the [sort
qualifier](#sort_reference)<span id="_Hlt446145190"></span>
**;P*a*-*b*** to save the FROM and TO values used to sort a report.
Then, in a customized header or footer (stored in SORT templates), you
can retrieve the sort values with **PARAM(“*a-string*”)**.

<img src="user-manual.fld/image002.png" id="Picture 98" data-border="0"
width="22" height="22" alt="Note" />     **REF:** For more information,
see the description of the
[**;Pa-b**](#pa-b)<span id="_Hlt446147899"></span><span id="_Hlt446145182"></span>
sort qualifier.

<span id="_Ref446306822"></span><span id="_Ref446309021"></span><span id="_Ref446310592"></span><span id="_Hlt446233742"></span> 

<span style="font-size:12.0pt;font-family:&quot;Times New Roman&quot;,serif;color:black">  
</span>

 

# <span id="_Ref524020378"></span><span id="_Ref524020477"></span><span id="_Ref524020487"></span><span id="_Ref524021302"></span><span id="_Toc527389064">4<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Search</span>

When you print reports, you can print a subset of the total number of
file entries, if you sort your output. For example, by sorting on a
file’s DATE field, you could sort for entries from October
1<sup>st</sup> to October 15<sup>th</sup>, and only print entries whose
DATE field falls in that sort range.

Selecting a subset of entries by sorting works well if the subset of
entries you would like to print can be isolated based on a contiguous
sort range. However, what if you would like a different set of entries
(e.g., only entries whose DATE field is equal to September
1<sup>st</sup>, October 1<sup>st</sup>, or November 1<sup>st</sup>)? You
*cannot* do this with a sort range, because the sort range that includes
September 1<sup>st</sup> and November 1<sup>st</sup> would include every
entry between the two dates.

When you use VA FileMan’s search capabilities, you have much more
control over what entries you select from a file for printing.

## <span id="How"></span><span id="_Toc527389065">4.1<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>How to Search</span>

As with VA FileMan’s print capabilities, there are two methods in which
you can use VA FileMan’s search features:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>An option that has been set up already to allow you to
search a particular file.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>VA FileMan’s **Search File Entries** \[DISEARCH\] option,
which lets you perform a search on any file to which you have access.

In either case, use of VA FileMan’s search features is very similar. In
most cases, the only difference is that with the **Search File
Entries** \[DISEARCH\] option, you have to choose which file to search.

The steps in searching are:

1.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>Enter
the search conditions (truth tests) to perform on each entry.

2.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Specify how the search conditions should be combined (link them
together with logical **AND**s & **OR**s) to select records.

3.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Format your output (i.e., choose the sort order and print
fields).

## <span id="_Toc527389066">4.2<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Search Steps</span>

### <span id="Step_1"></span><span id="_Toc527389067">4.2.1<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Enter Conditions</span>

First, you *must* enter **one** or more search conditions to test each
entry. For each condition you choose a field in the entry and a
condition to compare the field against.

For example, you could check if an entry’s DATE field is **NULL**,
**GREATER THAN** 10/1/96, or **EQUALS** 10/1/96.

#### 4.2.1.1<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Search Condition Tests

<u><span style="color:blue">Table 4</span></u> lists the **six**
possible search conditions against which you can test entries. It also
includes:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>The symbol that represents the condition (if any).

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>For what field types the condition can be used.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>The description/arguments of each condition.

<span id="_Toc527389328"></span><span id="_Ref446235223">Table</span> 4:
Search—Condition Tests

<table class="MsoNormalTable" data-border="1" data-cellspacing="0"
data-cellpadding="0"
style="margin-left:1.15pt;border-collapse:collapse;border:none">
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th width="114" data-valign="top"
style="width: 85.5pt; border: solid windowtext 1.0pt; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="COL001_TBL005"></span>Condition</p></th>
<th width="90" data-valign="top"
style="width: 67.5pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Symbol</p></th>
<th width="144" data-valign="top"
style="width: 1.5in; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>For
Field Types</p></th>
<th width="276" data-valign="top"
style="width: 207.0pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Description/Arguments</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td width="114" data-valign="top"
style="width: 85.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>NULL</strong></p></td>
<td width="90" data-valign="top"
style="width: 67.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>(none)</p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>All
data field types except WORD-PROCESSING.</p></td>
<td width="276" data-valign="top"
style="width: 207.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>NULL</strong>
returns true if the field in question is empty (<strong>NULL</strong>).
No argument is required.</p></td>
</tr>
<tr class="even">
<td width="114" data-valign="top"
style="width: 85.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>CONTAINS</strong></p></td>
<td width="90" data-valign="top"
style="width: 67.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>[</strong></p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>The
following data field types:</p>
<p><span style="font-family:
  Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>NUMERIC</p>
<p><span style="font-family:
  Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>FREE TEXT</p>
<p><span style="font-family:
  Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>WORD-PROCESSING</p>
<p><span style="font-family:
  Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>MUMPS</p>
<p><span style="font-family:
  Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>SET OF CODES</p>
<p><span style="font-family:
  Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>COMPUTED</p></td>
<td width="276" data-valign="top"
style="width: 207.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Enter
a character string that should be contained in matching entry
fields.</p></td>
</tr>
<tr class="odd">
<td width="114" data-valign="top"
style="width: 85.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>MATCHES</strong></p></td>
<td width="90" data-valign="top"
style="width: 67.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>(none)</p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>The
following data field types:</p>
<p><span style="font-family:
  Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>NUMERIC</p>
<p><span style="font-family:
  Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>FREE TEXT</p>
<p><span style="font-family:
  Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>MUMPS</p>
<p><span style="font-family:
  Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>COMPUTED</p>
<p><span style="font-family:
  Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>DATE/TIME</p></td>
<td width="276" data-valign="top"
style="width: 207.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Enter
a MUMPS pattern match. The pattern <em>must</em> be valid for the MUMPS
pattern match operator.</p></td>
</tr>
<tr class="even">
<td width="114" data-valign="top"
style="width: 85.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>LESS
THAN</strong></p></td>
<td width="90" data-valign="top"
style="width: 67.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt; </strong></p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>The
following data field types:</p>
<p><span style="font-family:
  Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>NUMERIC</p>
<p><span style="font-family:
  Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>COMPUTED</p>
<p><span style="font-family:
  Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>SET OF CODES</p>
<p><span style="font-family:
  Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>FREE TEXT</p>
<p><span style="font-family:
  Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>DATE/TIME</p></td>
<td width="276" data-valign="top"
style="width: 207.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Enter
a value that a matching entry field should be less than.
<em>Non</em>-NUMERIC fields are evaluated as if they were numbers. Thus,
strings beginning with alpha characters are evaluated as
<strong>zero</strong>.</p></td>
</tr>
<tr class="odd">
<td width="114" data-valign="top"
style="width: 85.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>EQUALS</strong></p></td>
<td width="90" data-valign="top"
style="width: 67.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>=</strong></p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>All
data field types except WORD-PROCESSING.</p></td>
<td width="276" data-valign="top"
style="width: 207.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Enter
a value to which a matching entry field should be equal.</p></td>
</tr>
<tr class="even">
<td width="114" data-valign="top"
style="width: 85.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>GREATER
THAN</strong></p></td>
<td width="90" data-valign="top"
style="width: 67.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&gt; </strong></p></td>
<td width="144" data-valign="top"
style="width: 1.5in; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>The
following data field types:</p>
<p><span style="font-family:
  Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>NUMERIC</p>
<p><span style="font-family:
  Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>COMPUTED</p>
<p><span style="font-family:
  Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>SET OF CODES</p>
<p><span style="font-family:
  Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>FREE TEXT</p>
<p><span style="font-family:
  Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>DATE/TIME</p></td>
<td width="276" data-valign="top"
style="width: 207.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Enter
a value to which a matching entry field should be less than.
<em>Non</em>-NUMERIC fields are evaluated as if they were numbers. Thus,
strings beginning with alpha characters are evaluated as
<strong>zero</strong>.</p></td>
</tr>
</tbody>
</table>

 

When you start your search, VA FileMan asks you to enter a:

1.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Field.

2.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Condition.

3.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>Value
to which the field is compared.

For example, to create a search condition that would find all entries
whose DATE ACCESS CODE LAST CHANGED field contains a date older than
**120** days in the past, you would enter the following:

<span id="_Toc527389243">Figure</span> 39: Search—Example of a Search
Condition

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

  -A- SEARCH FOR FIELD: **<span style="background:yellow">DATE ACCESS
CODE LAST CHANGED</span>**

  -A- CONDITION: **<span style="background:yellow">LESS THAN</span>**

  -A- GREATER THAN: **<span style="background:yellow">T-120
\<Enter\></span>** (Jun 20, 1995)

</div>

 

<img src="user-manual.fld/image002.png" id="Picture 99" data-border="0"
width="22" height="22" alt="Note" /><span style="font-size:10.0pt">    
</span>**NOTE:**<span style="font-size:10.0pt"> </span>Each prompt above
begins with “**-A-**”; what you have entered becomes search condition
**A**.

Once you enter your first search condition, you can enter additional
search conditions, if you wish. VA FileMan assigns the letter **A** to
the first search condition, **B** to the second search condition (if
any), **C** to the third, and so on.

<u><span style="color:blue">Figure 40</span></u> is an example of
entering two truth tests:

<span id="_Toc527389244"></span><span id="_Ref524016018">Figure</span>
40: Search—Example of Two Truth Tests

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

  -A- SEARCH FOR FIELD: **<span style="background:yellow">DATE ACCESS
CODE LAST CHANGED</span>**

  -A- CONDITION: **<span style="background:yellow">LESS THAN</span>**

  -A- GREATER THAN: **<span style="background:yellow">T-120
\<Enter\></span>** (Jun 20, 1995)

 

  -B- SEARCH FOR FIELD: **<span style="background:yellow">ACCESS
CODE</span>**

  -B- CONDITION: **<span style="background:yellow">‘NULL</span>**

 

  -C- SEARCH FOR FIELD:
**<span style="background:yellow">\<Enter\></span>**

</div>

 

### <span id="Step_2"></span><span id="_Toc527389068">4.2.2<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Combine Conditions</span>

After defining a series of conditions (**A**, **B**, etc.), you combine
the conditions to yield the complete test that an entry *must* satisfy
to be selected in the search. The complete test is a logical combination
of tests **A**, **B**, etc., using **AND**, **OR**, and **NOT**.

#### 4.2.2.1<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Operators for Combining Search Conditions

<u><span style="color:blue">Table 5</span></u> lists the possible
operators to combine search conditions:

<span id="_Toc527389329"></span><span id="_Ref345508725">Table</span> 5:
Search—Condition Operators

<table class="MsoNormalTable" data-border="1" data-cellspacing="0"
data-cellpadding="0"
style="margin-left:1.15pt;border-collapse:collapse;border:none">
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th width="114" data-valign="top"
style="width: 85.7pt; border: solid windowtext 1.0pt; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="COL001_TBL006"></span>Condition</p></th>
<th width="90" data-valign="top"
style="width: 67.7pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Symbol</p></th>
<th width="281" data-valign="top"
style="width: 211.1pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Description</p></th>
<th width="138" data-valign="top"
style="width: 103.5pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Example</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td width="114" data-valign="top"
style="width: 85.7pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>AND</strong></p></td>
<td width="90" data-valign="top"
style="width: 67.7pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&amp;</strong></p></td>
<td width="281" data-valign="top"
style="width: 211.1pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>For
truth test to be <strong>true</strong>, the conditions on both sides of
the <strong>AND</strong> operator <em>must</em> be
<strong>true</strong>. The <strong>&amp;</strong> symbol can be omitted
(i.e., <strong>AB</strong> is the same as
<strong>A&amp;B</strong>).</p></td>
<td width="138" data-valign="top"
style="width: 103.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>A&amp;B</strong></p></td>
</tr>
<tr class="even">
<td width="114" data-valign="top"
style="width: 85.7pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>NOT</strong></p></td>
<td width="90" data-valign="top"
style="width: 67.7pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>‘</strong>
or <strong>-</strong></p></td>
<td width="281" data-valign="top"
style="width: 211.1pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>For
truth test to be <strong>true</strong>, the condition following
<strong>NOT</strong> (i.e., single quote <strong>‘</strong> or dash
<strong>-</strong>) <em>must</em> be <strong>false</strong>. If
<strong>A</strong> is <strong>false</strong>, <strong>‘A</strong>
evaluates to <strong>true</strong>.</p></td>
<td width="138" data-valign="top"
style="width: 103.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>‘A</strong></p></td>
</tr>
<tr class="odd">
<td width="114" data-valign="top"
style="width: 85.7pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>OR</strong></p></td>
<td width="90" data-valign="top"
style="width: 67.7pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Enter
on new line.</p></td>
<td width="281" data-valign="top"
style="width: 211.1pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>For
truth test to be <strong>true</strong>, only one of the conditions that
are combined with <strong>OR</strong> needs to be <strong>true</strong>.
If <strong>A</strong> is <strong>true</strong> and <strong>B</strong> is
<strong>false</strong>, <strong>A OR B</strong> evaluates to
<strong>true</strong>.</p></td>
<td width="138" data-valign="top"
style="width: 103.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>IF:
<strong>A &lt;Enter&gt;</strong></p>
<p>OR: <strong>B &lt;Enter&gt;</strong></p></td>
</tr>
</tbody>
</table>

 

For example, if you just want to find all entries for which search
condition **A** is **true**, you would enter:

<span id="_Toc527389245">Figure</span> 41: Search—Example of a Single
Search Condition Using a Truth Test

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

  -B- SEARCH FOR FIELD:
**<span style="background:yellow">\<Enter\></span>**

   IF: **<span style="background:yellow">A</span>**

   OR: **<span style="background:yellow">\<Enter\></span>**

</div>

 

A more complicated search might have a number of search conditions
(e.g., **A**, **B**, **C**, and **D**). Thus, for example, to find all
entries which do either of the following:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Satisfy both truth tests **A** and **B**.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Do *not* satisfy truth test **C**, but satisfy truth test
**D**.

You could combine search conditions, as shown in
<u><span style="color:blue">Figure 42</span></u>:

<span id="_Toc527389246"></span><span id="_Ref524016944">Figure</span>
42: Search—Example of a Multiple Search Condition Using Truth Tests

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

  -E- SEARCH FOR FIELD:
**<span style="background:yellow">\<Enter\></span>**

   IF: **<span style="background:yellow">A&B</span>**

   OR: **<span style="background:yellow">‘C&D</span>**

   OR: **<span style="background:yellow">\<Enter\></span>**

</div>

 

In the example above, the logic says “if **A** and **B**, or if *not*
**C** (but **D**)”.

### <span id="Step_3"></span><span id="_Toc527389069"></span><span id="_Hlt446381469"></span><span id="_Hlt446234101"></span>4.2.3<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Format Output

The remaining steps to finish your search are to choose your sorting
criteria (same as with printing) and to choose the fields to print for
each matched entry (also the same as with the printing).

A complete search (entering search conditions, combining search
conditions, and finishing the search) is shown in
<u><span style="color:blue">Figure 43</span></u>:

<span id="_Toc527389247"></span><span id="_Ref345579400">Figure</span>
43. Search—Dialogue to a Completed Search: Sample User Entries at
Prompts and Sample Report

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

Select VA FileMan Option: **<span style="background:yellow">SEARCH
\<Enter\></span>** File Entries

 

OUTPUT FROM WHAT FILE: PATIENT// **<span style="background:yellow">NEW
PERSON \<Enter\></span>** (88362 entries)

<img src="user-manual.fld/image031.png" data-border="0" width="173"
height="51"
alt="1. Enter search conditions. - Title: 1. Enter search conditions. - Description: 1. Enter search conditions." />

  -A- SEARCH FOR NEW PERSON FIELD:
**<span style="background:yellow">DATE ACCESS \<Enter\></span>** CODE
LAST CHANGED

  -A- CONDITION: **<span style="background:yellow">\> \<Enter\></span>**
GREATER THAN

  -A- GREATER THAN DATE: **<span style="background:yellow">T-50
\<Enter\></span>** (DEC 25, 2012)

 

  -B- SEARCH FOR NEW PERSON FIELD:
**<span style="background:yellow">ACCESS CODE</span>**

     1   ACCESS CODE

     2   ACCESS CODE  Want to edit ACCESS CODE (Y/N)

CHOOSE 1-2: **<span style="background:yellow">1 \<Enter\></span>**
ACCESS CODE

  -B- CONDITION: **<span style="background:yellow">‘NULL</span>**

 

  -C- SEARCH FOR NEW PERSON FIELD:
**<span style="background:yellow">\<Enter\></span>**

<img src="user-manual.fld/image032.png" data-border="0" width="175"
height="41"
alt="2. Combine search conditions. - Title: 2. Combine search conditions. - Description: 2. Combine search conditions." />

IF: **<span style="background:yellow">AB</span>**

       DATE ACCESS CODE LAST CHANGED GREATER THAN the entire day DEC
25,2012 (T-50) and ACCESS CODE NOT NULL

OR: **<span style="background:yellow">\<Enter\></span>**

 

STORE RESULTS OF SEARCH IN TEMPLATE:
**<span style="background:yellow">ACCESS CODE SEARCH</span>**

  Are you adding ‘ACCESS CODE SEARCH’ as a new SORT TEMPLATE? No//
**<span style="background:yellow">Y \<Enter\></span>** (Yes)

DESCRIPTION:

  No existing text

  Edit? NO// **<span style="background:yellow">\<Enter\></span>**

<img src="user-manual.fld/image033.png" data-border="0" width="135"
height="44"
alt="3. Choose sort order. - Title: 3. Choose sort order. - Description: 3. Choose sort order." />

SORT BY: NAME// **<span style="background:yellow">\<Enter\></span>**

START WITH NAME: FIRST//
**<span style="background:yellow">\<Enter\></span>**

<img src="user-manual.fld/image034.png" data-border="0" width="135"
height="38"
alt="4. Choose print fields. - Title: 4. Choose print fields. - Description: 4. Choose print fields." />

FIRST PRINT FIELD: **<span style="background:yellow">NAME</span>**

     1   NAME

     2   NAME COMPONENTS

CHOOSE 1-2: **<span style="background:yellow">1 \<Enter\></span>** NAME

THEN PRINT FIELD: **<span style="background:yellow">DATE ACCESS CODE
\<Enter\></span>** LAST CHANGED

THEN PRINT FIELD: **<span style="background:yellow">\<Enter\></span>**

Heading (S/C): NEW PERSON SEARCH//
**<span style="background:yellow">\<Enter\></span>**

DEVICE: **<span style="background:yellow">\<Enter\></span>** SSH VIRTUAL
TERMINAL    Right Margin: 80//
**<span style="background:yellow">\<Enter\></span>**

**<img src="user-manual.fld/image035.png" data-border="0" width="166"
height="39"
alt="5. Search results are printed. - Title: 5. Search results are printed. - Description: 5. Search results are printed." />**

 

NEW PERSON SEARCH                              FEB 13,2013  17:17   
PAGE 1

                                     DATE ACCESS

                                     CODE LAST

NAME                                 CHANGED

--------------------------------------------------------------------------------

 

FMPERSON,ONE                        FEB 13,2013

FMPERSON,TWO                        JAN 16,2013

 

 

                         2 MATCHES FOUND.

 

Press RETURN to continue...

</div>

 

The previous search (<u><span style="color:blue">Figure 43</span></u>)
found **two** entries that matched the search conditions (i.e., DATE
ACCESS CODE LAST CHANGED greater than **2/2/99** and ACCESS CODE *not*
**NULL**).

## <span id="_Toc527389070">4.3<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Details and Features</span>

### <span id="Sorting"></span><span id="_Toc527389071">4.3.1<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Sorting and Searching</span>

As you recall from the “<u><span style="color:blue">Print</span></u>”
section, you can print a subset of entries from a file by sorting
(i.e., printing only those entries that fall between a sort-from value
and a sort-to value). Searches also select a subset of entries from a
file, although with more flexibility than with sorting.

When you print your output from a search, you are also given a chance to
sort the output. This means that while searching selects a subset of
entries to print, through sorting you can further restrict that subset
of entries that is going to print. How does sorting affect the output of
the searches?

The answer is that VA FileMan uses *both* your search and sort order to
select entries. You enter the search criteria *before* you enter the
sort order. However, the selection of entries indicated in the sort
(“START WITH … GO TO” dialogue) sorting is done first, after which the
search conditions are applied to all remaining entries to determine the
final set of matching entries.

### <span id="_Toc527389072">4.3.2<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>SEARCH Templates</span>

You can save the results of your search in a SEARCH template. Doing this
allows you to:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Reuse your search criteria to perform another search.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Reuse your search results (the list of entries selected as
a result of both the search and the sort order).

This is because SEARCH templates store both your search criteria and
also the list of entries that is found in your search. SEARCH templates
are stored in the SORT TEMPLATE (#.401) file.

#### 4.3.2.1<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Creating SEARCH Templates

The place to save your search criteria and results in a SEARCH template
is right after you specify your search conditions. At this point, you
are prompted:

<span id="_Toc527389248">Figure</span> 44: Search—Creating a Search
Template

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

  STORE RESULTS OF SEARCH IN TEMPLATE:

</div>

 

You can create a template at this prompt. Because SEARCH templates are
stored in the same file as SORT templates (SORT TEMPLATE \[#.401\]), you
*cannot* give a SEARCH template the same name as a SORT template. To
avoid creating a SEARCH template, just press the **Enter** key at this
prompt. Usually, only the creator of a SEARCH template can use it.

#### 4.3.2.2<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Reusing Search Criteria Stored in a SEARCH Template

Whenever you do a search, you can reuse the search criteria (i.e., your
combined search conditions) stored in a SEARCH template. To do this,
enter the bracketed SEARCH template name at the first “SEARCH FOR
FIELD:” prompt:

<span id="_Toc527389249">Figure</span> 45: Search—Reusing a Search
Template at the “SEARCH FOR FIELD” Prompt

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

  -A- SEARCH FOR FIELD: **<span style="background:yellow">\[RESEARCH
1\]</span>**

</div>

 

A new search is performed with the recalled search criteria.

#### 4.3.2.3<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Reusing Search Results in another Search

Whenever you do a search, you can recall the results of a previous
search (the list of entries found in the search) at the “SORT BY:”
prompt. In this case, the new search is done against the entries in the
SEARCH template, rather than the entire file. Answer the “SORT BY:”
prompt with the bracketed SEARCH template name:

<span id="_Toc527389250">Figure</span> 46: Search—Reusing a Search
Template at the “SORT BY” Prompt

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

  SORT BY:  NAME// **<span style="background:yellow">\[RESEARCH
1\]</span>**

</div>

 

#### 4.3.2.4<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Reusing Search Results in a Print

When doing VA FileMan prints, you can also recall the results of a
previous search at the “SORT BY:” prompt. In this case, the entries
saved in the SEARCH template are the ones printed in the report. This is
handy if you do a search, collect a group of entries, and then want to
print several different reports based on the same set of entries.

### <span id="Internal_External"></span><span id="_Toc527389073">4.3.3<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Internal vs. External Field Values for Search Conditions</span>

The following are search conditions for specific DATA TYPE fields:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span> **SET OF CODES—**You *must* use external values for the
search conditions.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**DATE/TIME** and **COMPUTED** (that evaluate to
**DATE/TIME**)**—**You can enter internal or external values for the
search conditions.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**NUMERIC**, **COMPUTED** (that do *not* evaluate to
**DATE/TIME**), and **FREE TEXT—**There is no difference between
internal and external value.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**POINTER TO A FILE** or **VARIABLE-POINTER—**The sort is
based on the field type of the **.01** field of the pointed-to file.

### <span id="Matches"></span><span id="_Toc527389074">4.3.4<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Print Number of Matches Found</span>

If you only want to print the number of matches found, *without*
printing any of the matched entries, answer the “FIRST PRINT FIELD:”
prompt by simply pressing the **Enter** key.

### <span id="_Toc527389075">4.3.5<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Searching Multiples</span>

Searching on Multiple-valued fields, like the DIAGNOSIS field in the
PATIENT (#2) file, is a special situation. You *must* specify whether a
truth test is to be considered met if *at least one* of the subentries
for an entry passes the test or if *all* the subentries *must* pass the
test.

When truth tests contain a negative (contains a single quote), you can
even specify that an entry with *no* subentries should automatically
pass the test.

For example, suppose that you want to search for all patients who were
born before **1920** and who *do not* have a DIAGNOSIS containing the
word ANGINA, as shown in <u><span style="color:blue">Figure
47</span></u>:

<span id="_Toc527389251"></span><span id="_Ref446319571">Figure</span>
47: Search—Dialogue of a Search on a Multiple Field: Sample User Entries
at Prompts

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

Select VA FileMan Option: **<span style="background:yellow">SEARCH
\<Enter\></span>** File Entries

 

OUTPUT FROM WHAT FILE: PATIENT//
**<span style="background:yellow">\<Enter\></span>**

 

  -A- SEARCH FOR PATIENT FIELD: **<span style="background:yellow">DATE
OF BIRTH</span>**

  -A- CONDITION: **<span style="background:yellow">\< \<Enter\></span>**
LESS THAN

  -A- LESS THAN DATE: **<span style="background:yellow">1920
\<Enter\></span>** (1920)

 

  -B- SEARCH FOR PATIENT FIELD:
**<span style="background:yellow">SERVICE CONNECTED</span>**

     1   <span style="background:aqua">SERVICE CONNECTED CONDITIONS    
(multiple)</span>

     2   SERVICE CONNECTED PERCENTAGE

     3   SERVICE CONNECTED?

CHOOSE 1-3: **<span style="background:yellow">1 \<Enter\></span>**
SERVICE CONNECTED CONDITIONS (multiple)

 

    -B- SEARCH FOR PATIENT SERVICE CONNECTED CONDITIONS SUB-FIELD:
**<span style="background:
yellow">SERVICE CONNECTED CONDITIONS</span>**

    -B- CONDITION: **<span style="background:yellow">\[
\<Enter\></span>** CONTAINS

    -B- CONTAINS: **<span style="background:yellow">ANGINA</span>**

 

    -C- SEARCH FOR PATIENT SERVICE CONNECTED CONDITIONS SUB-FIELD:
**<span style="background:
yellow">\<Enter\></span>**

 

  -C- SEARCH FOR PATIENT FIELD:
**<span style="background:yellow">\<Enter\></span>**

 

IF: **<span style="background:yellow">A&’B \<Enter\></span>**    DATE OF
BIRTH LESS THAN 1920 (1920)

                 and not PATIENT SERVICE CONNECTED CONDITIONS CONTAINS
(case-insensitive) “ANGINA”

 

DO YOU WANT THIS SEARCH SPECIFICATION TO BE CONSIDERED TRUE FOR
CONDITION -B-

        1) WHEN AT LEAST ONE OF THE ‘SERVICE CONNECTED CONDITIONS’
MULTIPLES SATISFIES IT

        2) WHEN ALL OF THE ‘SERVICE CONNECTED CONDITIONS’ MULTIPLES
SATISFY IT

        3) WHEN ALL OF THE ‘SERVICE CONNECTED CONDITIONS’ MULTIPLES
SATISFY IT,

                OR WHEN THERE ARE NO ‘SERVICE CONNECTED CONDITIONS’
MULTIPLES

 

    CHOOSE 1-3: 1// **<span style="background:yellow">3</span>**

 

 

OR:

 

STORE RESULTS OF SEARCH IN TEMPLATE:

</div>

 

For this example, choosing the following number means:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**1** = Find people born before **1920** who have *at
least one* SERVICE CONNECTED CONDITION that does *not* contain “ANGINA.”

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**2** = Find people born before **1920** who have *at
least one* SERVICE CONNECTED CONDITION and *none* containing “ANGINA.”

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**3** = Find people born before **1920** who either have
no SERVICE CONNECTED CONDITION at all or whose SERVICE CONNECTED
CONDITIONs do *not* contain “ANGINA.”

Another ambiguity about searches of multiple fields is how to interpret
two separate truth tests on the same subfield.

For example, if you are searching for DIAGNOSIS containing **ANGINA**
and also for DIAGNOSIS containing **PECTORIS**, do you want to find:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Only those patients who have **ANGINA** *and* **PECTORIS**
in the *same* diagnosis name?

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Patients who might have one diagnosis containing
**ANGINA** and a *different* diagnosis containing **PECTORIS**?

Whenever you combine two truth tests (e.g., **A** and **B**) pertaining
to the same Multiple-valued field, you are prompted with the following:

<span id="_Toc527389252"></span><span id="_Ref446319586">Figure</span>
48: Search—Prompts Encountered when Searching on a Multiple Field

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

CONDITION -A- WILL APPLY TO THE SAME MULTIPLE AS CONDITION -B-

OK? YES//

</div>

 

In this example (<u><span style="color:blue">Figure 47</span></u> and
<u><span style="color:blue">Figure 48</span></u>), a **YES** answer
means that **ANGINA** and **PECTORIS** *must* be found in the *same*
DIAGNOSIS. If you answer **NO**, you can specify how **A** and **B**
apply:<span id="_Hlt446381562"></span>

<span id="_Toc527389253">Figure</span> 49: Search—Additional Prompts
Encountered when Searching on a Multiple Field

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

DO YOU WANT THIS SEARCH SPECIFICATION TO BE CONSIDERED TRUE FOR
CONDITION -A-

 

        1) WHEN AT LEAST ONE OF THE ‘DIAGNOSIS’ MULTIPLES SATISFIES IT

 

        2) WHEN ALL OF THE ‘DIAGNOSIS’ MULTIPLES SATISFY IT

 

    CHOOSE 1-2: 1// **<span style="background:yellow">2</span>**

 

DO YOU WANT THIS SEARCH SPECIFICATION TO BE CONSIDERED TRUE FOR
CONDITION -B-

 

        1) WHEN AT LEAST ONE OF THE ‘DIAGNOSIS’ MULTIPLES SATISFIES IT

 

        2) WHEN ALL OF THE ‘DIAGNOSIS’ MULTIPLES SATISFY IT

 

    CHOOSE 1-2: 1// **<span style="background:yellow">\<Enter\></span>**

</div>

<span id="_Hlt446233975"></span> 

In this case, all the diagnoses would need to satisfy the **A**
condition, but only **one** (or more) would need to satisfy the **B**
condition.

<img src="user-manual.fld/image002.png" id="Picture 100" data-border="0"
width="22" height="22" alt="Note" /><span style="font-size:10.0pt">    
</span>**NOTE:** Applying search tests to fields in a Multiple selects
entries at the top-level of the file. VA FileMan’s searching features
*cannot* be used to select specific subentries.

<span id="_Hlt446232243"></span> 

# <span id="_Ref446306852"></span><span id="_Ref446310607"></span><span id="_Toc527389076"></span><span id="_Hlt446217660"></span><span id="_Hlt446292370"></span>5<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Browser

If your site is using Kernel, your site manager may have set up an
output device called **BROWSER**. If so, you can view any report *on the
screen* instead of *on paper*. Do this by printing your report to the
**BROWSER** device instead of the **HOME** device or a printer.

The Browser makes it very easy to view reports on screen. Its main
features are:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Scroll forwards *and backwards* through a report. This
means you do *not* lose reports “off the top” of the screen, like you do
when you print to the **HOME** device.

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Use the Search feature to find and immediately jump to any
text in a report.

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Copy text from the report to the VA FileMan clipboard;
later, if you are editing a mail message or other WORD-PROCESSING-type
field with the Screen E<span id="_Hlt446147907">d</span>itor, you can
paste from the clipboard.

<img src="user-manual.fld/image002.png" id="Picture 101" data-border="0"
width="22" height="22" alt="Note" /><span style="font-size:10.0pt">    
</span>**REF:** For more information on the Screen Editor, see the
“<u><span style="color:blue">Screen Editor</span></u>” section.

As you become accustomed to using the **BROWSER** device, you may find
that you start to save paper by viewing reports that otherwise you would
end up printing.

The [**Browser** \[DDBROWSER\]](#browser_option) option lets you browse
the contents of any WORD-PROCESSING-type field to which you have access.

## <span id="Screen"></span><span id="_Toc527389077">5.1<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Browser Screen</span>

<span id="_Hlt446205186"></span><span id="_Hlt446223728"></span><u><span style="color:blue">Figure
50</span></u> illustrates the Browser screen:

<span id="_Toc527389254"></span><span id="_Ref345583273">Figure</span>
50: <span id="_Hlt446224169">Browser—Sample Screen</span> Component
Parts

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
background:black;margin-left:9.35pt;margin-right:9.35pt">

<span style="color:white">                             
EXAMPLE                                </span>

<img src="user-manual.fld/image036.png" data-border="0" width="312"
height="40"
alt="Header Line: Shows the name of the current document. - Title: Header Line: Shows the name of the current document. - Description: Header Line: Shows the name of the current document." />

THIS IS LINE 1

THIS IS LINE 2

THIS IS LINE 3

THIS IS LINE 4

THIS IS LINE 5

THIS IS LINE 6

THIS IS LINE 7

THIS IS LINE 8

THIS IS LINE 9

THIS IS LINE 10

THIS IS LINE 11

THIS IS LINE 12

THIS IS LINE 13

THIS IS LINE 14

THIS IS LINE 15

THIS IS LINE 16

THIS IS LINE 17

THIS IS LINE 18

THIS IS LINE 19

THIS IS LINE 20

THIS IS LINE 21

THIS IS LINE 22

<img src="user-manual.fld/image037.png" data-border="0" width="69"
height="64"
alt="Leftmost column. - Title: Leftmost column. - Description: Leftmost column." /><img src="user-manual.fld/image038.png" data-border="0" width="94"
height="88"
alt="Keystroke reminder for accessing help and exiting. - Title: Keystroke reminder for accessing help and exiting. - Description: Keystroke reminder for accessing help and exiting." /><img src="user-manual.fld/image039.png" data-border="0" width="67"
height="48"
alt="Current line. - Title: Current line. - Description: Current line." /><img src="user-manual.fld/image040.png" data-border="0" width="66"
height="110"
alt="Total number of lines. - Title: Total number of lines. - Description: Total number of lines." /><img src="user-manual.fld/image041.png" data-border="0" width="69"
height="63"
alt="Current screen. - Title: Current screen. - Description: Current screen." /><img src="user-manual.fld/image042.png" data-border="0" width="72"
height="87"
alt="Total number of screens. - Title: Total number of screens. - Description: Total number of screens." />

<span style="color:white">Col\>   1 \|\<PF1\>H=Help \<PF1\>E=Exit\|
Line\>    22 of 300  Screen\>     1 of 14  </span>

</div>

 

## <span id="_Toc527389078">5.2<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Browser Features</span>

The following Browser features are described below:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>[Navigation
Keystrokes](#command_keystrokes)<span id="_Hlt446148020"></span>

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>[Clipboard](#clipboard)<span id="_Hlt446148022"></span>

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>[Search](#search)<span id="_Hlt446148024"></span>

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>[Online
Help](#online_help)<span id="_Hlt446148026"></span>

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>[Other
Features](#special_features)<span id="_Hlt446148028"></span>

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>[Browser as an Option](#browser_option)

### <span id="command_keystrokes"></span><span id="_Toc527389079"></span><span id="_Hlt446148021"></span>5.2.1<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Navigation Keystrokes

<span id="_Hlt446224772"></span><u><span style="color:blue">Table
6</span></u> lists the keystrokes you use to navigate while in the
Browser (i.e., cursor movement):

<span id="_Toc527389330"></span><span id="_Ref345509562">Table</span> 6:
Browser—Navigation Keystrokes

<table class="MsoNormalTable" data-border="1" data-cellspacing="0"
data-cellpadding="0"
style="margin-left:1.15pt;border-collapse:collapse;border:none">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header" style="page-break-inside:avoid">
<th width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="COL001_TBL007"></span>To</p></th>
<th width="468" data-valign="top"
style="width: 351.0pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Press</p></th>
</tr>
</thead>
<tbody>
<tr class="odd" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Scroll
Up or Down One Line at a Time</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;ArrowUp&gt;</strong>
and <strong>&lt;ArrowDown&gt;</strong></p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Scroll
Right <strong>22</strong> columns</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;ArrowRight&gt;</strong></p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Scroll
to Rightmost Edge</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;&lt;ArrowRight&gt;</strong></p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Scroll
Left <strong>22</strong> Columns</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;ArrowLeft&gt;</strong></p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Scroll
to Leftmost Edge</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;&lt;ArrowLeft&gt;</strong></p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Page
Down</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;&lt;ArrowDown&gt;</strong>,
<strong>&lt;NextScreen&gt;</strong>, or
<strong>&lt;PageDown&gt;</strong></p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Page
Up</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;&lt;ArrowUp&gt;</strong>,
<strong>&lt;PrevScreen&gt;</strong>, or
<strong>&lt;PageUp&gt;</strong></p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Go
to Top</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;T</strong></p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Go
to Bottom</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;B</strong></p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Go
to Specific Line, Screen, or Column</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;G</strong></p>
<p>At prompt, enter a number, which you can precede with any of the
following:</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span><strong>S—</strong>Screen</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span><strong>L</strong>—Line</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span><strong>C—</strong>Column</p>
<p>The cursor is re-positioned at the corresponding screen, line, or
column. If you enter a number only, screen is assumed.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Exit</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;E</strong>
or <strong>&lt;PF1&gt;Q</strong> or <strong>CTRL - E</strong></p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Print</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;&lt;PF1&gt;P</strong></p></td>
</tr>
</tbody>
</table>

 

### <span id="clipboard"></span><span id="_Toc527389080"></span><span id="_Hlt446148023"></span>5.2.2<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Clipboard

<u><span style="color:blue">Table 7</span></u> lists the keystrokes you
use to work with the Browser’s clipboard:

<span id="_Toc527389331"></span><span id="_Ref345583174">Table</span> 7:
Browser—Using the Browser Clipboard

<table class="MsoNormalTable" data-border="1" data-cellspacing="0"
data-cellpadding="0"
style="margin-left:1.15pt;border-collapse:collapse;border:none">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header" style="page-break-inside:avoid">
<th width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="COL001_TBL008"></span>To</p></th>
<th width="468" data-valign="top"
style="width: 351.0pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Press</p></th>
</tr>
</thead>
<tbody>
<tr class="odd" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Copy
Text to the VA FileMan Clipboard</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;C</strong></p>
<p>At the “Copy Text Line(s) to Paste Buffer &gt;" prompt, specify the
lines in the document to copy. You can enter:</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span><strong>#:#—</strong>For example, <strong>3:10</strong>
would copy text from line <strong>3</strong> to line <strong>10</strong>
in the document, and make that the contents of the clipboard.</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span><strong>#:#A—</strong>The <strong>A</strong> means append.
For example, <strong>3:10A</strong> would copy text from line
<strong>3</strong> to line <strong>10</strong> in the document and
append it to any existing text in the clipboard.</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span><strong>*—</strong>Entering <strong>*</strong> copies all
text in the document to the clipboard.</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span><strong>*A—</strong>The <strong>A</strong> means append.
Entering <strong>*A</strong> appends all text in the document to any
existing text in the clipboard.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>View
Contents of the Clipboard</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;V</strong></p>
<p>This lets you view the current contents of the VA FileMan clipboard.
To switch back to your document, enter
<strong>&lt;PF1&gt;E</strong>.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Paste
Text from the Clipboard</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>In
VA FileMan’s Screen E<span id="_Hlt446148055">d</span>itor, you can
paste the contents of the VA FileMan clipboard by entering
<strong>&lt;PF1&gt;V</strong>.</p>
<p><img src="user-manual.fld/image002.png" id="Picture 102"
data-border="0" width="22" height="22" alt="Note" />
<strong>REF:</strong> For more information on the Screen Editor, see the
“</p>
<p><u><span style="color:blue">Screen </span></u>Editor”
section.</p></td>
</tr>
</tbody>
</table>

 

### <span id="search"></span><span id="_Toc527389081"></span><span id="_Hlt446148025"></span>5.2.3<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Search

<u><span style="color:blue">Table 8</span></u> lists the keystrokes you
use to search for text in the Browser:

<span id="_Toc527389332"></span><span id="_Ref345582919">Table</span> 8:
Browser—Searching in the Browser

<table class="MsoNormalTable" data-border="1" data-cellspacing="0"
data-cellpadding="0"
style="margin-left:1.15pt;border-collapse:collapse;border:none">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header" style="page-break-inside:avoid">
<th width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="COL001_TBL009"></span>To</p></th>
<th width="468" data-valign="top"
style="width: 351.0pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Press</p></th>
</tr>
</thead>
<tbody>
<tr class="odd" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Find
a String or Characters</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;F</strong>
or <strong>&lt;FIND&gt;</strong></p>
<p>At the prompt, enter the string to find. You can specify the
direction of the search by ending your <strong>FIND</strong> string with
the <strong>&lt;ArrowUp&gt;</strong> or
<strong>&lt;ArrowDown&gt;</strong>. If you just press the
<strong>Enter</strong> key after the find string, the search direction
is down.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Next
Find</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;N</strong></p>
<p>Finds the next occurrence of the search string from a previous
<strong>FIND</strong> request.</p></td>
</tr>
</tbody>
</table>

 

### <span id="online_help"></span><span id="_Toc527389082"></span><span id="_Hlt446148027"></span>5.2.4<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Online Help

<u><span style="color:blue">Table 9</span></u> lists the keystrokes you
use to display and print help information in the Browser:

<span id="_Toc527389333"></span><span id="_Ref345582937">Table</span> 9:
Browser—Online Help

<table class="MsoNormalTable" data-border="1" data-cellspacing="0"
data-cellpadding="0"
style="margin-left:1.15pt;border-collapse:collapse;border:none">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header" style="page-break-inside:avoid">
<th width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="COL001_TBL010"></span>To</p></th>
<th width="468" data-valign="top"
style="width: 351.0pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Press</p></th>
</tr>
</thead>
<tbody>
<tr class="odd" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Get
Help</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;H</strong>
for Help Summary.</p>
<p><strong>&lt;PF1&gt;&lt;PF1&gt;H</strong> for more help.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Print
Help</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;&lt;PF1&gt;&lt;PF1&gt;H</strong></p>
<p>This prints the online help text.</p></td>
</tr>
</tbody>
</table>

 

### <span id="special_features"></span><span id="_Toc527389083"></span><span id="_Hlt446148030"></span>5.2.5<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Other Features

<span id="_Hlt446204953"></span><u><span style="color:blue">Table
10</span></u> lists the keystrokes you use to perform miscellaneous
tasks in the Browser:

<span id="_Toc527389334"></span><span id="_Ref445783452">Table</span>
10: Browser—Other Features

<table class="MsoNormalTable" data-border="1" data-cellspacing="0"
data-cellpadding="0"
style="margin-left:1.15pt;border-collapse:collapse;border:none">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header" style="page-break-inside:avoid">
<th width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="COL001_TBL011"></span>To</p></th>
<th width="468" data-valign="top"
style="width: 351.0pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Press</p></th>
</tr>
</thead>
<tbody>
<tr class="odd" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Repaint
the Screen</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;P</strong></p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Print
the Document</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;&lt;PF1&gt;P</strong></p>
<p>This feature allows you to print the document currently being
displayed in the Browser. You can choose to print a header on each page,
which includes:</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>Document title</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>Current date and time</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">       </span></span>Page
number</p>
<p>You can also choose whether to print the document in word wrap mode
and whether to have word-processing windows (<strong>|</strong>)
interpreted.</p>
<p><img src="user-manual.fld/image002.png" id="Picture 323"
data-border="0" width="22" height="22"
alt="Note" /> <strong>NOTE:</strong> This feature was released with
Patch DI*22.0*169.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Change
the Document Title in the Browser Header Line</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;&lt;PF1&gt;&lt;ArrowDown&gt;</strong>
or</p>
<p><strong>&lt;PF1&gt;&lt;PF1&gt;&lt;ArrowUp&gt;</strong></p>
<p>This feature lets you change the text in the Browser’s header to some
line in your report. Each time you press
<strong>&lt;PF1&gt;&lt;PF1&gt;&lt;ArrowDown&gt;</strong> you set the
Browser header line to the text of the next line down in your document
(and vice-versa for
<strong>&lt;PF1&gt;&lt;PF1&gt;&lt;ArrowUp&gt;</strong>).</p>
<p>Typically, you might want to set the Browser’s header line to the
text in your report’s header that contains field names for your report’s
data. You might need to press
<strong>&lt;PF1&gt;&lt;PF1&gt;&lt;ArrowDown&gt;</strong> four or five
times to get to your report’s field header line. Then, as you scroll
through your report, the Browser header line contains the field names
that match and help identify the data through which you are
scrolling.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Switch
to another Document</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;S</strong></p>
<p>Adds another document to the active list of documents and switches to
it. Choose another VA FileMan file, field, and entry for the document to
switch to.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Return
to Previous Document (after having switched at least once)</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Press
<strong>R</strong></p>
<p>Pressed repeatedly, <strong>R</strong> returns you all the way back
to your first document.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Split
Screen (while in Full Screen Mode)</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF2&gt;S</strong></p>
<p>Screen splits into <strong>two</strong> separate scroll
regions.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Move
Cursor to Lower Screen (in Split Screen Mode)</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF2&gt;
&lt;ArrowDown&gt;</strong></p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Move
Cursor to Upper Screen (in Split Screen Mode)</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF2&gt;&lt;ArrowUp&gt;</strong></p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Resize
screens (in Split Screen Mode)</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF2&gt;&lt;PF2&gt;&lt;ArrowUp&gt;</strong>
and</p>
<p><strong>&lt;PF2&gt;&lt;PF2&gt;&lt;ArrowDown&gt;</strong></p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="156" data-valign="top"
style="width: 117.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Return
to Full Screen from Split Screen Mode</p></td>
<td width="468" data-valign="top"
style="width: 351.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF2&gt;F</strong></p></td>
</tr>
</tbody>
</table>

 

### <span id="browser_option"></span><span id="_Toc527389084"></span><span id="_Hlt446148015"></span>5.2.6<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Browser as an Option

As well as being able send output to the **BROWSER** device, you can use
the VA FileMan
**<span style="color:windowtext">Browser</span>**<span style="color:windowtext"> \[DDBROWSER</span><span style="color:windowtext">\]</span>
option, located under the **Other Options** \[DIOTHER\] menu on the **VA
FileMan** \[DIUSER\] main menu, to view the contents of any
WORD-PROCESSING-type field that you have access to in the database. When
you use the
**<span style="color:windowtext">Browser</span>**<span style="color:windowtext"> \[DDBROWSER</span><span style="color:windowtext">\]</span>
option, you are prompted for the following:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>File

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>WORD-PROCESSING field

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Entry to view

By answering these prompts, you can view the contents of any accessible
WORD-PROCESSING field in the Browser.

 

# <span id="_Ref446308660"></span><span id="_Ref446310271"></span><span id="_Ref446310623"></span><span id="_Toc527389085"></span><span id="_Hlt446217678"></span>6<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>VA FileMan Prompts

<span id="_Hlt446218504"></span>Many VA VistA application packages have
a *Scrolling Mode* interface. Scrolling Mode works as follows:

1.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Computer puts a prompt on the screen.

2.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>User
enters a response to the prompt.

3.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Computer places another prompt on the screen, scrolling down one
line. Previous prompts move up and eventually off of the screen.

In Scrolling Mode, prompting occurs in the same predetermined order, in
a sequence designed by the application developer. You enter a value and
the computer stores your responses one at a time. And, unless you are
familiar with a few timesaving scrolling mode techniques, you have to
step through each prompt in a record before you can finish editing the
record.

Recently developed VistA applications often use a *screen-oriented*
interface (i.e., Screen Mode) for editing data. However, scrolling mode
interfaces are still used quite heavily in VistA applications.

<img src="user-manual.fld/image002.png" id="Picture 103" data-border="0"
width="22" height="22" alt="Note" /><span style="font-size:10.0pt">    
</span>**REF:** For more information on Screen Mode, see the
“<u><span style="color:blue">ScreenMan</span></u>” section.

After reading about a few of the Scrolling Mode operations discussed in
this section, you should be able to enter and edit data in Scrolling
Mode with a minimum number of keystrokes.

<img src="user-manual.fld/image002.png" id="Picture 324" data-border="0"
width="22" height="22" alt="Note" />     **NOTE:** VA FileMan is in the
process of converting all *non*-developer dialogues to use VA FileMan
(FM) dialogues framework, so that translations can be table-driven.

## <span id="ret"></span><span id="enter_key"></span><span id="_Toc527389086"></span><span id="_Hlt446148108"></span>6.1<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>The \<Enter\> Key

To enter data in scrolling mode, you primarily enter data or commands at
a prompt on your terminal screen. After typing a command or data at your
terminal keyboard, you *must* send your response from your terminal to
the computer. Pressing the **Enter** key on your keyboard (abbreviated
as **\<Enter\>** in examples) sends all of your typed input to the
computer for action or storage.

<img src="user-manual.fld/image002.png" id="Picture 104" data-border="0"
width="22" height="22" alt="Note" />     **NOTE:** Some older
documentation examples still refer to it as the **Return** key (shown as
**\<RET\>** in examples).

If you type a response but fail to press the **Enter** key, the computer
waits; it does *not* do anything until you indicate that you have
finished entering your response. Pressing the **Enter** key also
indicates to the computer when you have decided to “enter” nothing at
all. Whenever you press the **Enter** key without first entering data or
a command, you indicate to the computer either to avoid taking action or
to take the default action at the current prompt. The computer then
moves on to the next prompt.

<img src="user-manual.fld/image002.png" id="Picture 325" data-border="0"
width="22" height="22" alt="Note" />     **NOTE:** Some prompts require
a user response; so, if you only press the **Enter** key *without* a
valid response, the system continues to repeat the prompt until you
respond with a valid value.

## <span id="structure"></span><span id="_Toc527389087">6.2<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Standard Prompt Structure</span>

The standard VA FileMan prompt consists of three parts:

<span id="_Toc527389255">Figure</span> 51: VA FileMan Prompts—Sample
Component Parts of a Prompt

<img src="user-manual.fld/image043.png" id="Picture 105" data-border="0"
width="408" height="219"
alt="Title: VA FileMan Prompts—Sample Component Parts of a Prompt - Description: VA FileMan Prompts—Sample component parts of a prompt: 1) System Prompt; 2) Default Response; and 3) User Response Sample: NAME: FMUSER,ONE// FMUSER,TWO 1) &quot;NAME:&quot; This is the prompt question. It could be the name of a record you mihgt edit. 2) &quot;FMUSER,ONE//&quot;: This part of the prompt is optional and does not always appear, since it is VA FileMan&#39;s default value. Simply press the Enter key &lt;Enter&gt; here, if this is the value you want. 3) &quot;FMUSER,TWO&quot;: This is a response entered by the user, and it now becomes the default value for this record." />

 

## <span id="responding"></span><span id="_Toc527389088">6.3<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Responding to Prompts</span>

When VA FileMan prompts you for a response, typically, a colon (**:**)
is used at the end of the prompt; the computer waits for a response.
Prompts are often asking for the value of a field in a file, like the
one shown in <u><span style="color:blue">Figure 52</span></u>:

<span id="_Toc527389256"></span><span id="_Ref523837130">Figure</span>
52: VA FileMan Prompts—Asking for a Response

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    DATE OF BIRTH:

</div>

 

This type of prompt is waiting for you to enter a value (e.g., **3 OCT
49**). Do *not* forget to press the **Enter** key
([**\<Enter\>**](#enter_key)) to complete your interaction.

If the answer to the prompt question is a choice of several things, the
prompt often starts with the word “**Select**”, as in
<u><span style="color:blue">Figure 53</span></u>:

<span id="_Toc527389257"></span><span id="_Ref523837145">Figure</span>
53: VA FileMan Prompts—“Select-type” Prompts, Offering a Choice

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    Select PATIENT NAME:

</div>

 

If the question requires either a **YES** or **NO** response (in which
case simply entering **Y** or **N**, upper- or lowercase, is
acceptable), the prompt can end with a question mark, rather than by a
colon, as shown in <u><span style="color:blue">Figure 54</span></u>:

<span id="_Toc527389258"></span><span id="_Ref523837169">Figure</span>
54: VA FileMan Prompts—“Yes/No-type” Prompts

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    ARE YOU SURE?

</div>

 

<img src="user-manual.fld/image002.png" id="Picture 106" data-border="0"
width="22" height="22" alt="Note" /><span style="font-size:10.0pt">    
</span>**REF:** For more information on the specific types of fields
(DATE/TIME, NUMERIC, WORD-PROCESSING, FREE TEXT, etc.) and how to edit
them, see the “<u><span style="color:blue">Field Types</span></u>”
section.

## <span id="help"></span><span id="_Toc527389089">6.4<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Getting Online Help at Any Prompt (Enter ? or ??)</span>

If you are *not* sure how to answer a prompt, help is always available.
Just enter one question mark (**?**) to get brief help, or two question
marks (**??**) to get more detailed online help:

<span id="_Toc527389335">Table</span> 11: VA FileMan Prompts—Getting
Online Help at any Prompts Using Question Marks

| <span id="COL001_TBL012"></span>Help Value | Description                                                                                                                                                                                                |
|--------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **?**                                      | Entering **one** question mark at a prompt gets a single line of help.                                                                                                                                     |
| **??**                                     | Entering **two** question marks at a prompt gets more detailed help: a description of what values are acceptable, and/or a list of choices appropriate to the prompt where you entered the question marks. |

 

## <span id="incorrect"></span><span id="_Toc527389090">6.5<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Incorrect Responses</span>

VA FileMan checks each answer to a prompt immediately after you enter
it. If you answer a prompt incorrectly, VA FileMan “beeps,” and displays
**two** spaces and **two** question marks. You may be given an
explanation of what was incorrect. Then, you are given a chance to
respond to the prompt again.

## <span id="partial"></span><span id="_Toc527389091">6.6<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Partial Responses</span>

When you are choosing one of a set of responses, you can save keystrokes
by *not* typing the full response. Type in only the first letter of
first few letters representing the response that you desire. If the
characters you enter uniquely identify one of the possible acceptable
responses, VA FileMan “echoes back” the remaining characters and uses
the matching choice as your response.

If more than one possible answer begins with the characters that you
typed, VA FileMan displays the possible choices in a list, and asks you
to choose which choice you want by number:

<span id="_Toc527389259"></span><span id="_Ref345588389">Figure</span>
55: VA FileMan Prompts—Dialogue to Choose from a List in VA FileMan:
Sample User Entries at Prompts

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

<img src="user-manual.fld/image044.png" data-border="0" width="360"
height="73"
alt="Because S matches two choices at the “OPTION:” prompt, a list of matching choices is returned. You can choose by number which choice you want. - Title: Because S matches two choices at the “OPTION:” prompt, a list of matching choices is returned. You can choose by number which choice you want. - Description: Because S matches two choices at the “OPTION:” prompt, a list of matching choices is returned. You can choose by number which choice you want." />

OPTION: **<span style="background:yellow">S</span>**

     1   ScreenMan

     2   Statistics

CHOOSE 1-3: **<span style="background:yellow">1 \<Enter\></span>**
ScreenMan

 

</div>

 

## <span id="default"></span><span id="_Toc527389092">6.7<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Default Responses</span>

When working in VistA applications, the computer frequently presents a
*default* answer along with a prompt. This answer is built into the
application program and represents the most probable response to the
prompt that is being asked. These default answers are clearly identified
by the double slash marks that follow them (**//**). If the default
answer that is provided is correct, you need only press the **Enter**
key to accept it.

For example:

<span id="_Toc527389260">Figure</span> 56: VA FileMan Prompts—Prompts
with Default Responses

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    SSN: <span style="background:aqua">000123124</span>//

</div>

 

In this case, if you press the **Enter** key, **000123124** is posted as
your response to this prompt.

If, on the other hand, the default answer is *not* what you need, enter
the correct information at the prompt. For example:

<span id="_Toc527389261">Figure</span> 57: VA FileMan Prompts—Overriding
the Default Response to a Prompt

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    SSN: <span style="background:aqua">000123124</span>//
**<span style="background:yellow">000234563 \<Enter\></span>**

</div>

 

When editing data stored in fields, defaults are used to present the
current value of the field. As with any default prompt, if you just
press the **Enter** key, the current value of the field is left
unchanged. To change the value of the field, enter a new value and press
the **Enter** key.

## <span id="replace_with"></span><span id="_Toc527389093">6.8<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Longer Default Responses and the “Replace…With” Editor</span>

When a default is **20** or more characters in length, it is *not*
followed by double slashes (**//**). Instead, it is presented with a
“Replace” prompt:

<span id="_Toc527389262">Figure</span> 58: VA FileMan Prompts—Long
Responses Employing the “Replace...With” Editor

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    ADDRESS 1: 1 Main Street  Replace

</div>

 

The “Replace” prompt employs the “Replace...With” Editor. At the
“Replace” prompt, you can revise some or all of the existing default
answer. To revise only a piece of the existing default response, type in
any series of letters that are part of the existing default answer that
you want to change and then press the **Enter** key. At the “With”
prompt, enter the series of characters to replace the original series,
and press the **Enter** key. At this point, the “Replace” prompt is
presented again, so that you can enter additional corrections. If you
are all done, however, just press the **Enter** key to finish working in
the field and move on to the next prompt.

For example:

<span id="_Toc527389263">Figure</span> 59: VA FileMan Prompts—Changing a
Long Response Using the “Replace...With” Editor

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    ADDRESS 1: 1 Main Street  Replace
**<span style="background:yellow">Main \<Enter\></span>** With
**<span style="background:yellow">North \<Enter\></span>**

    Replace **<span style="background:yellow">\<Enter\></span>**

        1 North Street

    ADDRESS 2:

</div>

 

To replace the entire default answer at a “Replace...With” prompt,
simply enter **three** periods (**…**), called an ellipsis, at the
“Replace” prompt. You are then able to replace the entire default with
what you enter at the “With” prompt:

<span id="_Toc527389264">Figure</span> 60: VA FileMan Prompts—Replacing
an Entire Entry Using the Ellipsis (...)

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    ADDRESS 1: 1 Main Street  Replace
**<span style="background:yellow">... \<Enter\></span>** With
**<span style="background:yellow">1 North Street \<Enter\></span>**

      Replace **<span style="background:yellow">\<Enter\></span>**

       1 North Street

    ADDRESS 2:

</div>

 

If you want to delete the entire text, enter the at-sign (**@**) at the
“Replace” prompt:

<span id="_Toc527389265">Figure</span> 61: VA FileMan Prompts—Deleting
an Entire Entry Using the At-Sign (@)

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    ADDRESS 1: 1 Main Street  Replace
**<span style="background:yellow">@ \<Enter\></span>**

        SURE YOU WANT TO DELETE? **<span style="background:yellow">Y
\<Enter\></span>** (Yes)

    ADDRESS 2:

</div>

 

<img src="user-manual.fld/image002.png" id="Picture 107" data-border="0"
width="22" height="22" alt="Note" />     **NOTE:** The at-sign (**@**)
is the command in many places to signal deletion.

### <span id="_Toc527389094">6.8.1<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>“Replace...” Prompt Shortcuts</span>

<u><span style="color:blue">Table 12</span></u> lists shortcut responses
when entering data at the “Replace” prompt:

<span id="_Toc527389336"></span><span id="_Ref345582973">Table</span>
12: VA FileMan Prompts—“Replace” Prompt Shortcuts

| <span id="COL001_TBL013"></span>Shortcut | Action                                                                               |
|------------------------------------------|--------------------------------------------------------------------------------------|
| **...**                                  | Replaces everything.                                                                 |
| **xxx...**                               | Replaces everything starting from the characters ***xxx*** to the end.               |
| **...xxx**                               | Replaces everything from the beginning up to and including the characters ***xxx***. |
| **xxx...yyy**                            | Replaces everything starting from ***xxx*** up to and including ***yyy***.           |
| **end** or **END**                       | Appends what you enter at the “With” prompt to the end of the value.                 |

 

## <span id="list_prompts"></span><span id="_Toc527389095">6.9<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Prompts with a List of Choices</span>

If the acceptable answer to a field prompt is one of a set of choices,
you can display the list of choices by entering **one** or **two**
question marks. If that set of choices is short enough to be displayed
on five or six lines, the choices are listed when you enter **one**
question mark.

Here is an example:

<span id="_Toc527389266">Figure</span> 62: VA FileMan Prompts—Displaying
a List of Choices

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    Select PATIENT NAME: **<span style="background:yellow">?</span>**

    ANSWER WITH PATIENT NAME

    CHOOSE FROM:  

     FMPATIENT,SEVEN

     FMPATIENT,EIGHTEEN

     FMPATIENT,NINETEEN

    Answer must be 3-30 characters in length.

 

    Select PATIENT NAME:

</div>

 

When you enter **one** question mark (**?**) and the entry list is long,
you are asked if you want to see all the entries. Besides a **YES** or
**NO** response, you can enter a caret (**^**) followed by a string of
characters to see a list of all entries beginning with the one that
starts with those characters.

<u><span style="color:blue">Figure 63</span></u> shows selection of an
entry starting with an alpha character:

<span id="_Toc527389267"></span><span id="_Ref389661492">Figure</span>
63: VA FileMan Prompts—Displaying a Subset of Choices from a List

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    Select PATIENT NAME: **<span style="background:yellow">?</span>**

    ANSWER WITH PATIENT NAME, OR SSN

    DO YOU WANT THE ENTIRE 1890-ENTRY PATIENT LIST?
**<span style="background:yellow">^</span>F**

    CHOOSE FROM:

     FMPATIENT,20

     FMPATIENT,21

     FMPATIENT,22

     FMPATIENT,23

      ‘^’ TO STOP  **<span style="background:yellow">^</span>**

 

      YOU MAY ENTER A NEW PATIENT, IF YOU WISH

     Enter patient name in “Last, First Middle” format \[3-30
characters\].

 

    Select PATIENT NAME:

</div>

 

If you know the list is long and still want it to be displayed, you can
enter **two** question marks (**??**) to force the display of the entire
list.

## <span id="key_fields"></span><span id="_Toc527389096">6.10<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Key Fields</span><span id="_Hlt445716138"></span>

During a data entry session, VA FileMan checks that the combination of
fields that make up a key for a record is unique for all records in the
file. If a single field makes up a key, VA FileMan checks for uniqueness
as soon as that field is edited. If more than one field makes up a key
(i.e., compound key), VA FileMan checks that the combination of new key
field values is unique only at the end of the data entry session (unless
otherwise instructed in the software code by the developer). If a
compound key is *not* unique, VA FileMan restores the fields that make
up the key to their pre-edited values, and prints a message.

For example:

<span id="_Toc527389268">Figure</span> 64: VA FileMan Prompts—Entering a
Duplicate Compound Key

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

Select ZZTEST NAME: **<span style="background:yellow">\`16
\<Enter\></span>** FMPATIENT,THREE  9900  SEP 03, 1932

ID NUMBER: 9900// **<span style="background:yellow">9800</span>**

DATE: SEP 3,1932// **<span style="background:yellow">1/21/1932
\<Enter\></span>** (JAN 21, 1932)

 

\*\*\*\*\*  NOTE  \*\*\*\*\*

 

Some of the previous edits are not valid because they create one or more

duplicate keys.  Some fields have been restored to their pre-edited

values.

 

Do you want to see a list of those fields? YES//
**<span style="background:yellow">\<Enter\></span>**

 

The following field(s) have been restored to their pre-edited values:

 

File: ZZTEST File (#16999)

  Key: A

    Record: ‘FMPATIENT,THREE’ (#16)

 

              Field: ID NUMBER(#1)

      Invalid value: 9800

        Restored to: 9900

 

              Field: DATE (#2)

      Invalid value: JAN 21, 1932

        Restored to: SEP 03, 1932

</div>

 

## <span id="special"></span><span id="_Toc527389097">6.11<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Special Responses to Field Prompts</span>

### <span id="_Toc527389098">6.11.1<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Deleting a Field’s Value (</span><span id="_Hlt445716140">@</span>)

When you want to delete an answer previously entered, without
substituting any other answer, enter an at-sign (**@**) as a response to
that prompt:

<span id="_Toc527389269">Figure</span> 65: VA FileMan Prompts—Deleting a
Field Entry

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    DATE OF BIRTH:  May 21, 1946//
**<span style="background:yellow">@</span>**

SURE YOU WANT TO DELETE? **<span style="background:yellow">YES</span>**

</div>

 

In this example, the date on file would be erased: there is no answer to
the DATE OF BIRTH question; its value is now **NULL**. You are asked to
confirm the deletion; this gives you a chance to change your mind before
deleting the field.

### <span id="_Toc527389099"></span><span id="jumping">6.11.2<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Jumping to another Field with the</span> Caret (^)

If you fail to notice a typing error until after you pressed the
**Enter** key and stored a field, you can still correct this error. What
you need to do is go back to the field where the error occurred. You can
usually accomplish this by using the *jump* command. This command
requires entering a caret (**^**) along with the name, or first few
letters, of the field to which you wish to jump. Instead of moving to
the next prompt, you jump to the prompt you identified, as shown in
<u><span style="color:blue">Figure 66</span></u>:

<span id="_Toc527389270"></span><span id="_Ref523839079">Figure</span>
66: VA FileMan Prompts—Using the Caret (^) Key to “Jump” to a Specific
Field

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    SSN:  000123123// **<span style="background:yellow">^DATE OF
BIRTH</span>**

    DATE OF BIRTH:

</div>

 

To get a list of the fields to which you can jump, enter a caret and a
question mark (**^?**) at any field prompt.

You can use the caret to jump both forward and backward in a sequence of
fields.

<img src="user-manual.fld/image045.png" data-border="0" width="14"
height="43" alt="Tip" /> **TIP:** Sometimes, you may only need to update
one field in a record. You can jump directly to that field once you
start to edit that record. This can save time; you do not need to go
through every field and prompt that precedes the one you want!

<img src="user-manual.fld/image002.png" id="Picture 109" data-border="0"
width="22" height="22" alt="Note" />     **NOTE:** The caret (**^**) is
sometimes referred to as the *up-arrow* in some legacy documentation.

### <span id="_Toc527389100"></span><span id="up_arrow">6.11.3<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Exiting with the Single Caret</span> (^)

To exit or opt out of answering any question or prompt, enter the caret
(**^**) by itself at the field prompt, as in
<u><span style="color:blue">Figure 67</span></u>:

<span id="_Toc527389271"></span><span id="_Ref523840324">Figure</span>
67: VA FileMan Prompts—Using the Caret (^) Key to Exit a Prompt

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    SSN: 000123123// **<span style="background:yellow">^</span>**

    Select PATIENT NAME:

</div>

 

In the previous example, the field value **000123123** remains
unchanged, but you skip the rest of the questions for this record and
return to the “Select...” prompt. If you enter a caret (**^**) at the
“Select...” prompt, you return to the previous prompt, and so on.

Entering the caret (**^**) by itself to exit a given function is a
convention used throughout VistA applications.

### <span id="_Toc527389101"></span><span id="_Hlt457871798"></span>6.11.4<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Exiting w<span id="_Hlt457871603"></span>ith the Double Caret (^^)

When the user is doing a lookup to the file, VA FileMan may search many
indexes looking for a value that matches the users input. This can be
time consuming. If the user wants to get out of the lookup before VA
FileMan has completed the search, the user can enter two carets (**^^**)
at any prompt.

### <span id="mandatory"></span><span id="_Toc527389102">6.11.5<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Mandatory (Required) Fields</span>

<span id="_Hlt457872373"></span>In some cases a field is *mandatory*,
and you *must* enter a value, if one is *not* already there; in other
words, a **NULL** response (i.e., pressing the **Enter** key *without*
making an entry) is *not* valid. When you use the caret (**^**) or press
the **Enter** key *without* entering data in one or more fields in the
entry, your terminal “beeps” and prompts you again to enter information.

If you do *not* fill in all required fields in a record, it is
considered incomplete, and is *not* stored unless you fill in the
required fields. This protects the database from records containing so
little information that they are useless. Enter the requested
information.

If you still need to exit before you can provide all required
information, you should abort your edit and start over later. You can
usually exit out of the data editing sequence by answering any of the
prompts with a caret (**^**).

### <span id="spacebar"></span><span id="_Toc527389103">6.11.6<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Spacebar Recall</span>

VA FileMan can recall your most recent response to a prompt. This
feature is called **Spacebar Recall** and employs the **Spacebar** and
**Enter** keys. For example, if you are editing a particular patient in
a Nursing application and then switch to the Order/Entry application to
work with the same patient, you can usually retrieve the same patient by
pressing the **Spacebar** *and* **Enter** keys
(**\<Spacebar\>\<Enter\>**) at the second application’s (Order/Entry)
“Select PATIENT NAME:” prompt.

For example:

<span id="_Toc527389272">Figure</span> 68: VA FileMan Prompts—Using the
“Spacebar Recall” Functionality

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    Select PATIENT NAME:
**<span style="background:yellow">\<Spacebar\>\<Enter\></span>**

      FMPATIENT,24

    NAME: FMPATIENT,24//

</div>

 

<img src="user-manual.fld/image045.png" data-border="0" width="14"
height="43" alt="Tip" /> **TIP:** You can use **Spacebar Recall**
throughout VA FileMan and the Kernel. Experiment with this feature as a
quick way to recall your last response to most prompts.

### <span id="session"></span><span id="_Toc527389104">6.11.7<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Typical Data Entry Session</span>

<u><span style="color:blue">Figure 69</span></u> is an example of a
typical data entry session. This example is characteristic of editing
data in many VistA applications:

<span id="_Toc527389273"></span><span id="_Ref490818078">Figure</span>
69: VA FileMan Prompts—Example of a Typical Data Entry Session

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    Select Patient (Name or SSN):
**<span style="background:yellow">FMPATIENT, \<Enter\></span>** 
25        01-12-41

    000456789    COLLATERAL

 

    Height: 5’ 4”// **<span style="background:yellow">\<Enter\></span>**

    Weight: **<span style="background:yellow">150#</span>**

    Date Weight Taken: TODAY//
**<span style="background:yellow">\<Enter\></span>** (MAY 17, 1995)

    Usual Weight: **<span style="background:yellow">145#</span>**

    Wrist Circumference (cm):
**<span style="background:yellow">\<Enter\></span>**

    Frame Size (SMALL,MEDIUM,LARGE) MED//
**<span style="background:yellow">\<Enter\></span>**

 

    Calculation of Ideal Body Weight

              H Hamwi

              M Metropolitan 83

              S Spinal Cord Injury

              E Enter Manually

 

    Method: **<span style="background:yellow">S</span>**

 

    Extent of Injury:

           P Paraplegic

           Q Quadriplegic

 

    Select: **<span style="background:yellow">P</span>**

 

    Select Ideal Weight (109-118) 114 lb //
**<span style="background:yellow">\<Enter\></span>**

    Does Patient have an Amputation? NO//
**<span style="background:yellow">\<Enter\></span>**

    Do you wish Anthropometric Assessment? NO//
**<span style="background:yellow">\<Enter\></span>**

 

    Collecting laboratory data ...

 

    Calculate Energy Requirements Based On:

 

      1 Actual Body Weight

      2 Ideal Body Weight

      3 Obese Calculation

 

    Choose: **<span style="background:yellow">1</span>**

 

    Comments:

      No existing text

      Edit? NO// **<span style="background:yellow">\<Enter\></span>**

 

    Do you wish to FILE this Assessment Y//
**<span style="background:yellow">\<Enter\></span>**

</div>

 

<img src="user-manual.fld/image002.png" id="Picture 111" data-border="0"
width="22" height="22" alt="Note" />     **NOTE:** The fields in the
session listed in <u><span style="color:blue">Figure 69</span></u> take
many different responses. Some accept FREE TEXT values, some accept only
DATE/TIME, and some accept only NUMERIC input.

<img src="user-manual.fld/image002.png" id="Picture 112" data-border="0"
width="22" height="22" alt="Note" />     **REF:** For more information
on the specific types of fields (DATE/TIME, NUMERIC, WORD-PROCESSING,
FREE TEXT, etc.) and how to edit them, see the
“<u><span style="color:blue">Field Types</span></u>” section.

 

# <span id="_Hlt445776374"></span><span id="_Ref349206049"></span><span id="field_types"></span><span id="_Toc527389105"></span><span id="_Ref446309289"></span><span id="_Ref446309952"></span><span id="_Ref446310286"></span><span id="_Ref446310638"></span><span id="_Hlt446217690"></span>7<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Field Types

## <span id="_Toc527389106">7.1<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Introduction</span>

This document describes several fundamental VA FileMan conventions,
including:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>When the cursor comes to rest in a field, the computer
expects you to respond.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>A field serves much the same purpose as a blank on a form.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Each field has a prompt that identifies your response’s
subject matter.

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>You have a number of tools available to you at field
prompts, including the:

<span style="font-family:
&quot;Courier New&quot;">o<span style="font:7.0pt &quot;Times New Roman&quot;">  
</span></span>Caret (**^**) jump.

<span style="font-family:&quot;Courier New&quot;">o<span style="font:7.0pt &quot;Times New Roman&quot;">  
</span></span>Default response.

<span style="font-family:&quot;Courier New&quot;">o<span style="font:7.0pt &quot;Times New Roman&quot;">  
</span></span>“Replace...With” editor.

<span style="font-family:&quot;Courier New&quot;">o<span style="font:7.0pt &quot;Times New Roman&quot;">  
</span></span>Spacebar Recall (**\<Spacebar\>\<Enter\>**).

<span style="font-family:&quot;Courier New&quot;">o<span style="font:7.0pt &quot;Times New Roman&quot;">  
</span></span>At-sign (**@**) deletion.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Some fields have additional restrictions, such as your
response’s length or format. Enter **one** or **two** question marks
(**?** or **??**) to retrieve help on what is an acceptable entry for a
particular field.

When you are editing a field, entering **one** question mark (**?**) at
the field prompt usually provides enough help to infer what kind of
field you have reached and to predict what kind of data is acceptable in
this field (i.e., DATA TYPE field value).

You do *not* need to know a lot about these DATA TYPE field values, but
a little information can be helpful. In the sections that follow, you
will find examples and brief explanations about each field type
(i.e., DATA TYPE field value). In VA FileMan, you will work with many,
if not all, of the following DATA TYPE field values:

<span style="font-family:Symbol;color:black">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>[DATE/TIME](#date)<span id="_Hlt446149208"></span>

<span style="font-family:Symbol;color:black">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>[NUMERIC](#numeric)<span id="_Hlt446149210"></span>

<span style="font-family:Symbol;
color:black">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>[SET OF CODES](#set)<span id="_Hlt446149213"></span>

<span style="font-family:Symbol;
color:black">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>[FREE TEXT](#free)<span id="_Hlt446149215"></span>

<span style="font-family:Symbol;
color:black">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>[WORD-PROCESSING](#word)<span id="_Hlt446149217"></span>

<span style="font-family:Symbol;
color:black">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>[COMPUTED](#computed)<span id="_Hlt446149219"></span>

<span style="font-family:Symbol;
color:black">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>[POINTER TO A
FILE](#pointer)<span id="_Hlt446149221"></span>

<span class="MsoHyperlink"><span style="font-family:Symbol;color:black;text-decoration:none">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span></span>[VARIABLE-POINTER](#variable)<span id="_Hlt446149223"></span>

<span class="MsoHyperlink"><span style="font-family:Symbol;color:black;text-decoration:none">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span></span>[BOOLEAN](#boolean_fields)

<span class="MsoHyperlink"><span style="font-family:Symbol;color:black;text-decoration:none">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span></span>[LABEL REFERENCE](#label_reference_fields)

<span class="MsoHyperlink"><span style="font-family:Symbol;color:black;text-decoration:none">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span></span>[TIME](#time_fields)

<span class="MsoHyperlink"><span style="font-family:Symbol;color:black;text-decoration:none">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span></span>[YEAR](#year_fields)

<span class="MsoHyperlink"><span style="font-family:Symbol;color:black;text-decoration:none">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span></span>[UNIVERSAL TIME](#universal_time_fields)

<span class="MsoHyperlink"><span style="font-family:Symbol;color:black;text-decoration:none">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span></span>[FT POINTER](#ft_Pointer_fields)

<span class="MsoHyperlink"><span style="font-family:Symbol;color:black;text-decoration:none">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span></span>[FT DATE](#ft_date_fields)

<span style="font-family:Symbol;
color:black">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>[RATIO](#ratio_fields)

In addition, [Subfiles
(Multiples)](#subfiles)<span id="_Hlt446149225"></span> are introduced
at the end of this section.

## <span id="date"></span><span id="_Toc527389107"></span><span id="_Hlt446149209"></span>7.2<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>DATE/TIME Fields

You can use a variety of formats when entering dates. For example, a
DATA TYPE field value of DATE/TIME would probably be used to hold a
patient’s birthdate:

<span id="_Toc527389274">Figure</span> 70: Field Types—Entering a Date
at a DATE/TIME Field

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    DATE OF BIRTH: MAR 3, 1955

</div>

 

With a DATE/TIME field type, as with all field types, entering a
question mark retrieves help on acceptable responses. Enter **one**
question mark (**?**) at a DATE/TIME field prompt and you are given help
about what dates are acceptable for the particular field and what
precision of date is needed (e.g., year, month, day, or time).

### <span id="_Ref523917838"></span><span id="_Ref523917848"></span><span id="_Toc527389108">7.2.1<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Acceptable Formats for Entering Dates</span>

The following are acceptable formats for entering dates:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>JULY 20, 1999 ***or*** July 20, 1999

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>7/20/99

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>20 JUL 99

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>10jul99

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>10 jul 99

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>072099

To simplify entering dates, you can use shortcuts such as:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**T** for today

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**T-1** for yesterday

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**T+1** for tomorrow

You can also combine **T** with other shortcuts:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**D** for day. For example, **T-2D** means **two** days
ago.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**W** for week. For example, **T+1W** means today plus
**one** week.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**M** for month. For example, **T+4M** means **four**
months from today.

The year portion of the date can be left off. Normally, VA FileMan
assumes the current year. Sometimes, you can input imprecise dates such
as “**JUL 99**” or “**1999**”.

<img src="user-manual.fld/image002.png" id="Picture 113" data-border="0"
width="22" height="22" alt="Note" /><span style="font-size:10.0pt">    
</span>**NOTE:** VA FileMan is Year 2000 (Y2K) compliant.

### <span id="_Toc527389109">7.2.2<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Abbreviations for Dates</span>

<u><span style="color:blue">Table 13</span></u> lists acceptable
abbreviations when entering dates:

<span id="_Toc527389337"></span><span id="_Ref345582987">Table</span>
13: Field Types—Abbreviations for Dates

| <span id="COL001_TBL014"></span>Abbreviation | Meaning            |
|----------------------------------------------|--------------------|
| **TODAY** or **Today** or **T** or **t**     | Today.             |
| **TODAY+1** or **T+1** or **t+1**            | Tomorrow.          |
| **TODAY-7** or **T-7** or **t-7**            | One week ago.      |
| **TODAY+3W** or **T+3W** or **t+3w**         | Three weeks hence. |

 

### <span id="_Toc527389110">7.2.3<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Times in DATE/TIME Fields</span>

In some DATE/TIME fields, you can enter a time-of-day along with the
date. For example, to indicate **4:00 PM on July 20, 1999**, enter the
date in one of the formats shown in Section
<u><span style="color:blue">7.2.1</span></u>,
“<u><span style="color:blue">Acceptable Formats for Entering
Dates</span></u>,” followed by an at-sign (**@**), and then followed by
the time.

For example, you might enter:

<span id="_Toc527389275">Figure</span> 71: Field Types—Entering a Date
and Time

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    APPOINTMENT: **20 JUL 99@4PM**

</div>

 

To be totally unambiguous, you can enter time in any of the following
formats:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Military time (**four** or **six** digits, no colon)

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>hour AM/PM, hour:minute AM/PM

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>hour:minute:second AM/PM

If you do omit an AM/PM notation, the following assumptions are made:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>If you enter **one** digit for the hour, a time between
**6AM** and **6PM** is used. Thus, **T@330** (or **T@3:30**) means
**today at 3:30 PM** and **T@945** (or **T@9:45**) means **today at 9:45
AM**.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>If you enter **two** digits for the hour, the actual hour
entered is used (as if military time were being used). Thus, **T@0330**
(or **T@03:30**) means **today at 3:30 AM**.

As with dates, there are supported abbreviations you can use when
entering times in DATE/TIME fields. For example:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>To enter the present moment, you can enter the word
**NOW**.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>To enter an hour from the present moment, enter
**NOW+1H**.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>To enter an hour ago from the present moment, enter
**NOW-1H**.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>You can combine **NOW** with **D** for day and **M** for
month and **‘** (apostrophe) for minute.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>You can enter **MID** for **12 a.m.** and **NOON** for
**12 p.m.**

### <span id="_Toc527389111">7.2.4<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Abbreviations for Times</span>

<u><span style="color:blue">Table 14</span></u> lists acceptable
abbreviations when entering time:

<span id="_Toc527389338"></span><span id="_Ref345583002">Table</span>
14: Field Types—Abbreviations for Times

|                                              |                                      |
|----------------------------------------------|--------------------------------------|
| <span id="COL001_TBL015"></span>Abbreviation | Meaning                              |
| **NOW+3’**                                   | Present time plus **three** minutes. |
| **NOW+1H**                                   | Present time plus **one** hour.      |
| **NOW+3D**                                   | Present time plus **three** days.    |
| **NOW+4M**                                   | Present time plus **four** months.   |
| **NOON**                                     | Today at **12:00 noon**.             |
| **MID**                                      | Today at **24:00 midnight**.         |

 

## <span id="numeric"></span><span id="_Toc527389112"></span><span id="_Hlt446149212"></span>7.3<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>NUMERIC Fields

DATA TYPE field values of NUMERIC work very much like [FREE
TEXT](#free)<span id="_Hlt446149238"></span> fields, except that input
is restricted to valid numbers. There can also be restrictions as to how
small or large a number is allowed, and how many decimal places are
allowed. Entering **one** question mark retrieves help that tells you
what responses are acceptable.

For example, a NUMERIC field type would probably be used to store the
height of a patient:

<span id="_Toc527389276">Figure</span> 72: Field Types—Example of a
NUMERIC Field

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    HEIGHT (cm): 196

</div>

 

## <span id="set"></span><span id="_Toc527389113"></span><span id="_Hlt446149214"></span>7.4<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>SET OF CODES Fields

DATA TYPE field values of SET OF CODES (sometimes referred to as a SET)
are preset to accept coded information. The codes are usually only
**one** or **two** characters long. Each code in a SET represents a word
or a series of words. For example, the codes **Y** and **N** often
represent the words **YES** and **NO**. You can enter the code at this
prompt instead of the entire word. If, however, you enter anything other
than an acceptable code (or the word it represents), the computer
rejects your response.

To see a list of acceptable codes, simply enter **one** question mark
(**?**) in response to the prompt.

<u><span style="color:blue">Figure 73</span></u> shows how a SET OF
CODES field type is used to store whether or not a patient is a smoker:

<span id="_Toc527389277"></span><span id="_Ref389661523">Figure</span>
73: Field Types—Example of a SET OF CODES Field

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    Select PATIENT NAME:
**<span style="background:yellow">FMPATIENT,NINE</span>**

    SMOKER: **<span style="background:yellow">?</span>**

         Choose from:

           S      SMOKER

           N      NON-SMOKER

    SMOKER: **<span style="background:yellow">N \<Enter\></span>**
NON-SMOKER

</div>

 

In the example in <u><span style="color:blue">Figure 73</span></u>,
there were two choices for the user to select for the "SMOKER" field.

### <span id="_Toc527389114">7.4.1<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Internal vs. External Values for SET OF CODES Fields</span>

In <u><span style="color:blue">Figure 73</span></u>, the value of the
SMOKER field is set to **N**, which is the code for **NON-SMOKER**. In
this case:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**N**—Internal value of the field (the form in which it is
stored in the database).

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**NON-SMOKER**—External value of the field (the form in
which it is displayed on screen and in reports).

Every DATA TYPE field value has an internal and external value; in most
cases, however, the internal and external values are the same. SET OF
CODES field types are an exception.

<img src="user-manual.fld/image002.png" id="Picture 114" data-border="0"
width="22" height="22" alt="Note" /><span style="font-size:10.0pt">    
</span>**NOTE:** Probably, the only place you need to know the
distinction between internal and external values is when you print a
report and *sort* on a SET OF CODES-valued field. The sort order is
based on the internal values (codes) if you sort on a SET OF
CODES-valued field.

<img src="user-manual.fld/image002.png" id="Picture 115" data-border="0"
width="22" height="22" alt="Note" /><span style="font-size:10.0pt">    
</span>**REF:** For more information on printing and sorting, see the
“<u><span style="color:blue">Print</span></u>” section.

## <span id="free"></span><span id="_Toc527389115"></span><span id="_Hlt446149216"></span>7.5<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>FREE TEXT Fields

You can enter almost any character from your keyboard in a DATA TYPE
field value of FREE TEXT. The computer accepts numbers, letters, and
most of the symbols that can be entered. The FREE TEXT field type places
a restriction on the number of characters that you can enter. If you
enter **one** question mark (**?**) in response to the prompt for a FREE
TEXT-valued field, you learn how many characters you are allowed to
enter.

For example, a FREE TEXT field type would probably be used to hold a
patient’s street address:

<span id="_Toc527389278">Figure</span> 74: Field Types—Example of a FREE
TEXT Field

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    ADDRESS: 123 Main Street

</div>

 

In some places, even though the field is FREE TEXT, checks are applied
to make sure what is entered matches a certain format. For example, if
you are entering a Social Security Number, which is stored as a DATA
TYPE field value of FREE TEXT, *not* NUMERIC, your input would typically
be checked to make sure it is **nine** characters in length and contains
all digits:

<span id="_Toc527389279">Figure</span> 75: Field Types—Example of a FREE
TEXT Field with Validation

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    SSN: **<span style="background:yellow">abcde \<Enter\></span>** ??

     ANSWER MUST BE 9 CHARACTERS IN LENGTH

    SSN: **<span style="background:yellow">99999 \<Enter\></span>** ??

      ANSWER MUST BE 9 CHARACTERS IN LENGTH

    SSN: **<span style="background:yellow">33233290 \<Enter\></span>**
??

      ANSWER MUST BE 9 CHARACTERS IN LENGTH

    SSN: **<span style="background:yellow">000232343</span>**

    DATE:

</div>

 

## <span id="word"></span><span id="_Toc527389116"></span><span id="_Hlt446149218"></span>7.6<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>WORD-PROCESSING Fields

DATA TYPE field values of WORD-PROCESSING can contain unlimited amounts
of text data, and are suitable for things like mail messages, physician
notes, and descriptions. Because of their special nature, VA FileMan
provides special tools for entering and editing data into this kind of a
field.

Two editors for editing WORD-PROCESSING field types are provided with VA
FileMan (and described in their own section):

<span style="font-family:
Symbol;color:black">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Screen Editor</span></u>

<span style="font-family:Symbol;color:black">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Line Editor</span></u>

<img src="user-manual.fld/image002.png" id="Picture 116" data-border="0"
width="22" height="22" alt="Note" />     **REF:** To set your default
editor, see the “<u><span style="color:blue">Word-Processing
Fields</span></u>” section. This section also explains how you can
switch your current editor on-the-fly. For most people, the Screen
Editor should be your Preferred Editor for WORD-PROCESSING fields.

When you encounter a WORD-PROCESSING field type, if your default editor
is the Scre<span id="_Hlt446149323">e</span>n Editor, a portion of any
existing text is displayed, and you are prompted “Edit? NO//”:

<span id="_Toc527389280">Figure</span> 76: Field Types—Example of a
WORD-PROCESSING Field, Using the Screen Editor

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

Select PATIENT NAME:
**<span style="background:yellow">FMPATIENT,22</span>**

NAME: FMPATIENT,22//
**<span style="background:yellow">\<Enter\></span>**

SEX: MALE// **<span style="background:yellow">\<Enter\></span>**

DATE OF BIRTH: AUG 22,1948//
**<span style="background:yellow">\<Enter\></span>**

HISTORY:

Owing to poverty in early youth, patient seems not to

have had proper diet. Since achieving economic success,

his diet has been adequate, but traces of original

deficiency remain.

 

  Edit? NO//

</div>

 

<img src="user-manual.fld/image002.png" id="Picture 117" data-border="0"
width="22" height="22" alt="Note" /><span style="font-size:10.0pt">    
</span>**REF:** For more information on the Screen Editor, see the
“<u><span style="color:blue">Screen Editor</span></u>” section.

When you encounter a WORD-PROCESSING field type, if your default editor
is the <u><span style="color:blue">Line Editor</span></u> on the other
hand, a portion of the text is displayed, and you are prompted with
“Edit Option:”

<span id="_Toc527389281">Figure</span> 77: Field Types—Example of a
WORD-PROCESSING Field, Using the Line Editor

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

Select PATIENT NAME:
**<span style="background:yellow">FMPATIENT,22</span>**

NAME: FMPATIENT,22//
**<span style="background:yellow">\<Enter\></span>**

SEX: MALE// **\<Enter\>**

DATE OF BIRTH: AUG 22,1948//
**<span style="background:yellow">\<Enter\></span>**

HISTORY:

  1\>Owing to poverty in early youth, patient seems not to

  2\>have had proper diet. Since achieving economic success,

  3\>his diet has been adequate, but traces of original

  4\>deficiency remain.

 

EDIT OPTION:

</div>

 

<img src="user-manual.fld/image002.png" id="Picture 118" data-border="0"
width="22" height="22" alt="Note" /><span style="font-size:10.0pt">    
</span>**REF:** For more information on the Line Editor, see the
“<u><span style="color:blue">Line Editor</span></u>” section.

## <span id="computed"></span><span id="_Toc527389117"></span><span id="_Hlt446149220"></span>7.7<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>COMPUTED Fields

DATA TYPE field values of COMPUTED are typically used to output a value
computed at run-time in a report. You *cannot* edit the value of a
COMPUTED field type.

An example of a COMPUTED field type would be a field that calculated age
based on today’s date and a patient’s DATE OF BIRTH field. Because the
field is a COMPUTED field type, it can output a patient’s current age
based on whatever today’s date is. You *cannot* edit the AGE field, but
you can use it to print out the current age of the patient.

You are most likely to come across COMPUTED field types when printing
with the CAPTIONED PRINT template. Choosing the CAPTIONED OUTPUT
template automatically outputs all normal fields containing data for
each entry in a report. However, you *must* choose whether you want
COMPUTED fields included in the output as well, as shown in
<u><span style="color:blue">Figure 78</span></u>:

<span id="_Toc527389282"></span><span id="_Ref345588399">Figure</span>
78: Field Types—Dialogue to Choose a COMPUTED Field: Sample User Entries
at Prompts

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

STANDARD CAPTIONED OUTPUT? Yes//
**<span style="background:yellow">\<Enter\></span>** (Yes)

Include COMPUTED fields:  (N/Y/R/B): NO//
**<span style="background:yellow">?</span>**

<img src="user-manual.fld/image046.png" data-border="0" width="242"
height="46"
alt="Choose whether to output computed fields. - Title: Choose whether to output computed fields. - Description: Choose whether to output computed fields." />

Enter a code from the list.

     Select one of the following:

 

          N         NO - No record number (IEN), no Computed Fields

          Y         Computed Fields

          R         Record Number (IEN)

          B         BOTH Computed Fields and Record Number (IEN)

</div>

 

At the "Include COMPUTED fields: (N/Y/R/B): NO//" prompt, you choose
whether to output COMPUTED fields.

<img src="user-manual.fld/image002.png" id="Picture 119" data-border="0"
width="22" height="22" alt="Note" />     **REF:** For more information
on CAPTIONED OUTPUT, see the
“<u><span style="color:blue">Inquire</span></u>” and
“<u><span style="color:blue">Print</span></u>” sections.

## <span id="pointer"></span><span id="_Toc527389118"></span><span id="_Hlt446149222"></span>7.8<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>POINTER TO A FILE Fields

A DATA TYPE field value of POINTER TO A FILE is a field that directs the
computer to another file for information. If you are working in the
PATIENT (#2) file, for example, and you have reached a field that asks
for the patient’s STATE, the field is probably a POINTER TO A FILE field
that “points” to the STATE (#5) file. Because of pointers, such commonly
used information as states can be stored in a single STATE (#5) file.
Then, every file (e.g., PATIENT, VENDOR, INSURANCE, etc.) that needs to
record a value for STATE can use a POINTER TO A FILE field to the STATE
(#5) file to store that information.

For example:

<span id="_Toc527389283"><span class="CaptionChar">Figure
</span></span><span class="CaptionChar">79</span><span class="CaptionChar">:
</span>Field Types—<span class="CaptionChar">Sample of a POINTER TO A
FILE Field (1 of 2)</span>

<img src="user-manual.fld/image047.jpg" id="Picture 120" data-border="0"
width="468" height="212"
alt="Field Types—Sample of a POINTER TO A FILE field" />

 

<span id="_Toc527389284">Figure</span> 80. Field Types—Sample of a
POINTER TO A FILE Field (2 of 2)

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

INPUT TO WHAT FILE: PATIENT//
**<span style="background:yellow">\<Enter\></span>** (1890 entries)

EDIT WHICH FIELD: ALL// **<span style="background:yellow">STATE</span>**

THEN EDIT FIELD: **<span style="background:yellow">\<Enter\></span>**

 

Select PATIENT NAME: **FMPATIENT,THREE**

<img src="user-manual.fld/image048.png" data-border="0" width="277"
height="51"
alt="Enter two question marks at this prompt to list available choices. - Title: Enter two question marks at this prompt to list available choices. - Description: Enter two question marks at this prompt to list available choices." />

STATE: **<span style="background:yellow">??</span>**

CHOOSE FROM:

  ALABAMA

  ALASKA

  ARIZONA

  .

  .

  .

STATE: **<span style="background:yellow">COLORADO</span>**

</div>

 

Enter **two** question marks at the “STATE:” prompt to list available
choices. If the choice you need is *not* listed, you can add that choice
by typing it in (provided you have **LAYGO** access to add the entry).
If the entry you enter is *not* matched, you are asked if you want to
add a new entry. If you answer **YES**, VA FileMan adds the new entry.
For example, if there was a state that did *not* have an entry in the
STATE (#5) file, you could add it by entering it at the “STATE:” prompt.

## <span id="variable"></span><span id="_Toc527389119"></span><span id="_Hlt446149224"></span>7.9<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>VARIABLE-POINTER Fields

A DATA TYPE field value of VARIABLE-POINTER is like the regular [POINTER
TO A FILE](#pointer)<span id="_Hlt446149390"></span> field type, with
one difference:

The VARIABLE-POINTER DATA TYPE can point to a single record in one of
*several* files; whereas the regular POINTER TO A FILE DATA TYPE can
point to a single record in only *one* file.

The PATIENT (#2) file, for example, might use a VARIABLE-POINTER field
type to identify a provider; the provider might be a Staff Provider,
stored in the (fictitious) PROVIDER file, or an outside provider, stored
in another file.

For example, if you are working in a PATIENT (#2) file entry, and you
need information that explains how to look up a name listed in one of
several files. To get help, simply enter a single question mark (**?**)
at the “PROVIDER” prompt. The system then displays instructions that
explain how to choose a provider from either of the two files being
pointed to, as shown in <u><span style="color:blue">Figure
81</span></u>.

<span id="_Toc527389285"></span><span id="_Ref345588409">Figure</span>
81: Field Types—Dialogue Showing Help for Entries in a VARIABLE-POINTER
Field: Sample User Entries at Prompts

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

<img src="user-manual.fld/image049.png" data-border="0" width="320"
height="54"
alt="Online help (single question mark) shows what prefixes are used to refer to entries in each pointed to file. - Title: Online help (single question mark) shows what prefixes are used to refer to entries in each pointed to file. - Description: Online help (single question mark) shows what prefixes are used to refer to entries in each pointed to file." />

PROVIDER: **<span style="background:yellow">?</span>**

 

  Enter one of the following:

   S.EntryName to select a Staff Provider

   O.EntryName to select an Outside Provider

 

     To see the entries in any particular file, type \<Prefix.?\>

</div>

 

Entering one question mark at the “PROVIDER:” prompt displays online
help that shows what prefixes are used to refer to entries in each
pointed to file.

With VARIABLE-POINTER field types, you need to use a PREFIX in addition
to an entry name to select an entry. In this example, the online help
tells you that:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>To select a Staff Provider, prefix the provider’s name
with “**S.**”.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>To select an Outside Provider, prefix the provider’s name
with “**O.**”.

You can enter a PREFIX and **one** question mark to get a list of
entries in a particular pointed-to file. For example, if you enter
“**S.?**” you can get a list of all Staff Providers. Likewise, you can
enter “**S.FMPROVIDER**” to get a list of all Staff Providers whose last
names are **FMPROVIDER**. You can also enter “**S.FMPROVIDER,ONE**” to
select a Staff Provider named **One Fmprovider**.

For example:

<span id="_Toc527389286">Figure</span> 82: Field Types—Using the PREFIX
and a Question Mark to Get a List of Entries in a Pointed-To File

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

 

    PROVIDER: **<span style="background:yellow">S.?</span>**

     CHOOSE FROM:

       FMPROVIDER,ONE

       FMPROVIDER,TWO

        :

</div>

 

You can also select an entry in a VARIABLE-POINTER field by just
entering a name *without* the PREFIX. In this case, VA FileMan searches
each pointed-to file in succession until a match is found.

<img src="user-manual.fld/image002.png" id="Picture 121" data-border="0"
width="22" height="22" alt="Note" /><span style="font-size:10.0pt">    
</span>**NOTE:** This method requires more processing time, since VA
FileMan needs to search the various pointed-to files.

For example, to choose a provider *without* specifying in which file the
provider can be found, enter the provider name only:

<span id="_Toc527389287">Figure</span> 83: Field Types—Searching for an
Entry in a Pointed-To File

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    PROVIDER: **<span style="background:yellow">FMPROVIDER,EIGHT
M</span>**

 

    Searching for a Staff Provider

 

    Searching for a Outside Provider FMPROVIDER,EIGHT M

            ...OK?  YES//
**<span style="background:yellow">\<Enter\></span>** (YES)

</div>

 

You can add an entry to one of the files that is being pointed to by a
VARIABLE-POINTER field. To do this, enter the appropriate PREFIX and the
new name to add at the field prompt.

For example, to add “**FMPROVIDER,EIGHT M**” as an Outside Provider
(*not* a Staff Provider), use the appropriate PREFIX when adding the new
entry (in this case, “**O.**”). When the requested name is *not* found,
you are asked if you want to add the provider as a new entry. To add the
entry, enter **YES**:

<span id="_Toc527389288">Figure</span> 84: Field Types—Adding a New
Entry to a Pointed-To File

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    PROVIDER: **<span style="background:yellow">O.FMPROVIDER,EIGHT
M.</span>**

      Are you adding ‘FMPROVIDER,EIGHT M.’ as a new OUTSIDE PROVIDER? 
No// **<span style="background:yellow">YES \<Enter\></span>** (Yes)

    OUTSIDE PROVIDER SEX:
**<span style="background:yellow">MALE</span>**

    OUTSIDE PROVIDER DATE OF BIRTH:
**<span style="background:yellow">020235 \<Enter\></span>** (FEB 02,
1935)

    OUTSIDE PROVIDER SSN:
**<span style="background:yellow">000987321</span>**

</div>

 

## <span id="_Toc462297887"></span><span id="_Toc462650498"></span><span id="_Toc468372721"></span><span id="_Ref472184487"></span><span id="boolean_fields"></span><span id="_Toc527389120"></span><span id="_Hlt446149226"></span>7.10<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>BOOLEAN Fields

A field defined as a BOOLEAN data type can have only two entry choices:
**YES** or **NO**. The internal values of the BOOLEAN DATA TYPE is set
to:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**1—**YES

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**0—**NO

<span id="_Toc527389339">Table</span> 15: BOOLEAN Data Type Example

| External | Internal |
|----------|----------|
| **YES**  | **1**    |
| **NO**   | **0**    |

 

## <span id="_Toc462297888"></span><span id="_Toc462650499"></span><span id="_Toc468372722"></span><span id="label_reference_fields"></span><span id="_Toc527389121">7.11<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>LABEL REFERENCE Fields</span>

A field defined as a LABEL REFERENCE data type is designed to store a
tag and routine entry of the format, TAG^ROUTINE. It is stored as a
FREE-TEXT field.

<span id="_Toc527389340">Table</span> 16: LABEL REFERENCE Data Type
Example

| External    | Internal    |
|-------------|-------------|
| TAG^ROUTINE | TAG^ROUTINE |

 

## <span id="_Toc462297889"></span><span id="_Toc462650500"></span><span id="_Toc468372723"></span><span id="time_fields"></span><span id="_Toc527389122">7.12<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>TIME Fields</span>

A field defined as a TIME data type can accept many of the date/time
entries, but only stores the TIME portion.

<span id="_Toc527389341">Table</span> 17: TIME Data Type Example

| External | Internal |
|----------|----------|
| 15:09:43 | 150943   |

 

## <span id="_Toc462297890"></span><span id="_Toc462650501"></span><span id="_Toc468372724"></span><span id="year_fields"></span><span id="_Toc527389123">7.13<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>YEAR Fields</span>

A field defined as a YEAR data type can accept many of the date entries,
but only stores the YEAR portion.

<span id="_Toc527389342">Table</span> 18: YEAR Data Type Example

| External | Internal |
|----------|----------|
| 2016     | 3160000  |

 

## <span id="_Toc462297891"></span><span id="_Toc462650502"></span><span id="_Toc468372725"></span><span id="universal_time_fields"></span><span id="_Toc527389124">7.14<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>UNIVERSAL TIME Fields</span>

A field defined as a UNIVERSAL TIME data type can accept many of the
date/time entries and stores the date/time in a format with the local
time and includes an indicator showing the offset from Universal Time.

The first **14** characters of the internal storage of the UNIVERSAL
TIME data type are exactly like the current DATE/TIME data type that
includes seconds. The **three** characters in position **15**, **16**,
and **17** indicate the UTC time offset in **five** (**5**) minute
increments. In the example below: **(440-500)/12=-5**, this is a
negative **five** hour offset from UTC.

<span id="_Toc527389343">Table</span> 19: UNIVERSAL TIME Data Type
Example

| External                       | Internal          |
|--------------------------------|-------------------|
| JAN 6,2016@08:03:36 (UTC-5:00) | 3160106.080336440 |

 

## <span id="_Toc462297892"></span><span id="_Toc462650503"></span><span id="_Toc468372726"></span><span id="ft_Pointer_fields"></span><span id="_Toc527389125">7.15<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>FT POINTER Fields</span>

A field defined as a FT POINTER data type works similar to the POINTER
data type, but internally stores the free text that was returned from
the pointed-to value.

<span id="_Toc527389344">Table</span> 20: FT POINTER Data Type Example

| External   | Internal   |
|------------|------------|
| PATCH,USER | PATCH,USER |

 

## <span id="_Toc462297893"></span><span id="_Toc462650504"></span><span id="_Toc468372727"></span><span id="ft_date_fields"></span><span id="_Toc527389126">7.16<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>FT DATE Fields</span>

A field defined as a FT DATE data type works similar to the DATE/TIME
data type, but internally stores the free text that was input by the
user to determine the date.

<span id="_Toc527389345">Table</span> 21: FT DATE Data Type Example

| External | Internal |
|----------|----------|
| T-1      | T-1      |

 

## <span id="_Toc462297894"></span><span id="_Toc462650505"></span><span id="_Toc468372728"></span><span id="_Ref472184508"></span><span id="ratio_fields"></span><span id="_Toc527389127">7.17<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>RATIO Fields</span>

A field defined as a RATIO data type is designed to accept **two**
numbers with a colon (**:**) between the **two** numbers. It is
formatted and stored like a mathematical ratio.

<span id="_Toc527389346">Table</span> 22: RATIO Data Type Example

| External | Internal |
|----------|----------|
| 1:14     | 1:14     |

 

## <span id="_Toc527389128"></span><span id="subfiles">7.18<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Subfiles</span> (Multiples)

Sometimes, a single field in a record is *not* enough to hold all the
information required. For example, to keep track of the appointment
history for a patient, a single field would *not* be enough. An ordinary
field could only hold enough information to record a single appointment.
But there needs to be a way to record as many appointments as a patient
has had, which could range from none to several hundred. In addition,
each appointment might have its own information that needs to be stored
(e.g., date, time, location, doctor, etc.).

This situation is handled with what are known as Subfiles (also known as
Multiples). Within an individual record, a Subfile (Multiple) can be
used to hold this type of information:

<span id="_Toc527389289"></span><span id="_Ref491174811">Figure</span>
85: Field Types—Sample Subfile (Multiple) Field

<img src="user-manual.fld/image050.png" id="Picture 122" data-border="0"
width="479" height="259"
alt="Sample Subfile (Multiple) field Left: Sample Patient Record highlighting the Apppointments filed. Right: Sample of the Appointments Subfile (Multiple) showing 3 sample records." />

 

The fields in a Subfile (in this example
\[<u><span style="color:blue">Figure 85</span></u>\], DATE, TIME,
LOCATION, and DOCTOR) are called Subfields.

The word “**Select**” is always the first part of the prompt when you
encounter a Multiple, to indicate that you are choosing among one of
several possible values on file, as shown in
<u><span style="color:blue">Figure 86</span></u>:

<span id="_Toc527389290"></span><span id="_Ref504485476">Figure</span>
86: Field Types—Example of a Multiple Field Prompt

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

    <span style="background:aqua">Select</span> APPOINTMENTS:

</div>

 

If, for a given Multiple, more than one entry has already been entered,
the most recently created entry is displayed as a default. To see the
list of entries already in the Multiple, enter **two** question marks
(**??**) at the “Select...” prompt.

Because they are so useful, Subfiles (Multiples) are widely used
throughout VistA. They are usually straightforward to use, because their
structure as Subfiles mirrors the real-world structure of the
information. For example, for a purchase order, the top-level record
would be the purchase order. Because a single purchase order needs a
place to store as few or as many items as are requested, the purchase
order record has a Multiple to record the order items for the purchase
order.

Subfiles can themselves contain Subfiles creating additional levels in
files.

 

# <span id="_Ref446310298"></span><span id="_Ref446310653"></span><span id="_Toc527389129"></span><span id="_Hlt446217705"></span>8<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Adding and Deleting Records

## <span id="BM01_field"></span><span id="_Toc527389130">8.1<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>.01 Field</span>

The **.01** field is the most important field in a file. For the records
in a file, it usually identifies the record more than any other single
field. For example, the **.01** field of the PATIENT (#2) file is NAME.
The **.01** field of a WARD file might be WARD NAME.

Usually, in an edit dialogue the **.01** field is the field you are
prompted for when you choose a record to edit. Typically, it is also the
first field you actually edit once you have chosen the record.

The **.01** field plays a role in both adding and deleting entries in a
file:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>To *add* an entry to a file, you usually enter a new value
at the **.01** field’s prompt.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>To *delete* an entry to a file, you usually enter an
at-sign (**@**) in the entry’s **.01** field.

## <span id="add"></span><span id="_Toc527389131"></span><span id="_Hlt446149549"></span>8.2<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>How to Add a Record

As you recall from the
“<u><span style="color:blue">Introduction</span></u>”, an entry is a
complete record in a file. To *add* a new entry to a file, enter the
name of the new entry at the “Select...” prompt where you ordinarily
choose which record in the file to edit:

<span id="_Toc527389291"></span><span id="_Ref345588419">Figure</span>
87: Records—Dialogue to Add a Record: Sample User Entries at Prompts

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

<img src="user-manual.fld/image051.png" data-border="0" width="240"
height="34"
alt="Enter a new name at the “Select…” prompt. - Title: Enter a new name at the “Select…” prompt. - Description: Enter a new name at the “Select…” prompt." />

Select PATIENT NAME:
**<span style="background:yellow">FMPATIENT,ONE</span>**

   ARE YOU ADDING ‘FMPATIENT,ONE’ AS A NEW PATIENT (THE 121082ND)? No//
**<span style="background:yellow">Y \<Enter\></span>** (Yes)

</div>

 

This is the prompt for the record’s **.01** field (see
<u><span style="color:blue">Figure 87</span></u>). If you enter a name
that does *not* exist in the file, you are prompted “Are you adding
*‘XXXXXXXX*’ as a new ‘*ENTRY*’?”; where “*XXXXXXXX*” represents the
field value and “ENTRY” represents the field or file name. If **LAYGO**
is allowed and you answer **YES** to this prompt, VA FileMan adds the
new entry to the file. You then go on to edit other fields for the new
entry.

If a file has one or more data Keys defined (i.e., fields or
combinations of fields that uniquely identify a record), then those
fields *must* also be filled in before the new entry is added. There
*must not* be any other records on the file that have the same values in
all of those fields.

Finally, there may be a set of required fields (identifiers) for the new
entry; these *must* be filled in with values for the new entry to be
saved.

## <span id="_Toc527389132"></span><span id="same_name">8.3<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Adding a Duplicate Record</span> (Use Quotes)

What if there is already a “**FMPATIENT,ONE**” in the PATIENT (#2) file,
and you need to add a second entry with the same name
“**FMPATIENT,ONE**”? Simply entering that name at the “Select...” prompt
selects the existing entry. To create a *second* **FMPATIENT,ONE**
entry, even though one with that name *already* exists, enter the entry
name you want to add, but with *quotation marks* around it, as shown in
<u><span style="color:blue">Figure 88</span></u>:

<span id="_Toc527389292"></span><span id="_Ref345588428">Figure</span>
88: Records—Dialogue to Add a Duplicate Record: Sample User Entries at
Prompts

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

<img src="user-manual.fld/image052.png" data-border="0" width="245"
height="50"
alt="Use quotes at the “Select…” prompt to add another patient of the same name to the file. - Title: Use quotes at the “Select…” prompt to add another patient of the same name to the file. - Description: Use quotes at the “Select…” prompt to add another patient of the same name to the file." />

Select PATIENT NAME:
**<span style="background:yellow">“FMPATIENT,ONE”</span>**

   ARE YOU ADDING ‘FMPATIENT,ONE’ AS A NEW PATIENT (THE 121082ND)? No//
**<span style="background:yellow">Y \<Enter\></span>** (Yes)

</div>

 

<img src="user-manual.fld/image002.png" id="Picture 123" data-border="0"
width="22" height="22" alt="Note" />     **REF:** For instructions on
adding entries with the same name to pointed-to files from a POINTER TO
A FILE data type field, see the “[Adding Records at a POINTER TO A FILE
Field](#adding_pointed_to)<span id="_Hlt446224171"></span><span id="_Hlt446149444"></span><span id="_Hlt445181353"></span>”
section.

If a record has a data Key defined (i.e., fields or combinations of
fields that uniquely identify a record), and if the data Key contains
more than one field, then it would be possible to add a second
**FMPATIENT,ONE** *without* using quotes. Suppose the Key fields were
the NAME and the DATE OF BIRTH. Then the user would be prompted for both
NAME and DATE OF BIRTH, and assuming that the DATE OF BIRTH of the
second **FMPATIENT,ONE** were different from the existing record, VA
FileMan would allow the user to add the new **FMPATIENT,ONE** *without*
enclosing the name in quotes.

## <span id="deleting"></span><span id="_Toc527389133">8.4<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>How to Delete a Record</span>

To delete an existing record in a file, enter an at-sign (**@**) in the
record’s **.01** field. This tells VA FileMan to delete the record. In
all deletions, you are asked to confirm the deletion before VA FileMan
goes ahead and deletes the record. <u><span style="color:blue">Figure
89</span></u> is an example of deleting a record in a file:

<span id="_Toc527389293"></span><span id="_Ref345588440">Figure</span>
89: Records—Dialogue to Delete a Record: Sample User Entries at Prompts

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

Select DOCTOR NAME:
**<span style="background:yellow">FMDOCTOR,TWO</span>**

<img src="user-manual.fld/image053.png" data-border="0" width="340"
height="44"
alt="Enter an at-sign (@) at the .01 field to delete the entire entry. - Title: Enter an at-sign (@) at the .01 field to delete the entire entry. - Description: Enter an at-sign (@) at the .01 field to delete the entire entry." />

NAME: FMDOCTOR,TWO// **<span style="background:yellow">@</span>**

 ARE YOU SURE YOU WANT TO DELETE THE ENTIRE ‘FMDOCTOR,TWO” DOCTOR?
**<span style="background:
yellow">YES</span>**

</div>

 

In this example, the user entered an at-sign (**@**) at the DOCTOR NAME
(#.01) field to delete the entire entry for the **FMDOCTOR,TWO**.

## <span id="repointing"></span><span id="_Toc527389134">8.5<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Repointing When Deleting Records</span>

What if a record in another file points to the record you are deleting?

If you delete a record that is pointed to from another file, this would
leave a dangling pointer that points to a *non*-existent entry. To
prevent this, if the record you delete could be pointed to from another
file, you are given the opportunity to either delete any pointers to the
deleted record, or change them all to point to another record.

For example, an entry in the PATIENT (#2) file may have a field that
points to a doctor in the (fictitious) PROVIDER file. If you delete the
doctor from the (fictitious) PROVIDER file, you should indicate what
should happen to any entries in other files, including the PATIENT (#2)
file that points to this doctor.

In the example in
<span class="CaptionChar"><u><span style="font-family:&quot;Times New Roman&quot;,serif;color:blue;
font-weight:normal">Figure 90</span></u></span>, when you delete the
**FMDOCTOR,TWELVE** record, you also re-points any entries that had been
pointing to **FMDOCTOR,TWELVE** to point to **FMDOCTOR,EIGHT**.

<span id="_Toc527389294"></span><span id="_Ref345588452"><span class="CaptionChar">Figure
</span></span><span class="CaptionChar">90</span><span class="CaptionChar">:
</span>Records—<span class="CaptionChar">Dialogue to Delete a Record and
Re-Point to a Different Record</span>: Sample User Entries at Prompts

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

Select DOCTOR NAME:
**<span style="background:yellow">FMDOCTOR,TWELVE</span>**

 

NAME: FMDOCTOR,TWELVE// **<span style="background:yellow">@</span>**

 ARE YOU SURE YOU WANT TO DELETE THE ENTIRE ‘FMDOCTOR,TWELVE” DOCTOR?
**<span style="background:
yellow">YES</span>**

 

SINCE THE DELETED ENTRY MAY HAVE BEEN ‘POINTED TO’ BY ENTRIES IN THE
‘PATIENT’ FILE, ETC., DO YOU WANT THOSE POINTERS UPDATED (WHICH COULD
TAKE QUITE A WHILE)? NO// **<span style="background:yellow">Y
\<Enter\></span>** (YES)

<img src="user-manual.fld/image054.png" data-border="0" width="163"
height="35"
alt="Choose to update pointers. - Title: Choose to update pointers. - Description: Choose to update pointers." />

WHICH DO YOU WANT TO DO?

    1) DELETE ALL SUCH POINTERS

    2) CHANGE ALL SUCH POINTERS TO POINT TO A DIFFERENT ‘DOCTOR’ ENTRY

  CHOOSE 1) OR 2): **<span style="background:yellow">2</span>**

<img src="user-manual.fld/image055.png" data-border="0" width="266"
height="37"
alt="In this case, point them all to a different entry. - Title: In this case, point them all to a different entry. - Description: In this case, point them all to a different entry." />

 

THEN PLEASE INDICATE WHICH ENTRY SHOULD BE POINTED TO

<img src="user-manual.fld/image056.png" data-border="0" width="220"
height="54"
alt="Change FMDOCTOR,TWELVE entries to point to FMDOCTOR,EIGHT. - Title: Change FMDOCTOR,TWELVE entries to point to FMDOCTOR,EIGHT. - Description: Change FMDOCTOR,TWELVE entries to point to FMDOCTOR,EIGHT." />

 

Select DOCTOR NAME:
**<span style="background:yellow">FMDOCTOR,EIGHT</span>**

  -OK? YES// **<span style="background:yellow">Y \<Enter\></span>**
(YES)

   (RE-POINTING WILL OCCUR WHEN YOU LEAVE ENTER/EDIT OPTION)

</div>

 

When you leave the **Enter or Edit File Entries**
\[<span style="color:windowtext">DIEDIT</span>\] option, the updating is
done. A report is generated listing all changed entries; you need to
specify on what device this report should be listed:

<span id="_Toc527389295"></span><span id="_Ref345588470">Figure</span>
91: Records—Dialogue Showing a Report of Changed Entries: Sample Report

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

…EXCUSE ME, LET ME PUT YOU ON ‘HOLD’ FOR A SECOND...

DEVICE: HOME// **<span style="background:yellow">\<Enter\></span>**
SYSTEM

 

PATIENT ENTRIES WHOSE ‘ATTENDING PHYSICIAN’ POINTERS HAVE BEEN CHANGED

-———————————————————————————————————————————————————————————————————————————————-

 

 FMPATIENT,TWENTY

 FMPATIENT,ONE

 FMPATIENT,ELEVEN

 FMPATIENT,SEVEN

 

Select OPTION:

</div>

 

In this case (<u><span style="color:blue">Figure 91</span></u>), four
entries are found that had **FMDOCTOR,TWELVE** as their doctor. Now that
**FMDOCTOR,TWELVE** was deleted, these records are re-pointed to
**FMDOCTOR,EIGHT**.

## <span id="adding_pointed_to"></span><span id="_Toc527389135"></span><span id="_Hlt445181355"></span>8.6<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Adding Records to a POINTER TO A FILE Field

Suppose you are editing a POINTER TO A FILE-type field. This lets you
choose an entry from another file to point to. If you have
**Learn-As-You-Go** (**LAYGO**) access to the pointed-to file, you can
also *add* new entries to it when editing the POINTER TO A FILE field.

For example, suppose you are editing the TITLE (#8) field in the NEW
PERSON (#200) file, which is a POINTER TO A FILE type field that
“points” to the TITLE (#3.1) file. What if you want to choose a TITLE
that is *not* already in the TITLE (#3.1) file? You can add it as in the
example shown in <u><span style="color:blue">Figure 92</span></u>:

<span id="_Toc527389296"></span><span id="_Ref345588479">Figure</span>
92: Records—Dialogue to Add a New Entry to a Pointed-To File: Sample
User Entries at Prompts

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

NAME: FMUSER,ONE// **<span style="background:yellow">\<Enter\></span>**

 

.

.

.

<img src="user-manual.fld/image057.png" data-border="0" width="419"
height="64"
alt="Press Enter until you reach the field in question. Entering ?? at a pointer field provides a list of entries in the pointed-to file from which to choose. - Title: Press Enter until you reach the field in question. Entering ?? at a pointer field provides a list of entries in the pointed-to file from which to choose. - Description: Press Enter until you reach the field in question. Entering ?? at a pointer field provides a list of entries in the pointed-to file from which to choose." />

TITLE: **<span style="background:yellow">??</span>**

        This is the title for the new person.

   <img src="user-manual.fld/image058.png" data-border="0" width="414"
height="63"
alt="This is a list of existing entries in the TITLE file. Press Enter to see the whole list or a caret (^) to exist the list. - Title: This is a list of existing entries in the TITLE file. Press Enter to see the whole list or a caret (^) to exist the list. - Description: This is a list of existing entries in the TITLE file. Press Enter to see the whole list or a caret (^) to exist the list." />

   Choose from:

   ACCOUNTANT

   ACCOUNTANT/TRAINEE

   ACCOUNTING TECHNICIAN

   ACCOUNTING TECHNICIAN (OA)

   ACCOUNTS MAINT CLERK (OA)

   ACCOUNTS RECEIVABLE ASSISTANT

   ACOS/AMBULATORY CARE

   ADDICTION THERAPIST

   ADJUDICATOR

   ADMIN OFFICER

   ADMIN SUPPORT ASSISTANT

   ADMINISTRATIVE ASSISTANT

   ADMINISTRATIVE INTERN

   ADMINISTRATIVE LIBRARIAN

   ADMINISTRATIVE OFFICER

   AIR COND EQUIP MECHANIC

   AIR COND EQUIP MECHANIC/HLPR

   AIR COND EQUIP MECHANIC/LDR

   ANESTHESIOLOGIST

                **<span style="background:yellow">^</span>**

        You may enter a new TITLE, if you wish

        ANSWER MUST BE 3-30 CHARACTERS IN LENGTH

  

TITLE: **<span style="background:yellow">OIT STAFF</span>**

  Are you adding ‘OIT STAFF’ as a new TITLE (the 750TH)? No//
**<span style="background:yellow">Y \<Enter\></span>** (Yes)

   TITLE OCCUPATION CODE:
**<span style="background:yellow">2210</span>**

<img src="user-manual.fld/image059.png" data-border="0" width="424"
height="53"
alt="Add a new entry by typing it in and confirming its addition to the list. - Title: Add a new entry by typing it in and confirming its addition to the list. - Description: Add a new entry by typing it in and confirming its addition to the list." />

 

SSN: 000111659// **<span style="background:yellow">\<Enter\></span>**

 

.

.

.

 

</div>

 

In this example, after adding **OIT STAFF** as a new entry, if you go
back to the TITLE field and enter **two** question marks (**??**) again
and scroll through the list, **OIT STAFF** would be one of the choices
listed for TITLE.

### <span id="_Toc527389136">8.6.1<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Adding Duplicate-Named Entries</span>

You can force an entry to be added to the pointed-to file, even if an
entry with the same value already exists in the pointed-to file. To add
a duplicate-named entry, surround the value to be added with **one** set
of quotation marks, like <u><span style="color:blue">Figure
93</span></u>:

<span id="_Toc527389297"></span><span id="_Ref523490331">Figure</span>
93: Records—Adding a Duplicate-Named Entry to a Pointed-To File

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

POINTER FIELD: **<span style="background:yellow">“FORCED NEW
ENTRY”</span>**

</div>

 

If the POINTER TO A FILE field that you are editing happens to be the
NAME (#.01) field of the current file, you can add entries to both the
current file and to the pointed-to file by surrounding your value with
**two** sets of quotation marks as shown in
<u><span style="color:blue">Figure 94</span></u>:

<span id="_Toc527389298"></span><span id="_Ref523490387">Figure</span>
94: Records—Adding an Entry to Both the Current File and to a Pointed-To
File

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

POINTER FIELD (.01): **<span style="background:yellow">““FORCED NEW
ENTRY””</span>**

</div>

 

## <span id="multiples"></span><span id="_Toc527389137">8.7<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Adding and Deleting from Multiples</span>

Some special considerations apply when you are editing Multiple-valued
fields. One example of a Multiple field is the DIAGNOSIS field in the
PATIENT (#2) file. As you recall from the
<span style="color:black">“</span><u><span style="color:blue">Field
Types</span></u>” section, a Multiple is a field in a record that can
store multiple subrecords. In this case, VA FileMan *must* be able to
store multiple diagnosis entries for a single patient, and it uses a
Multiple field to do so:

<span id="_Toc527389299"></span><span id="_Ref345588487">Figure</span>
95: Records—Dialogue Showing Entries to a Multiple Field: Sample User
Entries at Prompts

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

Select PATIENT NAME:
**<span style="background:yellow">FMPATIENT,NINE</span>**

 

NAME: FMPATIENT,NINE //
**<span style="background:yellow">\<Enter\></span>**

PATIENT DATE OF BIRTH: 4/19/49//
**<span style="background:yellow">\<Enter\></span>**

Select DIAGNOSIS: **<span style="background:yellow">??</span>**

<img src="user-manual.fld/image060.png" data-border="0" width="355"
height="48"
alt="At the DIAGNOSIS Multiple’s “Select…” prompt, enter two question marks to see what entries are currently in the Multiple. - Title: At the DIAGNOSIS Multiple’s “Select…” prompt, enter two question marks to see what entries are currently in the Multiple. - Description: At the DIAGNOSIS Multiple’s “Select…” prompt, enter two question marks to see what entries are currently in the Multiple." />

 

  1  ANGINA PECTORIS

  2  PNEUMONIA

 

ANSWER with DIAGNOSIS

     You may enter a new DIAGNOSIS, if you wish

<img src="user-manual.fld/image061.png" data-border="0" width="355"
height="57"
alt="“Select” is used before the Multiple field name, indicating you should choose one value from among several possible values. - Title: “Select” is used before the Multiple field name, indicating you should choose one value from among several possible values. - Description: “Select” is used before the Multiple field name, indicating you should choose one value from among several possible values." />

<span style="background:aqua">Select</span> DIAGNOSIS:
**<span style="background:
yellow">ANGINA PECRORIS</span>**

   DIAGNOSIS: ANGINA PECTORIS//
**<span style="background:yellow">\<Enter\></span>**

   AGE AT ONSET: **<span style="background:yellow">25</span>**

   HISTORY:

   1) **<span style="background:yellow">\<Enter\></span>**

   EDIT OPTION: **<span style="background:yellow">\<Enter\></span>**

<img src="user-manual.fld/image062.png" data-border="0" width="372"
height="48"
alt="After you edit one DIAGNOSIS Multiple entry, you are given the chance to edit another. - Title: After you edit one DIAGNOSIS Multiple entry, you are given the chance to edit another. - Description: After you edit one DIAGNOSIS Multiple entry, you are given the chance to edit another." />

Select DIAGNOSIS: **<span style="background:yellow">\<Enter\></span>**

 

Select PATIENT NAME:

</div>

 

Multiples have **.01** fields, just like records at the top-level of a
file. Thus, just as with records at the top-level of a file, you select
entries in the Multiple at the Multiple’s “Select...” prompt. You can
also add a new entry by typing it in at the Multiple’s “Select...”
prompt. You can delete an entry in a Multiple by entering an
at-sign (**@**) in the existing entry’s **.01** field.

Enter **one** question mark (**?**) at a Multiple’s “Select...” prompt
to retrieve brief help for the field; enter **two** question marks
(**??**) to choose from the list of entries in the Multiple.

## <span id="option"></span><span id="_Toc527389138"></span><span id="_Hlt446147923"></span>8.8<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Enter or Edit File Entries Option

In most cases you enter and edit data through application programs.
Applications are pre-programmed to allow you to edit specific files, and
often only a subset of the fields in any given file. The application
shields you from many aspects of editing the file data, such as even
knowing the name of the file with which you are working. Usually, this
information is already chosen for you by the application.

You can also edit data in a file directly, however, using VA FileMan’s
**Enter or Edit File Entries** \[DIEDIT\] option. Your ability to edit
data in any given file depends on:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Whether you have the **Enter or Edit File Entries**
\[DIEDIT\] option on your menu.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Whether you have access to edit the file in question.

The steps to use the **Enter or Edit File Entries** \[DIEDIT\]
option are:

1.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>At
the “INPUT TO WHAT FILE:” prompt, choose which file to edit. To see what
files you have access to, you can enter two question marks (**??**) at
this prompt:

<span id="_Toc527389300">Figure</span> 96: Records—Choosing a File to
Edit

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:45.35pt;margin-right:0in">

    INPUT TO WHAT FILE:**<span style="background:yellow">??</span>**

     Choose from:

       335235          FMUSER’S DATA          (7 entries)

       335238          PROJECTS               (3 entries)

       335668          WARD HISTORY           (178 entries)

 

    INPUT TO WHAT FILE:
**<span style="background:yellow">PROJECTS</span>**

</div>

 

<span id="Step2"></span><span id="_Hlt445540463"></span>2.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>At the “EDIT WHICH FIELD:” prompt, choose what fields to edit for
each file entry. The easiest response is to just accept the default of
**ALL** fields by pressing the **Enter** key:

<span id="_Toc527389301">Figure</span> 97: Records—Choosing the File
Fields to Edit

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:45.35pt;margin-right:0in">

EDIT WHICH FIELD: ALL//

</div>

 

If, however, you want to edit only *certain fields* (*not all* fields),
answer the “EDIT WHICH FIELD:” prompt with the name (or number) of the
*first* field you want to edit. You can then enter additional fields to
edit (when you are done, press the **Enter** key at the “THEN EDIT
FIELD:” prompt). For a list of fields that you can edit, enter **two**
question marks at any “EDIT FIELD:” prompt.

<span id="_Toc527389302">Figure</span> 98: Records—Choosing Specific
File Fields to Edit

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:45.35pt;margin-right:0in">

    EDIT WHICH FIELD: ALL//
**<span style="background:yellow">NAME</span>**

    THEN EDIT FIELD: **<span style="background:yellow">PROJECT SHORT
DESCRIPTION</span>**

    THEN EDIT FIELD: **<span style="background:yellow">PROJECT ISSUE
\<Enter\></span>** (multiple)

       EDIT WHICH PROJECT ISSUE SUB-FIELD: ALL//
**<span style="background:yellow">\<Enter\></span>**

    THEN EDIT FIELD:
**<span style="background:yellow">\<Enter\></span>**

    Select PROJECTS NAME:

</div>

 

3.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>You
can now edit entries. Choose each entry to edit at the “Select...NAME:”
prompt. Each time you choose an entry, you step through each field you
specified in [Step
2](#Step2)<span id="_Hlt445540461"></span><span id="_Hlt446149487"></span>.
When you are done with editing an entry, you are prompted for another
entry to edit at the “Select...” prompt. When you are done editing
entries, just press the **Enter** key.

<span id="_Toc527389303"></span><span id="_Ref345588496">Figure</span>
99: Records—Dialogue Using the Enter or Edit File Entries Option: Sample
User Entries at Prompts

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:45.35pt;margin-right:0in">

Select VA FileMan Option: **<span style="background:yellow">ENTER
\<Enter\></span>** or Edit File Entries

<img src="user-manual.fld/image063.png" data-border="0" width="171"
height="41"
alt="1. Choose what file to edit. - Title: 1. Choose what file to edit. - Description: 1. Choose what file to edit." />

INPUT TO WHAT FILE: PROJECTS//
**<span style="background:yellow">\<Enter\></span>** (500 entries)

<img src="user-manual.fld/image064.png" data-border="0" width="271"
height="41"
alt="2. Choose which fields to edit (default is ALL). - Title: 2. Choose which fields to edit (default is ALL). - Description: 2. Choose which fields to edit (default is ALL)." />

EDIT WHICH FIELD: ALL// **<span style="background:yellow">NAME</span>**

     1   NAME

     2   NAME COMPONENTS

CHOOSE 1-2: **<span style="background:yellow">1 \<Enter\></span>** NAME

THEN EDIT FIELD: **<span style="background:yellow">PROJECT SHORT
DESCRIPTION</span>**

THEN EDIT FIELD: **<span style="background:yellow">PROJECT ISSUE
\<Enter\></span>** (multiple)

   EDIT WHICH PROJECT ISSUE SUB-FIELD  ALL//
**<span style="background:yellow">\<Enter\></span>**

<span style="font-size:10.0pt">THEN EDIT FIELD:
**<span style="background:yellow">\<Enter\></span>**</span>

<img src="user-manual.fld/image065.png" data-border="0" width="155"
height="47"
alt="3. Choose an entry to edit. - Title: 3. Choose an entry to edit. - Description: 3. Choose an entry to edit." />

Select PROJECTS NAME: **<span style="background:yellow">??</span>**

 

Choose from:

   BUILDING 9 NETWORK CABLING

   WARD 7 CONSTRUCTION

   WARD 9 CONSTRUCTION

<img src="user-manual.fld/image066.png" data-border="0" width="161"
height="37"
alt="4. Edit the fields in the entry you choose. - Title: 4. Edit the fields in the entry you choose. - Description: 4. Edit the fields in the entry you choose." />

Select PROJECTS NAME: **<span style="background:yellow">WARD 9
CONSTRUCTION</span>**

NAME: WARD 9 CONSTRUCTION//
**<span style="background:yellow">\<Enter\></span>**

PROJECT SHORT DESCRIPTION: **<span style="background:yellow">REFURBISH
WARD</span>**

Select PROJECT ISSUE: **<span style="background:yellow">??</span>**

<img src="user-manual.fld/image067.png" data-border="0" width="256"
height="34"
alt="5. Edit the entry’s PROJECT ISSUE Multiple. - Title: 5. Edit the entry’s PROJECT ISSUE Multiple. - Description: 5. Edit the entry’s PROJECT ISSUE Multiple." />

Choose from:

   ASBESTOS REMOVAL

   CEILING TILES

   DATA cabling

   DRYWALL

   ELECTRICAL WIRING

   ‘^’ TO STOP: **<span style="background:yellow">^</span>**

 

Select PROJECT ISSUE: **<span style="background:yellow">DRYWALL</span>**

         ...OK? YES//
**<span style="background:yellow">\<Enter\></span>** (Yes)

 

  PROJECT ISSUES: DRYWALL//
**<span style="background:yellow">\<Enter\></span>**

  Date Started: **<span style="background:yellow">3/3/96
\<Enter\></span>** (MAR 03, 1996)

  Status: In Progress//
**<span style="background:yellow">\<Enter\></span>**

  Description:

    No existing text

    Edit? NO// **<span style="background:yellow">\<Enter\></span>**

 

<img src="user-manual.fld/image068.png" data-border="0" width="245"
height="53"
alt="6. You can add or edit additional entries in the Multiple here. - Title: 6. You can add or edit additional entries in the Multiple here. - Description: 6. You can add or edit additional entries in the Multiple here." />

 

Select PROJECT ISSUE:
**<span style="background:yellow">\<Enter\></span>**

<img src="user-manual.fld/image069.png" data-border="0" width="245"
height="52"
alt="7. You can add or edit additional entries in the file here. - Title: 7. You can add or edit additional entries in the file here. - Description: 7. You can add or edit additional entries in the file here." />

 

Select PROJECTS NAME:
**<span style="background:yellow">\<Enter\></span>**

 

Select VA FileMan Option:

</div>

<span id="_Ref446309239"></span><span id="_Ref446310452"></span><span id="_Ref446310664"> </span>

# <span id="_Ref524020383"></span><span id="_Ref524020561"></span><span id="_Ref524020571"></span><span id="_Ref524021987"></span><span id="_Ref524023575"></span><span id="_Toc527389139">9<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>ScreenMan</span>

ScreenMan is VA FileMan’s *screen-oriented* data entry tool. It is an
alternative to the Scrolling Mode approach. With ScreenMan, data is
entered in *forms*. Each form field occupies a fixed position on the
screen (instead of scrolling off!). You can see many data fields at once
and use simple key combinations to edit data and move from field to
field on a screen. You can also move from one screen to another; like
turning through the pages of a book.

## <span id="_Toc527389140">9.1<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Scrolling Mode Editing vs. Screen Mode Editing</span>

### <span id="_Toc527389141">9.1.1<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Similarities</span>

The following are similarities when editing in Scrolling Mode and Screen
Mode:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>You can change a field’s value by entering a different
value or delete a field’s value by entering the at-sign (**@**).

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>You can enter one or two question marks to call up a list
of acceptable responses and other help. If you enter a value deemed
unacceptable, ScreenMan displays a message explaining what type of
information should be entered.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>You can jump from the current field to any other field in
your current screen. With your cursor resting at any field’s prompt,
simply enter a caret (**^**) and then the name of the field.

### <span id="_Toc527389142">9.1.2<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Differences</span>

The following are differences when editing in Scrolling Mode and Screen
Mode:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>In Scrolling Mode, you *must* enter and store your
response to one field prompt before you can continue to the next field.
In Screen Mode, you can move the cursor from field prompt to field
prompt without entering or storing any responses.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>In Scrolling Mode, your data values or responses to field
prompts are stored one at a time, as you move from prompt to prompt. In
Screen Mode, your responses to most prompts are stored only when you
exit the form.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>The “Customize Colors” suboption within ScreenMan allows
selection of ANSI colors for all ScreenMan presentations, on a
parameterized basis (user, institution, etc.) using Kernel parameters.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>The “ScreenMan Record Selection” page can now be a full
ScreenMan page using a COMPUTED Multiple pointer, so that the user can
select an entry by scrolling up or down. This feature lets forms contain
embedded lookups.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>You can set this up automatically when you create a form.
At the query “Do you want you’re Form to begin with a display of all
entries, for selection,” answer **YES**. The initial position can be set
to be the user’s last selection, rather than first, last, or new.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>ScreenMan supports the use of a mouse for emulators that
support ANSI standard control sequences to turn the mouse on and off.
However, the Department of Veterans Affairs (VA) has elected to turn
this feature off due to support complications with
Attachmate<sup>®</sup> and Micro Focus<sup>®</sup> Reflection terminal
emulator software. The **DI SCREENMAN NO MOUSE** parameter needs to be
established for SYSTEM and set to **YES**.

<span id="_Hlt446822195"><img src="user-manual.fld/image002.png" id="Picture 124" data-border="0"
width="22" height="22" alt="Note" /></span><span style="font-size:10.0pt">    
</span>**REF:** For a detailed explanation on *creating* ScreenMan
forms, see the *ScreenMan Tutorial for Developers Manual*—available in
both Adobe Acrobat PDF and HTML formats (Zip) on the VDL:
<http://www.va.gov/vdl/application.asp?appid=5>

## <span id="_Toc527389143">9.2<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>ScreenMan Screen</span>

<span id="_Toc527389304"></span><span id="_Ref345588504">Figure</span>
100:<span id="_Hlt446223712"></span> ScreenMan—Sample Screen Component
Parts and Field Values

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

                             Edit an Existing User

<u><span style="background:aqua">NAME</span></u>:
**FMUSER,ONE                  **                                Page 1
of 5

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

   <u><span style="background:aqua">NAME...</span></u>
**FMUSER,ONE                         **         INITIAL: **OF**

    TITLE: **OIT STAFF 
                    **           <span style="background:aqua">NICK
NAME:</span> **<span style="color:white;background:black">One</span>**

      SSN: **000111659**                                       DOB:

   DEGREE: **          **                                MAIL CODE:

  DISUSER: **   **                                 TERMINATION DATE:

  Termination Reason: **                                            **

** **

           PRIMARY MENU OPTION: **EVE                          **

 Select SECONDARY MENU OPTIONS: **TIU MED MANAGEMENT           **

Want to edit ACCESS CODE (Y/N): **   **   FILE MANAGER ACCESS CODE:
**@**

Want to edit VERIFY CODE (Y/N):

** **

               Select DIVISION:

              
<u><span style="background:aqua">SERVICE/SECTION</span></u>:
**INFORMATION RESOURCES MANAGEME**

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

<span style="background:aqua">Exit     Save     Next Page    
Refresh</span>

<span style="background:aqua"> </span>

<span style="background:aqua">Enter a command or ‘^’ followed by a
caption to jump to a specific field.</span>

<span style="background:aqua"> </span>

<span style="background:aqua"> </span>

<span style="background:aqua">COMMAND:</span>
<span style="background:white">                              </span>        <span style="background:aqua">Press
\<PF1\>H for help</span>   
<span style="color:white;background:black">Insert</span><span style="background:aqua">
</span>

</div>

 

In this screen capture, you see the following highlighted areas on a
sample ScreenMan form:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Required Fields are <u>underlined</u>.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Current field where the cursor is active are shown in
<span style="color:white;
background:black">reverse video</span> (i.e., white text on black
background), such as at the “NICK NAME:” field.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Command Area below the line is where ScreenMan displays
messages, help text, and interactive dialogue. For example, if you enter
**one** or **two** question marks in a field, help is displayed in this
area.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Command Line: Here you can issue the commands **Exit**,
**Save**, **Close**, **Next Page**, and **Refresh**.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Help Reminder: This reminds the user that to get help at
any time, press **\<PF1\>H**.

Fields are usually composed of a *data element* and a *caption*.
ScreenMan displays data elements in high intensity (**boldface**) and
other text in regular intensity. Text that identifies a data element is
called a *caption* and is usually followed by a colon (**:**). A caption
and its associated data element are together called a *field*. Captions
of *required* fields are <u>underlined</u>; to save any changes you make
on the form, required fields *must* contain data.

<img src="user-manual.fld/image002.png" id="Picture 136" data-border="0"
width="22" height="22" alt="Note" /><span style="font-size:10.0pt">    
</span>**NOTE:** ScreenMan highlights captions for required fields with
an <u>underline</u>. However, on some terminals or depending on your
terminal emulator software and your personal preferences, the form of
the highlight can vary (e.g., some terminal emulators will highlight
required fields in a different color, with an <u>underline</u>, or
both).  
  
Specifically, on Qume 102 and Wyse 75 terminals, captions for required
fields display in **boldface**, *not* underlined. Also, the edit window
is displayed with an <u>underline</u> extending from the last character
of the existing data to the right edge of the edit window. VA FileMan
supports longer than **24**-line screens for those using terminal
emulators.

## <span id="_Toc527389144">9.3<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Navigation Keystrokes (Cursor Movement)</span>

### <span id="Fields"></span><span id="_Toc527389145"></span><span id="_Hlt446224508"></span>9.3.1<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>How to Navigate between Fields

There are a number of ways you can move the cursor from field to field
on a form (i.e., navigate). This is to provide you with as much
flexibility as possible so that you can work quickly and efficiently
with forms.

You can use the keystrokes listed in <u><span style="color:blue">Table
23</span></u> to move the cursor to various fields located on a
ScreenMan form:

<span id="_Toc527389347"></span><span id="_Ref345579011">Table</span>
23: ScreenMan—Keystrokes to Navigate between Fields in a ScreenMan Form

| <span id="COL001_TBL016"></span>To                       | Press                                                |
|----------------------------------------------------------|------------------------------------------------------|
| Move to the next field (to right or below).              | **\<Tab\>**                                          |
| Move to the previous field (to left or above).           | **\<PF4\>**                                          |
| Move to the field above.                                 | **\<ArrowUp\>**                                      |
| Move to the field below.                                 | **\<ArrowDown\>**                                    |
| Move to the next field in the pre-defined edit sequence. | **\<Enter\>**                                        |
| Edit a WORD-PROCESSING field.                            | At field, press **\<Enter\>**                        |
| Select a subrecord in a Multiple.                        | At field, press **\<Enter\>**                        |
| Move to the next block on current page.                  | **\<PF1\>\<PF4\>**                                   |
| Jump to a specific field.                                | **^** followed by Caption of field and **\<Enter\>** |
| Jump to the Command Line.                                | **^\<Enter\>**                                       |

 

### <span id="Pages"></span><span id="_Toc527389146">9.3.2<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>How to Navigate between Pages</span>

Many ScreenMan forms have more than one *page* (i.e., there are
additional screens besides the first one on the form) with additional
fields that you can edit.

You can use the keystrokes listed in <u><span style="color:blue">Table
24</span></u> to move between pages on a ScreenMan form:

<span id="_Toc527389348"></span><span id="_Ref345579028">Table</span>
24: ScreenMan—Keystrokes to Navigate between Pages in a ScreenMan Form

<table class="MsoNormalTable" data-border="1" data-cellspacing="0"
data-cellpadding="0" width="641"
style="margin-left:1.15pt;border-collapse:collapse;border:none">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th width="324" data-valign="top"
style="width: 242.65pt; border: solid windowtext 1.0pt; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="COL001_TBL017"></span>To</p></th>
<th width="318" data-valign="top"
style="width: 238.3pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Press</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td width="324" data-valign="top"
style="width: 242.65pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Move
to next page.</p></td>
<td width="318" data-valign="top"
style="width: 238.3pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;&lt;ArrowDown&gt;</strong>
or</p>
<p><strong>&lt;PageDown&gt;</strong></p></td>
</tr>
<tr class="even">
<td width="324" data-valign="top"
style="width: 242.65pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Move
to previous page.</p></td>
<td width="318" data-valign="top"
style="width: 238.3pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;&lt;ArrowUp&gt;</strong>
or</p>
<p><strong>&lt;PageUp&gt;</strong></p></td>
</tr>
<tr class="odd">
<td width="324" data-valign="top"
style="width: 242.65pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Move
to a page you specify.</p></td>
<td width="318" data-valign="top"
style="width: 238.3pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;P</strong></p></td>
</tr>
</tbody>
</table>

 

### <span id="Saving"></span><span id="_Toc527389147">9.3.3<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Saving and Exiting</span>

To **SAVE** or **EXIT** the form, you need to reach ScreenMan’s command
line. It’s reachable from any ScreenMan screen. To reach the command
line, do any one of the following:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Enter a caret (**^**) at any field prompt.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Press **Enter**, **Tab**, or **PF4** to move from field to
field until you reach the command line.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Press the \<**ArrowDown**\> or \<**ArrowUp**\> keys to
move the cursor from field to field downwards or upwards, until you
reach the command line.

Then you can enter **SAVE** or **EXIT** at the [command
line](#Command)<span id="_Hlt446226422"></span>.

### <span id="_Toc527389148"></span><span id="Command"></span><span id="_Hlt446226423"></span>9.3.4<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Command Line Options (SAVE, EXIT, etc.)

From the Command Line, you can issue the commands to perform various
functions while in ScreenMan. You can also use a shortcut key sequence
to perform the same function without having to enter it on the command
line.

#### 9.3.4.1<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Shortcut Keys

<span id="_Hlt446228836"></span><u><span style="color:blue">Table
25</span></u> lists the command line options and the corresponding
shortcut responses while in a ScreenMan form:

<span id="_Toc527389349"></span><span id="_Ref345583017">Table</span>
25: ScreenMan—Command Line Options and Shortcut Keystrokes in a
ScreenMan Form

<table class="MsoNormalTable" data-border="1" data-cellspacing="0"
data-cellpadding="0" width="630"
style="margin-left:1.15pt;border-collapse:collapse;border:none">
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th width="110" data-valign="top"
style="width: 82.85pt; border: solid windowtext 1.0pt; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="COL001_TBL018"></span>Command Line Option</p></th>
<th width="162" data-valign="top"
style="width: 121.5pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Shortcut</p></th>
<th width="358" data-valign="top"
style="width: 268.15pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td width="110" data-valign="top"
style="width: 82.85pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="exit"></span><span
id="_Hlt446227366"></span><strong>EXIT</strong></p></td>
<td width="162" data-valign="top"
style="width: 121.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;E</strong></p></td>
<td width="358" data-valign="top"
style="width: 268.15pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Exits
the form. If you have made any changes, ScreenMan asks if you want to
save them before exiting.</p></td>
</tr>
<tr class="even">
<td width="110" data-valign="top"
style="width: 82.85pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="save"></span><span
id="_Hlt446227371"></span><strong>SAVE</strong></p></td>
<td width="162" data-valign="top"
style="width: 121.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;S</strong></p></td>
<td width="358" data-valign="top"
style="width: 268.15pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Saves
your changes without exiting the form.</p></td>
</tr>
<tr class="odd">
<td width="110" data-valign="top"
style="width: 82.85pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="refresh"></span><span
id="_Hlt446227363"></span><strong>REFRESH</strong></p></td>
<td width="162" data-valign="top"
style="width: 121.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;R</strong></p></td>
<td width="358" data-valign="top"
style="width: 268.15pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Repaints
the pages on the screen; if for some reason the information displayed on
the screen has become corrupted.</p></td>
</tr>
<tr class="even">
<td width="110" data-valign="top"
style="width: 82.85pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="next_page"><strong>NEXT PAGE</strong></span></p></td>
<td width="162" data-valign="top"
style="width: 121.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;&lt;ArrowDown&gt;</strong>
or</p>
<p><strong>&lt;PageDown&gt;</strong></p></td>
<td width="358" data-valign="top"
style="width: 268.15pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>(Available
only on multi-page forms.) Goes to the next page of the form.</p></td>
</tr>
<tr class="odd">
<td width="110" data-valign="top"
style="width: 82.85pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="close"></span><span
id="_Hlt446227361"></span><strong>CLOSE</strong></p></td>
<td width="162" data-valign="top"
style="width: 121.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;C</strong></p></td>
<td width="358" data-valign="top"
style="width: 268.15pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>(Available
only on “popup” pages.) Closes the current page and returns you to the
parent page.</p></td>
</tr>
<tr class="even">
<td width="110" data-valign="top"
style="width: 82.85pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="quit"></span><span id="_Hlt446227368"></span>(none)</p></td>
<td width="162" data-valign="top"
style="width: 121.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;Q</strong></p></td>
<td width="358" data-valign="top"
style="width: 268.15pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Quit
the form, discarding changes.</p></td>
</tr>
</tbody>
</table>

 

<img src="user-manual.fld/image002.png" id="Picture 137" data-border="0"
width="22" height="22" alt="Note" /><span style="font-size:10.0pt">    
</span>**NOTE:** On a “popup” page, your only Command Line options are
**CLOSE** and **REFRESH**.

## <span id="_Toc527389149">9.4<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Editing</span><span id="_Hlt446224483"></span>

### <span id="Fields_Edit"></span><span id="_Toc527389150">9.4.1<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>How to Edit Fields</span>

<u><span style="color:blue">Table 26</span></u>,
<u><span style="color:blue">Table 27</span></u>,
<u><span style="color:blue">Table 28</span></u>, and
<u><span style="color:blue">Table 29</span></u> list the key sequences
for ScreenMan’s Field Editor; the editor that allows you to edit data
fields on a ScreenMan Form.

#### 9.4.1.1<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Cursor Movement

<u><span style="color:blue">Table 26</span></u> lists the keystrokes you
use to move the cursor while in a ScreenMan form:

<span id="_Toc527389350"></span><span id="_Ref345583033">Table</span>
26: ScreenMan—Keystrokes to Move the Cursor in a ScreenMan Form

| <span id="COL001_TBL019"></span>To Move | Press                                     |
|-----------------------------------------|-------------------------------------------|
| Right one character.                    | **\<ArrowRight\>**                        |
| Left one character.                     | **\<ArrowLeft\>**                         |
| Right one word.                         | **\<Ctrl-L\>** or **\<PF1\>\<Spacebar\>** |
| Left one word.                          | **\<Ctrl-J\>**                            |
| Right edge of window.                   | **\<PF1\>\<ArrowRight\>**                 |
| Left edge of window.                    | **\<PF1\>\<ArrowLeft\>**                  |
| End of field.                           | **\<PF1\>\<PF1\>\<ArrowRight\>**          |
| Beginning of field.                     | **\<PF1\>\<PF1\>\<ArrowLeft\>**           |

 

#### 9.4.1.2<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Deletion

<u><span style="color:blue">Table 27</span></u> lists the keystrokes you
use to delete characters while in a ScreenMan form:

<span id="_Toc527389351"></span><span id="_Ref345583054">Table</span>
27: ScreenMan—Keystrokes to Delete Characters in a ScreenMan Form

| <span id="COL001_TBL020"></span>To Delete                  | Press                                           |
|------------------------------------------------------------|-------------------------------------------------|
| Character under cursor.                                    | **\<PF2\>** or **\<Delete\>** or **\<Remove\>** |
| Character left of cursor.                                  | **\<Backspace\>**                               |
| From cursor to end of word.                                | **\<Ctrl-W\>**                                  |
| From cursor to end of field.                               | **\<PF1\>\<PF2\>**                              |
| Delete entire field / Restore last edit / Restore default. | **\<PF1\>D** or **\<Ctrl-U\>**                  |

 

#### 9.4.1.3<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Modes

<u><span style="color:blue">Table 28</span></u> lists the keystrokes you
use to switch modes while in a ScreenMan form:

<span id="_Toc527389352"></span><span id="_Ref345583068">Table</span>
28: ScreenMan—Keystrokes to Switch Modes in a ScreenMan Form

| <span id="COL001_TBL021"></span>To Switch to | Press        |
|----------------------------------------------|--------------|
| Insert/Replace mode.                         | **\<PF3\>**  |
| Zoom editor (edit long fields).              | **\<PF1\>Z** |

 

If the first key you press upon navigating to a field is a printable
character, the Field Editor assumes you want to replace any existing
default and replaces the entire field with the character just typed. To
just edit the existing field value, first press an editing key, such as
**\<ArrowLeft\>** or **\<ArrowRight\>**.

### <span id="Long"></span><span id="_Toc527389151">9.4.2<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Long Fields (and the Zoom Editor)</span>

The actual contents of a field being edited can extend beyond the
confines of the visible field on a ScreenMan form. As you use the
**\<ArrowLeft\>** and **\<ArrowRight\>** keys at the left and right
edges of the window, you can scroll left or right to display one end or
the other of the field.

To see and edit the entire contents of a long field at once, press
**\<PF1\>Z** to invoke the Zoom Editor. This opens an area up at the
bottom of the screen, providing you as much space as you need to both
see and edit the entire long field.

### <span id="Wp"></span><span id="_Toc527389152">9.4.3<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>WORD-PROCESSING Fields</span>

To edit or display a WORD-PROCESSING field, press the **Enter** key at
the WORD-PROCESSING field. This clears the screen and passes control to
your Preferred Editor to edit the field. If you do *not* have a
Preferred Editor, the <u><span style="color:blue">Screen
Editor</span></u> is used. When you exit the editor, you return to the
ScreenMan screen.

<span id="_Hlt446381626"></span><img src="user-manual.fld/image002.png" id="Picture 138" data-border="0"
width="22" height="22" alt="Note" />     **REF:** To set your Preferred
Editor, see the “<u><span style="color:blue">Choosing a Preferred
Editor</span></u>” section.

<img src="user-manual.fld/image002.png" id="Picture 139" data-border="0"
width="22" height="22" alt="Note" /><span style="font-size:10.0pt">    
</span><span class="NoteChar">**<span style="font-size:11.0pt">NOTE</span>**</span><span class="NoteChar"><span style="font-size:11.0pt">:
If the WORD-PROCESSING field is uneditable or appears in a display
block, you can view the contents of the field with an editor. However,
if you edit the text, your changes are *not* filed in the permanent
database, even if you tell the editor to save the changes. A plus sign
(**+**) in a ScreenMan form indicates whether a WORD-PROCESSING field
already contains data. If users have their PREFERRED EDITOR field set to
**SCREEN EDITOR – VA FILEMAN**, the previous message “**No existing
Text**” has been modified to “**THERE ARE NO LINES!**” if a
WORD-PROCESSING field has no data.</span></span>

 

### <span id="_Toc527389153">9.4.4<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Multiples</span>

You can easily spot a Multiple field. It usually begins with the word
“Select” (as in “Select ADDRESS” or “Select ADMISSION DATE”). There are
two ways Multiples can be displayed on a form:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>The Multiple is linked to a “popup” subpage, which
contains the subfields of the Multiple.

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>The Multiple is displayed in a repeating block—several
subrecords can be displayed simultaneously on a page, much like a
scrolling list and the Multiples within a single SreenMan page can be
more than one line deep.

#### 9.4.4.1<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Multiples Linked to “Popup” Subpages

A Multiple field can appear on a page and be linked to a regular or
“popup” subpage. When you navigate to the Multiple field, select a
subrecord, and press **Enter**, you are taken to the subpage that
contains the fields within the Multiple.

In <u><span style="color:blue">Figure 101</span></u>, the Multiple is
the field with the caption “Select SECONDARY MENU OPTIONS:”. When you
enter a secondary menu option at this field, you are taken into a
“popup” subpage, where you can edit the fields for that particular
subrecord:

<span id="_Toc527389305"></span><span id="_Ref345579056">Figure</span>
101: ScreenMan—A “Popup” Subpage for a Multiple: Sample Component Parts
and Field Values

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

                             Edit an Existing User

<u>NAME</u>: **FMUSER,ONE                  **
                                  Page 1 of 5

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

   <u>NAME...</u> **FMUSER,ONE                       **
          INITIAL: **OF  **

    TITLE: **OIT STAFF                      **           NICK NAME:
**One     **

      SSN: **000111659**                                       DOB:
**           **

   DEGREE: **          **                                MAIL CODE:
**          **

  DISUSER: **   **                                 TERMINATION DATE:
**           **

  Termination Reason: **                                             **

** **

** **

** **

       
<span style="font-family:r_symbol">R,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,T</span>

 Select
<span style="font-family:r_symbol">.</span>                                
SECONDARY MENU OPTIONS <span style="font-family:r_symbol">.</span>

Want to
<span style="font-family:r_symbol">.</span>                                                       
<span style="font-family:r_symbol">.</span>

Want to <span style="font-family:r_symbol">.</span> SECONDARY MENU
OPTIONS: <span style="background:aqua">XU CHECKSUM
REPORT</span>             <span style="font-family:r_symbol">.</span>

        <span style="font-family:r_symbol">.</span>               
SYNONYM:                               
<span style="font-family:r_symbol">.</span>

       
<span style="font-family:r_symbol">.</span>                                                       
<span style="font-family:r_symbol">.</span>

       
<span style="font-family:r_symbol">F,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,G</span>

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Close     Refresh

 

Enter a command or ‘^’ followed by a caption to jump to a specific
field.

 

 

COMMAND: Close                                 Press \<PF1\>H for
help    <span style="color:white;background:black">Insert</span>

</div>

 

In this example, the popup subpage displays when an entry was made at
the “Select SECONDARY MENU OPTIONS” prompt. The user can edit the
selected entry for the Multiple in this popup subpage.

#### 9.4.4.2<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Exiting a Subpage

While in a subpage, your only Command Line options are
[**CLOSE**](#close)<span id="_Hlt446227359"></span> and
[**REFRESH**](#refresh)<span id="_Hlt446227362"></span>. You *cannot*
[**EXIT**](#exit)<span id="_Hlt446227365"></span>,
<span id="_Hlt446227367"></span>[**Quit**](#quit), or
[**SAVE**](#save)<span id="_Hlt446227369"></span> until you return to
the parent page. You can return to the parent page by pressing
**\<PF1\>C** or issuing the
[**CLOSE**](#close)<span id="_Hlt446227372"></span> command at the
Command Line. From there, you can select another subrecord to edit or
navigate to another field.

#### 9.4.4.3<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Deleting an Entry in a Multiple

If a default subrecord is displayed at a Multiple field, you can delete
that subrecord by entering an at-sign (**@**) at the Multiple field. You
can also delete a specific subrecord by selecting that subrecord and
going into the subpage and entering an at-sign (**@**) at the **.01**
field.

<img src="user-manual.fld/image003.png" data-border="0" width="32"
height="32" alt="Caution" />    CAUTION: Deletions of subrecords are
immediate and permanent; even if you quit the form without saving,
deleted subrecords are *not* restored to the database.

#### 9.4.4.4<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Adding a New Entry to a Multiple

You can respond to a Multiple field in one of two ways:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Accept the field’s default answer.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Enter a new item: an employee’s second address, for
example, or another admission date for the same patient.

To enter a new entry in a Multiple, enter the new value for the new
entry in the Multiple’s **.01** field. If you have **LAYGO** access
(permission to add new entries), you are asked if you want to add the
entry to the Multiple. To change your mind about adding the item, enter
**NO**. If you enter **YES**, though, ScreenMan opens either a “popup”
page or a new window, allowing you to enter additional information for
the new Multiple entry.

#### 9.4.4.5<span style="font:7.0pt &quot;Times New Roman&quot;">         </span>Multiples in Repeating Blocks

Subrecords in a Multiple can be displayed in another way. Rather than
just the name of single entry in the Multiple being displayed on the
current page, you can also see Multiples where several subrecords are
displayed simultaneously on the page. Each subrecord occupies one line
on the screen, in a scrolling list. This is called a repeating block.
Instead of leading to a “popup” page, you can edit all visible fields in
the Multiple as they are displayed.

For example:

<span id="_Toc527389306"></span><span id="_Ref345588519">Figure</span>
102: ScreenMan—Dialogue Showing a Repeating Block in a Multiple: Sample
ScreenMan Fields and Field Values

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

                             Employee Profile

<u>NAME</u>: **FMUSER,ONE                  **
                                  Page 1 of 2

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

 

                              NAME: FMUSER,ONE

                         NICK NAME: ONE

                             TITLE: ARTIFICIAL INTELLIGENCE THEORETICIAN

         POSITION DESCRIPTION (WP):

 

   <span style="background:aqua">DATE OF EMPLOYMENT  
EMPLOYER                                   YEARS WORKED</span>

   —————————————————-   ———————-                                  
———————————-

   **<span style="background:aqua">+</span>**FEB 1, 1967         TEST
EMPLOYER B                                 2

    MAR 1, 1969         TEST EMPLOYER C                                
3

    APR 1, 1972         TEST EMPLOYER D 
                               4

    MAY 1, 1976         TEST EMPLOYER E                                
5

 

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Exit     Save    Next Page    Refresh

 

Enter a command or ‘^’ followed by a caption to jump to a specific
field.

 

 

COMMAND: Close                                 Press \<PF1\>H for
help    <span style="color:white;background:black">Insert</span>

</div>

 

In this example, the employment data is the Repeated Block for the
Multiple. There are **four** entries in the Multiple that are visible.
The plus sign (**+**) indicates more records exist in the list above.

You can always navigate to a blank line below the end of the list. At
this blank line, you can add a new subrecord if **LAYGO** is allowed or
jump to an existing subrecord by entering its name.

### <span id="_Toc527389154">9.4.5<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Navigational Keys for Repeating Blocks</span>

<u><span style="color:blue">Table 29</span></u> lists the keystrokes you
use to navigate while in a Repeating Block in a ScreenMan
form:<span id="_Hlt446230513"></span>

<span id="_Toc527389353"></span><span id="_Ref345583086">Table</span>
29: ScreenMan—Keystrokes to Navigate Repeating Blocks in a ScreenMan
Form

<table class="MsoNormalTable" data-border="1" data-cellspacing="0"
data-cellpadding="0" width="641"
style="margin-left:1.15pt;border-collapse:collapse;border:none">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th width="324" data-valign="top"
style="width: 242.65pt; border: solid windowtext 1.0pt; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="COL001_TBL022"></span>To</p></th>
<th width="318" data-valign="top"
style="width: 238.3pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Press</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td width="324" data-valign="top"
style="width: 242.65pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Scroll
through the list.</p></td>
<td width="318" data-valign="top"
style="width: 238.3pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;ArrowUp&gt;</strong>
and</p>
<p><strong>&lt;ArrowDown&gt;</strong></p></td>
</tr>
<tr class="even">
<td width="324" data-valign="top"
style="width: 242.65pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Page
down through the list.</p></td>
<td width="318" data-valign="top"
style="width: 238.3pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;&lt;ArrowDown&gt;</strong>
or <strong>&lt;PageDown&gt;</strong></p></td>
</tr>
<tr class="odd">
<td width="324" data-valign="top"
style="width: 242.65pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Page
up through the list.</p></td>
<td width="318" data-valign="top"
style="width: 238.3pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;&lt;ArrowUp&gt;</strong>
or <strong>&lt;PageUp&gt;</strong></p></td>
</tr>
<tr class="even">
<td width="324" data-valign="top"
style="width: 242.65pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Jump
to the blank line at end of list.</p></td>
<td width="318" data-valign="top"
style="width: 238.3pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>^&lt;Enter&gt;</strong>
in a <em>non</em>-blank line</p></td>
</tr>
<tr class="odd">
<td width="324" data-valign="top"
style="width: 242.65pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Jump
to the Command line.</p></td>
<td width="318" data-valign="top"
style="width: 238.3pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>^&lt;Enter&gt;</strong>
at the end of the list</p></td>
</tr>
</tbody>
</table>

 

## <span id="_Toc527389155">9.5<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Details</span>

### <span id="Filed"></span><span id="_Toc527389156">9.5.1<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>How to File Edits</span>

In general, the database is unaffected while you edit a record in a
ScreenMan form. Changes are filed only at your request, when you
[**SAVE**](#save)<span id="_Hlt446227851"></span> or
[**EXIT**](#exit)<span id="_Hlt446227853"></span>.

Before filing, ScreenMan checks that:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Required fields on all pages that can be accessed via the
**Next** and **Previous** page links have values, even if you have *not*
accessed those pages during the editing session.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>If you have accessed any subpages, required fields in
those subpages *must* also have values.

If any required field is empty, you *cannot* file any data changes. When
you attempt to file, ScreenMan displays a list of those fields that
require values.

The **\<PF1\>Q** key sequence allows you to [**Quit**](#quit) the form
without saving changes. Filing does *not* occur if you time out.

<img src="user-manual.fld/image003.png" id="Picture 40" data-border="0"
width="32" height="32" alt="Caution" />    CAUTION: There is one
situation in which a change to the database is made immediately: when
you delete an entry from a file or subfile. When you attempt to delete
an entry, ScreenMan issues a warning that deletions are immediate and
permanent. Even if you [Quit](#quit) the form without
[saving](#save)<span id="_Hlt446227890"></span> your changes, the entry
is *not* restored to the database.

### <span id="_Toc527389157">9.5.2<span style="font:7.0pt &quot;Times New Roman&quot;">       </span>Troubleshooting</span>

While screen displays offer many advantages, they also require that the
software can correctly identify the type of terminal being used or
emulated. An incorrect identification may produce unreadable and
unusable screens. To exit such a screen, enter **^\<Enter\>^\<Enter\>**.

If you continue to find the screens are unreadable, check the following
sources for troubleshooting information:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>“Syste<span id="_Hlt446227906">m</span> Management”
section in the *VA FileMan Advanced User Manual* (e.g., the “Device
Handling for Standalone VA FileMan” section).

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>*Kernel 8.0 & Kernel Toolkit 7.3 Systems Management Guide*
(look for information on “Device Type at Signon” and changing your
terminal type).

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Systems Administrator.

 

# <span id="_Ref446306018"></span><span id="_Ref446306186"></span><span id="_Ref446306296"></span><span id="_Ref446306765"></span><span id="_Ref446310313"></span><span id="_Ref446310677"></span><span id="_Ref387227123"></span><span id="_Ref387232054"></span><span id="_Ref387232207"></span><span id="_Ref387304793"></span><span id="_Ref387304838"></span><span id="_Toc527389158"></span><span id="_Hlt446306085"></span>10<span style="font:7.0pt &quot;Times New Roman&quot;">    </span>Word-Processing Fields

## <span id="_Toc527389159">10.1<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Word-Processing Editors</span>

WORD-PROCESSING-type fields are typically used so that you can write,
edit, and format text for letters and reports, text information in
patient records, electronic MailMan messages, application packages,
responses, and so on.

VA FileMan provides two editors for WORD-PROCESSING fields:

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Line Editor</span></u>

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Screen Editor</span></u>

The system manager can provide other editors as well (e.g., Extensible
Editor).

You can s<span id="_Hlt446304948">e</span>lect any of the available
editors on the system as your Preferred Editor. If you select a
Preferred Editor that editor is used whenever you edit a WORD-PROCESSING
field. If you *do not* choose a Preferred Editor, the following defaults
are used:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Line
Editor</span></u>**—**When editing WORD-PROCESSING fields from Scrolling
Mode.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Screen
Editor</span></u>**—**When editing WORD-PROCESSING fields from a
ScreenMan form.

## <span id="_Ref523921860"></span><span id="_Ref523999968"></span><span id="_Ref524007100"></span><span id="_Toc527389160">10.2<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Choosing a Preferred Editor</span>

To select your preferred editor, perform the following procedure:

1.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>At
any menu prompt, enter “**TBOX**" to go to the **User’s
Toolbox** \[<span style="color:windowtext">XUSERTOOLS</span>\] menu.

2.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>From
the **User’s
Toolbox** \[<span style="color:windowtext">XUSERTOOLS</span>\] menu,
choose the **Edit User
Characteristics** \[<span style="color:windowtext">XUSEREDITSELF</span>\]
option.

3.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>At
the “Select TERMINAL TYPE NAME:" prompt, you can usually just accept the
default by pressing the **Enter** key.

4.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>You
are now placed in a ScreenMan form where you can edit your user
characteristics. Press **\<ArrowDown\>** until your cursor arrives at
the “PREFERRED EDITOR:” prompt.

5.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>At
the “PREFERRED EDITOR:” prompt, you can choose your Preferred Editor.
Enter **two** question marks (**??**) to get a list of the available
editors on your system. Choose one as your Preferred Editor and then
press the **Enter** key. The Screen Editor is usually a good choice.

6.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>Press
**\<PF1\>E** to exit the
<u><span style="color:blue">ScreenMan</span></u> form. If you are asked
whether to save changes before leaving the form, answer **YES**.

Your Preferred Editor should now be set to the editor you have chosen.
This is the editor that is used whenever you edit the contents of a
WORD-PROCESSING field.

## <span id="switch"></span><span id="_Toc527389161">10.3<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Switching to another Editor While Editing</span>

Selecting your default editor determines which editor is used whenever
you edit a WORD-PROCESSING field. However, if you want to *temporarily*
switch to another editor once you have started editing, both the Screen
Editor and the Line Editor allow you to do this:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>In the <u><span style="color:blue">Screen
Editor</span></u>:

1.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>Press
**\<PF1\>A**.

2.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Choose the editor to which you wish to switch.

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>In the <u><span style="color:blue">Line Editor</span></u>:

1.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Choose the **Utilities in Word-processing** option.

2.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>At
the “Edit Option:” prompt, choose **Editor Change**.

3.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Choose the editor to which you wish to switch.

<img src="user-manual.fld/image002.png" id="Picture 142" data-border="0"
width="22" height="22" alt="Note" /><span style="font-size:10.0pt">    
</span>**REF:** For more information on the Screen Editor, see the
“<u><span style="color:blue">Screen Editor</span></u>” section. For more
information on the Line Editor, see the
“<u><span style="color:blue">Line Editor</span></u>” section.

<span id="_Ref446305738"></span><span id="_Ref446306055"></span><span id="_Ref446309773"></span><span id="_Ref446310321"></span><span id="_Ref446310687"></span><span id="_Hlt446306062"></span> 

# <span id="_Ref524020384"></span><span id="_Ref524020606"></span><span id="_Ref524020622"></span><span id="_Ref524020936"></span><span id="_Ref524021779"></span><span id="_Ref524022289"></span><span id="_Ref524022383"></span><span id="_Ref524022683"></span><span id="_Ref524023461"></span><span id="_Ref524023608"></span><span id="_Ref524023934"></span><span id="_Toc527389162">11<span style="font:7.0pt &quot;Times New Roman&quot;">    </span>Screen Editor</span>

<span id="_Hlt446205132"></span>To edit the contents of DATA TYPE field
values of WORD-PROCESSING in files, you need to use a word-processing
editor. VA FileMan provides two standard editors:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Screen Editor

<span style="font-family:Symbol;color:black">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span><u><span style="color:blue">Line Editor</span></u>

The Screen Editor provides flexibility and freedom *not* provided by the
<u><span style="color:blue">Line Editor</span></u>. The Screen Editor
provides such features as the following:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Full-screen editing

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Automatic text wrapping

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Search-and-replace

In most cases, you would want your default editor to be the Screen
Editor.

For most people, the Screen Editor should be your Preferred Editor for
WORD-PROCESSING fields.

<img src="user-manual.fld/image002.png" id="Picture 143" data-border="0"
width="22" height="22" alt="Note" />     **REF:** To set your default
editor, see the “<u><span style="color:blue">Choosing a Preferred
Editor</span></u>” section. This section also explains how you can
switch your current editor on-the-fly.

<img src="user-manual.fld/image002.png" id="Picture 144" data-border="0"
width="22" height="22" alt="Note" /><span style="font-size:10.0pt">    
</span>**REF:** For more information on the Line Editor, see the
“<u><span style="color:blue">Line Editor</span></u>” section.

If you enter **\<PF1\>H** at any time in the Screen Editor, you can get
online help that lists all the available commands.

At any time, while entering text using the Screen Editor, you can select
a command. For example, at any time you can change your left margin,
move to a different screen, save your document, or get online help. To
invoke most commands, you need to enter only two keystrokes: the
**\<PF1\>** key and a character key, such as **D** for delete line.

You usually find the **\<PF\>** keys at the top or right-hand side of
your terminal keyboard, along with the numeric keypad. If you are using
a personal computer rather than a computer terminal, the **\<PF\>** keys
are mostly likely re-mapped to another set of keys (consult your system
administrator to find out to what keys the **\<PF1\>** through
**\<PF4\>** are re-mapped).

## <span id="Main_screen"></span><span id="_Toc527389163">11.1<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Screen E</span><span id="_Hlt446208527"></span>ditor Screen

<span id="_Hlt446223797"></span>The Screen Editor display consists of a
status bar at the top and a ruler at the bottom. Between the two status
bars is the area where you create and edit text, as shown in
<u><span style="color:blue">Figure 103</span></u>:

<span id="_Toc527389307"></span><span id="_Ref345588527">Figure</span>
103: Screen Editor—Sample WORD-PROCESSING Field in the Screen Editor:
Sample Component Parts

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

 

==\[ <span style="background:aqua">WRAP</span> \]==\[
<span style="background:aqua">INSERT</span> \]============\<
<span style="background:aqua">FIELD NAME</span> \>============\[
<span style="background:aqua">\<PF1\>H=Help</span> \]====

<img src="user-manual.fld/image070.png" data-border="0" width="92"
height="65"
alt="Wrap Mode is set to “ON.” - Title: Wrap Mode is set to “ON.” - Description: Wrap Mode is set to “ON.”" /> <img src="user-manual.fld/image071.png" data-border="0" width="92"
height="67"
alt="Insert Mode is set to “ON.” - Title: Insert Mode is set to “ON.” - Description: Insert Mode is set to “ON.”" /> 
<img src="user-manual.fld/image072.png" data-border="0" width="104"
height="72"
alt="Name of word-processing field being edited. - Title: Name of word-processing field being edited. - Description: Name of word-processing field being edited." />   <img src="user-manual.fld/image073.png" data-border="0" width="123"
height="70"
alt="&lt;PF1&gt;H displays help for all Screen Editor commands. - Title: &lt;PF1&gt;H displays help for all Screen Editor commands. - Description: &lt;PF1&gt;H displays help for all Screen Editor commands." />

 

 

 

 

<img src="user-manual.fld/image074.png" data-border="0" width="101"
height="56"
alt="Location of left margin (&lt;). - Title: Location of left margin (&lt;) - Description: Location of left margin (&lt;)" />       
<img src="user-manual.fld/image075.png" data-border="0" width="99"
height="35"
alt="Tab stops (“T”). - Title: Tab stops (“T”). - Description: Tab stops (“T”)." />                <img src="user-manual.fld/image076.png" data-border="0" width="109"
height="55"
alt="Location of right margin (&gt;). - Title: Location of right margin (&gt;). - Description: Location of right margin (&gt;)." />

<span style="background:aqua">\<</span>=======<span style="background:aqua">T</span>=======<span style="background:aqua">T</span>=======<span style="background:aqua">T</span>=======<span style="background:aqua">T</span>=======<span style="background:aqua">T</span>=======<span style="background:aqua">T</span>=======<span style="background:aqua">T</span>=======<span style="background:aqua">T</span>=======<span style="background:aqua">T\></span>======

<span style="background:aqua">Scr 1 of 52                           Ln 1
of 97                          Col 1</span>

 

<img src="user-manual.fld/image077.png" data-border="0" width="433"
height="58"
alt="The bottom line, with the current screen, line, and column numbers, is ordinarily hidden. The &lt;PF1&gt;? toggles display of this line. - Title: The bottom line, with the current screen, line, and column numbers, is ordinarily hidden. The &lt;PF1&gt;? toggles display of this line. - Description: The bottom line, with the current screen, line, and column numbers, is ordinarily hidden. The &lt;PF1&gt;? toggles display of this line." />

</div>

 

## <span id="Entering_text"></span><span id="_Toc527389164">11.2<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Entering Text</span>

When using the Screen Editor, you type your text as you normally would.
As you type, the Screen Editor automatically wraps lines of text to fit
within the left and right margins. There is no need to press the
**Enter** key at the end of each line. The Screen Editor accepts any
printable characters as keyboard input. However, it *cannot* be used to
edit text that contains control characters.

## <span id="Commands"></span><span id="_Toc527389165"></span><span id="_Hlt448902028"></span>11.3<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Entering Commands

Editor commands are invoked using keyboard command sequences. The Screen
Editor makes use of the **\<PF\>** keys, the cursor keypad, and, if
available on the keyboard, the edit keypad to perform its editing
functions.

## <span id="Cursor"></span><span id="_Toc527389166">11.4<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Navigation Keystrokes (</span><span id="_Hlt446224550"></span>Cursor Movement)

<span id="_Hlt446205423"></span><span id="_Hlt446224726"></span>

<span id="_Hlt446229129"></span><u><span style="color:blue">Table
30</span></u> lists the keystrokes you use to navigate while in the
Screen Editor<span id="_Hlt446204867"></span>:

<span id="_Toc527389354"></span><span id="_Ref345576164">Table</span>
30: Screen Editor—Keystrokes to Navigate in the Screen Editor

<div align="center">

<table class="MsoNormalTable" data-border="1" data-cellspacing="0"
data-cellpadding="0" style="border-collapse:collapse;border:none">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th width="258" data-valign="top"
style="width: 193.5pt; border: solid windowtext 1.0pt; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="COL001_TBL023"></span>Action</p></th>
<th width="366" data-valign="top"
style="width: 274.45pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Key
Sequence</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td width="258" data-valign="top"
style="width: 193.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Move
one column left or right.</p></td>
<td width="366" data-valign="top"
style="width: 274.45pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;ArrowLeft&gt;</strong>
or <strong>&lt;ArrowRight&gt;</strong></p></td>
</tr>
<tr class="even">
<td width="258" data-valign="top"
style="width: 193.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Move
one line up or down.</p></td>
<td width="366" data-valign="top"
style="width: 274.45pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;ArrowUp&gt;</strong>
or <strong>&lt;ArrowDown&gt;</strong></p></td>
</tr>
<tr class="odd">
<td width="258" data-valign="top"
style="width: 193.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Move
one word left or right.</p></td>
<td width="366" data-valign="top"
style="width: 274.45pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;Ctrl&gt;J</strong>
or <strong>&lt;Ctrl&gt;L</strong></p></td>
</tr>
<tr class="even">
<td width="258" data-valign="top"
style="width: 193.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Move
to next tab stop to the right.</p></td>
<td width="366" data-valign="top"
style="width: 274.45pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;Tab&gt;</strong></p></td>
</tr>
<tr class="odd">
<td width="258" data-valign="top"
style="width: 193.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Move
cursor left or right one screen.</p></td>
<td width="366" data-valign="top"
style="width: 274.45pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;&lt;ArrowLeft&gt;</strong>
or <strong>&lt;PF1&gt;&lt;ArrowRight&gt;</strong></p></td>
</tr>
<tr class="even">
<td width="258" data-valign="top"
style="width: 193.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Move
cursor to beginning or end of line.</p></td>
<td width="366" data-valign="top"
style="width: 274.45pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;&lt;PF1&gt;&lt;ArrowLeft&gt;</strong>
or <strong>&lt;PF1&gt;&lt;PF1&gt;&lt;ArrowRight&gt;</strong></p>
<p>Or: <strong>&lt;Find&gt;</strong> or
<strong>&lt;Select&gt;</strong></p>
<p>Or: <strong>&lt;Home&gt;</strong> or
<strong>&lt;End&gt;</strong></p></td>
</tr>
<tr class="odd">
<td width="258" data-valign="top"
style="width: 193.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Move
cursor one screen up or down.</p></td>
<td width="366" data-valign="top"
style="width: 274.45pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;&lt;ArrowUp&gt;</strong>
or <strong>&lt;PF1&gt;&lt;ArrowDown&gt;</strong></p>
<p>Or: <strong>&lt;PrevScreen&gt;</strong> or
<strong>&lt;NextScreen&gt;</strong></p>
<p>Or: <strong>&lt;Page Up&gt;</strong> or <strong>&lt;Page
Down&gt;</strong></p></td>
</tr>
<tr class="even">
<td width="258" data-valign="top"
style="width: 193.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Move
to top or bottom of document.</p></td>
<td width="366" data-valign="top"
style="width: 274.45pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;T</strong>
or <strong>&lt;PF1&gt;B</strong></p></td>
</tr>
<tr class="odd">
<td width="258" data-valign="top"
style="width: 193.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Go
to a specific screen, line, or column.</p></td>
<td width="366" data-valign="top"
style="width: 274.45pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;G</strong></p></td>
</tr>
</tbody>
</table>

</div>

 

You can *move forward quickly across a line* by pressing the **Tab** key
(**\<Tab\>**). The **Tab** key in the Screen Editor does *not* insert
anything into the text. The **Tab** key is for navigation only and
simply moves the cursor to the next tab stop to the right. Another way
to move across a line, either forward or backward, is to move a word at
a time, using **\<Ctrl\>J** or **\<Ctrl\>L**.

## <span id="_Toc527389167"></span><span id="Exiting_Saving">11.5<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Saving, Printing, and</span> Exiting

<u><span style="color:blue">Table 31</span></u> lists the keystrokes you
use to exit and save text while in the Screen Editor:

<span id="_Toc527389355"></span><span id="_Ref345576275">Table</span>
31: Screen Editor—Keystrokes to Exit and Save Text in the Screen Editor

<div align="center">

<table class="MsoNormalTable" data-border="1" data-cellspacing="0"
data-cellpadding="0" style="border-collapse:collapse;border:none">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th width="324" data-valign="top"
style="width: 242.65pt; border: solid windowtext 1.0pt; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="COL001_TBL024"></span>Action</p></th>
<th width="300" data-valign="top"
style="width: 225.35pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Key
Sequence</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td width="324" data-valign="top"
style="width: 242.65pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Exit
and save text</p></td>
<td width="300" data-valign="top"
style="width: 225.35pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;E</strong></p>
<p>Or</p>
<p>Enter <strong>two</strong> carriage returns (press
<strong>Enter</strong> twice) at the end of the document to exit
ScreenMan.</p></td>
</tr>
<tr class="even">
<td width="324" data-valign="top"
style="width: 242.65pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Quit
without saving</p></td>
<td width="300" data-valign="top"
style="width: 225.35pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;Q</strong></p></td>
</tr>
<tr class="odd">
<td width="324" data-valign="top"
style="width: 242.65pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Exit,
save, and switch editors</p></td>
<td width="300" data-valign="top"
style="width: 225.35pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;A</strong></p></td>
</tr>
<tr class="even">
<td width="324" data-valign="top"
style="width: 242.65pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Save
without exiting</p></td>
<td width="300" data-valign="top"
style="width: 225.35pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;S</strong></p></td>
</tr>
<tr class="odd">
<td width="324" data-valign="top"
style="width: 242.65pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Screen
Print (including all multiples)</p></td>
<td width="300" data-valign="top"
style="width: 225.35pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;P</strong></p></td>
</tr>
</tbody>
</table>

</div>

 

If your editing session ends unexpectedly because of hardware failure or
another reason that prevents normal exiting, any changes you have made
in the current WORD-PROCESSING field *are not* saved. On the other hand,
if you time out when editing text, your changes *are* saved.

## <span id="Finding"></span><span id="_Toc527389168">11.6<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Finding Text</span>

<span id="_Hlt448902503"></span><u><span style="color:blue">Table
32</span></u> lists the keystrokes you use to find text while in the
Screen Editor:

<span id="_Toc527389356"></span><span id="_Ref345576495">Table</span>
32: Screen Editor—Keystrokes to Find Text in the Screen Editor

<div align="center">

<table class="MsoNormalTable" data-border="1" data-cellspacing="0"
data-cellpadding="0" style="border-collapse:collapse;border:none">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th width="198" data-valign="top"
style="width: 148.5pt; border: solid windowtext 1.0pt; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="COL001_TBL025"></span>Action</p></th>
<th width="426" data-valign="top"
style="width: 319.5pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Key
Sequence</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td width="198" data-valign="top"
style="width: 148.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Find
text (<em>not</em> case sensitive)</p></td>
<td width="426" data-valign="top"
style="width: 319.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;F</strong></p>
<p>Brings up a “Find” dialogue (see <u><span style="color:blue">Figure
104</span></u>):</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">       </span></span>To
search for text downward, enter the text to find and press the
<strong>Enter</strong> key.</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">       </span></span>To
search for text upward, enter the text to find and press
<strong>&lt;ArrowUp&gt;</strong>.</p></td>
</tr>
<tr class="even">
<td width="198" data-valign="top"
style="width: 148.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Find
next occurrence of text</p></td>
<td width="426" data-valign="top"
style="width: 319.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;N</strong></p></td>
</tr>
<tr class="odd">
<td width="198" data-valign="top"
style="width: 148.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Find/Replace
text</p></td>
<td width="426" data-valign="top"
style="width: 319.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;P</strong></p></td>
</tr>
</tbody>
</table>

</div>

 

<span id="_Toc527389308"></span><span id="_Ref345588540">Figure</span>
104: Screen Editor—Dialogue to Do a “FIND” while Using the Screen Editor

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

Find What:
<span style="color:white;background:black">\_                           
</span>

Replace with:

Option:                   
<span style="color:white;background:black">F</span>ind Next  
<span style="color:white;background:black">R</span>eplace     Replace
<span style="color:white;background:black">A</span>ll   
<span style="color:white;
background:black">Q</span>uit

</div>

 

## <span id="Formatting"></span><span id="_Toc527389169">11.7<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Formatting Paragraphs</span>

<u><span style="color:blue">Table 33</span></u> lists the keystrokes you
use to format paragraphs while in the Screen Editor:

<span id="_Toc527389357"></span><span id="_Ref345576474">Table</span>
33: Screen Editor—Keystrokes to Format Paragraphs in the Screen Editor

<div align="center">

<table class="MsoNormalTable" data-border="1" data-cellspacing="0"
data-cellpadding="0" style="border-collapse:collapse;border:none">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header" style="page-break-inside:avoid">
<th width="294" data-valign="top"
style="width: 220.5pt; border: solid windowtext 1.0pt; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="COL001_TBL026"></span>Action</p></th>
<th width="330" data-valign="top"
style="width: 247.5pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Key
Sequence</p></th>
</tr>
</thead>
<tbody>
<tr class="odd" style="page-break-inside:avoid">
<td width="294" data-valign="top"
style="width: 220.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Join
and/or break the current line and next line</p></td>
<td width="330" data-valign="top"
style="width: 247.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;J</strong></p>
<p>Make sure Wrap mode is on before joining or breaking lines (Toggle
Wrap mode with <strong>&lt;PF2&gt;</strong>).</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="294" data-valign="top"
style="width: 220.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Reformat
paragraph</p></td>
<td width="330" data-valign="top"
style="width: 247.5pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;R</strong></p>
<p>Joins and/or breaks all lines between current line and next
<em>blank</em> line, to create a word-wrapped paragraph. Make sure Wrap
mode is on first (Toggle with <strong>&lt;PF2&gt;</strong>).</p>
<p><img src="user-manual.fld/image002.png" id="Picture 145"
data-border="0" width="22" height="22"
alt="Note" /> <strong>NOTE:</strong> The reformat paragraph command is
very useful!</p></td>
</tr>
</tbody>
</table>

</div>

 

## <span id="Cutting_Pasting"></span><span id="_Toc527389170">11.8<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Cutting and Pasting</span>

<u><span style="color:blue">Table 34</span></u> lists the keystrokes you
use to cut and paste text while in the Screen Editor:

<span id="_Toc527389358"></span><span id="_Ref345576609">Table</span>
34: Screen Editor—Keystrokes to Cut and Paste Text in the Screen Editor

<div align="center">

<table class="MsoNormalTable" data-border="1" data-cellspacing="0"
data-cellpadding="0" style="border-collapse:collapse;border:none">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th width="188" data-valign="top"
style="width: 141.3pt; border: solid windowtext 1.0pt; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="COL001_TBL027"></span>Action</p></th>
<th width="416" data-valign="top"
style="width: 312.3pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Key
Sequence</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td width="188" data-valign="top"
style="width: 141.3pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Select/M<span
id="_Hlt446381674"></span>ark text</p></td>
<td width="416" data-valign="top"
style="width: 312.3pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;M</strong></p>
<p>Position the cursor at the beginning of the text you wish to select
and press <strong>&lt;PF1&gt;M</strong>. Move the cursor to the end of
the text you want and press <strong>&lt;PF1&gt;M</strong> again. The
selected text is highlighted in reverse video.</p></td>
</tr>
<tr class="even">
<td width="188" data-valign="top"
style="width: 141.3pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Deselect/Unmark
text</p></td>
<td width="416" data-valign="top"
style="width: 312.3pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;&lt;PF1&gt;M</strong></p></td>
</tr>
<tr class="odd">
<td width="188" data-valign="top"
style="width: 141.3pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Delete
selected text</p></td>
<td width="416" data-valign="top"
style="width: 312.3pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;Delete&gt;</strong>
or <strong>&lt;Backspace&gt;</strong> on selected text</p></td>
</tr>
<tr class="even">
<td width="188" data-valign="top"
style="width: 141.3pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Cut
and save to buffer</p></td>
<td width="416" data-valign="top"
style="width: 312.3pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;X</strong>
on selected text</p></td>
</tr>
<tr class="odd">
<td width="188" data-valign="top"
style="width: 141.3pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Copy
and save to buffer</p></td>
<td width="416" data-valign="top"
style="width: 312.3pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;C</strong>
on selected text</p></td>
</tr>
<tr class="even">
<td width="188" data-valign="top"
style="width: 141.3pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Paste
from buffer</p></td>
<td width="416" data-valign="top"
style="width: 312.3pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;V</strong></p></td>
</tr>
<tr class="odd">
<td width="188" data-valign="top"
style="width: 141.3pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Move
text to another location</p></td>
<td width="416" data-valign="top"
style="width: 312.3pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;X</strong>
at new location</p></td>
</tr>
<tr class="even">
<td width="188" data-valign="top"
style="width: 141.3pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Copy
text to another location</p></td>
<td width="416" data-valign="top"
style="width: 312.3pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;C</strong>
at new location</p></td>
</tr>
</tbody>
</table>

</div>

 

To *move or copy* selected text to another location:

1.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Select the text (use **\<PF1\>M**).

2.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>Place
the *cursor at the new location*.

3.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>Press
**\<PF1\>X** (move text) or **\<PF1\>C** (copy text).

To *save* text to the buffer so that you can paste one or more times:

1.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Select the text (use **\<PF1\>M**).

2.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>With
the *cursor on the selected text*, press **\<PF1\>X** (cut text to
buffer) or **\<PF1\>C** (copy text to buffer).

To *paste* text from the buffer:

1.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>Move
the cursor to the location you want to paste the text.

2.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>Press
**\<PF1\>V**.

## <span id="_Toc527389171">11.9<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Deleting</span>

<u><span style="color:blue">Table 35</span></u> lists the keystrokes you
use to delete text while in the Screen Editor:

<span id="_Toc527389359"></span><span id="_Ref345576907">Table</span>
35: Screen Editor—Keystrokes to Delete Text in the Screen Editor

<div align="center">

<table class="MsoNormalTable" data-border="1" data-cellspacing="0"
data-cellpadding="0" style="border-collapse:collapse;border:none">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th width="180" data-valign="top"
style="width: 135.0pt; border: solid windowtext 1.0pt; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="COL001_TBL028"></span>Action</p></th>
<th width="444" data-valign="top"
style="width: 333.0pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Key
Sequence</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td width="180" data-valign="top"
style="width: 135.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Character
before cursor</p></td>
<td width="444" data-valign="top"
style="width: 333.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;Backspace&gt;</strong></p></td>
</tr>
<tr class="even">
<td width="180" data-valign="top"
style="width: 135.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Character
at cursor</p></td>
<td width="444" data-valign="top"
style="width: 333.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF4&gt;</strong>
or <strong>&lt;Remove&gt;</strong> or
<strong>&lt;Delete&gt;</strong></p>
<p>(which key depends on your terminal and keyboard type)</p></td>
</tr>
<tr class="odd">
<td width="180" data-valign="top"
style="width: 135.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Word
at cursor</p></td>
<td width="444" data-valign="top"
style="width: 333.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;Ctrl&gt;W</strong></p></td>
</tr>
<tr class="even">
<td width="180" data-valign="top"
style="width: 135.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>From
cursor to end of line</p></td>
<td width="444" data-valign="top"
style="width: 333.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;&lt;PF2&gt;</strong></p></td>
</tr>
<tr class="odd">
<td width="180" data-valign="top"
style="width: 135.0pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Entire
line</p></td>
<td width="444" data-valign="top"
style="width: 333.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;D</strong></p></td>
</tr>
</tbody>
</table>

</div>

<span id="Settings_Modes"> </span>

## <span id="_Toc527389172">11.10<span style="font:7.0pt &quot;Times New Roman&quot;">                </span>Settings/Modes</span>

<u><span style="color:blue">Table 36</span></u> lists the keystrokes you
use to change settings and mode while in the Screen Editor:

<span id="_Toc527389360"></span><span id="_Ref345577006">Table</span>
36: Screen Editor—Keystrokes to Change the Settings and Mode in the
Screen Editor

<div align="center">

<table class="MsoNormalTable" data-border="1" data-cellspacing="0"
data-cellpadding="0" width="641"
style="border-collapse:collapse;border:none">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th width="189"
style="width: 141.5pt; border: solid windowtext 1.0pt; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="COL001_TBL029"></span>Action</p></th>
<th width="453"
style="width: 339.45pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Key
Sequence</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td width="189" data-valign="top"
style="width: 141.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Wrap/No
Wrap mode toggle</p></td>
<td width="453" data-valign="top"
style="width: 339.45pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF2&gt;</strong></p>
<p>If wrap is off, left and right margin settings are ignored.</p></td>
</tr>
<tr class="even">
<td width="189" data-valign="top"
style="width: 141.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Insert/Replace
mode toggle</p></td>
<td width="453" data-valign="top"
style="width: 339.45pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF3&gt;</strong>
or <strong>&lt;Insert Here&gt;</strong> or
<strong>&lt;Insert&gt;</strong></p>
<p>Determines whether new characters are inserted before existing text,
or instead overwrite existing text.</p></td>
</tr>
<tr class="odd">
<td width="189" data-valign="top"
style="width: 141.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Set/Clear
tab stop</p></td>
<td width="453" data-valign="top"
style="width: 339.45pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;&lt;Tab&gt;</strong></p>
<p>Change from default tab stops is effective for current session
only.</p></td>
</tr>
<tr class="even">
<td width="189" data-valign="top"
style="width: 141.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Set
left margin</p></td>
<td width="453" data-valign="top"
style="width: 339.45pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;&lt;Comma&gt;</strong></p>
<p>Move cursor to desired left margin position first.</p></td>
</tr>
<tr class="odd">
<td width="189" data-valign="top"
style="width: 141.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Set
right margin</p></td>
<td width="453" data-valign="top"
style="width: 339.45pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;&lt;Period&gt;</strong></p>
<p>Move cursor to desired right margin position first.</p></td>
</tr>
<tr class="even">
<td width="189" data-valign="top"
style="width: 141.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Status
line toggle (on or off)</p></td>
<td width="453" data-valign="top"
style="width: 339.45pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>&lt;PF1&gt;?</strong></p></td>
</tr>
</tbody>
</table>

</div>

<span id="_Hlt448902843"></span> 

## <span id="Troubleshooting"></span><span id="_Toc527389173">11.11<span style="font:7.0pt &quot;Times New Roman&quot;">                </span>Troubleshooting</span>

### <span id="troubleshooting_1"></span><span id="_Toc527389174">11.11.1<span style="font:7.0pt &quot;Times New Roman&quot;">             </span>Terminal Type Setting</span>

The Screen Editor is designed for use on all terminal types known in the
Kernel computing environment. It is very important that your terminal
type be correctly identified to VA FileMan.

<img src="user-manual.fld/image002.png" id="Picture 322" data-border="0"
width="22" height="22" alt="Note" />     **REF:** For more information
about how terminal types are identified, see the Kernel documentation
located on the VDL: <https://www.va.gov/vdl/application.asp?appid=10>

Since the **\<PF\>** keys are used in the Screen Editor, those keys
should *not* be reprogrammed.

### <span id="troubleshooting_2"></span><span id="_Toc527389175">11.11.2<span style="font:7.0pt &quot;Times New Roman&quot;">             </span>\<PF\> Keys Not Working: How to Exit</span>

If your **\<PF\>** keys do *not* work in the Screen Editor, your
terminal type is probably set incorrectly. Before you can correct the
setting, you need to make an emergency exit from the editor by using one
of the following keystroke combinations:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Press **\<Esc\>OPQ** (if your keyboard has an **Escape
\[Esc\]** key).

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Press **\<Ctrl\>\[OPQ** (if your keyboard does *not* have
an **Escape\[Esc\]** key).

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Press **\<Ctrl\>A@\<Enter\>Q** (if *neither* of the above
methods work).

<img src="user-manual.fld/image002.png" id="Picture 146" data-border="0"
width="22" height="22" alt="Note" />**     NOTE:** You *must* enter all
letters in the above key sequences in *uppercase*.

## <span id="_Toc527389176">11.12<span style="font:7.0pt &quot;Times New Roman&quot;">                </span>Screen Editor and Personal Computers</span>

### <span id="Pasting"></span><span id="_Toc527389177">11.12.1<span style="font:7.0pt &quot;Times New Roman&quot;">             </span>Pasting and Uploading</span>

If you are accessing your computer system from a personal computer (PC),
you can *paste* text from an application on the PC into the Screen
Editor, and also *upload* files into the Screen Editor. There are some
issues to be aware of when pasting text or uploading files into the
Screen Editor.

### <span id="pasting_1"></span><span id="_Toc527389178">11.12.2<span style="font:7.0pt &quot;Times New Roman&quot;">             </span>Symbol Characters</span>

Extended ASCII characters (typically “symbol” characters) *cannot* be
stored in WORD-PROCESSING fields. Examples of such characters include:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>“Smart Quote” characters

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Bullets

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Symbols

Such characters, when encountered, are stripped or replaced with a
**space**, **‘**, **“**, or **\***, as appropriate. To avoid problems
uploading these types of characters, you should:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Turn off “Smart Quotes” in your word-processor on your
personal computer.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Avoid using bullets.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Avoid using symbols in your text such as: **¼**, **½** ,
and **º**.

### <span id="pasting_2"></span><span id="_Toc527389179">11.12.3<span style="font:7.0pt &quot;Times New Roman&quot;">             </span>Files: Save as Text</span>

If you are uploading an entire word-processing document (as opposed to
pasting), save it first as a “Text Only with Line Breaks” (or similar)
file type in your personal computer word-processor.

### <span id="pasting_3"></span><span id="_Toc527389180">11.12.4<span style="font:7.0pt &quot;Times New Roman&quot;">             </span>Wrap Vs. No Wrap</span>

If your source document contains a carriage return at the end of every
line, turn **WRAP** off in the Screen Editor *before* you paste or
upload by pressing **PF2**. Turn it back on once the paste or upload is
completed. If your source document contains a carriage return at the end
of each paragraph only; however, leave **WRAP** on in the Screen Editor.

### <span id="pasting_4"></span><span id="_Toc527389181">11.12.5<span style="font:7.0pt &quot;Times New Roman&quot;">             </span>Avoiding Lost Characters</span>

If the host computer system *cannot* keep up with the text upload,
characters can get “lost.” This can be a factor if you upload large
quantities of text or characters. This character loss can occur because
pastes and ASCII uploads do *not* use *error*-correcting communications
protocols.

If you notice characters getting lost, one way to solve this is to
adjust the “character pacing” (or similar) setting in your terminal
emulation program. This can slow down the transfer of text such that
characters no longer get lost due to communications overload.

If you need to paste or upload large quantities of text, consider
switching to an Alternate Editor (e.g., Kermit) that uses an
*error*-correcting communications protocol. This automatically
compensates for communications overflows, preventing the loss of
characters during text transfer.

<img src="user-manual.fld/image002.png" id="Picture 147" data-border="0"
width="22" height="22" alt="Note" />     **NOTE:** To use Kermit, it
*must* be installed as an Alternate Editor at your
site.<span id="_Hlt446228310"></span>

 

<span style="font-size:12.0pt;font-family:&quot;Times New Roman&quot;,serif;color:black">  
</span>

<span id="_Ref446305605"></span><span id="_Ref446305606"></span><span id="_Ref446305609"></span><span id="_Ref446305662"></span><span id="_Ref446306078"></span><span id="_Ref446306411"></span><span id="_Ref446306464"></span><span id="_Ref446309782"></span><span id="_Ref446310329"></span><span id="_Ref446310700"></span><span id="_Hlt446205137"></span> 

# <span id="_Ref524020385"></span><span id="_Ref524020653"></span><span id="_Ref524020665"></span><span id="_Ref524020900"></span><span id="_Ref524022296"></span><span id="_Ref524022376"></span><span id="_Ref524022716"></span><span id="_Ref524023634"></span><span id="_Toc527389182">12<span style="font:7.0pt &quot;Times New Roman&quot;">    </span>Line Editor</span><span id="_Hlt446217849"></span>

The Line Editor is a scrolling mode editor. It is the second of two
standard editors VA FileMan provides for editing WORD-PROCESSING-type
fields. The distinguishing characteristic of a Scrolling Mode editor is
that you enter your text one line at a time, and that you can only edit
lines one at a time. Because word-processing in a scrolling mode
interface can be cumbersome, you can set your Preferred Editor to the
<u><span style="color:blue">Screen Editor</span></u>. VA FileMan
continues to provide the Scrolling-Mode Line Editor, however, for those
who prefer it.

<img src="user-manual.fld/image002.png" id="Picture 148" data-border="0"
width="22" height="22" alt="Note" />     **REF:** To set your default
editor, see the “<u><span style="color:blue">Choosing a Preferred
Editor</span></u>” section.  
  
**NOTE:** For most people, the <u><span style="color:blue">Screen
Editor</span></u> should be your Preferred Editor for WORD-PROCESSING
fields.

## <span id="_Toc527389183">12.1<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Recognizing the Line Editor</span>

When you edit a WORD-PROCESSING field, it’s easy to see if VA FileMan
chooses the Line Editor as your editor. If the Line Editor is used, the
last **nine** lines of text (if there are that many) are displayed on
the screen, with numbered prompts at the start of each line. Also, after
the text is listed, you are prompted with “EDIT Option:”. The “EDIT
Option:” prompt is where you can enter each Line Editor command to work
with the text.

For example:

<span id="_Toc527389309">Figure</span> 105:
<span id="_Hlt446204445">Line Editor—Example of a WORD-PROCESSING Field
in the Line Editor</span>

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

  HISTORY:

    1\>Owing to poverty in early youth, patient seems not to

    2\>have had proper diet. Since achieving economic success,

    3\>his diet has been adequate, but traces of original

    4\>deficiency remain.

    5\>

  EDIT Option:

</div>

 

## <span id="Entering"></span><span id="_Toc527389184">12.2<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>How to Enter Text in the Line Editor</span>

If no text exists yet in a WORD-PROCESSING field that you are about to
edit, you see the field name followed by “**1\>**”. This is the Line
Editor’s prompt for entering word-processing text.

For example:

<span id="_Toc527389310">Figure</span> 106: Line Editor—Prompts for
Entering Word-Processing Text

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

  Select PATIENT FILE NAME:
**<span style="background:yellow">FMPATIENT,FOUR</span>**

    Select DIAGNOSIS: ANGINA PECTORIS//
**<span style="background:yellow">B-12 DEFICIENCY</span>**

    HISTORY:

      1\>

</div>

 

You can now enter the text for Line **1** and press the **Enter** key.
This brings you to a prompt “**2\>**” for Line **2**, and so forth. Keep
adding lines until you are done; then, press the **Enter** key on a
blank line to finish your edit, as shown in
<u><span style="color:blue">Figure 107</span></u>:

<span id="_Toc527389311"></span><span id="_Ref523922313">Figure</span>
107: Line Editor—Completing Your Edits in the Line Editor

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

  HISTORY:

    1\>**<span style="background:yellow">Owing to poverty in early
youth, patient seems not to\<Enter\></span>**

    2\>**<span style="background:yellow">have had proper diet. Since
achieving economic success,\<Enter\></span>**

    3\>**<span style="background:yellow">his diet has been adequate, but
traces of original\<Enter\></span>**

    4\>**<span style="background:yellow">deficiency
remain.\<Enter\></span>**

    5\>**<span style="background:yellow">\<Enter\></span>**

  EDIT Option: **<span style="background:yellow">\<Enter\></span>**

 

  Select DIAGNOSIS:

</div>

 

## <span id="Revising"></span><span id="_Toc527389185">12.3<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Revising Existing Text</span>

To revise the contents of the WORD-PROCESSING field, you need to call up
each individual line that you want to edit and then edit each line.

To revise existing text, perform the following procedure:

1.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>At
the “EDIT Option:” prompt, enter the letter **E** for Edit a Line
(Replace \_\_ With \_\_).

2.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>At
the “Edit line:” prompt, enter the number of the line you need to
revise.

3.<span style="font:7.0pt &quot;Times New Roman&quot;">    
</span>Beneath the “EDIT Option:” and “Edit line:” prompts, you see the
line of text that you identified by number and you see the “Replace”
prompt.

4.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>Enter
a string in the current line to be replaced.

5.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>If
the string you enter is found in the current line, set the “With”
prompt. Enter a string to replace the original string.

6.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>The
line is now updated, and you are prompted for another string to replace.
If you are done editing the line, simply press the **Enter** key.

### <span id="_Toc527389186">12.3.1<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Shortcut: Enter Line Number to Edit at “EDIT Option:” Prompt</span>

There’s a shortcut to edit a particular line. At the “EDIT Option:”
prompt, instead of choosing the Edit a Line (Replace \_\_ With \_\_)
option and entering the line number, just enter the line number instead.
You are taken directly to the line you specify, and then given the
“Replace” prompt to edit the line:

<span id="_Toc527389312">Figure</span> 108: Line Editor—Shortcut to Edit
a Specific Line Using the Line Editor

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

  EDIT Option: **<span style="background:yellow">5</span>**

    5\>was the time of the day that I
<span style="background:aqua">wnet</span> over to Building 8 and

    Replace **<span style="background:yellow">wnet</span>** With
**<span style="background:yellow">went</span>**  Replace
**<span style="background:yellow">\<Enter\></span>**

     was the time of the day that I
<span style="background:aqua">went</span> over to Building 8 and

  Edit line:

</div>

 

## <span id="Replace"></span><span id="_Toc527389187">12.4<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>“Replace...With” Edits: Be Careful</span>

When editing individual lines, you make changes using the
“Replace...With” dialogue, where you enter an existing string in the
line, and a new string with which to replace it. Be careful as you enter
your responses to the “Replace” and “With” prompts. Enter enough letters
to ensure that the computer replaces the desired string of characters.

Here is why this issue is so important. In one line, you may have two
identical words, or you may have two identical sets of characters
embedded. Since the computer changes only the ***first*** occurrence of
any series of letters that you enter, review your line carefully before
responding to the “Replace” prompt. Then enter enough identifying
characters to correct *the specific word or characters* you wish to
change. To illustrate the point, look at an ***incorrect*** entry
(<u><span style="color:blue">Figure 109</span></u>).

In <u><span style="color:blue">Figure 109</span></u>, you need to change
the sentence in the second line from “This example is sample” to the
sentence “This example is simple.”

<span id="_Toc527389313"></span><span id="_Ref523927459">Figure</span>
109: Line Editor—Example of an *Incorrect* Edit with the
“Replace...With” Editor

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

  EDIT Option: **<span style="background:yellow">2</span>**

    2\>This ex<span style="background:aqua">ample</span> is
s<span style="background:aqua">ampl</span>e

    Replace **<span style="background:yellow">ample</span>** With
**<span style="background:
yellow">imple</span>** Replace
**<span style="background:yellow">\<Enter\></span>**

     This eximple is sample

  Edit line:

</div>

 

As you can see from this example, VA FileMan replaced the ***first***
occurrence of the “**ample**” characters. Thus, “**example**” was
changed to “**eximple**” rather than “**sample**” being changed to
“**simple**” because the word “**example**” came before the word
“**simple**” in the sentence (i.e., it was the first occurrence).
Obviously, we should have replaced the whole word “**sample**” with
“**simple**” to avoid any confusion.

### <span id="_Toc527389188">12.4.1<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Shortcuts at the “Replace...With” Prompt</span>

As with editing long field values, you can replace long strings of
characters by using ellipses. An ellipsis is **three** successive
periods (**...**). When editing, you can replace longer strings of
characters by using an ellipsis at the “Replace” prompt. You can specify
ranges of text to replace for any line (just as with a long text field)
with the ellipsis.

For example, to replace an entire line at a “Replace...With” prompt,
enter the ellipsis (three periods) at the “Replace” prompt. You are then
able to replace the entire default with what you entered at the “With”
prompt, as shown in <u><span style="color:blue">Figure 110</span></u>:

<span id="_Toc527389314"></span><span id="_Ref523927771">Figure</span>
110: Line Editor—Using the Ellipsis (…) to Replace an Entire Line

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

  EDIT Option: **<span style="background:yellow">5</span>**

    5\>care of the boxes.

    Replace **<span style="background:yellow">...</span>** With
**<span style="background:yellow">care to replace the existing
supplies.</span>**  Replace
**<span style="background:yellow">\<Enter\></span>**

     care to replace the existing supplies.

  Edit line:

</div>

 

### <span id="_Toc527389189">12.4.2<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>“Replace...” Prompt Shortcuts</span>

<u><span style="color:blue">Table 37</span></u> lists valid shortcut you
can use in the “Replace...With” editor:

<span id="_Toc527389361"></span><span id="_Ref345577805">Table</span>
37: Line Editor—”Replace” Prompt Shortcuts

<table class="MsoNormalTable" data-border="1" data-cellspacing="0"
data-cellpadding="0" width="635"
style="margin-left:1.15pt;border-collapse:collapse;border:none">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><span
id="COL001_TBL030"></span>Shortcut</p></th>
<th width="533" data-valign="top"
style="width: 399.8pt; border: solid windowtext 1.0pt; border-left: none; background: #F2F2F2; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Action</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>...</strong></p></td>
<td width="533" data-valign="top"
style="width: 399.8pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Replaces
everything.</p></td>
</tr>
<tr class="even">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>xxx...</strong></p></td>
<td width="533" data-valign="top"
style="width: 399.8pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Replaces
everything starting from the characters <strong><em>xxx</em></strong> to
the end.</p>
<p><strong>&lt;PF1&gt;E</strong>.</p></td>
</tr>
<tr class="odd">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>...xxx</strong></p></td>
<td width="533" data-valign="top"
style="width: 399.8pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Replaces
everything from the beginning up to and including the characters
<strong>xxx</strong>. <strong>&lt;PF1&gt;Q</strong>.</p></td>
</tr>
<tr class="even">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>xxx...yyy</strong></p></td>
<td width="533" data-valign="top"
style="width: 399.8pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Replaces
everything starting from <strong><em>xxx</em></strong> up to and
including <strong><em>yyy</em></strong></p>
<p><strong>&lt;PF1&gt;A</strong>.</p></td>
</tr>
<tr class="odd">
<td width="102" data-valign="top"
style="width: 76.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p><strong>end</strong>
or <strong>END</strong></p></td>
<td width="533" data-valign="top"
style="width: 399.8pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 3.0pt 3.0pt 3.0pt 3.0pt"><p>Appends
what you enter at the “With” prompt to the end of the value.</p>
<p><strong>&lt;PF1&gt;S</strong>.</p></td>
</tr>
</tbody>
</table>

 

## <span id="Available"></span><span id="_Toc527389190">12.5<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Commands</span>

### <span id="_Toc527389191"></span><span id="_Hlt446381721"></span>12.5.1<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Available Commands

In the Line Editor, all commands are available at the “EDIT Option:”
prompt. To see a list of available commands, simply enter **two**
question marks, as shown in <u><span style="color:blue">Figure
111</span></u>:

<span id="_Toc527389315"></span><span id="_Ref446125940">Figure</span>
111: Line Editor—Edit Options Available with the Line Editor

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

  EDIT Option: **<span style="background:yellow">??</span>**

       Choose, by first letter, a Word Processing Command from the
following:

            Add Lines to End of Text

            Break a Line into Two

            Change Every String to Another in a Range of Lines

            Delete Line(s)

            Edit a Line (Replace \_\_  With \_\_)

            Insert Line(s) after an Existing Line

            Join Line to the One Following

            List a Range of Lines

            Move Lines to New Location within Text

            Print Lines as Formatted Output

            Repeat Lines at a New Location

            Search for a String

            Transfer Lines From Another Document

            Utility Sub-Menu

            Y-Programmer Edit

       or type a Line Number to edit that line.

  EDIT Option: **<span style="background:yellow">U \<Enter\></span>**
tilities in Word-Processing

  UTILITY Option: **<span style="background:yellow">??</span>**

       Choose, by first letter, a Utility Command from the following:

            Editor Change

            File Transfer from Foreign CPU

            Text-Terminator-String Change

  UTILITY Option:

</div>

 

### <span id="List"></span><span id="_Toc527389192"></span><span id="_Hlt446149542"></span>12.5.2<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>LIST: List the Message

Assume that you have just entered four lines of text in a
WORD-PROCESSING field and would now like to review the entire text.
After entering text on Line **4** (**4\>**), press the **Enter** key.
When prompted for Line **5** (**5\>**), press the **Enter** key again
and you arrive at the “EDIT Option:” prompt. Enter **L** (for List a
Range of Lines option) and choose the range of lines to list (in this
case, Lines **1** to **4**):

<span id="_Toc527389316">Figure</span> 112: Line Editor—Example Using
the List a Range of Lines Option

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

  EDIT Option: **<span style="background:yellow">L \<Enter\></span>**
ist line: 1// **<span style="background:yellow">\<Enter\></span>** to:
4// **<span style="background:yellow">\<Enter\></span>**

    1\>Owing to poverty in early youth, patient seems not to

    2\>have had proper diet. Since achieving economic success,

    3\>his diet has been adequate, but traces of original

    4\>deficiency remain.

  EDIT Option:

</div>

 

### <span id="_Toc527389193">12.5.3<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>ADD: Append More Text</span>

After listing lines of text (see “[LIST: List the
Message](#List)<span class="MsoHyperlink"><span style="color:black;text-decoration:none">”
section</span></span>), suppose you need to add a few comments at the
end of your message. From the “EDIT Option:” prompt, enter **A** (for
Add Lines to End of Text option). You can now add additional lines:

<span id="_Toc527389317">Figure</span> 113: Line Editor—Example Using
the Add Lines to End of Text Option

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

  EDIT Option: **<span style="background:yellow">A \<Enter\></span>** dd
lines

    5\> **<span style="background:yellow">Next appointment is in three
weeks.\<Enter\></span>**

    6\> **<span style="background:yellow">Regular appointments need to
be set up. \<Enter\></span>**

    7\> **<span style="background:yellow">\<Enter\></span>**

</div>

 

### <span id="Join"></span><span id="_Toc527389194">12.5.4<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>JOIN: Combine Two Lines of Text</span>

Suppose you are at the “EDIT Option:” prompt. After briefly reviewing
your text, you have decided that Lines **2** and **3** (**2\>** and
**3\>**) are too short. You can use the **Join** command (i.e., Join
Line to the One Following option) to join Line **2** to the next line:

<span id="_Toc527389318">Figure</span> 114: Line Editor—Example Using
the Join Line to the One Following Option

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

  EDIT Option: **<span style="background:yellow">L \<Enter\></span>**
ist line: 2// **<span style="background:yellow">\<Enter\></span>** to:
3// **<span style="background:yellow">\<Enter\></span>**

    2\>left by

    3\>the doorway.

  EDIT Option: **<span style="background:yellow">J \<Enter\></span>**
oin line: **<span style="background:yellow">2</span>**

    2\>left by the doorway.

  ..

  EDIT Option:

</div>

 

### <span id="Insert"></span><span id="_Toc527389195">12.5.5<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>INSERT: Insert New Lines of Text between Existing Ones</span>

Suppose that you want to insert new lines of text in the middle of
existing text in a WORD-PROCESSING field. Using the [Add Lines to End of
Text](#Add)<span id="_Hlt446149547"></span> does *not* work, because
that appends new text lines at the *end* of the existing lines. Instead,
you can use the **Insert** command \[i.e., Insert Lines after an
Existing Line option\], to do this:

<span id="_Toc527389319">Figure</span> 115: Line Editor—Example Using
the Insert Lines after an Existing Line Option

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

  EDIT Option: **<span style="background:yellow">L \<Enter\></span>**
ist line: 1// **<span style="background:yellow">\<Enter\></span>** to:
5// **<span style="background:yellow">\<Enter\></span>**

    1\>The delivery people came, and left several packages

    2\>by the doorway.

    3\>We have some work ahead of us now.

  EDIT Option: **<span style="background:yellow">I \<Enter\></span>**
nsert after line: **<span style="background:yellow">2</span>**

    3\> **<span style="background:yellow">\<Enter\></span>**

    4\> **<span style="background:yellow">Finally, the order arrived!
\<Enter\></span>**

    5\> **<span style="background:yellow">\<Enter\></span>**

</div>

 

### <span id="Delete"></span><span id="_Toc527389196">12.5.6<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>DELETE: Delete a Line or Lines</span>

To delete lines of text in a WORD-PROCESSING field, use the **Delete**
command \[i.e., Delete Line(s) option\] at the “EDIT Option:” prompt, as
shown in <u><span style="color:blue">Figure 116</span></u>:

<span id="_Toc527389320"></span><span id="_Ref523929212">Figure</span>
116: Line Editor—Example Using the Delete Line(s) Option

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

  EDIT Option: **<span style="background:yellow">D \<Enter\></span>**
elete from line: **<span style="background:yellow">5 \<Enter\></span>**
thru: 3// **<span style="background:yellow">6</span>**

 

  OK TO REMOVE 2 LINES? No// **<span style="background:yellow">Y
\<Enter\></span>** (Yes).....

    1\>The delivery people came, and left several packages

    2\>by the doorway.

    3\>

    4\>Finally, the order arrived!

  EDIT Option:

</div>

 

## <span id="_Toc527389197">12.6<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Advanced Features</span>

Most of the features of the Line Editor are self-explanatory and simple
to use. However, a few require additional explanation, as follows in
this section.

<img src="user-manual.fld/image002.png" id="Picture 149" data-border="0"
width="22" height="22" alt="Note" /><span style="font-size:10.0pt">    
</span>**NOTE:** To see a full list of the commands available at the
“EDIT Option:” prompt, enter two question marks (**??**), as shown in
<u><span style="color:blue">Figure 111</span></u>.

### <span id="Transfer"></span><span id="_Toc527389198"></span><span id="_Hlt446127596"></span>12.6.1<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>File Transfer (Use When Uploading ASCII Text)

The **File Transfer from Foreign CPU** option from the **Utility** menu
lets you upload text from another system into your WORD-PROCESSING field
text, using an ASCII (*non-error*-correcting) transfer. For example, if
you are connected from a personal computer (PC), you can use your
communication software to send a text file.

The file to be transferred *must* be a text (pure ASCII) file. Most
word-processing programs have a way of saving a document as text
(i.e., without special formatting information); check your
word-processor’s manual. Also, you need to know how to send a text file
using your PC’s communication software; if you are not sure how, check
your communications software manual.

To use the **File Transfer from Foreign CPU** option, perform the
following procedure:

1.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>Make
sure the file you are transferring is a pure ASCII text file.

2.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>While
editing a WORD-PROCESSING field in the Line Editor, choose the
**Utility** menu option at the “EDIT Option:” prompt. Then choose the
**File Transfer from Foreign CPU** option from the **Utility** menu.

3.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>At
the “MAXIMUM string length? : (3-245):” prompt, enter maximum string
length for lines you are uploading.

4.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>The
Line Editor now waits up to **30** seconds for you to initiate an ASCII
transfer of the file.

5.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>Use
your communications software to perform an ASCII upload of the file. All
uploaded text is appended to the WORD-PROCESSING field that you are
editing.

6.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span>Once
you have finished uploading, it takes **30** seconds of inactivity until
the transfer can complete. When done, and after **30** seconds of
inactivity, the computer responds “FILE TRANSFER COMPLETE” and you are
returned to the “EDIT Option:” prompt.

The same precautions apply for uploading large quantities of text to the
Line Editor as apply with the <u><span style="color:blue">Screen
Editor</span></u>. In particular, if you need to upload large quantities
of text quickly, consider switching to an Alternate Editor, such as
Kermit (if installed as an Alternate Editor by your site), which
provides *error*-correcting communications protocol. Unlike an ASCII
transfer (used with the **File Transfer** option), an error-correcting
protocol (e.g., Kermit) can transfer text and automatically compensate
for any communications overflows, without losing characters.

### <span id="Terminator"></span><span id="_Toc527389199">12.6.2<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Text Terminator-String Change</span>

<img src="user-manual.fld/image002.png" id="Picture 150" data-border="0"
width="22" height="22" alt="Note" />     **NOTE:** Use this when
uploading text with blank lines.

In the Line Editor, a blank line (**NULL** string) signals the end of
data entry (and returns you to the “EDIT Option:” prompt. Thus, if you
plan to *paste* or *upload* text into the Line Editor from a personal
computer, any blank lines in the uploaded text have the side-effect of
signaling the end of data entry (prematurely). One way around this is to
use the [File Transfer from Foreign CPU
option](#Transfer)<span id="_Hlt446149569"></span><span id="_Hlt446127624"></span>.
Another way around this problem is to use the **Text-Terminator-String
Change** option on the **Utility** menu. This lets you change the text
terminator so that some character string, rather than a blank line, is
what is used to signal the end of data entry.

You can change the text terminator to any string of between **one** and
**five** characters; question marks (**?**) or carets (**^**) are *not*
allowed in the string. To finish editing a WORD-PROCESSING field and get
to the “EDIT Option:” prompt, simply enter your new text terminator
string instead of pressing the **Enter** key on a blank line. You should
choose a text terminator that does *not* appear in your text: “**end**”
would *not* be a good choice, but “**EnD**” might be.

The new text terminator is *not permanent*; it remains only as long as
you are editing a particular WORD-PROCESSING field. You can change it
back to a **NULL** line by entering an at-sign (**@**) at the
“Text-Terminator:” prompt. You can permanently change your default text
terminator by changing it in your user characteristics as described in
the Kernel manuals.

### <span id="Programmer"></span><span id="_Toc527389200">12.6.3<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Programmer Edit (Edit Lines with M Commands)</span>

The **Y-Programmer Edit** option (invoked by entering the letter **Y**)
is only available to users with programmer’s access. You can enter a
line of M code that, line-by-line, reads in the current line in variable
**X** and returns the transformed line in variable **Y**. You can
specify the range of lines to be transformed by the M code you enter.

For example, to blank out all lines containing the words “**Top
Secret**”, you could enter the following M code:

<span id="_Toc527389321">Figure</span> 117: Line Editor—Example of
Entering M Code while Using the Y-Programmer Edit Option

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

EDIT Option: **<span style="background:yellow">Y</span>**

 

The text is in X and returned in Y

Enter MUMPS xecute string to do transformation:
**<span style="background:yellow">I X\[“Top Secret” S Y=“ “</span>**

</div>

 

### <span id="Editor"></span><span id="_Toc527389201">12.6.4<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Editor Change: Switch Editors</span>

The **Editor Change** option, on the **Utility** menu, shows you a list
of the editors available for your use, if you enter **two** question
marks (**??**) at the “Select ALTERNATE EDITOR:” prompt. The editors
include VA FileMan’s own editors (the Line Editor and Screen Editor) and
any other editors to which you have access. You choose the editor to use
by entering its name. When you exit your chosen editor, you return to
the Line Editor’s “EDIT option:” prompt.

### <span id="_Toc527389202"></span><span id="Text">12.6.5<span style="font:7.0pt &quot;Times New Roman&quot;">   </span>Transfer Text</span> (from another WORD-PROCESSING Field)

The **Transfer Lines From Another Document** option lets you copy text
from some other WORD-PROCESSING field into your current field. You need
to specify on which line of the current field to place the incoming text
and identify the source of the text.

To identify the source of the text, you need to use extended
point<span id="_Hlt446149577">e</span>r syntax.

<img src="user-manual.fld/image002.png" id="Picture 151" data-border="0"
width="22" height="22" alt="Note" />     **REF:** The extended pointer
syntax is described in the “R<span id="_Hlt446149585">e</span>lational
Navigation” section in the *VA FileMan Advanced User Manual*.

The syntax lets you specify the particular field of a specific entry in
a specific file. Briefly, the syntax can be in one of the following two
forms:

\<*expression*\>:\<*file*\>:\<*field*\>

**Or**

\<*expression*\> IN \<*file*\> FILE:\<*field*\>

The **\<*expression*\>** or lookup value has several possible forms. One
way to refer to the field is by entry name. To retrieve text from the
WORD-PROCESSING PROGNOSIS field of the entry **Angina Pectoris** in a
(fictitious) file named DIAGNOSES, you could enter the following, as
shown in <u><span style="color:blue">Figure 118</span></u>:

<span id="_Toc527389322"></span><span id="_Ref523930871">Figure</span>
118: Line Editor—Dialogue of the Extended Pointer Syntax while Using the
Transfer Lines From Another Document Option: Sample User Entries at
Prompts (Example \#1)

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

  EDIT Option: **<span style="background:yellow">T \<Enter\></span>**
ransfer incoming text after line:
**<span style="background:yellow">1</span>**

  From what text: **<span style="background:yellow">?</span>**

 

       Select another entry in this file, OR

       use relational syntax to pick up information from a word-

       processing field in another file.

       ex.  “VALUE”:FILE NAME:WORD PROCESSING FIELD NAME

 

  Do you want the entire TEST list?

  Enter Yes or No: **<span style="background:yellow">^</span>**

  From what text: **<span style="background:yellow">“Angina
Pectoris”:DIAGNOSES:PROGNOSIS</span>**

  From line: **<span style="background:yellow">1 \<Enter\></span>**
thru: **<span style="background:yellow">20</span>**

  ARE YOU SURE? NO// **<span style="background:yellow">Y
\<Enter\></span>** (YES)... . .

</div>

 

Alternately, you can use the second syntax to retrieve the same field in
the same file entry, as shown in <u><span style="color:blue">Figure
119</span></u>:

<span id="_Toc527389323"></span><span id="_Ref345588550">Figure</span>
119: Line Editor—Dialogue of the Extended Pointer Syntax while Using the
Transfer Lines From Another Document Option: Sample User Entries at
Prompts (Example \#2)

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

EDIT Option: **<span style="background:yellow">T \<Enter\></span>**
ransfer incoming text after line:
**<span style="background:yellow">4</span>**

<img src="user-manual.fld/image078.png" data-border="0" width="114"
height="35"
alt="Entry Name - Title: Entry Name - Description: Entry Name" />      
<img src="user-manual.fld/image079.png" data-border="0" width="78"
height="44"
alt="File Name - Title: File Name - Description: File Name" />          <img src="user-manual.fld/image080.png" data-border="0" width="78"
height="42"
alt="Field Name - Title: Field Name - Description: Field Name" />

From what text: **<span style="background:yellow">“Angina Pectoris” IN
DIAGNOSIS FILE:PROGNOSIS</span>**

From line: **<span style="background:yellow">1 \<Enter\></span>**  thru:
**<span style="background:yellow">20</span>**

ARE YOU SURE?  NO// **<span style="background:yellow">Y
\<Enter\></span>**   (YES) ...

</div>

 

In this example, at the "From what text:" prompt:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>"**Angina Pectoris**" is the entry name.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**DIAGNOSIS** is the file name.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>**Prognosis** is the field name.

The requested text is identified by the value of the **.01** field in
quotes (“**Angina Pectoris**”). Thus, in this example the
***\<expression\>*** is the entry’s name. You also specify which lines
you want to transfer. If you enter **one** question mark (**?**) at the
“From line:” prompt, you can list the current numbered lines in the
WORD-PROCESSING field. You can then easily choose the lines to be
transferred.

If the field from which you are transferring text displays text without
wrapping, you receive the message shown in
<u><span style="color:blue">Figure 120</span></u>:

<span id="_Toc527389324"></span><span id="_Ref389661772">Figure</span>
120: Line Editor—Example of a Possible Warning Message when Using the
Transfer Lines From Another Document Option

<div style="border:solid windowtext 1.0pt;padding:3.0pt 3.0pt 3.0pt 3.0pt;
margin-left:9.35pt;margin-right:9.35pt">

  WARNING!

  The field you are transferring text from displays text without
wrapping.

  The field you are transferring text into may display text differently.

 

  Do you want to continue?

 

  Enter Yes or No:

</div>

 

Consider the possibility that the text transferred from the no-wrap
field may be unreadable, if the field you are transferring into does
wrap text. For example, a spreadsheet might lose the alignment of its
columns.

If the transfer does *not* succeed, the message **\<no change\>** is
shown. The transfer might fail for several reasons:

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Incorrect syntax for the extended pointer.

<span style="font-family:
Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>An attempted transfer from other than a WORD-PROCESSING
field type.

<span style="font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">     
</span></span>Lack of permission to read the file from which you are
trying to extract text.

You *must* have **READ** access to transfer text from a file.

<img src="user-manual.fld/image002.png" id="Picture 152" data-border="0"
width="22" height="22" alt="Note" />     **REF:** For details of the
different types of file security, see the <span id="_Hlt446149627">“Data
Security</span>” section in the *VA FileMan Advanced User Manual*.

 

</div>

<span style="font-size:12.0pt;font-family:&quot;Times New Roman&quot;,serif;color:black">  
</span>

<div class="WordSection5">

<span id="_Toc446123570"></span><span id="Glossary"></span><span id="_Toc527389203">Glossary</span>

<table class="MsoNormalTable" data-border="1" data-cellspacing="0"
data-cellpadding="0" style="border-collapse:collapse;border:none">
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header" style="page-break-inside:avoid">
<th width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; background: #D9D9D9; padding: 0in 4.0pt 0in 4.0pt"><p>Term</p></th>
<th width="471" data-valign="top"
style="width: 353.0pt; border: solid windowtext 1.0pt; border-left: none; background: #D9D9D9; padding: 0in 4.0pt 0in 4.0pt"><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>.001
Field</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
field containing the <span id="_Hlt446298897">internal</span> entry
number of the record.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>.01
Field</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>The
one field that <em>must</em> be present for every file and file entry.
It is also called the NAME field. At a file’s creation the
<strong>.01</strong> field is given the label <strong>NAME</strong>.
This label can be changed.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Access
Codes</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>In
VA FileMan, a string of codes that determines your security access to
files, fields, and templates. In Kernel, you enter an Access code to
identify yourself during signon.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Alternate
Editor</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>One
of the text editors available for use from VA FileMan. Editors available
vary from site to site. They are entries in the ALTERNATE EDITOR (#1.2)
file.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><span
id="at_sign"></span><span
id="at_sign_index"><strong>At-Sign</strong></span>
<strong>(@)</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
VA FileMan security Access Code that gives the user programmer-level
access to files and to VA FileMan’s developer features. See <a
href="#programmer_access">Programmer Access</a><span
id="_Hlt446149643"></span>. Also, the at-sign character
(<strong>@</strong>) is used at VA FileMan field prompts to delete
data.</p>
<p><img src="user-manual.fld/image003.png" data-border="0" width="37"
height="37" alt="Caution" /> CAUTION: Programmer access in VistA is
defined as DUZ(0)=“@”. It grants the privilege to become a developer in
VistA. Programmer access allows you to work outside many of the security
controls enforced by VA FileMan, enables access to all VA FileMan files,
access to modify data dictionaries, etc. It is important to proceed with
caution when having access to the system in this way.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Audit
Trail</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>The
record or log of an ongoing audit.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Auditing</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>The
monitoring and recording of computer use.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Backward
Pointer</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
pointer to your current file from another file; used in the extended
pointer syntax.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Boolean
Expression</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
logical comparison between values yielding a <strong>true</strong> or
<strong>false</strong> result. In M:</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span><strong>Zero</strong> means <strong>false</strong>.</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span><em>Non</em>-<strong>Zero</strong> (often one) means
<strong>true</strong>.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Canonic
Number</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
number with no leading <strong>zeroes</strong> and no trailing
<strong>zeroes</strong> after a decimal point.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Caption</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>In
<a href="#screenman">ScreenMan</a><span id="_Hlt446149648"></span>, a
label displayed on the screen. Captions often identify fields that are
to be edited.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Caret</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>The
<strong>^</strong> character (caret); used in VA FileMan for exiting an
option or canceling a response. Also used in combination with a field
name or prompt to jump to the specified field or prompt.</p>
<p><img src="user-manual.fld/image002.png" id="Picture 326"
data-border="0" width="22" height="22"
alt="Note" /> <strong>NOTE:</strong> Sometimes referred to as the
up-arrow in some legacy documentation.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Command
Area</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>In
<a href="#screenman">ScreenMan</a><span id="_Hlt446149651"></span>, the
bottom portion of the screen used to display help information and to
accept user commands.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Cross-Reference</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>An
attribute of a field or a file that identifies an action that should
take place when the value of a field is changed. Often, the action is
the placement of the field’s value into an index. A Traditional
cross-reference is defined with a specific field. A New-Style
cross-reference is a file attribute and can be composed of one or more
fields. New-Style cross-references are stored in the INDEX (#.11)
file.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Cursor</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>On
your display terminal, the line or rectangle identifying where your next
input is placed on the screen.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Data
Dictionary</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
record of a file’s structure, its elements (fields and their
attributes), and relationships to other files. Often abbreviated as
DD.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><span
id="data_type"></span><span id="_Hlt446149670"></span><strong>DATA
TYPE</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>The
kind of data stored in a field. The following are examples of VA FileMan
DATA TYPEs:</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>NUMERIC</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>COMPUTED</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span>WORD-PROCESSING</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Database</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>An
organized collection of data spanning many files. Often, all the files
on a system constitute that system’s database.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Decentralized
Hospital Computer Program (DHCP)</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>See
<a href="#vista">VistA</a>.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Default</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
computer-provided response to a question or prompt. The default might be
a value pre-existing in a file. Often, you can change a
default.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Device
Prompt</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
Kernel prompt at which you identify where to send your output.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Edit
Window</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>In
<a href="#screenman">ScreenMan</a><span id="_Hlt446149660"></span>, the
area in which you enter or edit data. It is highlighted with either
reverse video or an underline. In Screen Editor, the area in which you
enter and edit text; the area between the status bar and the
ruler.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Entry</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
record in a file. “Entry” and “record” are used
interchangeably.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Extended
Pointers</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
means to reference fields in files other than your current
file.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Field</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>In
an entry, a specified area used to hold values. The specifications of
each VA FileMan field are documented in the file’s data
dictionary.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Field
Number</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>The
unique number used to identify a field in a file. A field can be
referenced by <strong>#</strong> followed by the field number.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><span
id="file"></span><span
id="_Hlt446149822"></span><strong>File</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
set of related records (or entries) treated as a unit.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Form</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>In
<a href="#screenman">ScreenMan</a><span id="_Hlt446149664"></span><span
id="_Hlt445775658"></span>, a group of one or more pages that comprise a
complete transaction. Comparable to an <a href="#input_template">INPUT
template</a><span id="_Hlt446149667"></span>.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>FREE
TEXT</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
<a href="#data_type">DATA TYPE</a><span id="_Hlt446149669"></span> that
can contain any printable characters.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Full-Screen
Editing</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>The
ability to enter data in various locations on the two-dimensional
computer display. Compare to scrolling mode.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Histogram</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
type of bar graph that indicates frequency of occurrence of particular
values.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Identifier</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>In
VA FileMan, a field that is defined to aid in identifying an entry in
conjunction with the NAME field.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Index</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>An
ordered list used to speed retrieval of entries from a file based on a
value in some field or fields. Definitions:</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span><strong>Simple Index—</strong>Refers to an index that
stores the data for a single field.</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span><strong>Compound Index—</strong>Refers to an index that
stores the data for more than one field.</p>
<p>Indexes are created and maintained via cross-references.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><span
id="input_template"></span><span id="_Hlt446149668"></span><strong>INPUT
Template</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
pre-defined list of fields that together comprise an editing
session<span style="color:windowtext">. Within INPUT templates, sub
files can now be edited in more than one place within the template, so
that different subfields can be edited each time.</span></p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><span
id="ien"></span><span id="_Hlt446149790"></span><strong>Internal Entry
Number</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>The
number used to identify an entry within a file. Every record has a
unique internal entry number. Often abbreviated as IEN.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Kernel</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
<span id="_Hlt445772256"></span><a href="#vista">VistA</a> software
application that functions as an intermediary between the host operating
system and <a href="#vista">VistA</a> applications. Kernel includes
installation, menu, security, and device services.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Key</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
group of fields that, taken collectively, uniquely identifies a record
in a file or subfile. All fields in a key <em>must</em> have values.
Definitions:</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span><strong>Simple Key—</strong>Refers to keys that are
composed of only one field.</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span><strong>Compound Key—</strong>Refers to keys that are
composed of more than one field.</p>
<p>Keys are stored in the KEY (#.31) file.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>LAYGO</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
user’s authorization to create a new entry when editing a computer file.
An acronym for <strong>L</strong>earn <strong>A</strong>s
<strong>Y</strong>ou <strong>Go</strong>.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><span
id="line_editor"></span><span id="_Hlt446149796"></span><strong>Line
Editor</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>The
VA FileMan editor that lets you input and change text on a line-by-line
basis. The Line Editor works in scrolling mode. See <a
href="#screen_editor">Screen Editor</a><span
id="_Hlt446149680"></span>.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Lookup</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>To
find an entry in a file using a value for one of its fields.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Mailman</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>An
electronic mail system (email) that allows you to send messages to and
receive them from other users via the computer. It is part of <a
href="#vista">VistA</a>.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Menu</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
list that includes the names of options from which you can select an
activity.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><span
id="multiple"></span><span
id="_Hlt446143601"></span><strong>Multiple</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
VA FileMan <a href="#data_type">DATA TYPE</a><span
id="_Hlt446149685"></span> that allows more than one value for a single
entry. See <a href="#subfile">Subfile</a><span
id="_Hlt446149744"></span>.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>MUMPS</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>Abbreviated
as M. The American National Standards Institute (ANSI) computer language
used by VA FileMan and throughout <a href="#vista">VistA</a>. The
acronym MUMPS stands for <strong>M</strong>assachusetts General Hospital
<strong>U</strong>tility <strong>M</strong>ulti
<strong>P</strong>rogramming <strong>S</strong>ystem.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Name
Field</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>The
one field that <em>must</em> be present for every file and file entry.
It is also called the <strong>.01</strong> field. At a file’s creation
the <strong>.01</strong> field is given the label <strong>NAME</strong>.
This label can be changed.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Navigation</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>Navigation
can mean switching your reference point from one file to another.
Navigation can also mean moving your cursor around a terminal display or
a document using cursor keys and other commands.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Non-Canonic
Number</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
number with either leading <strong>zeroes</strong> or trailing
<strong>zeroes</strong> after a decimal point. M treats
<em>non</em>-canonic numbers as text instead of as numbers.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Non-NULL</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
value other than <strong>NULL</strong>. A <strong>space</strong> and
<strong>zero</strong> are <em>non</em>-<strong>NULL</strong>
values.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>NULL</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>Empty.
A field or variable that has no value associated with it is
<strong>NULL</strong>.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>NULL
Response</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>When
replying to a prompt, pressing only the <strong>Enter</strong> key,
abbreviated as <strong>&lt;Enter&gt;</strong>, to enter
nothing.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Numeric
Expression</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>An
expression whose value is a number. Compare to string
expression.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Operator</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>One
of the processes done to the elements in an expression to create a
value.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Option</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
computing activity that you can select, usually a choice from a
menu.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Paste</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>Insert
text or other data as input into one computer program that has been
copied into a clipboard by the same or by another computer
program.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Pattern
Match</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>In
M, an operator that compares the contents of a variable or literal to a
specified pattern of characters or kinds of characters.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>PF
Keys</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>Keys
on a terminal keyboard labeled <strong>PF1</strong>,
<strong>PF2</strong>, etc. that are used to perform special functions
instead of displaying visible characters.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>POINTER
TO A FILE</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
field <a href="#data_type">DATA TYPE</a><span id="_Hlt446149692"></span>
that contains an explicit reference to an entry in a file. POINTER TO A
FILE-type fields are used to relate files to each other.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Popup
Page</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>In
<a href="#screenman">ScreenMan</a><span id="_Hlt446149695"></span>, a
page that overlays the regular ScreenMan screen in order to present the
contents of a selected Multiple.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Preferred
Editor</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>The
editor always entered when you access a WORD-PROCESSING-type field; your
default editor. Kernel <em>must</em> be present to establish a Preferred
Editor.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><span
id="print_template"><strong>Print Template</strong></span></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>The
stored specifications of a printed report, including fields to be
printed and formatting instructions.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><span
id="programmer_access"></span><span
id="_Hlt446149645"></span><strong>Programmer Access</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>The
ability to use VA FileMan features that are reserved for application
developers. Referred to as “having the <span
id="_Hlt446149762">at-sign</span> (<strong>@</strong>)” because the
at-sign is the <strong>DUZ(0)</strong> value that grants programmer
access.</p>
<p><img src="user-manual.fld/image003.png" data-border="0" width="37"
height="37" alt="Caution" /> CAUTION: Programmer access in VistA is
defined as DUZ(0)=“@”. It grants the privilege to become a developer in
VistA. Programmer access allows you to work outside many of the security
controls enforced by VA FileMan, enables access to all VA FileMan files,
access to modify data dictionaries, etc. It is important to proceed with
caution when having access to the system in this way.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Prompt</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
question or message from the computer requiring your response.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Record</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
set of data pertaining to a single entity in a file; an entry in a
file.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Record
Number</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>See
<a href="#ien">Internal Entry Number</a><span
id="_Hlt446149788"></span>.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Relational
Navigation</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>Changing
your current (or primary) file reference to another file. Relational
navigation is accomplished by using the extended pointer syntax without
specifying a field in the referenced file.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Required
Field</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
field that <em>cannot</em> be left <strong>NULL</strong> for an
entry.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Scattergram</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
graph in which occurrences of two fields are displayed on an
<strong>X-Y</strong> coordinate grid to aid in data analysis.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><span
id="screen_editor"></span><span id="_Hlt446149682"></span><strong>Screen
Editor</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>VA
FileMan’s <a href="#screen_oriented">Screen-Oriented</a> text editor. It
can be used to enter data into any WORD-PROCESSING field using
full-screen editing instead of line-by-line editing. See <a
href="#line_editor">Line Editor</a><span
id="_Hlt446149795"></span>.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><span
id="screen_oriented"></span><span
id="_Hlt446149793"></span><strong>Screen-Oriented</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
computer interface in which you see many lines of data at a time and in
which you can move your cursor around the display screen using screen
navigation commands. Compare to <a href="#scrolling_mode">Scrolling
Mode</a><span id="_Hlt446149798"></span>.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><span
id="screenman"></span><span
id="_Hlt445775660"></span><strong>ScreenMan</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>The
set of routines that supports <a
href="#screen_oriented">Screen-Oriented</a> data editing and data
display.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><span
id="scrolling_mode"></span><span
id="_Hlt446149799"></span><strong>Scrolling Mode</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>The
presentation of the interactive dialogue one line at a time. Compare to
<a href="#screen_oriented">Screen-Oriented</a>.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>SDP</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>An
area on disk set aside for temporary, sequential storage of data; an
abbreviation for <strong>S</strong>equential <strong>D</strong>isk
<strong>P</strong>rocessor. It is available on some M implementations
(e.g., DSM-11).</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>SEARCH
Template</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>The
saved results of a search operation. Usually, the actual entries found
are stored in addition to the criteria used to select those
entries.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Security</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>The
strategies and procedures used to ensure that user access to data and
data structures is controlled and appropriate.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>SET
OF CODES</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
field <a href="#data_type">DATA TYPE</a><span id="_Hlt446149808"></span>
where a short character string is defined to represent a longer
value.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Simple
Extended Pointers</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>An
extended pointer that uses a pre-existing pointer relationship to access
entries in another file.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Sort</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>To
place items in order, often in alphabetical or numeric
sequence.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>SORT
Template</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>The
stored record of sort specifications. It contains sorting order as well
as restrictions on the selection of entries. Used to prepare entries for
printing.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Stuff</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>To
place values directly into a field, usually with no user
interaction.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Subentry</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>An
entry in a Multiple; also called a subrecord.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Subfield</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>A
field in a <a href="#multiple">Multiple</a><span
id="_Hlt446149813"></span>.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><span
id="subfile"></span><span
id="_Hlt446149746"></span><strong>Subfile</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>The
data structure of a <a href="#multiple">Multiple</a><span
id="_Hlt446149817"></span>. In many respects, a Subfile has the same
characteristics as a <a href="#file">File</a><span
id="_Hlt446149820"></span>.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Terminal
Emulation</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>Using
one kind of terminal or computer display to mimic another kind. Often
used with personal computer (PC) remote communication
applications.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Terminal
Type</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>The
designation of the kind of computer peripheral being used (e.g., the
kind of video display or printer). Full terminal type functionality is
supplied by Kernel.</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Truth
Test</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>An
evaluation of an expression yielding a <strong>true</strong> or
<strong>false</strong> result. In M, usually either of the following is
returned from a truth test:</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span><strong>1—</strong>True.</p>
<p><span style="font-family:Symbol">·<span
style="font:7.0pt &quot;Times New Roman&quot;">      
</span></span><strong>0—</strong>False.</p></td>
</tr>
<tr class="even" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><strong>Upload</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>Send
a file from one computer system to another (usually using communications
software).</p></td>
</tr>
<tr class="odd" style="page-break-inside:avoid">
<td width="159" data-valign="top"
style="width: 119.5pt; border: solid windowtext 1.0pt; border-top: none; padding: 0in 4.0pt 0in 4.0pt"><p><span
id="vista"></span><span
id="_Hlt445773681"></span><strong>VistA</strong></p></td>
<td width="471" data-valign="top"
style="width: 353.0pt; border-top: none; border-left: none; border-bottom: solid windowtext 1.0pt; border-right: solid windowtext 1.0pt; padding: 0in 4.0pt 0in 4.0pt"><p>The
Veterans Health Information Systems and Technology Architecture (VistA),
within the Department of Veterans Affairs (VA), is the component of the
Veterans Health Administration (VHA) that develops software and
installs, maintains, and updates compatible computer systems in VA
medical sites. (Previously known as the Decentralized Hospital Computer
Program [DHCP].)</p></td>
</tr>
</tbody>
</table>

<span id="_Hlt445772258"></span> 

<img src="user-manual.fld/image081.png" id="Picture 173" data-border="0"
width="24" height="24" alt="Note" />    **REF:** For a list of commonly
used terms and definitions, see the OIT Master Glossary VA Intranet
website.  
  
For a list of commonly used acronyms, see the VA Acronym Lookup Intranet
Website.

 

</div>

<span style="font-size:12.0pt;font-family:&quot;Times New Roman&quot;,serif;color:black">  
</span>

<div class="WordSection6">

<span id="_Toc446123571"></span><span id="Index"></span><span id="_Toc527389204"></span><span id="_Hlt446131684"></span>Index

</div>

<span style="font-size:12.0pt;font-family:&quot;Times New Roman&quot;,serif;color:black">  
</span>

<div class="WordSection7">

A

Abbreviations

Dates, 65

Times, 66

Acceptable Formats for Entering

Dates, 64

Times, 65

Access

LAYGO, 4

Add (Append) More Text (Line Editor), 117

Add a Record at a POINTER TO A FILE Field, How to, 83

Add a Record, How to, 78

Add Lines to End of Text Option, 117

Adding

From Multiples, 85

Records, 78

Adding a

Duplicate Record, 79

Duplicate-Named Entry, 84

New Entry to a Multiple

ScreenMan, 98

Advanced Features

Line Editor, 118

Assumptions, xxi

At-sign

Deleting

Field’s Value, 59

File/Record Entry, 78, 80

Multiple Entry, 85

Subrecord, 98

Template, 27

Text at the Replace... prompt, 56

Text Terminator, 119

Entering Times, 65

Including NULL Records in a Report, 15

Omit Headers and Page Feeds from Printed Output, 31

Omit Headers from Printed Output, 31

Suppressing Subheaders, 17

Audit Trail, 7

Avoiding Lost Characters

Screen Editor, 111

B

BOOLEAN DATA TYPE Fields, 74

Browser, 45

As an Option, 51

Clipboard, 48

Cursor Movement (Navigation Keystrokes), 47

Features, 47

Navigation Keystrokes, 47

Online Help, 49

Other Features, 50

Screen, 46

Search, 49

Browser Option, 45, 51

C

Callout Boxes, xx

Capabilities When Printing, 10

CAPTIONED OUTPUT

COMPUTED Fields and Record Numbers, 28

Template, 70

CAPTIONED PRINT Template, 28, 70

Caret

Exiting at Prompts, 60, 61

Inserting

Multiple-type Print Fields, 27

Jumping to another Field, 60

ScreenMan, 92

Characters Lost, Avoiding

Screen Editor, 111

Choose Your Own

Device, 9

Print Fields, 8, 21

Word-processing Editors, 101

Choosing a Preferred Editor, 101

Clipboard

Browser, 48

Column Format for VA FileMan Prints, 11

Commands

Available with the Line Editor, 116

ScreenMan Command Line Options:, 93

Compound Key, 59

COMPUTED DATA TYPE Fields, 70

Computed Fields, 7

COMPUTED Fields and Record Numbers in CAPTIONED OUTPUT, 28

Conditions

Combining in a Search, 37

Entering in a Search, 34

Tests in a Search, 35

Conventions

Documentation, xix

Creating

PRINT Templates, 26

SEARCH Templates, 41

SORT Templates, 7, 20

Criteria, Saving in

PRINT Templates, 26

SEARCH Templates, 41

SORT Templates, 20

Cursor Movement (Navigation Keystrokes)

Browser, 47

Screen Editor, 105

ScreenMan, 91, 94

Custom Footers, 32

Custom Headings and Footers, 31

Cutting and Pasting

Screen Editor, 107

D

Data Dictionary

Data Dictionary Utilities Menu, xxi

Listings, xxi

Data Entry Session (Typical Example), 62

Data Types of Fields, 63

DATE/TIME, 64

FREE TEXT, 68

NUMERIC, 66

SET OF CODES, 67

WORD-PROCESSING, 68

DATA TYPEs of Fields

COMPUTED, 70

Multiples (Subfiles), 77

POINTER TO A FILE, 71

Subfiles (Multiples), 77

VARIABLE-POINTER, 72

DATA TYPES of Fields

BOOLEAN, 74

FT DATE, 76

FT POINTER, 76

LABEL REFERENCE, 74

RATIO, 76

TIME, 75

UNIVERSAL TIME, 75

YEAR, 75

Database and Files, 2

DATE/TIME Data Type Fields, 64

Dates

Abbreviations, 65

Acceptable Formats, 64

DDBROWSER Option, 45, 51

Default Responses, 55

Default Responses (Longer), 56

Delete Line(s) Option, 118

Deleting

A Field’s Value with the at-sign, 59

A Multiple (Subfile) Entry in ScreenMan, 98

From Multiples, 85

How to Delete a Record, 80

Lines of Text in the Line Editor, 118

Records, 78

Screen Editor, 108

ScreenMan, 94

Details

ScreenMan, 100

Search, 40

Devices, Choose Your Own, 9

DI DDU Menu, xxi

DIEDIT Option, 82, 86

Differences from Scrolling Mode Editing

ScreenMan, 89

DIINQUIRE Option, 5, 6, 10

DILIST Option, xxi

DIOTHER Menu, 51

DIPRINT Option, 10

Disclaimers, xix

Software, xviii

DISEARCH Option, 34

DIUSER Menu, 51

Documentation

Conventions, xix

Symbols, xix

Documentation Navigation, xx

Duplicates

Adding a

Duplicate Record, 79

Duplicate-Named Entry, 84

E

Edit a Line (Replace \_\_ With \_\_) option, 113

Edit Fields

How to do it in ScreenMan, 94

Edit Lines with M Commands

Line Editor, 120

Edit User Characteristics Option, 101

Editing

ScreenMan, 94

Editor Change Option, 120

Editors

Change (Switch) Editors

Line Editor, 120

Choice of Word-processing Editors, 101

Choosing a Preferred Editor, 101

Line Editor, 112

Replace...With, 56, 63, 114, 115

Screen Editor, 102

Select Your Preferred Editor, 101

Switch (Change) Editors

Line Editor, 120

Switching to another Editor While Editing, 102

WORD-PROCESSING Fields, 68

Zoom Editor in ScreenMan, 95

Edits

Edit User Characteristics Option, 101

How to File in ScreenMan, 100

Ellipsis, 114

Enter Key (\<Enter\>), 52

Enter or Edit File Entries Option, 82, 86

Entering

Commands in the Screen Editor, 104

Text in the

Line Editor, 112

Screen Editor, 104

Example

Data Entry Session (Typical), 62

Exiting

Screen Editor, 106

ScreenMan, 92

From a Subpage:, 98

With the Caret, 60, 61

External vs. Internal Field Values

Search Conditions, 42

SET OF CODES, 67

F

Features

Browser, 47

Line Editor Advanced Features, 118

Other Features of the Browser, 50

Other Print Features, 29

Search, 40

Field Prompts

Special Responses to, 59

Fields

.01 Field, 78

Choosing Fields to Print, 21

Data Types, 63

DATE/TIME, 64

FREE TEXT, 68

NUMERIC, 66

SET OF CODES, 67

WORD-PROCESSING, 68

DATA TYPEs

BOOLEAN, 74

COMPUTED, 70

FT DATE, 76

FT POINTER, 76

LABEL REFERENCE, 74

Multiples (Subfiles), 77

POINTER TO A FILE, 71

RATIO, 76

Subfiles (Multiples), 77

TIME, 75

UNIVERSAL TIME, 75

VARIABLE-POINTER, 72

YEAR, 75

Deleting a Field’s Value, 59

Jumping to another Field, 60

Mandatory (Required), 61

Required (Mandatory), 61

Fields, Records, and Files, 1

File Access

LAYGO, 4

File Edits

How to do it in ScreenMan, 100

File Transfer from Foreign CPU Option, 118

Line Editor, 118

FileMan

Prompts, 51

What is it?, xvi

Files

KERNEL SYSTEM PARAMETERS (#8989.3), 29

PATIENT (#2), 71, 72

PRINT TEMPLATE (#.4), 26

PROVIDER, 72

SORT TEMPLATE (#.401), 20, 40, 41

STATE (#5), 71, 72

Files and the Database, 2

Files, Save as Text

Screen Editor, 110

Finding Text

Screen Editor, 106

Footers

Customized, 31, 32

Forcing Creation of a

PRINT Template, 26

SORT Template, 21

Format

Output in a Search, 39

Paragraphs in the Screen Editor, 107

FREE TEXT Data Type Fields, 68

FT DATE DATA TYPE Fields, 76

FT POINTER DATA TYPE Fields, 76

G

Getting Online Help at Any Prompt, 54

Glossary, 123

H

Headings

Customized, 31

Help

At Prompts, xxi

Getting Online Help at Any Prompt, 54

Online, xxi

Question Marks, xxi

Home Pages

Adobe Website, xxii

VA Software Document Library (VDL) Website, xxii

How to

Add a Record, 78

Add a Record at a POINTER TO A FILE Field, 83

Delete a Record, 80

Edit Fields

ScreenMan, 94

Enter Text in the Line Editor, 112

Exit the Screen Editor When PF Keys Not Working, 110

File Edits

ScreenMan, 100

Navigate between Fields

ScreenMan, 91

Navigate between Pages

ScreenMan, 92

Obtain Technical Information Online, xxi

Print Reports from Files, 10

Revise Existing Text in the Line Editor, 113

Search, 34

Select Your Preferred Editor, 101

Use this Manual, xvii

HTML Manuals, xviii

I

Incorrect Responses, 54

Inquire, 5

Inquire to File Entries Option, 6

Standard Captioned Output, 7

Inquire to File Entries Option, 5, 6, 10

Insert Lines after an Existing Line Option, 117

Insert New Lines of Text (Line Editor), 117

Intended Audience, xviii

Internal vs. External Field Values

Search Conditions, 42

SET OF CODES, 67

Introduction, xvi

J

Join (Combine) Two Lines of Text (Line Editor), 117

Join Line to the One Following Option, 117

Jumping to another Field with the Caret, 60

K

KERNEL SYSTEM PARAMETERS (#8989.3) File, 29

Key Fields, 59

Keys

Compound, 59

L

LABEL REFERENCE DATA TYPE Fields, 74

LAYGO File Access, 4

Line Editor, 112

Add (Append) More Text, 117

Add Lines to End of Text Option, 117

Advanced Features, 118

Change (Switch) Editors, 120

Commands, 116

Delete Line(s) Option, 118

Deleting Lines of Text, 118

Edit Lines with M Commands, 120

Editor Change Option, 120

Entering Text, 112

File Transfer from Foreign CPU Option, 118

Insert Lines after an Existing Line Option, 117

Insert New Lines of Text, 117

Join (Combine) Two Lines of Text, 117

Join Line to the One Following Option, 117

List a Range of Lines Option, 116

List the Message, 116

Programmer Edit, 120

Recognizing, 112

Revising Text, 113

Shortcuts, 113

Switch (Change) Editors, 120

Text-Terminator-String Change Option, 119

Transfer Lines From Another Document Option, 120

Transfer Text (from another WORD-PROCESSING Field), 120

Uploading Text with Blank Lines, 119

Y-Programmer Edit Option, 120

List a Range of Lines Option, 116

List File Attributes Option, xxi

List of Choices Prompts, 57

List the Message (Line Editor), 116

Long Fields

ScreenMan, 95

Longer Default Responses, 56

M

Mandatory (Required) Fields, 61

Manuals

In HTML, xviii

Menus

Data Dictionary Utilities, xxi

DI DDU, xxi

DIOTHER, 51

DIUSER, 51

Other Options, 51

User’s Toolbox, 101

VA FileMan, 51

XUSERTOOLS, 101

Modes

Screen Editor, 109

ScreenMan, 95

Scrolling Mode vs. Screen Mode, 4

Multiple Copies of a Print, 29

Multiples (Subfiles)

Adding a

New Entry in ScreenMan, 98

Adding and Deleting from, 85

DATA TYPE Fields, 77

DATA TYPEs Fields

Adding and Deleting from, 85

Deleting an Entry in ScreenMan, 98

In Repeating Blocks in ScreenMan, 99

Linked to ”Popup” Subpages in ScreenMan, 97

ScreenMan, 97

Searching for, 42

N

Navigate between

Fields

How to do it in ScreenMan, 91

Pages

How to do it in ScreenMan, 92

Navigation Keystrokes

Browser, 47

Screen Editor, 105

ScreenMan, 91

Navigational Keys for Repeating Blocks

ScreenMan, 100

NULL Fields in Your Sort, 15

Numbers

Canonic Numbers and Non-Canonic Strings, 13

NUMERIC Data Type Fields, 66

O

Online

Documentation, xxi

Technical Information, How to Obtain, xxi

Online Help

Browser, 49

Operators for Combining Search Conditions, 37

Options

Add Lines to End of Text, 117

Browser, 45, 51

Data Dictionary Utilities, xxi

DDBROWSER, 45, 51

Delete Line(s), 118

DI DDU, xxi

DIEDIT, 82, 86

DIINQUIRE, 5, 6, 10

DILIST, xxi

DIOTHER, 51

DIPRINT, 10

DISEARCH, 34

DIUSER, 51

Edit a Line (Replace \_\_ With \_\_), 113

Edit User Characteristics, 101

Editor Change, 120

Enter or Edit File Entries, 82, 86

File Transfer from Foreign CPU, 118

Inquire to File Entries, 5, 6, 10

Insert Lines after an Existing Line, 117

Join Line to the One Following, 117

List a Range of Lines, 116

List File Attributes, xxi

Other Options, 51

Print File Entries, 10

Search File Entries, 34

Text-Terminator-String Change, 119

Transfer Lines From Another Document, 120

User’s Toolbox, 101

VA FileMan, 51

XUSEREDITSELF, 101

XUSERTOOLS, 101

Y-Programmer Edit, 120

Order When Sorting, 13

Orientation, xvii

Other Features

Browser, 50

Print, 29

Other Options Menu, 51

Output

Format in a Search, 39

P

Partial Responses, 55

Pasting and Cutting

Screen Editor, 107

Pasting and Uploading

Screen Editor, 110

PATIENT  (#2)File, 72

PATIENT (#2) File, 71, 72

Personal Computers and the Screen Editor, 110

PF Keys Not Working, How to Exit in the Screen Editor, 110

POINTER TO A FILE DATA TYPE Fields, 71

PREFERRED EDITOR Prompt, 102

Print, 10

Capabilities, 10

CAPTIONED PRINT Template, 28

Choosing Fields to Print, 21

Custom Footers, 32

Custom Headings and Footers, 31

Forcing Creation of a PRINT Template, 26

Including NULL Fields in Your Sort, 15

Inserting Multiple-type Print Fields, 27

Multiple Copies, 29

Other Features, 29

PRINT FIELD Prompts, 22

Qualifiers, 22

Report Headings, 29

Reports from Files, How to, 10

Saving Criteria in PRINT Templates, 26

Selecting Entries

All Entries with the Same Value for One Field to Print, 14

For Printing, 14

Other Ways to Print, 14

SORT BY Fields, 31

Prompts, 17

Specifying, 12

Sorting, 12

Order, 13

Print Sort Criteria in the Heading or the Footer, 33

Qualifiers, 17

Specifying Fields to Print, 21

Specifying SORT BY Fields, 12

Standard Column Format, 11

Statistics Only, 29

Suppressing Report Headings (and Page Feeds), 31

Templates

CAPTIONED PRINT, 28

Forcing the Creation of, 26

PRINT, 26

Using and Editing, 27

Using and Editing PRINT Templates, 27

Print Fields, Choose Your Own, 8

Print File Entries Option, 10

Print Number of Matches Found, 42

PRINT TEMPLATE (#.4) File, 26

Programmer Edit

Line Editor, 120

Prompts

Default Responses, 55

Display Audit Trail, 7

Getting Online Help, 54

Include Computed Fields, 7

Incorrect Responses, 54

List of Choices, 57

Longer Default Responses, 56

Partial Responses, 55

PREFERRED EDITOR, 102

PRINT FIELD, 22

Replace... Prompt Shortcuts, 57

Replace...With, 114

Editor, 56

Shortcuts, 114, 115

Responding to, 53

SORT BY Fields, 17

Special Responses to Field Prompts, 59

Standard Prompt Structure, 53

VA FileMan, 51

PROVIDER File, 72

PS Anonymous Directories, xxii

Q

Question Mark Help, xxi, 54

Quotes

Use When Adding a

Duplicate Record, 79

Duplicate-Named Entry, 84

R

RATIO DATA TYPE Fields, 76

Recall (Spacebar), 61

Recognizing the Line Editor, 112

Records

Add a Record, 78

Add a Record at a POINTER TO A FILE Field, 83

Adding a

Duplicate, 79

Duplicate-Named Entry, 84

Adding and Deleting, 78

Delete a Record, 80

Repointing When Deleting Records, 80

Records, Fields, and Files, 1

Reference

Print Qualifiers, 22

Sort Qualifiers, 17

References, xxii

Repeating Blocks

ScreenMan, 99

Replace... Prompt Shortcuts, 57

Replace...With Editor, 56, 63, 114, 115

Repointing When Deleting Records, 80

Report Headings, 29

Required (Mandatory) Fields, 61

Responding to Prompts, 53

Responses

Default Entry, 55

Incorrect Entry, 54

Longer Default Entry, 56

Partial Entry, 55

Return Key (\<RET\>), 52

Reusing

Search

Criteria, 41

Results in a Print, 41

Results in another Search, 41

Sort Criteria in New Reports, 21

Revising Text in the Line Editor, 113

S

Saving

Print Criteria in PRINT Templates, 26

Screen Editor, 106

ScreenMan, 92

Search Criteria in SEARCH Templates, 41

Sort Criteria in SORT Templates, 20

Screen Editor, 102

Avoiding Lost Characters, 111

Characters Lost, Avoiding, 111

Cursor Movement (Navigation Keystrokes), 105

Cutting and Pasting, 107

Deleting, 108

Entering

Commands, 104

Text, 104

Exiting and Saving, 106

Files, Save as Text, 110

Finding Text, 106

Formatting Paragraphs, 107

How to Exit When PF Keys Not Working, 110

Modes/Settings, 109

Navigation Keystrokes, 105

Pasting and Cutting, 107

Pasting and Uploading, 110

Personal Computers, 110

Saving and Exiting, 106

Screen, 104

Settings/Modes, 109

Symbol Characters, 110

Terminal Type Setting, 109

Troubleshooting, 109

Uploading, 110

Wrap Vs. No Wrap, 110

Screen Mode vs. Scrolling Mode, 4

ScreenMan, 88

Adding a

New Entry to a Multiple, 98

Command Line Options, 93

Cursor Movement (Navigation Keystrokes), 91, 94

Deleting, 94

Deleting an Entry in a Multiple, 98

Details, 100

Differences from Scrolling Mode Editing, 89

Editing, 94

Exiting a Subpage, 98

Exiting and Saving, 92

How to

Edit Fields, 94

File Edits, 100

Navigate between Fields, 91

Navigate between Pages, 92

Long Fields, 95

Modes, 95

Multiples (Subfiles), 97

In Repeating Blocks, 99

Linked to ”Popup” Subpages, 97

Navigation Keystrokes, 91

Navigational Keys for Repeating Blocks, 100

Repeating Blocks, 99

Saving and Exiting, 92

Screen, 90

Shortcut Keys, 93

Similarities with Scrolling Mode Editing, 88

Troubleshooting, 101

WORD-PROCESSING Fields, 95

Zoom Editor, 95

Scrolling Mode vs. Screen Mode, 4

Search, 34

Browser, 49

Combine Conditions, 37

Conditions, 34

Tests, 35

External vs. Internal Field Values in Search Conditions, 42

Format Output, 39

How to Search, 34

Internal vs. External Field Values in Search Conditions, 42

Multiples (Subfiles), 42

Operators for Combining Search Conditions, 37

Print Number of Matches Found, 42

Reusing

Search Criteria, 41

Search Results in a Print, 41

Search Results in another Search, 41

Saving Criteria in SEARCH Templates, 41

Steps, 34

Combine Conditions, 37

Entering Conditions, 34

Format Output, 39

Subfiles (Multiples), 42

Templates, 40, 41

Creating, 41

Reusing

Search Criteria, 41

Search Results in a Print, 41

Search Results in another Search, 41

Search File Entries Option, 34

Select Entries for Printing

Sorting, 14

Select Your Preferred Editor, How to, 101

Selecting All Entries with the Same Value for One Field to Print, 14

Selecting Entries Other Ways to Print, 14

SET OF CODES Data Type Fields, 67

Settings

Screen Editor, 109

Shortcuts

Line Editor, 113

Replace... Prompt, 57

Replace...With Prompt, 114, 115

ScreenMan, 93

Similarities with Scrolling Mode Editing

ScreenMan, 88

Software Disclaimer, xviii

Sort

Canonic Numbers and Non-Canonic Strings, 13

Forcing Creation of a SORT Template, 21

Including NULL Fields in Your Sort, 15

Non-Canonic Strings and Canonic Numbers, 13

Order Before Printing, 13

Qualifiers, 17

TXT, 13

Reusing Sort Criteria in New Reports, 21

Saving Criteria in SORT Templates, 20

Searching, 40

Select Entries for Printing, 14

SORT BY Fields

Prompts, 17

Specifying, 12

Sorting Before Printing, 12

Specifying SORT BY Fields, 12

Templates, 7, 20

Forcing the Creation of, 21

Reusing Sort Criteria in New Reports, 21

SORT BY Fields, 31

SORT TEMPLATE (#.401) File, 20, 40, 41

Spacebar Recall, 61

Special Responses to Field Prompts, 59

Specifying Fields to

Print, 21

Sort, 12

Specifying SORT BY Fields, 12

Standard Captioned Output, 7

Standard Column Format for VA FileMan Prints, 11

Standard Prompt Structure, 53

STATE  (#5)File, 71

STATE (#5) File, 71, 72

Statistics Only in Printing, 29

Steps in Searching, 34

Subfields, 77

Subfiles (Multiples)

Adding and Deleting from, 85

DATA TYPE Fields, 77

Adding and Deleting from, 85

Searching for, 42

Suppressing Report Headings (and Page Feeds), 31

Switching to another Editor While Editing, 102

Symbols

Found in the Documentation, xix

Screen Editor, 110

T

TBOX, 101

Templates

CAPTIONED OUTPUT, 70

CAPTIONED PRINT, 28, 70

PRINT, 26

Forcing the Creation of, 26

Using and Editing, 27

SEARCH, 40, 41

Reusing

Search Criteria, 41

Search Results in a Print, 41

Search Results in another Search, 41

SORT, 7, 20

Forcing the Creation of, 21

Reusing Sort Criteria in New Reports, 21

Terminal Type Setting

Screen Editor, 109

Text-Terminator-String Change Option, 119

Line Editor, 119

TIME DATA TYPE Fields, 75

Times

Abbreviations, 66

Acceptable Formats, 65

Transfer Lines From Another Document Option, 120

Transfer Text (from another WORD-PROCESSING Field), 120

Troubleshooting

Screen Editor, 109

ScreenMan, 101

TXT Sort Qualifier, 13

U

UNIVERSAL TIME DATA TYPE Fields, 75

Uploading ASCII Text, File Transfer from Foreign CPU

Line Editor, 118

Uploading Text with Blank Lines

Line Editor, 119

URLs

Adobe Website, xxii

VA Software Document Library (VDL) Website, xxii

User’s Toolbox Menu, 101

Using and Editing PRINT Templates, 27

V

VA FileMan

Prompts, 51

What is it?, xvi

VA FileMan Menu, 51

VA Software Document Library (VDL)

Website, xxii

VARIABLE-POINTER DATA TYPE Fields, 72

W

Websites

Adobe Website, xxii

VA Software Document Library (VDL), xxii

What is VA FileMan?, xvi

WORD-PROCESSING Data Type Fields, 68

Word-processing Editors, Choices, 101

WORD-PROCESSING Fields

ScreenMan, 95

Wrap Vs. No Wrap

Screen Editor, 110

X

XUSEREDITSELF Option, 101

XUSERTOOLS Menu, 101

Y

YEAR DATA TYPE Fields, 75

Y-Programmer Edit Option, 120

Z

Zoom Editor

ScreenMan, 95

</div>

<span style="font-size:12.0pt;font-family:&quot;Times New Roman&quot;,serif;color:black">  
</span>

<div class="WordSection8">

<span id="_Hlt457719552"></span> 

</div>
