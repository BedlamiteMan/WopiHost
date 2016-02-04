### Introduction

This repository contains a Wopi Host demo.
With Cobalt(FSSHTTPB/D) support for Office Web Apps. 
Support DOCX Editing, and also PPTX,XLSX.
Welcome any contribution, and discussion of supporting coauthoring

### Requirements

Requires Microsoft.CobaltCore.dll assembly from Office Web Apps server.  
**Compatible with Office Web Apps 2013**

### Known Issues

Doesn't support coauthoring.

### Usage & Examples

http://[owas.domain]/we/wordeditorframe.aspx?WOPISrc=http%3a%2f%2flocalhost%3a8080%2fwopi%2ffiles%2fword.docx&access_token=[token]&ui=zh-CN
http://[owas.domain]/p/PowerPointFrame.aspx?WOPISrc=http%3a%2f%2flocalhost%3a8080%2fwopi%2ffiles%2fppt.pptx&access_token=[token]&ui=zh-CN
http://[owas.domain]/x/_layouts/xlviewerinternal.aspx?WOPISrc=http%3a%2f%2flocalhost%3a8080%2fwopi%2ffiles%2fBook1.xlsx&access_token=[token]&ui=zh-CN
