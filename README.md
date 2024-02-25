## Regular Expression Resources
#### The best ressources to learn and practice Regular Expressions :
- Web site 1 : https://regexlearn.com/learn 
- Web site 2 : https://regexr.com/
- Web site 1 : https://regex101.com/ 
- Web site 2 : https://www.regextester.com
#### Extract properties from log file
 - The Regular Expression used to extract application propertie from the event : <b>source-address="(.*?)" </b> <br/><br/>
13:33.758 AAA0000-0 RT_FLOW - APPTRACK_SESSION_CLOSE [sampleuser@1111.1.1.1.1.11 reason="unset" source-address="<b>192.0.2.0</b>" source-port="10" destination-address="192.0.2.255" destination-port="10" service-name="sample-service" application="sample-application" nested-application="None" nat-source-address="192.0.2.0" nat-source-port="10" nat-destination-address="192.0.2.255" nat-destination-port="10" src-nat-rule-name="None" dst-nat-rule-name
File Hash fileHash=34649ca8ec993aac953ba61d4c1a5420
<br/><br/>
- The Regular Expression used to extract File Hash propertie from the event : <b>fileHash=(\w+)</b><br/><br/>
LEEF:1.0|FireEye|CMS|7.5.0.258966|malware-object|osinfo=Microsoft WindowsXP 32-bit 5.1 sp3 14.0528^sev=4^sname=Malware.Binary.pdf;Malware.Binary.Pdf^proto=tcp^fileHash=<b>34649ca8ec993aac953ba61d4c1a5420</b>^filePath=/analysis/doubleb/english/pdf_9996936^vlan=0^dvchost=fmps^dvc=172.17.15.10^action=notified^cncHost=clickhos.bz.cm^externalId=3^devTime=Aug 04 2014 21:49:48 UTC^cncPort=80^link="https://axhcms.eng.fireeye.com/fmps/fanalysis?ma_id\=3^anomaly=misc-anomaly^cncChannel=GET /kntrn334e/load.php?e\=5&amp;amp;o\=5&amp;amp;b\=5&amp;amp;id\=7deee6c92a39c5d3cb7f51629d9ca87f&amp;amp
<br/><br/>

For more examples consult this link https://ibm.ent.box.com/s/ich0yyiw54y0ek6s9a66xvtjku8e42rc/file/732613622781
