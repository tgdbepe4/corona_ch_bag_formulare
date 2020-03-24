# COVID19 registration forms for PC processing

Many medical doctors mentioned on Twitter that they have to manually process the registration of new CODVI19 cases with the Federal Office for Health, BAG on a printed PDF form. This takes time and sending by email is complicated because the completed sheet needs to be scanned before sending. And FAX is really very old-fashioned!

Some noted that they would suggest and help establish an electronic solution. But that also takes time and needs training in how to use it.

This gave me the idea of ​​expanding the PDF files with form fields. These new files can then now be filled in on the PC und sending via e-mail.

## Download from similar project (use this now for download!)

There is another very similar activity, https://github.com/lakay/COVID-19_PDF-Reporting and a download page is available. I copy it from there to make access to the files easier. 

https://github.com/lakay/COVID-19_PDF-Reporting/wiki/Download-Meldeformulare-f%C3%BCr-Covid-19

## Download from this project

Non IT persons don't like download files from here. For this reason there is an other way to get the PDF documents. Use this link for download, https://www.mycloud.ch/s/S005BE60DADA8A0461682D10365FD646D6A4C25C3AC.

## Feedback
Any comments, corrections and recommendations can be addressed to mailto:corona@bergi-it-consulting.ch.

## XML files for import and export

### Required: Adobe Acrobat software and maybe MS Access

With Adobe Acrobat you can easily edit the forms and import and export data to the form. Best way is over an XML-File. There is an XML file at the repository which can be edited and use it to add data to the form.

MS Access allows very easy to import such an XML-File into a DB (data base). The only thing to have to take care is initially re declare the fields with bigger content, for example remark fields as "Langer Text" instead of "Short Text".

And adding the following PDF data import to the same table.

A report of a feasibility study can you find over the link here, https://github.com/tgdbepe4/corona_ch_bag_formulare/blob/master/tests/Machbarkeit%20BAG%20Meldeformulare%20mit%20digialen%20Formularfeldern.pdf.

## Comments welcomed

Please comments and make recommendations with open an issue (you can find it on the top) here.

