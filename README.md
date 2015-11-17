Stability patches for [wsdlpull project](http://wsdlpull.sourceforge.net).

````
$ links 'http://sourceforge.net/projects/wsdlpull/files/wsdlpull/wsdlpull%201.24/wsdlpull-1.24.tar.gz/download'
$ tar zxvf wsdlpull-1.24.tar.gz
$ cd wsdlpull-1.24
$ patch -p0 < Soap.diff 
$ patch -p0 < WsdlInvoker.diff 
$ patch -p0 < WsdlPull_Handle_RelativePathInImport.patch
$ patch -p0 < WsdlPull_ExternalUriFetcher_Support.patch
````
