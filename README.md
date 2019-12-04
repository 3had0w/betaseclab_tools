# betaseclab_weblogic
贝塔安全实验室成员针对常见的中间件漏洞、web框架，应用漏洞等安全问题进行了总结，并汇总了一些poc与exp脚本工具，其目的是为方便网络安全人员进行安全测试，切记不做违法犯罪之事，否则一切后果后果自行承担。

[fVistaST]:  http://stascorp.com/images/rdpwrap/VistaST.png
[fVistaHB]:  http://stascorp.com/images/rdpwrap/VistaHB.png
[fWin7ST]:   http://stascorp.com/images/rdpwrap/Win7ST.png
[fWin7HB]:   http://stascorp.com/images/rdpwrap/Win7HB.png
[fWin8DP]:   http://stascorp.com/images/rdpwrap/Win8DP.png
[fWin8CP]:   http://stascorp.com/images/rdpwrap/Win8CP.png
[fWin8RP]:   http://stascorp.com/images/rdpwrap/Win8RP.png
[fWin8]:     http://stascorp.com/images/rdpwrap/Win8.png
[fWin81P]:   http://stascorp.com/images/rdpwrap/Win81P.png
[fWin81]:    http://stascorp.com/images/rdpwrap/Win81.png
[fWin10TP]:  http://stascorp.com/images/rdpwrap/Win10TP.png
[fWin10PTP]: http://stascorp.com/images/rdpwrap/Win10PTP.png
[fWin10]:    http://stascorp.com/images/rdpwrap/Win10.png

| NT Version    | Screenshots |
| ------------- | ----------- |
| Windows Vista | [![Windows Vista Starter][pVistaST]][fVistaST] [![Windows Vista Home Basic][pVistaHB]][fVistaHB] |
| Windows 7     | [![Windows 7 Starter][pWin7ST]][fWin7ST] [![Windows 7 Home Basic][pWin7HB]][fWin7HB] |
| Windows 8     | [![Windows 8 Developer Preview][pWin8DP]][fWin8DP] [![Windows 8 Consumer Preview][pWin8CP]][fWin8CP] [![Windows 8 Release Preview][pWin8RP]][fWin8RP] [![Windows 8][pWin8]][fWin8] |
| Windows 8.1   | [![Windows 8.1 Preview][pWin81P]][fWin81P] [![Windows 8.1][pWin81]][fWin81] |
| Windows 10    | [![Windows 10 Technical Preview][pWin10TP]][fWin10TP] [![Windows 10 Pro Technical Preview][pWin10PTP]][fWin10PTP] [![Windows 10][pWin10]][fWin10] |

CVE编号	                   漏洞类型	                     影响版本号	                工具来源

CVE-2014-4210	      SSRF(服务端请求伪造攻击)	        10.0.2.0, 10.3.6.0	

CVE-2015-4852	     JAVA反序列化	          12.2.1.0，12.1.3.0，12.1.2.0， 10.3.6.0 https://github.com/koutto/jok3r-pocs

CVE-2016-0638	     JAVA反序列化	          12.2.1.0，12.1.3.0，12.1.2 0 ,  10.3.6 0	

CVE-2016-3510	     JAVA反序列化	          10.3.6.0, 12.1.3.0, 12.2.1.0	          https://github.com/koutto/jok3r-pocs

CVE-2017-3428	     JAVA反序列化	          10.3.6.0, 12.1.3.0,12.2.1.0, 12.2.1.1	  http://www.0-sec.org/download/CVE-2017-3248.rar

CVE-2017-3506	     XMLDecoder反序列化	    10.3.6.0, 12.1.3.0, 12.2.1*            	https://github.com/ianxtianxt/CVE-2017-3506

CVE-2017-10271	   XMLDecoder反序列化	    10.3.6.0, 12.1.3.0, 12.2.1.*            https://github.com/RealBearcat/

CVE-2018-2628	     JAVA反序列化	          10.3.6.0，12.1.3.0，12.2.1.2	          https://github.com/jas502n/CVE-2018-2628

CVE-2018-2893	     JAVA反序列化	          10.3.6.0，12.1.3.0，12.2.1.2，12.2.1.3	 https://github.com/qianl0ng/CVE-2018-2893

CVE-2018-2894	     任意文件上传	          10.3.6.0，12.1.3.0，12.2.1.2，12.2.1.3	  https://github.com/jas502n/CVE-2018-2894

CVE-2018-3245	     JAVA反序列化	          10.3.6.0， 12.1.3.0， 12.2.1.3	         https://github.com/pyn3rd/CVE-2018-3245

CVE-2018-3191	     JAVA反序列化	          10.3.6.0、12.2.1.0、12.1.3.0、12.2.1.1、12.2.1.3	http://0-sec.org/download/CVE-2018-3191.zip

CVE-2018-3252	     JAVA反序列化	          10.3.6.0, 12.1.3.0, 12.2.1.3	

CVE-2019-2615	     WebLogic任意文件读取 	10.3.6.0 ，12.1.3.0 ，12.2.1.3	         https://github.com/chiaifan/CVE-2019-2615

CVE-2019-2618	     任意文件上传	          10.3.6.0、12.1.3.0、12.2.1.3	           https://github.com/jas502n/cve-2019-2618

CVE-2019-2725	     JAVA反序列化	          10.* 、12.1.3	                          https://github.com/ianxtianxt/CVE-2019-2725

CVE-2019-2729	     JAVA反序列化	          10.3.6.0.0，12.1.3.0.0，12.2.1.3.0	     https://github.com/black-mirror/Weblogic

CNVD-C-2019-48814	 JAVA反序列化	          10.3.6.0，12.1.3.0，12.2.1.2，12.2.1.3	  https://github.com/bigsizeme/CNVD-C-2019-48814

weblogic-admin	   weblogic后台和常用弱口令		                                     https://github.com/rabbitmask/WeblogicWeakPwd

