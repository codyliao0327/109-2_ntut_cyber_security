班級：資財二乙  
學號：108AB0744  
姓名：廖劭其  

# 分析探討Proxy Logon
#### 事件流程
> 2020.12 台灣資安業者 DEVCORE 發現漏洞  
> 2021.0105 DEVCORE 通報微軟  
> 2021.0106 微軟證實漏洞  
> 2021.0302 微軟發布公告及修補程式  

#### 事件嚴重性
此漏洞是發生在Exchange Server上，然而Exchange Server的普及率很高，所以才會導致在公告漏洞後短短三天內就有數萬台伺服器受到攻擊。

#### 漏洞攻擊者
原先只有中國駭客組織Hafnium針對漏洞進行攻擊，待微軟公告漏洞後，ESET研究人員表示，至少超過10個APT駭客組織發動攻擊，這些駭客組織包括LuckyMouse、Tick，以及Winnti Group等等。

#### 漏洞修補後
1. 為防止駭客成功留下攻擊管道以便日後有所行動，微軟建議修補完Exchange Server漏洞的企業，還是得調查是否有其他駭入跡象，也得變更所有用戶帳號和本地管理員帳號密碼。
2. 微軟不斷釋出更多補救措施，包括涵蓋面更廣的第二波Exchange Server更新，以及一鍵式工具EOMT（Exchange On-premise Migration Tool）和更新Microsoft Defender Antivirus特徵檔。
