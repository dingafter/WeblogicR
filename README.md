	软件作者：Tide_RabbitMask
	感谢来自网络的开源POC，
	我只是进行了魔改和接口统一。
    免责声明：Pia!(ｏ ‵-′)ノ”(ノ﹏<。)
    本工具仅用于安全测试，请勿用于非法使用，要乖哦~
        
    V 1.0功能介绍：
    提供一键poc检测，收录几乎全部weblogic历史漏洞。
    详情如下：
        #控制台路径泄露
        managerURL200  
        
        #SSRF：
        uddi-ssrf       
        
        #JAVA反序列化：
        CVE-2015-4852  
        CVE-2016-0638  
        CVE-2016-3510   
        CVE-2017-3248   
        CVE-2018-2628 
        CVE-2018-2893   
        
        #任意文件上传
        CVE-2018-2894   
        
        #XMLDecoder反序列化：
        CVE-2017-10271 
        CVE-2017-3506
	
	其中两个exp功能完美，不忍魔改，
	暂且请手动进行测试。
	后期版本会单独补上这两个poc。
	
    
    V1.*功能预告：
        多进程并发
        修复建议
        模块优化
        交互优化 
        报告生成
		
    软件使用Demo：	
    =========================================================================
    __        __   _     _             _                    
    \ \      / /__| |__ | | ___   __ _(_) ___     _     _   
     \ \ /\ / / _ \ '_ \| |/ _ \ / _` | |/ __|  _| |_ _| |_ 
      \ V  V /  __/ |_) | | (_) | (_| | | (__  |_   _ _   _|
       \_/\_/ \___|_.__/|_|\___/ \__, |_|\___|   |_|   |_|  
                                 |___/    
                                 
                                 By Tide_RabbitMask | V 1.0 
    
    Welcome To Weblogic++ !!
    
        1、开启POC检测
        2、开启EXP利用
        3、关于本软件
    
    1
    Please enter the IP：127.0.0.1
    Please enter the port：7001
    [*]开始控制台路径检测
    [+]目标weblogic控制台地址暴露!
    [+]路径为:http://127.0.0.1:7001/console/login/LoginForm.jsp
    [+]请自行尝试弱口令爆破!
    [*]开始SSRF检测
    [+]目标weblogic存在UDDI组件!
    [+]路径为:http://127.0.0.1:7001/uddiexplorer/
    [+]请自行验证SSRF漏洞!
    [*]开始CVE_2015_4852检测
    [*]测试返回内容为:10.3.6.0.false
    AS:2048
    HL:19
    [*]开始CVE_2016_0638检测
    [+]目标weblogic存在JAVA反序列化漏洞：CVE-2016-0638
    [*]开始CVE_2016_3510检测
    [-]目标weblogic未检测到CVE-2016-3510
    [*]开始CVE_2017_3248检测
    [-]目标weblogic未检测到CVE-2017-3248
    [*]开始CVE_2017_3506检测
    [+]目标weblogic存在JAVA反序列化漏洞：CVE-2017-3506
    [*]开始CVE_2018_2628检测
    [+]目标weblogic存在JAVA反序列化漏洞：CVE-2018-2628
    [*]开始CVE_2018_2893检测
    [+]目标weblogic存在JAVA反序列化漏洞：CVE-2018-2893
    [*]本次检测任务结束，目标 127.0.0.1:7001
    
    =========================================================================
