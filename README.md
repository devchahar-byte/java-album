# jAlbum


This is a local photo management system written with the Java language. Using B/S architecture. The server uses Servlet
to provide RESTful style interface and dynamic page for direct access to the web browser, integrated photos Exif
information processing, video stream information processing and face recognition technology, integrated local and Amazon
S3 cloud storage synchronous backup function. Service provides a background task scans the specified directory, and
collect the specified suffix photos, then generate a photo gallery. HASH fingerprint is used to recognize the duplicate
pic fils. The shooting time in Exif is used to sort all the files. By identifying the picture's aspect ratio, set the
appropriate display size on a Web page. Eventually in time axis to generate a year, month, and day dimensions page.
HomePage of jAlbum：

