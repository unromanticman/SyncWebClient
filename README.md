# SyncWebClient
A WebClient , It can request GET method and don't need runnable and Thread.

### Support
Stable:AndroidSdkVersion >= 19
### Install 
1.download two jar
<li>
<ul>jsoup.jar </ul>
<ul>SyncWebClient.jar  </ul>
</li>
2.put jsoup.jar、SyncWebClient.jar into app libs folder
<pre>/app/libs</pre>

### Useage
<pre>
 SyncWebClient client = new SyncWebClient(getActivity());
 String rs = client.get(<b>"http://www.google.com.tw"</b>);
</pre>
