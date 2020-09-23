<div align="center">

## VB6 Native HTTP/FTP Async Multiple Download


</div>

### Description

Downloads any URL to a byte array/string in async mode without using any API's or external components. VB6 NATIVE CODE.

I only needed MS Common Controls to add the listview for demonstration, but the control itself doesn't require it at all.

You can add more than one URL at the same time for download. - Accepts both HTTP and FTP url's.
 
### More Info
 
DownloadURL as string

ByteArray of the retrieved data

2 events (progress/complete)

Isn't affected by the IE 'Offline mode' like MSINET.OCX is. Uses any proxy configured in IE automatically, etc.


<span>             |<span>
---                |---
**Submitted On**   |2006-03-22 09:10:02
**By**             |[Filipe Lage](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/filipe-lage.md)
**Level**          |Intermediate
**User Rating**    |5.0 (30 globes from 6 users)
**Compatibility**  |VB 6\.0
**Category**       |[Internet/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-html__1-34.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[VB6\_Native1982023222006\.zip](https://github.com/Planet-Source-Code/filipe-lage-vb6-native-http-ftp-async-multiple-download__1-64750/archive/master.zip)

### API Declarations

```
' This component doesn't require any external calls/apis/references
' Obtains an url to a byte array using native VB6 calls
' Asyncronous - no need to wait for data to arrive
' Multiple downloads are accepted at the same time (different URL's, etc)
' If you like this code, please VOTE for it
' You may use this code freely in your projects, but whenever possible,
' include my name 'Filipe Lage' on the 'Help-&gt;About' or something ;)
' Cheers :)
'
' Filipe Lage
' fclage@ezlinkng.com
'
```





