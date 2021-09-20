# ConsoleWrite
Encode a string  ConsoleWrite( B64Encode('Hello World') &amp; @CRLF ) Encode a UTF-8 string:  ConsoleWrite( B64Encode('British people do not use the € (euro)', 1) &amp; @CRLF ) Decode a string:  $EncodedData = 'SSB0b3RhbGx5IGxvdmUgYXV0b2l0IGd1eXMuLi4=' ConsoleWrite( B64Decode($EncodedData) &amp; @CRLF)
