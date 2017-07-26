# SyncWebClient
A WebClient , It can request GET method and don't need runnable and Thread.

## Support
Stable:AndroidSdkVersion >= 19
## Install 
1.download two jar
<ul><li>jsoup.jar</li><li>SyncWebClient.jar</li>
</ul>
2.put jsoup.jar、SyncWebClient.jar into app libs folder  
<pre>/app/libs</pre>  

## Usage 
<pre>
 SyncWebClient client = new SyncWebClient(getActivity());
 String rs = client.get(<b>"http://www.google.com.tw"</b>);
</pre>
## Screenshot
<img width="750" src="https://github.com/unromanticman/SyncWebClient/blob/master/screenshot.png?raw=true">  

## License  
SyncWebClient is licensed under The MIT License (MIT).
