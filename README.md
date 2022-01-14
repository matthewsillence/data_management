---
description: >-
  This is a guide to activities required for the training event for researchers
  in the arts and humanities.
---

# Information Capture and Creation

### Thinking about inputs <a href="#thinking-about-inputs" id="thinking-about-inputs"></a>

Think about the information you are accessing for your research, list everything that you are capturing (e.g. archival sources) and creating (e.g. transcribed and translated archival sources). Some of these might seem like the same thing. Don't worry about that for now. If you prefer, you could lay out this information visually, like so:

![](.gitbook/assets/capture\_creation.png)

A diagram showing the relationships between information captured and created.

Some of the information you have identified might be very specific, and some of it might be very general. For instance, the content of a 15th-century will is very specific because the researcher intends to analyse that content in some way. The thesis bibliography, however, is primarily for reference purposes, to evidence the sources the researcher has used.

### Information versus data <a href="#information-versus-data" id="information-versus-data"></a>

Research information, whether very specific or generic, is normally meaningful for the researcher and other people. The term 'data' is often seen as a synonym for information, but in the following exercises, we will try to think in terms of data and metadata (data about data). Data can be productively understood as units of information. These units might be very granular, or 'discrete' such as characters and numbers. In the humanities, we rarely devote time to thinking about these units of information, but in digital media, they are very important as they can take on linear, hierarchical and multi-relational structures (Schöch 2013).

### Unstructured and structured data <a href="#unstructured-and-structured-data" id="unstructured-and-structured-data"></a>

Thinking in terms of data allows researchers to better understand the information that they capture and create in the research process. One of the most important questions to ask is whether the data are unstructured or structured. The most obvious form of structured data would be a table of names, addresses and telephone numbers. Each column of the table contains a specific form of data that has certain conventions and properties. For example, a name is a string of characters, but a full name in that column might be formatted in a particular way; for instance, surname then a comma, then the first name. A telephone number is also likely to be a string, consisting of a country code, area code and then the specific line number or extension.

| Name        | Address                                                                                     | Telephone         |
| ----------- | ------------------------------------------------------------------------------------------- | ----------------- |
| Bloggs, Joe | Faculty of Arts and Humanities, University of East Anglia, Norwich, NR4 7TJ, United Kingdom | +44(0)1603 000000 |

Unstructured data can be more challenging to define, but in some ways it can be found in some of our most common forms of communication. E-mail messages, blog posts, an interview transcript or translation of a 15th-century will, are all forms of unstructured data. They may contain elements found in structured data (such as text strings), but they do not conform to data model: the conventions and properties that allow data to be categorised and analysed.

> Dear David,
>
> Thanks for the slides from yesterday's presentation. They were really helpful. I will let you know the dates for the upcoming teaching observations very soon.
>
> Best wishes,
>
> Elise
>
> Faculty of Arts and Humanities, University of East Anglia, Norwich, NR4 7TJ

The human brain is particularly good at making sense of unstructured data. Computers, however, are not. When data are used in applications, such as spreadsheets or even just the address book on your mobile phone, they are more useful when they are structured. This allows for effective data processing.

Think about your own research project and try to answer the following questions:

* Does the information you are capturing contain names, numbers or other features, such as a place name, that you need to collect and compare?
* If so, are there a lot of such pieces of information inside multiple documents?
* Do you intend to use bibliographic management software to create the bibliography for your thesis and/or the citations?

If you answered yes to any of the questions above, then you will be using structured data in some form.

### Exploring datasets <a href="#exploring-datasets" id="exploring-datasets"></a>

In these exercises, we will be using some data from the British Library. The first is a dataset that includes keylogging data from the author C. M. Taylor. You can learn more about this collection here: [https://data.bl.uk/cmtaylorkeylogging/](https://data.bl.uk/cmtaylorkeylogging/) and download the first part of the dataset from here: [https://data.bl.uk/cmtaylorkeylogging/](https://data.bl.uk/cmtaylorkeylogging/)​

Unzip the file and open the folder containing the key logs and open the first few files.

* What kind of data do these files contain?

### Structuring data <a href="#structuring-data" id="structuring-data"></a>

The first file in the top-level folder is a .txt file, and it contains a significant amount of standardised data. We can see dates, time codes, titles, keystrokes and the application on the author's computer that was running at that time.

```
Start               Title                                 Keystrokes Application
------------------- ------------------------------------- ---------- -----------
07/11/2014 16:09:17 Battery Meter                                 42 Explorer   
07/11/2014 16:07:47 Start                                          1 Explorer   
01/11/2014 13:26:20 Book Nine.odt - OpenOffice.org Writer      6,571 Soffice    
31/10/2014 07:46:09 Book Nine.odt - OpenOffice.org Writer     22,543 Soffice    
30/10/2014 13:00:13 Find & Replace                                31 Soffice    
30/10/2014 10:00:02 Book Nine.odt - OpenOffice.org Writer     22,447 Soffice    
29/10/2014 14:33:31 offcuts.odt - OpenOffice.org Writer           12 Soffice    
29/10/2014 11:43:23 Book Nine.odt - OpenOffice.org Writer     31,115 Soffice    
28/10/2014 14:57:40 offcuts.odt - OpenOffice.org Writer           65 Soffice    
28/10/2014 14:33:48 Book Nine.odt - OpenOffice.org Writer      4,737 Soffice    
28/10/2014 11:19:40 Find & Replace                                 4 Soffice    
28/10/2014 10:27:04 Book Nine.odt - OpenOffice.org Writer     20,684 Soffice    
28/10/2014 10:25:35 System Protection                             93 Systempr   
28/10/2014 10:25:09 Start menu                                    13 Explorer   
27/10/2014 12:35:36 offcuts.odt - OpenOffice.org Writer          167 Soffice    
27/10/2014 11:00:24 Find & Replace                                16 Soffice    
27/10/2014 09:35:40 Book Nine.odt - OpenOffice.org Writer     30,759 Soffice    
27/10/2014 09:35:18 Share Result                                   1 Snapdo     
25/10/2014 20:57:56 Book Nine.odt - OpenOffice.org Writer      2,691 Soffice    
24/10/2014 12:02:43 offcuts.odt - OpenOffice.org Writer            9 Soffice    
24/10/2014 11:57:08 Find & Replace                                 4 Soffice    
24/10/2014 11:47:07 Book Nine.odt - OpenOffice.org Writer     21,773 Soffice    
23/10/2014 10:17:30 Book Nine.odt - OpenOffice.org Writer      7,133 Soffice    
22/10/2014 10:10:34 Book Nine.odt - OpenOffice.org Writer      4,835 Soffice    
22/10/2014 10:10:14 Share Result                                   1 Snapdo     
17/10/2014 19:11:15 Task Information                               1 Manageme   
17/10/2014 18:46:22 System Protection                             51 Systempr   
17/10/2014 18:45:58 Start menu                                    14 Explorer   
17/10/2014 16:16:18 Find & Replace                                 8 Soffice    
17/10/2014 14:42:49 Book Nine.odt - OpenOffice.org Writer     21,493 Soffice    
17/10/2014 09:10:27 Book Nine.odt - OpenOffice.org Writer     18,426 Soffice    
```

This file is a good example of metadata, i.e. data about data, in this case, data that describes that 31 files of key log data.

The files themselves, however, are far less structured. Here is an example from the first file '1.rtf':

```
Keystrokes Typed

Application: Soffice
Start: 17/10/2014 09:10:27
Title: Book Nine.odt - OpenOffice.org Writer


 [Book Nine.odt - OpenOffice.org Writer]
<09:10>
she<RIGHT:7><DOWN><LEFT:36><RIGHT:14> She <RIGHT:36><UP><LEFT:24>the overground <RIGHT:3><DOWN><LEFT:60><DOWN><UP:2><LEFT:13><DOWN:3><RIGHT:63><UP:2><DOWN><UP:9><DOWN:6><RIGHT:25><DOWN:2><LEFT:24><DOWN><UP><RIGHT:49><LEFT:16><RIGHT:7>a small <RIGHT:8> in the hallway<RIGHT><DOWN><LEFT> <DOWN><RIGHT:58><DOWN><RIGHT:13> <DOWN><LEFT:58><DOWN><LEFT:3>nearly sixty<RIGHT:28><DOWN:4><UP><DOWN><LEFT><UP><LEFT:17>r tum<LEFT:18><DOWN><UP> <UP:15><DOWN:8><LEFT:51><RIGHT:4><DOWN:9><UP:2><RIGHT:8><DOWN><LEFT:53><DOWN><LEFT:23><DOWN:2><LEFT:32>.<DOWN><LEFT:13><DOWN:2><UP><LEFT:29><RIGHT:32> - <RIGHT><DOWN><LEFT:26><RIGHT:36><DOWN:4><UP><LEFT:34><RIGHT:74><DOWN><UP><RIGHT><DOWN><LEFT:20>
     <RIGHT:31><LEFT>
     <RIGHT:2><UP><RIGHT:65>
     <DOWN:3><UP:3><DOWN:3><RIGHT:37> always does<RIGHT:9><LEFT>event, every attitude a person held, really went <DELETE:13><RIGHT:54><DOWN><LEFT:9><RIGHT>change their whole<DOWN:4><UP:4><DOWN><UP><LEFT:51><UP><LEFT:11><RIGHT:2>fear, every anger, <RIGHT:114><LEFT:3> into the tendencies and the psycho-drama of the kin before you could even hope to feel the shape of it, let alone untie it.
     She knew that. That was her job. That was what Ems did. She got people adopted<RIGHT:2>
     <UP:2><DOWN:2><LEFT:3><RIGHT>She worked with families, she got kids fostered, got kids adopted, matched parents with kids and too kids off parents.<DOWN><UP:34><DOWN:17><UP:11><DOWN><RIGHT:3><LEFT><DOWN><LEFT:17>He were from home, Nick was, but she'd met him here in London. He were about the only bit of home she could take. <UP:2><DOWN><RIGHT:18>next village, <DOWN><LEFT:17>
     <DOWN><UP:8><DOWN:14><UP:8><LEFT:51><RIGHT>really <DOWN:28><UP:3><LEFT:48> <DOWN><LEFT:32><RIGHT:12><LEFT>t<UP><RIGHT:21>at<DOWN><UP:31><DOWN:5><LEFT:32><DOWN><LEFT:8><DOWN><UP><RIGHT:32><DOWN:29><UP:6><RIGHT:28><LEFT><RIGHT:26>o<RIGHT:2>s<RIGHT:8><LEFT:31>problem, every roadblock inside a person, every unhelpful <RIGHT:37><LEFT>trals<LEFT:3><RIGHT>i<DOWN><UP:4><DOWN:2><RIGHT:25><LEFT:3>tangle<RIGHT:74>e<RIGHT:64><LEFT:3>ad<DOWN><LEFT:58><DOWN:3><UP><RIGHT:3>; t<RIGHT:2>k<RIGHT:18><LEFT> too<DOWN><RIGHT:23>
     She knew that. It was her thing.<DOWN:6><UP:4><RIGHT:3>S<DOWN><LEFT>
<DOWN:15><UP:58><DOWN:35><RIGHT:2><DOWN><RIGHT:9><LEFT><RIGHT:17>s<DOWN><LEFT:17><RIGHT:4><LEFT:3><DOWN:4><UP:6><DOWN>He <UP><LEFT:42><DOWN><RIGHT:5>saw her. He smiled. <DOWN:2><RIGHT:53><DOWN><RIGHT:15><DOWN:2><LEFT:17><UP:2><DOWN>'<DOWN><RIGHT:14><UP><RIGHT:2><UP:4><DOWN:3><LEFT:33>oody<RIGHT:2><DOWN><LEFT:7><UP:4><RIGHT:19><LEFT><DOWN:2><LEFT:23><DOWN><RIGHT:63><LEFT:2><DOWN><LEFT:17>didn't take it personal. He were good like that. Nick <RIGHT:3><DOWN><RIGHT:2>
     <UP:3><DOWN>She could see that <DELETE>h<UP:49><DOWN:21><UP:3><RIGHT:28><LEFT:2>Maybe u<RIGHT><DOWN:34><UP:3><RIGHT:17>, <RIGHT:5>. He <DOWN><LEFT:25><DOWN><RIGHT:43><DOWN><LEFT:80> as <DOWN><LEFT:30><DOWN><LEFT> when she touched her tummy<DOWN:9><UP:61><DOWN:20><UP:23><DOWN:6><UP><DELETE:2><DOWN:3><DELETE>
<DOWN:56><UP:18><DOWN><UP:51><DOWN:33><UP:26><DOWN:13><UP:4><RIGHT:5>realy <LEFT:2>l<DOWN:29><UP:2><LEFT:27> - <RIGHT><DOWN:14><UP:3><LEFT:10><RIGHT>T<RIGHT:17><LEFT:4>ed<RIGHT:8><LEFT> behind Nicks. Ems<RIGHT:2> <LEFT:4>Litte <LEFT:2>l<DOWN><UP><LEFT:7><DOWN><LEFT:32>ed<LEFT:23><DOWN><LEFT:27><DOWN><LEFT>belly<RIGHT><DOWN><LEFT:31><RIGHT:2><LEFT:3><DOWN><UP:57><DOWN:26><UP:9><DOWN><RIGHT:38><LEFT>; he hadn't heard her<RIGHT:37>
     <DOWN:2><LEFT:2> be <RIGHT:61><DOWN><LEFT:59>d sit<RIGHT:52><LEFT:9>at <RIGHT:3><DOWN:4><LEFT:26>jammed her knees either side of the bowl <LEFT:27><RIGHT:3>on the floor <RIGHT:57><LEFT:4>toilet <RIGHT:6>w<DOWN><UP><DOWN><UP><DOWN><LEFT:25><DOWN:19><UP:45><DOWN:71><UP:29><DOWN:46><UP:22><DOWN:5><UP:67><DOWN:35><CTRL+S>
<09:51>
<10:07>
<CTRL+S><DOWN><LEFT:14><RIGHT:4> <RIGHT:34><LEFT:10><RIGHT:81><DOWN:6><CTRL+S>
<10:09>
<10:22>
 <UP:44><DOWN:19>working <LEFT:22>. He were oblivious,<RIGHT:56><DOWN:17><UP:11><DOWN:23><UP:9><LEFT:12>'d never <DOWN:5><UP:2><DOWN><RIGHT:14>go <DELETE:17>way <RIGHT:7><LEFT:2><DELETE:29><RIGHT:22><UP><RIGHT:9><DOWN><LEFT:62><DOWN><LEFT:2><RIGHT:4> <RIGHT:18>I<RIGHT:5>ere<DOWN><RIGHT:19><DOWN:3><RIGHT:24><LEFT:37><DOWN:8><LEFT:10>
     <DOWN:2><RIGHT>self<RIGHT>, and like her belly were smiling back at her hands.
     <DOWN><UP:52><DOWN:23><UP:27><DOWN:26><UP:8><RIGHT:2>He shushed her, wagged a palm at her to be quiet. <UP><RIGHT:11><LEFT:7><RIGHT:16><LEFT:2>didn't look up. He <RIGHT><DOWN><LEFT:36><DOWN><LEFT:17><DOWN><RIGHT:43><LEFT:2>just about <DOWN:3><UP><RIGHT:11><LEFT:4><RIGHT:12>S<RIGHT:17>go and cuddle Nick <DELETE:10><DOWN><LEFT:40><RIGHT:2>the <RIGHT:34>tiles <DELETE:6><DOWN><LEFT:13><RIGHT:13><LEFT>'d been <DOWN:13><LEFT:45><RIGHT:2>t<RIGHT:7> <RIGHT:50><DOWN:2><UP><RIGHT:2><DOWN:4><UP:4><RIGHT:6>Ems <UP:27><DOWN:18><UP:16><LEFT:39><RIGHT>s<DOWN><UP><DOWN:23><UP><DOWN:3><RIGHT:39><LEFT:2><RIGHT><DOWN:6><UP:4><DOWN><LEFT:12><RIGHT>ere<DOWN:7><UP:4><LEFT:10><RIGHT:11><DOWN:6><UP><LEFT:38><RIGHT:2><DOWN><LEFT:11><DOWN:6><UP:4><LEFT:22><RIGHT:70>by<DOWN><LEFT:30><DOWN><LEFT:46>; <DOWN:2><LEFT:61><RIGHT:20> <RIGHT:3>Nick would <DELETE:5><LEFT:15><RIGHT>out <UP:53><DOWN:17><UP:2><DOWN:27><UP:18><DOWN><UP:11><DOWN:5><LEFT:33><RIGHT><LEFT:22><RIGHT:2>With Nick turning forty, ten years older than her. and especially not now they had Lukey. <RIGHT:56>, p<DOWN><LEFT:43><UP><RIGHT:41><LEFT>. P<UP><RIGHT:17><LEFT>, w<RIGHT:48><UP:15><DOWN:19><UP:4><RIGHT:3>, and not now <DELETE:3> <DOWN><RIGHT:51><UP:4><DOWN><LEFT:20><DOWN:2><LEFT:28><DOWN:2><UP:20><DOWN:22><UP:3><LEFT:20><RIGHT:2>the <DOWN:4><CTRL+S><DOWN:5><UP:6><DOWN><LEFT:9><RIGHT><DOWN:18><UP:4><LEFT:11><RIGHT> <RIGHT:19><DOWN><UP:34><DOWN:24><UP:9><LEFT:16><DOWN><UP><RIGHT:4>kid<DOWN:2><RIGHT:6><LEFT>Em <DOWN><RIGHT:28>down <RIGHT:2>to<DOWN:2><CTRL+S><DOWN><UP:27><DOWN:30><UP:11><DOWN:3><LEFT:6>She weren't having<DOWN:2><UP><DOWN> So it were good he were working.<UP:13><DOWN:14><UP:7><DOWN:2><UP:5><DOWN:47><UP:55><DOWN:11><CTRL+S><DOWN:3><UP:5><DOWN:17><UP:15><DOWN:9><UP:9><DOWN:39><UP:9><DOWN:2><UP:40><DOWN:21><UP:8><DOWN:2><RIGHT>stepped forward <DOWN:2><UP:2><RIGHT:12><UP:13><DOWN:19><UP:9><DOWN:3><LEFT:20>towards the kitchenette <DELETE:30><DOWN><LEFT:19><RIGHT><DOWN:12><UP:32><DOWN:39><UP><LEFT:35><RIGHT><LEFT:16><DOWN:3><UP><DOWN:2><UP:3><RIGHT:10><LEFT:4>Em <DOWN:12><UP:53><DOWN:23><UP:2><LEFT:3>Right, a cuppa. <RIGHT:14><DOWN:7><UP:2><DOWN:37><UP:63><DOWN:14><UP:8><DOWN><DELETE><DOWN:55><UP:65><DOWN:12><UP:5>
<DOWN:24><UP:9><RIGHT:3><LEFT>She were gasping for a coffee. <RIGHT:14><DOWN><UP><DOWN:3><UP:3><DOWN:44><UP><DOWN><UP:64><DOWN:21><UP:8><DOWN:7>brew<DOWN:13><UP:3><DOWN><UP><LEFT:6><RIGHT:24> <DOWN:10><UP:7><DOWN:6><UP:41><DOWN:29><UP:6><DOWN:45><UP:68><DOWN:64><UP:19><CTRL+S>
<11:12>
<11:36>
<CTRL+S><UP:43><DOWN:52><UP:8><DOWN:2><LEFT:9><DOWN><UP><LEFT:9><DOWN><UP><RIGHT:40><LEFT:2><RIGHT:21>, he said. '<RIGHT:2><LEFT:13><RIGHT>'<DOWN><RIGHT:107><LEFT:2><DOWN><LEFT>him<RIGHT:3>Suddenly she was alone. Except she wasn't. <DOWN><UP><RIGHT:28><LEFT>ahead barely seeing <DELETE:14><DOWN><UP><LEFT:20><RIGHT:6>ing, <RIGHT:18>a<DOWN><LEFT:19><DOWN><LEFT:40>flet <LEFT:3><RIGHT>l<DOWN><UP:51><DOWN:15><UP:14><DOWN:29><UP:9><DOWN:2><UP><LEFT:11><RIGHT><DOWN:24><UP><LEFT:2> She couldn't.<DOWN:6><UP:5><DOWN:6><UP:3><LEFT:33><DOWN><LEFT:61><DOWN><LEFT:76><DOWN><RIGHT:4> tum<RIGHT:21>tum<DOWN:2><UP><DOWN:8><UP:57><DOWN:6><CTRL+S><DOWN:10><UP:6><LEFT>,<RIGHT> she said.<CTRL+S><CTRL+S><CTRL+S><DOWN:4><LEFT:18><RIGHT>her <RIGHT>e<RIGHT:13><CTRL+S><DOWN:44><UP:61><DOWN:21><UP:7><RIGHT:58><DOWN><LEFT:13><DOWN:25><UP:3><LEFT:6><RIGHT:13> <DOWN:2><UP><DOWN:8><UP:3><DOWN><LEFT:32>, c<DOWN><RIGHT:70>.<DOWN><LEFT:46>O<DOWN><RIGHT:31><DOWN:6><UP:57><DOWN:60><UP:55><DOWN:70><CTRL+S>
<11:55>
<12:02>
<CTRL+S><DOWN:32><UP:42><DOWN:22><UP:11><DOWN:139><UP:209><DOWN:61><UP:63><DOWN:21><UP:7><RIGHT:42><DOWN:3><CTRL+S>
<12:04>
<12:14>
<DOWN:14><UP:9><DOWN:41><UP:61><DOWN:9><UP:4><DOWN><RIGHT:19><DOWN><LEFT:32><DOWN><LEFT:12><DOWN:53><UP:63><DOWN:63><UP><DOWN:15><UP:6><RIGHT:5><DOWN:12><UP:5><RIGHT:46><LEFT> either<DOWN><LEFT:30><DOWN><LEFT:18><DOWN:10><RIGHT:15><DOWN><LEFT:14><DOWN><LEFT:49><RIGHT> of England<RIGHT:57><LEFT>. And now look at her, <RIGHT:42><LEFT:45><RIGHT:3>sun-blissed. G<RIGHT:2><LEFT><UP:7><DOWN:4><RIGHT:8><LEFT:8><RIGHT>the<DOWN><RIGHT:32><DOWN><LEFT:11><DOWN><LEFT:21><RIGHT> - g<DOWN:3><UP:3><RIGHT:41>north <DELETE:6><DOWN:8><CTRL+S><UP:44><DOWN:51><UP:35><DOWN:16><UP:8><LEFT:11>the <DOWN:4><UP:20><DOWN:28><UP><LEFT:40><RIGHT:4><DOWN><RIGHT:44><DOWN:3><UP:2><RIGHT:2>He winked at |Laney but she didn't respond.
     <UP><RIGHT:14><DOWN:7><UP:6><DOWN:2><RIGHT:5>the <DOWN:15><RIGHT:35><LEFT:23><RIGHT>eful <DELETE:17>for <CTRL+S><DOWN:27><UP:5><DOWN:11><UP:6><LEFT:21>the <DOWN:64><UP:4><RIGHT:47><LEFT:2><RIGHT><DOWN><LEFT:14><DOWN:24><UP:5><RIGHT:32><DOWN><LEFT:31><DOWN:74><UP:95><DOWN:120><UP:87>
<12:32>
<12:39>
<DOWN:64><UP:189><DOWN:4><UP:114><DOWN:59><UP:54><DOWN:208><UP:6><DOWN:113><UP:4><DOWN:7><UP:7><CTRL+S><DOWN:93><UP:27><DOWN:6><RIGHT:10><LEFT:8><RIGHT>Tony were on the booze and <DOWN><LEFT:29><RIGHT:5><CTRL+S><DOWN:6><UP:123><DOWN:49><UP:10>
<12:44>
<13:00>
 <CTRL+S><CTRL+S>
<13:00>

```

A simple way of demonstrating how structured data can be processed more effectively is to import it into a spreadsheet application, such as Microsoft Excel.

Open a new file in Excel, then select File > Import > Text file. Select the document 'CTC1 spector report 1n 20141107.txt' and then select the 'Fixed width' import option. Preview the column locations and select 'Next', then choose to keep the column data format as 'General'. Finally, select 'Finish'.

Your imported data should resemble this format:

| Start           | ​               | Title           | Keystrokes      | Application     |
| --------------- | --------------- | --------------- | --------------- | --------------- |
| --------------- | --------------- | --------------- | --------------- | --------------- |
| 07/11/2014      | 16:09:17        | Battery meter   | 42              | Explorer        |
| ...             | ​               | ​               | ​               | ​               |

With this tabulated data, it is very easy to generate statistics, such as the number of different keystrokes in each document, such as 'DELETE', or the number of occurrences of certain words in that part of the manuscript. If we wanted to drill down into the unstructured data (the .rtf files), then we would need to find a way of structuring the data so that it would be extracted and meaningfully tabulated. This could be down manually, but over large numbers of files, this would be very time-consuming.

## Big data and smart data

Schöch (2013) argues that there are two general types of data, which depends on the intersection of two general characteristics: structure and size. Generally unstructured data, which voluminous, would be 'big data'. Smart data is generally more structured and smaller. This latter type is probably more common within the humanities. Scholarly digital editions are a good example of this. For example, the Catalogue of Digital Editions: [https://dig-ed-cat.acdh.oeaw.ac.at/](https://dig-ed-cat.acdh.oeaw.ac.at) provides a helpful repository of details of projects that have used more structured approaches to data, which includes [XML](https://www.w3schools.com/xml/xml\_whatis.asp) (Extensible Markup Language) and [TEI](https://tei-c.org/guidelines/) (the Text Encoding Inititiave).

Although the example of the key logging data above may not seem structured, it is possible to identify features of a structure, such as the time stamps and the recurring keystrokes, which are placed in angle brackets: '<' and '>'. With the appropriate interpretive [schema](https://www.w3schools.com/xml/schema\_intro.asp), which describes the structure of a document, it would resemble Schöch's definition of 'smart data'.

## Understanding 'messy' data

Structure is one aspect of data, but even structured data can have problems. Data can easily be inconsistent or incomplete. Such errors can be introduced by humans (input errors) or sometimes through automation, such as OCR (optical character recognition), which constitute processing errors.

Can you spot the differences in this table of publications held in different libraries?

| Name        | Publication Location | Publisher                  | Library                          |
| ----------- | -------------------- | -------------------------- | -------------------------------- |
| Bloggs, Joe | Princeton, NJ        | Princeton University Press | British Library                  |
| Bloggs, J.  | Princeton, NJ        | Princeton University Press | Cambridge University Library     |
| Bloggs,Joe  | Princeton, NJ        | Princeton University Press | Durham University Library        |
| Bloggs,J    | Princeton, NJ        | Princeton University Press | Institute of Historical Research |

Consistency in data allows for more accurate analysis, and is inevitably more useful for future researchers. Incomplete data are also problematic, particularly when analysed computationally, and it may be difficult to know whether or not the data were in fact not available, or were simply omitted by mistake or through choice.

Data scientists often refer to 'messy' or 'dirty' data, which may be a combination of a lack of structure and inconsistency or incompleteness. Fortunately, there are tools available to assist with this process, such as [Open Refine](https://openrefine.org).

This concludes the first section of the workbook. The next section will be completed in the workshop.
