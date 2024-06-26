---
layout: post
title: "List of ETW Providers on Windows Server 2016"
description: "Full list of ETW Providers on Windows"
comments: true
keywords: "etw, event tracing for windows, eventlog, powershell, windows, windows server"
---

To query, run this command:

```powershell
c:\Windows\System32\logman.exe query providers
```
If you want a list of ETW providers, run `start-transcript` in Powershell.

```powershell
Provider                                 GUID
-------------------------------------------------------------------------------
.NET Common Language Runtime             {E13C0D23-CCBC-4E12-931B-D9CC2EEE27E4}
ACPI Driver Trace Provider               {DAB01D4D-2D48-477D-B1C3-DAAD0CE6F06B}
Active Directory Domain Services: SAM    {8E598056-8993-11D2-819E-0000F875A064}
Active Directory: Kerberos Client        {BBA3ADD2-C229-4CDB-AE2B-57EB6966B0C4}
Active Directory: NetLogon               {F33959B4-DBEC-11D2-895B-00C04F79AB69}
ADODB.1                                  {04C8A86F-3369-12F8-4769-24E484A9E725}
ADOMD.1                                  {7EA56435-3F2F-3F63-A829-F0B35B5CAD41}
Application Popup                        {47BFA2B7-BD54-4FAC-B70B-29021084CA8F}
Application-Addon-Event-Provider         {A83FA99F-C356-4DED-9FD6-5A5EB8546D68}
ATA Port Driver Tracing Provider         {D08BD885-501E-489A-BAC6-B7D24BFE6BBF}
AuthFw NetShell Plugin                   {935F4AE6-845D-41C6-97FA-380DAD429B72}
BCP.1                                    {24722B88-DF97-4FF6-E395-DB533AC42A1E}
BFE Trace Provider                       {106B464A-8043-46B1-8CB8-E92A0CD7A560}
BITS Service Trace                       {4A8AAA94-CFC4-46A7-8E4E-17BC45608F0A}
Certificate Services Client CredentialRoaming Trace {EF4109DC-68FC-45AF-B329-CA2825437209}
Certificate Services Client Trace        {F01B7774-7ED7-401E-8088-B576793D7841}
Circular Kernel Session Provider         {54DEA73A-ED1F-42A4-AF71-3E63D056F174}
Classpnp Driver Tracing Provider         {FA8DE7C4-ACDE-4443-9994-C4E2359A9EDB}
Critical Section Trace Provider          {3AC66736-CC59-4CFF-8115-8DF50E39816B}
DBNETLIB.1                               {BD568F20-FCCD-B948-054E-DB3421115D61}
Disk Class Driver Tracing Provider       {945186BF-3DD6-4F3F-9C8E-9EDD3FC9D558}
DNS Server Trace Provider                {57840C25-FA99-4F0D-928D-D81D1851E3DD}
Downlevel IPsec API                      {94335EB3-79EA-44D5-8EA9-306F49B3A041}
Downlevel IPsec NetShell Plugin          {E4FF10D8-8A88-4FC6-82C8-8C23E9462FE5}
Downlevel IPsec Policy Store             {94335EB3-79EA-44D5-8EA9-306F49B3A070}
Downlevel IPsec Service                  {94335EB3-79EA-44D5-8EA9-306F49B3A040}
EA IME API                               {E2A24A32-00DC-4025-9689-C108C01991C5}
Error Instrument                         {CD7CF0D0-02CC-4872-9B65-0DBA0A90EFE8}
FD Core Trace                            {480217A9-F824-4BD4-BBE8-F371CAAF9A0D}
FD Publication Trace                     {649E3596-2620-4D58-A01F-17AEFE8185DB}
FD SSDP Trace                            {DB1D0418-105A-4C77-9A25-8F96A19716A4}
FD WNet Trace                            {8B20D3E4-581F-4A27-8109-DF01643A7A93}
FD WSDAPI Trace                          {7E2DBFC7-41E8-4987-BCA7-76CADFAD765F}
FDPHost Service Trace                    {F1C521CA-DA82-4D79-9EE4-D7A375723B68}
File Kernel Trace; Operation Set 1       {D75D8303-6C21-4BDE-9C98-ECC6320F9291}
File Kernel Trace; Operation Set 2       {058DD951-7604-414D-A5D6-A56D35367A46}
File Kernel Trace; Optional Data         {7DA1385C-F8F5-414D-B9D0-02FCA090F1EC}
File Kernel Trace; Volume To Log         {127D46AF-4AD3-489F-9165-F00BA64D5467}
FWPKCLNT Trace Provider                  {AD33FA19-F2D2-46D1-8F4C-E3C3087E45AD}
FWPUCLNT Trace Provider                  {5A1600D2-68E5-4DE7-BCF4-1C2D215FE0FE}
Heap Trace Provider                      {222962AB-6180-4B88-A825-346B75F2A24A}
Hypervisor Trace                         {52FC89F8-995E-434C-A91E-199986449890}
IKEEXT Trace Provider                    {106B464D-8043-46B1-8CB8-E92A0CD7A560}
IMAPI1 Shim                              {1FF10429-99AE-45BB-8A67-C9E945B9FB6C}
IMAPI2 Concatenate Stream                {0E85A5A5-4D5C-44B7-8BDA-5B7AB54F7E9D}
IMAPI2 Disc Master                       {0E85A5A5-4D5C-44B7-8BDA-5B7AB54F7E91}
IMAPI2 Disc Recorder                     {0E85A5A5-4D5C-44B7-8BDA-5B7AB54F7E93}
IMAPI2 Disc Recorder Enumerator          {0E85A5A5-4D5C-44B7-8BDA-5B7AB54F7E92}
IMAPI2 dll                               {0E85A5A5-4D5C-44B7-8BDA-5B7AB54F7E90}
IMAPI2 Interleave Stream                 {0E85A5A5-4D5C-44B7-8BDA-5B7AB54F7E9E}
IMAPI2 Media Eraser                      {0E85A5A5-4D5C-44B7-8BDA-5B7AB54F7E97}
IMAPI2 MSF                               {0E85A5A5-4D5C-44B7-8BDA-5B7AB54F7E9F}
IMAPI2 Multisession Sequential           {0E85A5A5-4D5C-44B7-8BDA-5B7AB54F7EA0}
IMAPI2 Pseudo-Random Stream              {0E85A5A5-4D5C-44B7-8BDA-5B7AB54F7E9C}
IMAPI2 Raw CD Writer                     {0E85A5A5-4D5C-44B7-8BDA-5B7AB54F7E9A}
IMAPI2 Raw Image Writer                  {07E397EC-C240-4ED7-8A2A-B9FF0FE5D581}
IMAPI2 Standard Data Writer              {0E85A5A5-4D5C-44B7-8BDA-5B7AB54F7E98}
IMAPI2 Track-at-Once CD Writer           {0E85A5A5-4D5C-44B7-8BDA-5B7AB54F7E99}
IMAPI2 Utilities                         {0E85A5A5-4D5C-44B7-8BDA-5B7AB54F7E94}
IMAPI2 Write Engine                      {0E85A5A5-4D5C-44B7-8BDA-5B7AB54F7E96}
IMAPI2 Zero Stream                       {0E85A5A5-4D5C-44B7-8BDA-5B7AB54F7E9B}
IMAPI2FS Tracing                         {F8036571-42D9-480A-BABB-DE7833CB059C}
Intel-iaLPSS-GPIO                        {D386CC7A-620A-41C1-ABF5-55018C6C699A}
Intel-iaLPSS-I2C                         {D4AEAC44-AD44-456E-9C90-33F8CDCED6AF}
IPMI Driver Trace                        {D5C6A3E9-FA9C-434E-9653-165B4FC869E4}
IPMI Provider Trace                      {651D672B-E11F-41B7-ADD3-C2F6A4023672}
KMDFv1 Trace Provider                    {544D4C9D-942C-46D5-BF50-DF5CD9524A50}
Layer2 Security HC Diagnostics Trace     {2E8D9EC5-A712-48C4-8CE0-631EB0C1CD65}
Local Security Authority (LSA)           {CC85922F-DB41-11D2-9244-006008269001}
LsaSrv                                   {199FE037-2B82-40A9-82AC-E1D46C792B99}
Microsoft-Antimalware-AMFilter           {CFEB0608-330E-4410-B00D-56D8DA9986E6}
Microsoft-Antimalware-Engine             {0A002690-3839-4E3A-B3B6-96D8DF868D99}
Microsoft-Antimalware-Protection         {E4B70372-261F-4C54-8FA6-A5A7914D73DA}
Microsoft-Antimalware-RTP                {8E92DEEF-5E17-413B-B927-59B2F06A3CFC}
Microsoft-Antimalware-Service            {751EF305-6C6E-4FED-B847-02EF79D26AEF}
Microsoft-Antimalware-UI                 {911F2490-C3DB-4781-94E6-7A9C404803E5}
Microsoft-AppV-Client                    {E4F68870-5AE8-4E5B-9CE7-CA9ED75B0245}
Microsoft-AppV-Client-StreamingUX        {28CB46C7-4003-4E50-8BD9-442086762D12}
Microsoft-AppV-ServiceLog                {9CC69D1C-7917-4ACD-8066-6BF8B63E551B}
Microsoft-AppV-SharedPerformance         {FB4A19EE-EB5A-47A4-BC52-E71AAC6D0859}
Microsoft-Client-Licensing-Platform      {B6CC0D55-9ECC-49A8-B929-2B9022426F2A}
Microsoft-IE                             {9E3B3947-CA5D-4614-91A2-7B624E0E7244}
Microsoft-IE-JSDumpHeap                  {7F8E35CA-68E8-41B9-86FE-D6ADC5B327E7}
Microsoft-IEFRAME                        {5C8BB950-959E-4309-8908-67961A1205D5}
Microsoft-JScript                        {57277741-3638-4A4B-BDBA-0AC6E45DA56C}
Microsoft-OneCore-OnlineSetup            {41862974-DA3B-4F0B-97D5-BB29FBB9B71E}
Microsoft-Pef-WFP-MessageProvider        {C22D1B14-C242-49DE-9F17-1D76B8B9C458}
Microsoft-PerfTrack-IEFRAME              {B2A40F1F-A05A-4DFD-886A-4C4F18C4334C}
Microsoft-PerfTrack-MSHTML               {FFDB9886-80F3-4540-AA8B-B85192217DDF}
Microsoft-User Experience Virtualization-Admin {61BC445E-7A8D-420E-AB36-9C7143881B98}
Microsoft-User Experience Virtualization-Agent Driver {DE29CF61-5EE6-43FF-9AAC-959C4E13CC6C}
Microsoft-User Experience Virtualization-App Agent {1ED6976A-4171-4764-B415-7EA08BC46C51}
Microsoft-User Experience Virtualization-IPC {21D79DB0-8E03-41CD-9589-F3EF7001A92A}
Microsoft-User Experience Virtualization-SQM Uploader {57003E21-269B-4BDC-8434-B3BF8D57D2D5}
Microsoft-Windows Networking VPN Plugin Platform {E5FC4A0F-7198-492F-9B0F-88FDCBFDED48}
Microsoft-Windows-AAD                    {4DE9BC9C-B27A-43C9-8994-0915F1A5E24F}
Microsoft-Windows-ACL-UI                 {EA4CC8B8-A150-47A3-AFB9-C8D194B19452}
Microsoft-Windows-ActionQueue            {0DD4D48E-2BBF-452F-A7EC-BA3DBA8407AE}
Microsoft-Windows-ADSI                   {7288C9F8-D63C-4932-A345-89D6B060174D}
Microsoft-Windows-AIT                    {6ADDABF4-8C54-4EAB-BF4F-FBEF61B62EB0}
Microsoft-Windows-All-User-Install-Agent {D2E990DA-8504-4702-A5E5-367FC2F823BF}
Microsoft-Windows-AllJoyn                {2ED299D2-2F6B-411D-8D15-F4CC6FDE0C70}
Microsoft-Windows-AppHost                {98E0765D-8C42-44A3-A57B-760D7F93225A}
Microsoft-Windows-AppID                  {3CB2A168-FE19-4A4E-BDAD-DCF422F13473}
Microsoft-Windows-AppIDServiceTrigger    {D02A9C27-79B8-40D6-9B97-CF3F8B7B5D60}
Microsoft-Windows-ApplicabilityEngine    {10A208DD-A372-421C-9D99-4FAD6DB68B62}
Microsoft-Windows-Application Server-Applications {C651F5F6-1C0D-492E-8AE1-B4EFD7C9D503}
Microsoft-Windows-Application-Experience {EEF54E71-0661-422D-9A98-82FD4940B820}
Microsoft-Windows-ApplicationExperience-Cache {6D8A3A60-40AF-445A-98CA-99359E500146}
Microsoft-Windows-ApplicationExperience-LookupServiceTrigger {18F4A5FD-FD3B-40A5-8FC2-E5D261C5D02E}
Microsoft-Windows-ApplicationExperience-SwitchBack {17D6E590-F5FE-11DC-95FF-0800200C9A66}
Microsoft-Windows-ApplicationExperienceInfrastructure {5EC13D8E-4B3F-422E-A7E7-3121A1D90C7A}
Microsoft-Windows-ApplicationResourceManagementSystem {770CA594-B467-4811-B355-28F5E5706987}
Microsoft-Windows-AppLocker              {CBDA4DBF-8D5D-4F69-9578-BE14AA540D22}
Microsoft-Windows-AppModel-Exec          {EB65A492-86C0-406A-BACE-9912D595BD69}
Microsoft-Windows-AppModel-Runtime       {F1EF270A-0D32-4352-BA52-DBAB41E1D859}
Microsoft-Windows-AppModel-State         {BFF15E13-81BF-45EE-8B16-7CFEAD00DA86}
Microsoft-Windows-AppReadiness           {F0BE35F8-237B-4814-86B5-ADE51192E503}
Microsoft-Windows-AppSruProv             {0CC157B3-CF07-4FC2-91EE-31AC92E05FE1}
Microsoft-Windows-AppXDeployment         {8127F6D4-59F9-4ABF-8952-3E3A02073D5F}
Microsoft-Windows-AppXDeployment-Server  {3F471139-ACB7-4A01-B7A7-FF5DA4BA2D43}
Microsoft-Windows-AppxPackagingOM        {BA723D81-0D0C-4F1E-80C8-54740F508DDF}
Microsoft-Windows-ASN1                   {D92EF8AC-99DD-4AB8-B91D-C6EBA85F3755}
Microsoft-Windows-AssignedAccess         {8530DB6E-51C0-43D6-9D02-A8C2088526CD}
Microsoft-Windows-AssignedAccessBroker   {F2311B48-32BE-4902-A22A-7240371DBB2C}
Microsoft-Windows-AsynchronousCausality  {19A4C69A-28EB-4D4B-8D94-5F19055A1B5C}
Microsoft-Windows-ATAPort                {CB587AD1-CC35-4EF1-AD93-36CC82A2D319}
Microsoft-Windows-Audio                  {AE4BD3BE-F36F-45B6-8D21-BDD6FB832853}
Microsoft-Windows-Audit                  {75EBC33E-0936-4A55-9D26-5F298F3180BF}
Microsoft-Windows-Audit-CVE              {85A62A0D-7E17-485F-9D4F-749A287193A6}
Microsoft-Windows-AuthenticationProvider {DDDC1D91-51A1-4A8D-95B5-350C4EE3D809}
Microsoft-Windows-AxInstallService       {DAB3B18C-3C0F-43E8-80B1-E44BC0DAD901}
Microsoft-Windows-BackgroundTransfer-ContentPrefetcher {648A0644-7D62-4FD3-8841-440064762F95}
Microsoft-Windows-Backup                 {1DB28F2E-8F80-4027-8C5A-A11F7F10F62D}
Microsoft-Windows-Base-Filtering-Engine-Connections {121D3DA8-BAF1-4DCB-929F-2D4C9A47F7AB}
Microsoft-Windows-Base-Filtering-Engine-Resource-Flows {92765247-03A9-4AE3-A575-B42264616E78}
Microsoft-Windows-Battery                {59819D0A-ADAF-46B2-8D7C-990BC39C7C15}
Microsoft-Windows-BestPractices          {5218E51A-3996-4A9A-A75A-70BA4EB66312}
Microsoft-Windows-BfeTriggerProvider     {54732EE5-61CA-4727-9DA1-10BE5A4F773D}
Microsoft-Windows-Biometrics             {A0E3D8EA-C34F-4419-A1DB-90435B8B21D0}
Microsoft-Windows-Bits-Client            {EF1CC15B-46C1-414E-BB95-E76B077BD51E}
Microsoft-Windows-Bluetooth-BthLEPrepairing {4AF188AC-E9C4-4C11-B07B-1FABC07DFEB2}
Microsoft-Windows-Bluetooth-MTPEnum      {04268430-D489-424D-B914-0CFF741D6684}
Microsoft-Windows-BootUX                 {67D781BD-CBD2-4BD2-AD1F-6152FB891246}
Microsoft-Windows-BranchCacheSMB         {4A933674-FB3D-4E8D-B01D-17EE14E91A3E}
Microsoft-Windows-BrokerInfrastructure   {E6835967-E0D2-41FB-BCEC-58387404E25A}
Microsoft-Windows-Build-RegDll           {D39B6336-CFCB-483B-8C76-7C3E7D02BCB8}
Microsoft-Windows-Calculator             {75F48521-4131-4AC3-9887-65473224FCB2}
Microsoft-Windows-CAPI2                  {5BBCA4A8-B209-48DC-A8C7-B23D3E5216FB}
Microsoft-Windows-CDROM                  {9B6123DC-9AF6-4430-80D7-7D36F054FB9F}
Microsoft-Windows-CertificateServices-Deployment {B2D1F576-2E85-4489-B504-1861C40544B3}
Microsoft-Windows-CertificateServicesClient {73370BD6-85E5-430B-B60A-FEA1285808A7}
Microsoft-Windows-CertificateServicesClient-AutoEnrollment {F0DB7EF8-B6F3-4005-9937-FEB77B9E1B43}
Microsoft-Windows-CertificateServicesClient-CertEnroll {54164045-7C50-4905-963F-E5BC1EEF0CCA}
Microsoft-Windows-CertificateServicesClient-CredentialRoaming {89A2278B-C662-4AFF-A06C-46AD3F220BCA}
Microsoft-Windows-CertificateServicesClient-Lifecycle-System {BC0669E1-A10D-4A78-834E-1CA3C806C93B}
Microsoft-Windows-CertificateServicesClient-Lifecycle-User {BEA18B89-126F-4155-9EE4-D36038B02680}
Microsoft-Windows-CertificationAuthorityClient-CertCli {98BF1CD3-583E-4926-95EE-A61BF3F46470}
Microsoft-Windows-CertPolEng             {AF9CC194-E9A8-42BD-B0D1-834E9CFAB799}
Microsoft-Windows-ClearTypeTextTuner     {0A88862D-20A3-4C1F-B76F-162C55ADBF93}
Microsoft-Windows-CloudStorageWizard     {9FC66DD7-98C7-4B83-8293-46A18439B03B}
Microsoft-Windows-CmiSetup               {75EBC33E-0CC6-49DA-8CD9-8903A5222AA0}
Microsoft-Windows-CodeIntegrity          {4EE76BD8-3CF4-44A0-A0AC-3937643E37A3}
Microsoft-Windows-COM                    {D4263C98-310C-4D97-BA39-B55354F08584}
Microsoft-Windows-COM-Perf               {B8D6861B-D20F-4EEC-BBAE-87E0DD80602B}
Microsoft-Windows-ComDlg32               {7F912B92-21AD-496E-B97A-88622A72BC42}
Microsoft-Windows-Compat-Appraiser       {442C11C5-304B-45A4-AE73-DC2194C4E876}
Microsoft-Windows-Complus                {0F177893-4A9C-4709-B921-F432D67F43D5}
Microsoft-Windows-COMRuntime             {BF406804-6AFA-46E7-8A48-6C357E1D6D61}
Microsoft-Windows-Containers-Wcifs       {AEC5C129-7C10-407D-BE97-91A042C61AAA}
Microsoft-Windows-Containers-Wcnfs       {B99317E5-89B7-4C0D-ABD1-6E705F7912DC}
Microsoft-Windows-CoreSystem-NetProvision-JoinProviderOnline {3629DD4D-D6F1-4302-A623-0768B51501C7}
Microsoft-Windows-CoreWindow             {A3D95055-34CC-4E4A-B99F-EC88F5370495}
Microsoft-Windows-CorruptedFileRecovery-Client {BA093605-3909-4345-990B-26B746ADEE0A}
Microsoft-Windows-CorruptedFileRecovery-Server {D6F68875-CDF5-43A5-A3E3-53FFD683311C}
Microsoft-Windows-Crashdump              {ECDAACFA-6FE9-477C-B5F0-85B76F8F50AA}
Microsoft-Windows-CredUI                 {5A24FCDB-1CF3-477B-B422-EF4909D51223}
Microsoft-Windows-Crypto-BCrypt          {C7E089AC-BA2A-11E0-9AF7-68384824019B}
Microsoft-Windows-Crypto-CNG             {E3E0E2F0-C9C5-11E0-8AB9-9EBC4824019B}
Microsoft-Windows-Crypto-DPAPI           {89FE8F40-CDCE-464E-8217-15EF97D4C7C3}
Microsoft-Windows-Crypto-DSSEnh          {43DAD447-735F-4829-A6FF-9829A87419FF}
Microsoft-Windows-Crypto-NCrypt          {E8ED09DC-100C-45E2-9FC8-B53399EC1F70}
Microsoft-Windows-Crypto-RNG             {54D5AC20-E14F-4FDA-92DA-EBF7556FF176}
Microsoft-Windows-Crypto-RSAEnh          {152FDB2B-6E9D-4B60-B317-815D5F174C4A}
Microsoft-Windows-D3D10Level9            {7E7D3382-023C-43CB-95D2-6F0CA6D70381}
Microsoft-Windows-D3D9                   {783ACA0A-790E-4D7F-8451-AA850511C6B9}
Microsoft-Windows-DAL-Provider           {7E87506F-BACE-4BF1-BC09-3A1F37045C71}
Microsoft-Windows-Data-Pdf               {B97561FE-B27A-4C48-AA3E-7D3ADDC105B1}
Microsoft-Windows-DataCollectionService  {3B416199-2C3B-4C28-98B8-F7165F5936F0}
Microsoft-Windows-DataIntegrityScan      {13BC4371-4E21-4E46-A84F-8C0FFB548CED}
Microsoft-Windows-DateTimeControlPanel   {741FC222-44ED-4BA7-98E3-F405B2D2C4B4}
Microsoft-Windows-DCLocator              {CFAA5446-C6C4-4F5C-866F-31C9B55B962D}
Microsoft-Windows-Defrag-Core            {E3257C8C-C7CB-444F-9DA0-5D92A2625289}
Microsoft-Windows-Deplorch               {B9DA9FE6-AE5F-4F3E-B2FA-8E623C11DC75}
Microsoft-Windows-DesktopActivityModerator {32DD13DF-9C0B-4C3B-B854-EE76C050F5F4}
Microsoft-Windows-DesktopWindowManager-Diag {31F60101-3703-48EA-8143-451F8DE779D2}
Microsoft-Windows-DeviceAssociationService {56C71C31-CFBD-4CDD-8559-505E042BBBE1}
Microsoft-Windows-DeviceConfidence       {1D5990C1-EC62-49F0-9E37-1F4DB12DB41E}
Microsoft-Windows-DeviceGuard            {F717D024-F5B4-4F03-9AB9-331B2DC38FFB}
Microsoft-Windows-DeviceManagement-Enterprise-Diagnostics-Provider {3DA494E4-0FE2-415C-B895-FB5265C5C83B}
Microsoft-Windows-DeviceManagement-Pushrouter {F1201B5A-E170-42B6-8D20-B57AC57E6416}
Microsoft-Windows-Devices-Background     {64EF2B1C-4AE1-4E64-8599-1636E441EC88}
Microsoft-Windows-DeviceSetupManager     {FCBB06BB-6A2A-46E3-ABAA-246CB4E508B2}
Microsoft-Windows-DeviceSync             {09EC9687-D7AD-40CA-9C5E-78A04A5AE993}
Microsoft-Windows-DeviceUx               {DED165CF-485D-4770-A3E7-9C5F0320E80C}
Microsoft-Windows-DfsSvc                 {7DA4FE0E-FD42-4708-9AA5-89B77A224885}
Microsoft-Windows-Dhcp-Client            {15A7A4F8-0072-4EAB-ABAD-F98A4D666AED}
Microsoft-Windows-DHCP-Server            {6D64F02C-A125-4DAC-9A01-F0555B41CA84}
Microsoft-Windows-DHCPv6-Client          {6A1F2B00-6A90-4C38-95A5-5CAB3B056778}
Microsoft-Windows-DiagCpl                {1A396961-5F3C-4C71-8310-44C653C0BF8A}
Microsoft-Windows-Diagnosis-AdvancedTaskManager {178DADAF-7AC4-4593-AB3E-A45FDA6D0D55}
Microsoft-Windows-Diagnosis-DPS          {6BBA3851-2C7E-4DEA-8F54-31E5AFD029E3}
Microsoft-Windows-Diagnosis-MSDE         {A50B09F8-93EB-4396-84C9-DC921259F952}
Microsoft-Windows-Diagnosis-PCW          {AABF8B86-7936-4FA2-ACB0-63127F879DBF}
Microsoft-Windows-Diagnosis-PerfHost     {F27B948B-0A7C-4EB6-92EC-8A2C1B353ECD}
Microsoft-Windows-Diagnosis-PLA          {E4D53F84-7DE3-11D8-9435-505054503030}
Microsoft-Windows-Diagnosis-Scheduled    {40AB57C2-1C53-4DF9-9324-FF7CF898A02C}
Microsoft-Windows-Diagnosis-Scripted     {E1DD7E52-621D-44E3-A1AD-0370C2B25946}
Microsoft-Windows-Diagnosis-ScriptedDiagnosticsProvider {9363CCD9-D429-4452-9ADB-2501E704B810}
Microsoft-Windows-Diagnosis-WDC          {05921578-2261-42C7-A0D3-26DDBCE6C50D}
Microsoft-Windows-Diagnosis-WDI          {E01B1A7C-C5C9-4E67-99A9-5E85ACFB2E10}
Microsoft-Windows-Diagnostics-LoggingChannel {4BD2826E-54A1-4BA9-BF63-92B73EA1AC4A}
Microsoft-Windows-Diagnostics-Networking {36C23E18-0E66-11D9-BBEB-505054503030}
Microsoft-Windows-Diagtrack              {56DC463B-97E8-4B59-E836-AB7C9BB96301}
Microsoft-Windows-Direct3D10             {9B7E4C0F-342C-4106-A19F-4F2704F689F0}
Microsoft-Windows-Direct3D10_1           {9B7E4C8F-342C-4106-A19F-4F2704F689F0}
Microsoft-Windows-Direct3D11             {DB6F6DDB-AC77-4E88-8253-819DF9BBF140}
Microsoft-Windows-Direct3D12             {5D8087DD-3A9B-4F56-90DF-49196CDC4F11}
Microsoft-Windows-DirectAccess-MediaManager {DD2FE441-6C12-41FD-8232-3709C6045F63}
Microsoft-Windows-DirectComposition      {C44219D0-F344-11DF-A5E2-B307DFD72085}
Microsoft-Windows-DirectManipulation     {5786E035-EF2D-4178-84F2-5A6BBEDBB947}
Microsoft-Windows-Directory-Services-SAM {0D4FDC09-8C27-494A-BDA0-505E4FD8ADAE}
Microsoft-Windows-Directory-Services-SAM-Utility {BD8FEA17-5549-4B49-AA03-1981D16396A9}
Microsoft-Windows-DirectoryServices-Deployment {71B4B0DA-68D5-4925-9F9B-61750F989527}
Microsoft-Windows-DirectShow-Core        {968F313B-097F-4E09-9CDD-BC62692D138B}
Microsoft-Windows-DirectShow-KernelSupport {3CC2D4AF-DA5E-4ED4-BCBE-3CF995940483}
Microsoft-Windows-DirectSound            {8A93B54B-C75A-49B5-A5BE-9060715B1A33}
Microsoft-Windows-DirectWrite            {D775F388-5A4A-474D-8726-7B255544285F}
Microsoft-Windows-DirectWrite-FontCache  {E856C26A-E105-4683-A948-6920DCC42E45}
Microsoft-Windows-Disk                   {6B4DB0BC-9A3D-467D-81B9-A84C6F2F3D40}
Microsoft-Windows-DiskDiagnostic         {E670A5A2-CE74-4AB4-9347-61B815319F4C}
Microsoft-Windows-DiskDiagnosticDataCollector {E104FB41-6B04-4F3A-B47D-F0DF2F02B954}
Microsoft-Windows-DiskDiagnosticResolver {6B1FFE48-5B1E-4793-9F7F-AE926454499D}
Microsoft-Windows-Dism-Api               {75B0DA21-8B50-42EB-9448-EC48B1729B57}
Microsoft-Windows-Dism-Cli               {2F959466-24D4-4972-8729-0D5E3539EBC3}
Microsoft-Windows-Display                {6ECE3302-FEE1-4EA9-8B88-086D459ED976}
Microsoft-Windows-DisplayColorCalibration {3239EB6F-C7FC-4953-AA15-646829A4CA4C}
Microsoft-Windows-DisplaySwitch          {192EDE41-9175-4C86-AC02-9D003C9D43AB}
Microsoft-Windows-DistributedCOM         {1B562E86-B7AA-4131-BADC-B6F3A001407E}
Microsoft-Windows-DLNA-Namespace         {D38FB874-33E4-4DCF-911E-1B53BB106D53}
Microsoft-Windows-DNS-Client             {1C95126E-7EEA-49A9-A3FE-A378B03DDB4D}
Microsoft-Windows-DNS-Server-Service     {71A551F5-C893-4849-886B-B5EC8502641E}
Microsoft-Windows-DNSServer              {EB79061A-A566-4698-9119-3ED2807060E7}
Microsoft-Windows-Documents              {C89B991E-3B48-49B2-80D3-AC000DFC9749}
Microsoft-Windows-DomainJoinManagerTriggerProvider {5B004607-1087-4F16-B10E-979685A8D131}
Microsoft-Windows-Dot3MM                 {F3419A17-E994-4C40-B593-79B8EDEC54E9}
Microsoft-Windows-DotNETRuntime          {E13C0D23-CCBC-4E12-931B-D9CC2EEE27E4}
Microsoft-Windows-DotNETRuntimeRundown   {A669021C-C450-4609-A035-5AF59AF4DF18}
Microsoft-Windows-DriverFrameworks-KernelMode-Performance {486A5C7C-11CC-46C5-9DE7-43DFE0BB57C1}
Microsoft-Windows-DriverFrameworks-UserMode {2E35AAEB-857F-4BEB-A418-2E6C0E54D988}
Microsoft-Windows-DriverFrameworks-UserMode-Performance {9FA5DD5D-999E-466A-8CA9-7B3A66F8882F}
Microsoft-Windows-DSC                    {50DF9E12-A8C4-4939-B281-47E1325BA63E}
Microsoft-Windows-DUI                    {8360BD0F-A7DC-4391-91A7-A457C5C381E4}
Microsoft-Windows-DUSER                  {8429E243-345B-47C1-8A91-2C94CAF0DAAB}
Microsoft-Windows-DVD                    {E18D0FCA-9515-4232-98E4-89E456D8551B}
Microsoft-Windows-Dwm-Api                {292A52C4-FA27-4461-B526-54A46430BD54}
Microsoft-Windows-Dwm-Core               {9E9BBA3C-2E38-40CB-99F4-9E8281425164}
Microsoft-Windows-Dwm-Dwm                {D29D56EA-4867-4221-B02E-CFD998834075}
Microsoft-Windows-Dwm-Redir              {7D99F6A4-1BEC-4C09-9703-3AAA8148347F}
Microsoft-Windows-Dwm-Udwm               {A2D1C713-093B-43A7-B445-D09370EC9F47}
Microsoft-Windows-DXGI                   {CA11C036-0102-4A2D-A6AD-F03CFED5D3C9}
Microsoft-Windows-DxgKrnl                {802EC45A-1E99-4B83-9920-87C98277BA9D}
Microsoft-Windows-DXP                    {728B8C72-0F0F-4071-9BCC-27CB3B6DACBE}
Microsoft-Windows-DxpTaskSyncProvider    {271C5228-C3FE-4E47-831F-48C3652CE5AC}
Microsoft-Windows-EapHost                {6EB8DB94-FE96-443F-A366-5FE0CEE7FB1C}
Microsoft-Windows-EapMethods-RasChap     {58980F4B-BD39-4A3E-B344-492ED2254A4E}
Microsoft-Windows-EapMethods-RasTls      {9CC0413E-5717-4AF5-82EB-6103D8707B45}
Microsoft-Windows-EapMethods-Sim         {3D42A67D-9CE8-4284-B755-2550672B0CE0}
Microsoft-Windows-EapMethods-Ttls        {D710D46C-235D-4798-AC20-9F83E1DCD557}
Microsoft-Windows-EaseOfAccess           {74B4A4B1-2302-4768-AC5B-9773DD456B08}
Microsoft-Windows-EDP-Audit-Regular      {50F99B2D-96D2-421F-BE4C-222C4140DA9F}
Microsoft-Windows-EDP-Audit-TCB          {287D59B6-79BA-4741-A08B-2FEDEEDE6435}
Microsoft-Windows-EFS                    {3663A992-84BE-40EA-BBA9-90C7ED544222}
Microsoft-Windows-ELS-Hyphenation        {51AEDB05-890B-4ADE-8BA1-0BA14B8E8973}
Microsoft-Windows-EmbeddedAppLauncher    {56285391-9B96-4696-9EAD-2D17F98FBDB2}
Microsoft-Windows-EndpointTriggerProvider {92AAB24D-D9A9-4A60-9F94-201FED3E3E88}
Microsoft-Windows-Energy-Estimation-Engine {DDCC3826-A68A-4E0D-BCFD-9C06C27C6948}
Microsoft-Windows-EnergyEfficiencyWizard {1A772F65-BE1E-4FC6-96BB-248E03FA60F5}
Microsoft-Windows-EnhancedStorage-EhStorTcgDrv {AA3AA23B-BB6D-425A-B58C-1D7E37F5D02A}
Microsoft-Windows-EnrollmentPolicyWebService {F64ED6BA-BD9B-4CE1-90FB-7B8765928134}
Microsoft-Windows-EnrollmentWebService   {C3CBA89D-B3D1-48F1-BE6C-9B317A3CF3D5}
Microsoft-Windows-EQoS                   {54CB22FF-26B4-4393-A8C2-6B0715912C5F}
Microsoft-Windows-ErrorReportingConsole  {017247F2-7E96-11DC-8314-0800200C9A66}
Microsoft-Windows-ESE                    {478EA8A8-00BE-4BA6-8E75-8B9DC7DB9F78}
Microsoft-Windows-EventCollector         {B977CF02-76F6-DF84-CC1A-6A4B232322B6}
Microsoft-Windows-Eventlog               {FC65DDD8-D6EF-4962-83D5-6E5CFE9CE148}
Microsoft-Windows-EventLog-WMIProvider   {35AC6CE8-6104-411D-976C-877F183D2D32}
Microsoft-Windows-EventSystem            {899DAACE-4868-4295-AFCD-9EB8FB497561}
Microsoft-Windows-exFAT-SQM              {494E7A3D-8DB9-4EC4-B43E-2844AF6E38D6}
Microsoft-Windows-FailoverClustering-Client {A82FDA5D-745F-409C-B0FE-18AE0678A0E0}
Microsoft-Windows-Fat-SQM                {3E59A529-B0B3-4A11-8129-9FFE6BB46EB9}
Microsoft-Windows-Fault-Tolerant-Heap    {6B93BF66-A922-4C11-A617-CF60D95C133D}
Microsoft-Windows-FederationServices-Deployment {C19E175B-30A0-42DA-A5E3-124011DE54B6}
Microsoft-Windows-Feedback-Service-TriggerProvider {E46EEAD8-0C54-4489-9898-8FA79D059E0E}
Microsoft-Windows-FileInfoMinifilter     {A319D300-015C-48BE-ACDB-47746E154751}
Microsoft-Windows-FileServices-ServerManager-EventProvider {78B0E04E-3F81-11E0-99F5-02CFDED72085}
Microsoft-Windows-FileShareShadowCopyProvider {89300202-3CEC-4981-9171-19F59559E0F2}
Microsoft-Windows-FilterManager          {F3C5E28E-63F6-49C7-A204-E48A1BC4B09D}
Microsoft-Windows-Firewall               {E595F735-B42A-494B-AFCD-B68666945CD3}
Microsoft-Windows-Firewall-CPL           {546549BE-9D63-46AA-9154-4F6EB9526378}
Microsoft-Windows-FirstUX-PerfInstrumentation {FBEF8096-2CA3-4082-ACDE-DCFB47E96B72}
Microsoft-Windows-FMS                    {DEA07764-0790-44DE-B9C4-49677B17174F}
Microsoft-Windows-Folder Redirection     {7D7B0C39-93F6-4100-BD96-4DDA859652C5}
Microsoft-Windows-Forwarding             {699E309C-E782-4400-98C8-E21D162D7B7B}
Microsoft-Windows-FunctionDiscovery      {9DB0FDB5-3B21-440E-A94B-63738A4BE5DE}
Microsoft-Windows-FunctionDiscoveryHost  {538CBBAD-4877-4EB2-B26E-7CAEE8F0F8CB}
Microsoft-Windows-GenericRoaming         {4EACB4D0-263B-4B93-8CD6-778A278E5642}
Microsoft-Windows-Globalization          {12E3DA5B-14E4-4F76-8E35-C540763EF300}
Microsoft-Windows-Globalization-FontGroups {E1168941-8333-497F-98D9-67BEE05A6034}
Microsoft-Windows-GPIO-ClassExtension    {55AB77F6-FA04-43EF-AF45-688FBF500482}
Microsoft-Windows-GPIOButtons            {E13FF11E-E989-4838-A9FA-38A4D13914CF}
Microsoft-Windows-Graphics-Printing      {E7AA32FB-77D0-477F-987D-7E83DF1B7ED0}
Microsoft-Windows-Graphics-Printing3D    {BE967569-E3C8-425B-AD0E-4F2C790B1848}
Microsoft-Windows-GroupPolicy            {AEA1B4FA-97D1-45F2-A64C-4D69FFFD92C9}
Microsoft-Windows-GroupPolicyTriggerProvider {BD2F4252-5E1E-49FC-9A30-F3978AD89EE2}
Microsoft-Windows-HAL                    {63D1E632-95CC-4443-9312-AF927761D52A}
Microsoft-Windows-HealthCenter           {588C5C5A-FFC5-44A2-9A7F-D5E8DBE6EFD7}
Microsoft-Windows-HealthCenterCPL        {959F1FAC-7CA8-4ED1-89DC-CDFA7E093CB0}
Microsoft-Windows-Help                   {DE513A55-C345-438B-9A74-E18CAC5C5CC5}
Microsoft-Windows-HomeGroup-ControlPanel {134EA407-755D-4A93-B8A6-F290CD155023}
Microsoft-Windows-Http-SQM-Provider      {F5344219-87A4-4399-B14A-E59CD118ABB8}
Microsoft-Windows-HttpEvent              {7B6BC78C-898B-4170-BBF8-1A469EA43FC5}
Microsoft-Windows-HttpLog                {C42A2738-2333-40A5-A32F-6ACC36449DCC}
Microsoft-Windows-HttpService            {DD5EF90A-6398-47A4-AD34-4DCECDEF795F}
Microsoft-Windows-Hyper-V-Guest-Drivers-Dynamic-Memory {BA2FFB5C-E20A-4FB9-91B4-45F61B4B66A0}
Microsoft-Windows-Hyper-V-Guest-Drivers-IcSvc {C18672D1-DC18-4DFD-91E4-170CF37160CF}
Microsoft-Windows-Hyper-V-Guest-Drivers-Storage-Filter {0B9FDCCC-451C-449C-9BD8-6756FCC6091A}
Microsoft-Windows-Hyper-V-Guest-Drivers-Vmbus {F2E2CE31-0E8A-4E46-A03B-2E0FE97E93C2}
Microsoft-Windows-Hyper-V-Netvsc         {152FBE4B-C7AD-4F68-BADA-A4FCC1464F6C}
Microsoft-Windows-IdCtrls                {6D7662A9-034E-4B1F-A167-67819C401632}
Microsoft-Windows-IdleTriggerProvider    {9E03F75A-BCBE-428A-8F3C-D46F2A444935}
Microsoft-Windows-IE-F12-Provider        {D17FFF2F-392D-478C-A41D-737A216EB2A4}
Microsoft-Windows-IIS-APPHOSTSVC         {CAC10856-9223-48FE-96BA-2A772274FB53}
Microsoft-Windows-IIS-Configuration      {DC0B8E51-4863-407A-BC3C-1B479B2978AC}
Microsoft-Windows-IIS-FTP                {AB29F35C-8531-42FF-810D-B8552D23BC92}
Microsoft-Windows-IIS-IisMetabaseAudit   {BBB924B8-F415-4F57-AA45-1007F704C9B1}
Microsoft-Windows-IIS-IISReset           {DA9A85BB-563D-40FB-A164-8E982EA6844B}
Microsoft-Windows-IIS-Logging            {7E8AD27F-B271-4EA2-A783-A47BDE29143B}
Microsoft-Windows-IIS-W3SVC              {05448E22-93DE-4A7A-BBA5-92E27486A8BE}
Microsoft-Windows-IIS-W3SVC-PerfCounters {90303B54-419D-4081-A683-6DBCB532F261}
Microsoft-Windows-IIS-W3SVC-WP           {670080D9-742A-4187-8D16-41143D1290BD}
Microsoft-Windows-IIS-WMSVC              {23108B68-1B7E-43FA-94FB-EC3066805744}
Microsoft-Windows-IME-Broker             {E2C15FD7-8924-4C8C-8CFE-DA0BE539CE27}
Microsoft-Windows-IME-CandidateUI        {7C4117B1-ED82-4F47-B2CA-29E4E25719C7}
Microsoft-Windows-IME-CustomerFeedbackManager {E2242B38-9453-42FD-B446-00746E76EB82}
Microsoft-Windows-IME-CustomerFeedbackManagerUI {1B734B40-A458-4B81-954F-AD7C9461BED8}
Microsoft-Windows-IME-JPAPI              {31BCAC7F-4AB8-47A1-B73A-A161EE68D585}
Microsoft-Windows-IME-JPLMP              {DBC388BC-89C2-4FE0-B71F-6E4881FB575C}
Microsoft-Windows-IME-JPPRED             {3AD571F3-BDAE-4942-8733-4D1B85870A1E}
Microsoft-Windows-IME-JPSetting          {14371053-1813-471A-9510-1CF1D0A055A8}
Microsoft-Windows-IME-JPTIP              {8C8A69AD-CC89-481F-BBAD-FD95B5006256}
Microsoft-Windows-IME-KRAPI              {7562948E-2671-4DDA-8F8F-BF945EF984A1}
Microsoft-Windows-IME-KRTIP              {E013E74B-97F4-4E1C-A120-596E5629ECFE}
Microsoft-Windows-IME-OEDCompiler        {FD44A6E7-580F-4A9C-83D9-D820B7D3A033}
Microsoft-Windows-IME-TCCORE             {F67B2345-47FA-4721-A6FB-FE08110EECF7}
Microsoft-Windows-IME-TCTIP              {D5268C02-6F51-436F-983B-74F2EFBFAF3A}
Microsoft-Windows-IME-TIP                {BDD4B92E-19EF-4497-9C4A-E10E7FD2E227}
Microsoft-Windows-Immersive-Shell        {315A8872-923E-4EA2-9889-33CD4754BF64}
Microsoft-Windows-Immersive-Shell-API    {5F0E257F-C224-43E5-9555-2ADCB8540A58}
Microsoft-Windows-IndirectDisplays-ClassExtension-Events {966CD1C0-3F69-42AD-9877-517DCE8462B4}
Microsoft-Windows-Input-HIDCLASS         {6465DA78-E7A0-4F39-B084-8F53C7C30DC6}
Microsoft-Windows-InputSwitch            {BB8E7234-BBF4-48A7-8741-339206ED1DFB}
Microsoft-Windows-Install-Agent          {E0C6F6DE-258A-50E0-AC1A-103482D118BC}
Microsoft-Windows-International          {3AA52B8B-6357-4C18-A92E-B53FB177853B}
Microsoft-Windows-International-RegionalOptionsControlPanel {C6BF6832-F7BD-4151-AC21-753CE4707453}
Microsoft-Windows-Iphlpsvc               {66A5C15C-4F8E-4044-BF6E-71D896038977}
Microsoft-Windows-Iphlpsvc-Trace         {6600E712-C3B6-44A2-8A48-935C511F28C8}
Microsoft-Windows-IPMIProvider           {2A45D52E-BBF3-4843-8E18-B356ED5F6A65}
Microsoft-Windows-IPNAT                  {A67075C2-3E39-4109-B6CD-6D750058A732}
Microsoft-Windows-IPSEC-SRV              {C91EF675-842F-4FCF-A5C9-6EA93F2E4F8B}
Microsoft-Windows-IsolatedUserMode       {73A33AB2-1966-4999-8ADD-868C41415269}
Microsoft-Windows-KdsSvc                 {89203471-D554-47D4-BDE4-7552EC219999}
Microsoft-Windows-Kerberos-KdcProxy      {D3F8787E-656F-4876-9EBD-6F5E3CB0A45B}
Microsoft-Windows-Kernel-Acpi            {C514638F-7723-485B-BCFC-96565D735D4A}
Microsoft-Windows-Kernel-AppCompat       {16A1ADC1-9B7F-4CD9-94B3-D8296AB1B130}
Microsoft-Windows-Kernel-Audit-API-Calls {E02A841C-75A3-4FA7-AFC8-AE09CF9B7F23}
Microsoft-Windows-Kernel-Boot            {15CA44FF-4D7A-4BAA-BBA5-0998955E531E}
Microsoft-Windows-Kernel-BootDiagnostics {96AC7637-5950-4A30-B8F7-E07E8E5734C1}
Microsoft-Windows-Kernel-Disk            {C7BDE69A-E1E0-4177-B6EF-283AD1525271}
Microsoft-Windows-Kernel-EventTracing    {B675EC37-BDB6-4648-BC92-F3FDC74D3CA2}
Microsoft-Windows-Kernel-File            {EDD08927-9CC4-4E65-B970-C2560FB5C289}
Microsoft-Windows-Kernel-General         {A68CA8B7-004F-D7B6-A698-07E2DE0F1F5D}
Microsoft-Windows-Kernel-Interrupt-Steering {951B41EA-C830-44DC-A671-E2C9958809B8}
Microsoft-Windows-Kernel-IO              {ABF1F586-2E50-4BA8-928D-49044E6F0DB7}
Microsoft-Windows-Kernel-IoTrace         {A103CABD-8242-4A93-8DF5-1CDF3B3F26A6}
Microsoft-Windows-Kernel-Licensing-StartServiceTrigger {F5528ADA-BE5F-4F14-8AEF-A95DE7281161}
Microsoft-Windows-Kernel-LicensingSqm    {A0AF438F-4431-41CB-A675-A265050EE947}
Microsoft-Windows-Kernel-LiveDump        {BEF2AA8E-81CD-11E2-A7BB-5EAC6188709B}
Microsoft-Windows-Kernel-Memory          {D1D93EF7-E1F2-4F45-9943-03D245FE6C00}
Microsoft-Windows-Kernel-Network         {7DD42A49-5329-4832-8DFD-43D979153A88}
Microsoft-Windows-Kernel-Pep             {5412704E-B2E1-4624-8FFD-55777B8F7373}
Microsoft-Windows-Kernel-PnP             {9C205A39-1250-487D-ABD7-E831C6290539}
Microsoft-Windows-Kernel-PnP-Rundown     {B3A0C2C8-83BB-4DDF-9F8D-4B22D3C38AD7}
Microsoft-Windows-Kernel-Power           {331C3B3A-2005-44C2-AC5E-77220C37D6B4}
Microsoft-Windows-Kernel-PowerTrigger    {AA1F73E8-15FD-45D2-ABFD-E7F64F78EB11}
Microsoft-Windows-Kernel-Prefetch        {5322D61A-9EFA-4BC3-A3F9-14BE95C144F8}
Microsoft-Windows-Kernel-Process         {22FB2CD6-0E7B-422B-A0C7-2FAD1FD0E716}
Microsoft-Windows-Kernel-Processor-Power {0F67E49F-FE51-4E9F-B490-6F2948CC6027}
Microsoft-Windows-Kernel-Registry        {70EB4F03-C1DE-4F73-A051-33D13D5413BD}
Microsoft-Windows-Kernel-ShimEngine      {0BF2FB94-7B60-4B4D-9766-E82F658DF540}
Microsoft-Windows-Kernel-StoreMgr        {A6AD76E3-867A-4635-91B3-4904BA6374D7}
Microsoft-Windows-Kernel-Tm              {4CEC9C95-A65F-4591-B5C4-30100E51D870}
Microsoft-Windows-Kernel-Tm-Trigger      {CE20D1C3-A247-4C41-BCB8-3C7F52C8B805}
Microsoft-Windows-Kernel-WDI             {2FF3E6B7-CB90-4700-9621-443F389734ED}
Microsoft-Windows-Kernel-WHEA            {7B563579-53C8-44E7-8236-0F87B9FE6594}
Microsoft-Windows-Kernel-WSService-StartServiceTrigger {3635D4B6-77E3-4375-8124-D545B7149337}
Microsoft-Windows-Kernel-XDV             {F029AC39-38F0-4A40-B7DE-404D244004CB}
Microsoft-Windows-KernelStreaming        {548C4417-CE45-41FF-99DD-528F01CE0FE1}
Microsoft-Windows-KnownFolders           {8939299F-2315-4C5C-9B91-ABB86AA0627D}
Microsoft-Windows-KPSSVC-WPP             {97A38277-13C0-4394-A0B2-2A70B465D64F}
Microsoft-Windows-L2NACP                 {85FE7609-FF4A-48E9-9D50-12918E43E1DA}
Microsoft-Windows-LanGPA                 {CB070027-1534-4CF3-98EA-B9751F508376}
Microsoft-Windows-LanguagePackSetup      {7237FFF9-A08A-4804-9C79-4A8704B70B87}
Microsoft-Windows-LanguageProfile        {F91577C6-A704-4A0A-A8F5-7D10DFC761DF}
Microsoft-Windows-LDAP-Client            {099614A5-5DD7-4788-8BC9-E29F43DB28FC}
Microsoft-Windows-LimitsManagement       {73AA0094-FACB-4AEB-BD1D-A7B98DD5C799}
Microsoft-Windows-LinkLayerDiscoveryProtocol {DCBFB8F0-CD19-4F1C-A27D-23AC706DED72}
Microsoft-Windows-LiveId                 {05F02597-FE85-4E67-8542-69567AB8FD4F}
Microsoft-Windows-LLTD-Mapper            {CCC64809-6B5F-4C1B-AB39-336904DA9B3B}
Microsoft-Windows-LLTD-MapperIO          {0741C7BE-DAAC-4A5B-B00A-4BD9A2D89D0E}
Microsoft-Windows-LLTD-Responder         {E159FC63-02FE-42F3-A234-028B9B8561CB}
Microsoft-Windows-LoadPerf               {122EE297-BB47-41AE-B265-1CA8D1886D40}
Microsoft-Windows-LUA                    {93C05D69-51A3-485E-877F-1806A8731346}
Microsoft-Windows-Magnification          {C882FF1D-7585-4B33-B135-95C577179137}
Microsoft-Windows-Management-UI          {9B6FE9C5-8691-4257-9E61-E3C6DFD27205}
Microsoft-Windows-ManagementTools-RegistryProvider {8656EA1B-E71C-4EC8-AB69-4EBFF5BAC0F3}
Microsoft-Windows-ManagementTools-TaskManagerProvider {FF562E6C-15D5-4727-A837-1BC1DF33ED7D}
Microsoft-Windows-MCCS-AccountAccessor   {4025D192-273D-42EC-BDF8-940EC34EEDCA}
Microsoft-Windows-MCCS-AccountsHost      {04ECCF8E-8490-4AD1-8ED5-0AE7750E69E6}
Microsoft-Windows-MCCS-AccountsRT        {DD2743C6-1722-4674-9F6F-C80044C4232E}
Microsoft-Windows-MCCS-ActiveSyncCsp     {602A0873-9BDE-48B3-B6B7-277035293458}
Microsoft-Windows-MCCS-ActiveSyncProvider {4A155F10-25AD-47E6-ABA8-2C4F5EEE7846}
Microsoft-Windows-MCCS-DavSyncProvider   {5D86C4E2-8FCD-48D7-A713-9A04609C0189}
Microsoft-Windows-MCCS-EngineShared      {BF460FC6-45C5-4119-ADD3-E361A6E7D5AC}
Microsoft-Windows-MCCS-InternetMail      {618473BC-8EEF-4868-ADFF-A1B640B06411}
Microsoft-Windows-MCCS-InternetMailCsp   {BEC5E7A4-0527-42E8-8174-FABDE799AD7F}
Microsoft-Windows-MCCS-NetworkHelper     {25B99A4C-2F80-4FCD-982D-69CD1F77BADF}
Microsoft-Windows-MCCS-SyncController    {7FCB9791-F481-46D1-846E-2EB6F003C4D3}
Microsoft-Windows-MCCS-SyncUtil          {DCA074CE-547C-4595-AE90-56229B8E3BD9}
Microsoft-Windows-Media-Streaming        {982824E5-E446-46AE-BC74-836401FFB7B6}
Microsoft-Windows-MediaEngine            {8F2048E0-F260-4F57-A8D1-932376291682}
Microsoft-Windows-MediaFoundation-MFCaptureEngine {B8197C10-845F-40CA-82AB-9341E98CFC2B}
Microsoft-Windows-MediaFoundation-MFReadWrite {4B7EAC67-FC53-448C-A49D-7CC6DB524DA7}
Microsoft-Windows-MediaFoundation-MSVProc {A4112D1A-6DFA-476E-BB75-E350D24934E1}
Microsoft-Windows-MediaFoundation-Performance {F404B94E-27E0-4384-BFE8-1D8D390B0AA3}
Microsoft-Windows-MediaFoundation-Performance-Core {B20E65AC-C905-4014-8F78-1B6A508142EB}
Microsoft-Windows-MediaFoundation-Platform {BC97B970-D001-482F-8745-B8D7D5759F99}
Microsoft-Windows-MediaFoundation-PlayAPI {B65471E1-019D-436F-BC38-E15FA8E87F53}
Microsoft-Windows-Memory-Diagnostic-Task-Handler {BABDA89A-4D5E-48EB-AF3D-E0E8410207C0}
Microsoft-Windows-MemoryDiagnostics-Results {5F92BC59-248F-4111-86A9-E393E12C6139}
Microsoft-Windows-MemoryDiagnostics-Schedule {73E9C9DE-A148-41F7-B1DB-4DA051FDC327}
Microsoft-Windows-MF                     {A7364E1A-894F-4B3D-A930-2ED9C8C4C811}
Microsoft-Windows-MFH264Enc              {2A49DE31-8A5B-4D3A-A904-7FC7409AE90D}
Microsoft-Windows-Minstore               {55B24B1D-DD9C-44C0-BA77-4F749F1B6976}
Microsoft-Windows-MiStreamProvider       {018C05B7-0E3B-4C5A-9AB2-553BA1489332}
Microsoft-Windows-MMCSS                  {36008301-E154-466C-ACEC-5F4CBD6B4694}
Microsoft-Windows-Mobile-Broadband-Experience-Api {2E2BBB16-0C36-4B9B-A567-40924A199FD5}
Microsoft-Windows-Mobile-Broadband-Experience-Api-Internal {2AABD03B-F48B-419A-B4CE-7A14403F4A46}
Microsoft-Windows-Mobile-Broadband-Experience-Parser-Task {28E25B07-C47F-473D-8B24-2E171CCA808A}
Microsoft-Windows-Mobile-Broadband-Experience-SmsApi {0FF1C24B-7F05-45C0-ABDC-3C8521BE4F62}
Microsoft-Windows-Mobile-Broadband-Experience-SmsRouter {FA773482-F6ED-4895-8A7D-4F5850678E59}
Microsoft-Windows-MobilityCenter         {91F42016-0B4E-4A4B-9BBB-825D06CBED35}
Microsoft-Windows-mobsync                {B44AEC44-38F4-4B59-8DF3-10306ABF19B2}
Microsoft-Windows-MountMgr               {E3BAC9F8-27BE-4823-8D7F-1CC320C05FA7}
Microsoft-Windows-MP4SDECD               {7F2BD991-AE93-454A-B219-0BC23F02262A}
Microsoft-Windows-MPEG2_DLNA-Encoder     {86EFFF39-2BDD-4EFD-BD0B-853D71B2A9DC}
Microsoft-Windows-Mprddm                 {3A5BEF13-D0F7-4E7F-9EC8-5E707DF711D0}
Microsoft-Windows-MPRMSG                 {F2C628AE-D26C-4352-9C45-74754E1E2F9F}
Microsoft-Windows-MPS-CLNT               {37945DC2-899B-44D1-B79C-DD4A9E57FF98}
Microsoft-Windows-MPS-DRV                {50BD1BFD-936B-4DB3-86BE-E25B96C25898}
Microsoft-Windows-MPS-SRV                {5444519F-2484-45A2-991E-953E4B54C8E0}
Microsoft-Windows-MSDTC                  {719BE4ED-E9BC-4DD8-A7CF-C85CE8E4975D}
Microsoft-Windows-MSDTC 2                {5D9E0020-3761-4F36-90C8-38CE6511BD12}
Microsoft-Windows-MSDTC Client           {7A67066E-193F-4D3A-82D3-322FEE5259DE}
Microsoft-Windows-MSDTC Client 2         {155CB334-3D7F-4FF1-B107-DF8AFC3C0363}
Microsoft-Windows-MSFTEDIT               {9640427C-7D03-4331-B8EE-FB77625BF381}
Microsoft-Windows-MsiServer              {17E92E2A-3D08-413E-BAEB-A79A262BF486}
Microsoft-Windows-MsLbfoEventProvider    {B72C6994-9FE0-45AD-83B3-8F5885F20E0E}
Microsoft-Windows-MsLbfoSysEvtProvider   {387ED463-8B1B-42C9-9EF0-803FDFD5D94E}
Microsoft-Windows-MSMPEG2VDEC            {AE5CF422-786A-476A-AC96-753B05877C99}
Microsoft-Windows-msmpeg2venc            {D17B213A-C505-49C9-98CC-734253EF65D4}
Microsoft-Windows-MSPaint                {1D75856D-36A7-4ECB-A3F5-B13152222D29}
Microsoft-Windows-MUI                    {A8A1F2F6-A13A-45E9-B1FE-3419569E5EF2}
Microsoft-Windows-Narrator               {835B79E2-E76A-44C4-9885-26AD122D3B4D}
Microsoft-Windows-Narrator-Inproc        {C8D49B04-3234-42AE-98F0-F13F336A2F85}
Microsoft-Windows-Ncasvc                 {126DED58-A28D-4113-8E7A-59D7444B2AF1}
Microsoft-Windows-NCSI                   {314DE49F-CE63-4779-BA2B-D616F6963A88}
Microsoft-Windows-NDF-HelperClassDiscovery {FC3BC8A7-2F61-449C-A8B4-22AC22058F92}
Microsoft-Windows-NDIS                   {CDEAD503-17F5-4A3E-B7AE-DF8CC2902EB9}
Microsoft-Windows-NDIS-PacketCapture     {2ED6006E-4729-4609-B423-3EE7BCD678EF}
Microsoft-Windows-NdisImPlatformEventProvider {11C5D8AD-756A-42C2-8087-EB1B4A72A846}
Microsoft-Windows-NdisImPlatformSysEvtProvider {62DE9E48-90C6-4755-8813-6A7D655B0802}
Microsoft-Windows-NetAdapterCim-Diag     {6CC2405D-817F-4886-886F-D5D1643210F0}
Microsoft-Windows-Netshell               {AF2E340C-0743-4F5A-B2D3-2F7225D215DE}
Microsoft-Windows-Network-and-Sharing-Center {6A502821-AB44-40C8-B32F-37315D9D52E0}
Microsoft-Windows-Network-Connection-Broker {3EB875EB-8F4A-4800-A00B-E484C97D7551}
Microsoft-Windows-Network-DataUsage      {5C1C9AB3-8689-4E41-90FA-85858306D7B7}
Microsoft-Windows-Network-Setup          {A111F1C2-5923-47C0-9A68-D0BAFB577901}
Microsoft-Windows-NetworkBridge          {A67075C2-3E39-4109-B6CD-6D750058A731}
Microsoft-Windows-NetworkConnectivityStatus {014DE49F-CE63-4779-BA2B-D616F6963A87}
Microsoft-Windows-NetworkGCW             {BE932B00-0F8E-4386-AB89-873F7D0274AA}
Microsoft-Windows-Networking-Correlation {83ED54F0-4D48-4E45-B16E-726FFD1FA4AF}
Microsoft-Windows-Networking-RealTimeCommunication {1E39B4CE-D1E6-46CE-B65B-5AB05D6CC266}
Microsoft-Windows-NetworkManagerTriggerProvider {9B307223-4E4D-4BF5-9BE8-995CD8E7420B}
Microsoft-Windows-NetworkProfile         {FBCFAC3F-8459-419F-8E48-1F0B49CDB85E}
Microsoft-Windows-NetworkProfileTriggerProvider {FBCFAC3F-8460-419F-8E48-1F0B49CDB85E}
Microsoft-Windows-NetworkProvider        {1E9A4978-78C2-441E-8858-75B5D1326BC5}
Microsoft-Windows-NetworkSecurity        {7B702970-90BC-4584-8B20-C0799086EE5A}
Microsoft-Windows-NetworkStatus          {7868B0D4-1423-4681-AFDF-27913575441E}
Microsoft-Windows-NFC-ClassExtension     {85C070E6-F9AE-481F-AACB-BC550BFD35A1}
Microsoft-Windows-NlaSvc                 {63B530F8-29C9-4880-A5B4-B8179096E7B8}
Microsoft-Windows-Ntfs                   {3FF37A1C-A68D-4D6E-8C9B-F79E8B16C482}
Microsoft-Windows-Ntfs-UBPM              {8E6A5303-A4CE-498F-AFDB-E03A8A82B077}
Microsoft-Windows-NTLM                   {AC43300D-5FCC-4800-8E99-1BD3F85F0320}
Microsoft-Windows-ntshrui                {676F167F-F72C-446E-A498-EDA43319A5E3}
Microsoft-Windows-OfflineFiles           {95353826-4FBE-41D4-9C42-F521C6E86360}
Microsoft-Windows-OfflineFiles-CscApi    {19EE4CF9-5322-4843-B0D8-BAB81BE4E81E}
Microsoft-Windows-OfflineFiles-CscDclUser {D5418619-C167-44D9-BC36-765BEB5D55F3}
Microsoft-Windows-OfflineFiles-CscFastSync {791CD79C-65B5-48A3-804C-786048994F47}
Microsoft-Windows-OfflineFiles-CscNetApi {361F227C-AA14-4D19-9007-0C8D1A8A541B}
Microsoft-Windows-OfflineFiles-CscService {89D89015-C0DF-414C-BC48-F50E114832BC}
Microsoft-Windows-OfflineFiles-CscUM     {5E23B838-5B71-47E6-B123-6FE02EF573EF}
Microsoft-Windows-OLE-Perf               {84958368-7DA7-49A0-B33D-07FABB879626}
Microsoft-Windows-OLEACC                 {19D2C934-EE9B-49E5-AAEB-9CCE721D2C65}
Microsoft-Windows-OneBackup              {72561CF0-C85C-4F78-9E8D-CBA9093DF62D}
Microsoft-Windows-OneX                   {AB0D8EF9-866D-4D39-B83F-453F3B8F6325}
Microsoft-Windows-OOBE-FirstLogonAnim    {2D4C0C5E-6704-493A-A44B-F5ADD4FC9283}
Microsoft-Windows-OOBE-Machine-Core      {EC276CDE-2A17-473C-A010-2FF78D5426D2}
Microsoft-Windows-OOBE-Machine-DUI       {F5DBAA02-15D6-4644-A784-7032D508BF64}
Microsoft-Windows-OOBE-Machine-Plugins   {2F4C4F72-75B8-4F4C-9D97-4CE334ECD3E0}
Microsoft-Windows-OOBE-Machine-Plugins-Wireless {0F352580-E9E2-46C2-8336-6AC66E986416}
Microsoft-Windows-OobeLdr                {75EBC33E-8670-4EB6-B535-3B9D6BB222FD}
Microsoft-Windows-osk                    {4F768BE8-9C69-4BBC-87FC-95291D3F9D0C}
Microsoft-Windows-OtpCredentialProviderEvt {5CAD485A-210F-4C16-80C5-F892DE74E28D}
Microsoft-Windows-OverlayFilter          {46C78E5C-A213-46A8-8A6B-622F6916201D}
Microsoft-Windows-PackageStateRoaming    {5B5AB841-7D2E-4A95-BB4F-095CDF66D8F0}
Microsoft-Windows-Partition              {412BDFF2-A8C4-470D-8F33-63FE0D8C20E2}
Microsoft-Windows-PCI                    {1A9443D4-B099-44D6-8EB1-829B9C2FE290}
Microsoft-Windows-PDC                    {A6BF0DEB-3659-40AD-9F81-E25AF62CE3C7}
Microsoft-Windows-PDFReader              {DFA86FAA-2C55-4140-BFF9-5CC586217A7B}
Microsoft-Windows-PDH                    {04D66358-C4A1-419B-8023-23B73902DE2C}
Microsoft-Windows-PerceptionRuntime      {ADD0DE40-32B0-4B58-9D5E-938B2F5C1D1F}
Microsoft-Windows-PerceptionSensorDataService {85BE49EA-38F1-4547-A604-80060202FB27}
Microsoft-Windows-PerfCtrs               {973143DD-F3C7-4EF5-B156-544AC38C39B6}
Microsoft-Windows-PerfDisk               {7F9D83DE-8ABB-457F-98E8-4AD161449ECC}
Microsoft-Windows-Perflib                {13B197BD-7CEE-4B4E-8DD0-59314CE374CE}
Microsoft-Windows-PerfNet                {CAB2B8A5-49B9-4EEC-B1B0-FAC21DA05A3B}
Microsoft-Windows-Performance-Recorder-Control {36B6F488-AAD7-48C2-AFE3-D4EC2C8B46FA}
Microsoft-Windows-PerfOS                 {F82FB576-E941-4956-A2C7-A0CF83F6450A}
Microsoft-Windows-PerfProc               {72D211E1-4C54-4A93-9520-4901681B2271}
Microsoft-Windows-Photo-Image-Codec      {BE3A31EA-AA6C-4196-9DCC-9CA13A49E09F}
Microsoft-Windows-PhotoAcq               {76CFA528-B26E-B773-62D0-9588270442A6}
Microsoft-Windows-PlayToManager          {BB311100-2D9F-4CD3-B2D6-F4EA3839C548}
Microsoft-Windows-PnPMgrTriggerProvider  {84051B98-F508-4E54-82FA-8865C697C3B1}
Microsoft-Windows-PortableDeviceStatusProvider {8C63B5A5-B484-4381-892D-EDD424582DF7}
Microsoft-Windows-PortableDeviceSyncProvider {A3E1697B-A12C-46B9-84D1-7FFE73C4B678}
Microsoft-Windows-Power-Meter-Polling    {306C4E0B-E148-543D-315B-C618EB93157C}
Microsoft-Windows-Power-Troubleshooter   {CDC05E28-C449-49C6-B9D2-88CF761644DF}
Microsoft-Windows-PowerCfg               {9F0C4EA8-EC01-4200-A00D-B9701CBEA5D8}
Microsoft-Windows-PowerCpl               {B1F90B27-4551-49D6-B2BD-DFC6453762A6}
Microsoft-Windows-PowerShell             {A0C1853B-5C40-4B15-8766-3CF1C58F985A}
Microsoft-Windows-PowerShell-DesiredStateConfiguration-FileDownloadManager {AAF67066-0BF8-469F-AB76-275590C434EE}
Microsoft-Windows-PrimaryNetworkIcon     {8CE93926-BDAE-4409-9155-2FE4799EF4D3}
Microsoft-Windows-PrintBRM               {CF3F502E-B40D-4071-996F-00981EDF938E}
Microsoft-Windows-PrintDialogs           {27E76321-1E5B-4A82-BA0C-26E978F15072}
Microsoft-Windows-PrintDialogs3D         {12DC38E3-E395-4C8E-9156-B5642057F5FA}
Microsoft-Windows-PrintService           {747EF6FD-E535-4D16-B510-42C90F6873A1}
Microsoft-Windows-PrintService-USBMon    {7F812073-B28D-4AFC-9CED-B8010F914EF6}
Microsoft-Windows-ProcessExitMonitor     {FD771D53-8492-4057-8E35-8C02813AF49B}
Microsoft-Windows-Processor-Aggregator   {CBA16CF2-2FAB-49F8-89AE-894E718649E7}
Microsoft-Windows-ProcessStateManager    {D49918CF-9489-4BF1-9D7B-014D864CF71F}
Microsoft-Windows-Program-Compatibility-Assistant {4CB314DF-C11F-47D7-9C04-65FB0051561B}
Microsoft-Windows-propsys                {9485FA1E-23CD-49A1-84E3-11D8BC550CB7}
Microsoft-Windows-Proximity-Common       {28058203-D394-4AFC-B2A6-2F9155A3BB95}
Microsoft-Windows-PushNotifications-Developer {5CAD3597-5FEC-4C62-9CE1-9D7ABC723D3A}
Microsoft-Windows-PushNotifications-InProc {815A1F4A-3F8D-4B37-9B31-5142F9D724A5}
Microsoft-Windows-PushNotifications-Platform {88CD9180-4491-4640-B571-E3BEE2527943}
Microsoft-Windows-QoS-Pacer              {914ED502-B70D-4ADD-B758-95692854F8A3}
Microsoft-Windows-QoS-qWAVE              {6BA132C4-DA49-415B-A7F4-31870DC9FE25}
Microsoft-Windows-QoS-WMI-Diag           {725BA9B3-C1F3-4518-AF1B-C8D669191E15}
Microsoft-Windows-RadioManager           {92061E3D-21CD-45BC-A3DF-0E8AE5E8580A}
Microsoft-Windows-Ras-AgileVpn           {B5325CD6-438E-4EC1-AA46-14F46F2570E4}
Microsoft-Windows-Ras-NdisWanPacketCapture {D84521F7-2235-4237-A7C0-14E3A9676286}
Microsoft-Windows-RasServer              {29D13147-1C2E-48EC-9994-E29DFE496EB3}
Microsoft-Windows-RasSstp                {6C260F2C-049A-43D8-BF4D-D350A4E6611A}
Microsoft-Windows-Rdms-UI                {FB750AD9-8544-427F-B284-8ED9C6C221AE}
Microsoft-Windows-ReadyBoost             {E6307A09-292C-497E-AAD6-498F68E2B619}
Microsoft-Windows-ReFS                   {CD9C6198-BF73-4106-803B-C17D26559018}
Microsoft-Windows-ReFS-v1                {059F0F37-910E-4FF0-A7EE-AE8D49DD319B}
Microsoft-Windows-Registry-SQM-Provider  {017BA13C-9A55-4F1F-8200-323055AAC810}
Microsoft-Windows-Remote-FileSystem-Log  {20C46239-D059-4214-A11E-7D6769CBE020}
Microsoft-Windows-Remote-FileSystem-Monitor {51734B23-5B7E-4892-BA8E-45BC110B735C}
Microsoft-Windows-RemoteApp and Desktop Connections {1B8B402D-78DC-46FB-BF71-46E64AEDF165}
Microsoft-Windows-RemoteDesktopServices-RdpCoreTS {1139C61B-B549-4251-8ED3-27250A1EDEC8}
Microsoft-Windows-RemoteDesktopServices-RemoteFX-Synth3dvsc {3903D5B9-988D-4C31-9CCD-4022F96703F0}
Microsoft-Windows-RemoteDesktopServices-RemoteFX-VM-Kernel-Mode-Transport {7EB5F4CF-A4F6-4E92-AA8F-A8E7EF937745}
Microsoft-Windows-RemoteDesktopServices-RemoteFX-VM-User-Mode-Transport {741C6BE3-F74B-4E4D-88E7-5CE3A35FAEB3}
Microsoft-Windows-RemoteDesktopServices-SessionServices {F1394DE0-32C7-4A76-A6DE-B245E48F4615}
Microsoft-Windows-Remotefs-Rdbss         {1A870028-F191-4699-8473-6FCD299EAB77}
Microsoft-Windows-ResetEng               {A4445C76-ED85-C8A3-02C1-532A38614A9E}
Microsoft-Windows-ResetEng-Trace         {7FA514B5-A023-4B62-A6AB-2946A483E065}
Microsoft-Windows-Resource-Exhaustion-Detector {9988748E-C2E8-4054-85F6-0C3E1CAD2470}
Microsoft-Windows-Resource-Exhaustion-Resolver {91F5FB12-FDEA-4095-85D5-614B495CD9DE}
Microsoft-Windows-ResourcePublication    {74C2135F-CC76-45C3-879A-EF3BB1EEAF86}
Microsoft-Windows-RestartManager         {0888E5EF-9B98-4695-979D-E92CE4247224}
Microsoft-Windows-RPC                    {6AD52B32-D609-4BE9-AE07-CE8DAE937E39}
Microsoft-Windows-RPC-Events             {F4AED7C7-A898-4627-B053-44A7CAA12FCD}
Microsoft-Windows-RPC-FirewallManager    {F997CD11-0FC9-4AB4-ACBA-BC742A4C0DD3}
Microsoft-Windows-RPC-Proxy-LBS          {272A979B-34B5-48EC-94F5-7225A59C85A0}
Microsoft-Windows-RPCSS                  {D8975F88-7DDB-4ED0-91BF-3ADF48C48E0C}
Microsoft-Windows-RRAS                   {24989972-0967-4E21-A926-93854033638E}
Microsoft-Windows-RTWorkQueue-Extended   {83FAAA86-63C8-4DD8-A2DA-FBADDDFC0655}
Microsoft-Windows-RTWorkQueue-Threading  {E18D0FC9-9515-4232-98E4-89E456D8551B}
Microsoft-Windows-Runtime-Graphics       {FA5CF675-72EB-49E2-B447-DE5552FAFF1C}
Microsoft-Windows-Runtime-Media          {8F0DB3A8-299B-4D64-A4ED-907B409D4584}
Microsoft-Windows-Runtime-Networking     {6EB875EB-8F4A-4800-A00B-E484C97D7561}
Microsoft-Windows-Runtime-Networking-BackgroundTransfer {B9D5B35D-BBB8-4625-9450-F71A5D414F4F}
Microsoft-Windows-Runtime-Web-Http       {41877CB4-11FC-4188-B590-712C143C881D}
Microsoft-Windows-Runtime-WebAPI         {6BD96334-DC49-441A-B9C4-41425BA628D8}
Microsoft-Windows-Schannel-Events        {91CC1150-71AA-47E2-AE18-C96E61736B6F}
Microsoft-Windows-ScmBus                 {107754EE-5B5A-4DFF-AFAB-4AFA44C8429E}
Microsoft-Windows-ScmDisk0101            {DB1CC2D9-3197-41A7-9988-AE6ECD877B2E}
Microsoft-Windows-SCPNP                  {9F650C63-9409-453C-A652-83D7185A2E83}
Microsoft-Windows-Sdbus                  {FE28004E-B08F-4407-92B3-BAD3A2C51708}
Microsoft-Windows-SDDC-Management        {7F8DA3B5-A58F-481E-9637-D41435AE6D8B}
Microsoft-Windows-Sdstor                 {AFE654EB-0A83-4EB4-948F-D4510EC39C30}
Microsoft-Windows-Search                 {CA4E628D-8567-4896-AB6B-835B221F373F}
Microsoft-Windows-Search-Core            {49C2C27C-FE2D-40BF-8C4E-C3FB518037E7}
Microsoft-Windows-Search-ProfileNotify   {FC6F77DD-769A-470E-BCF9-1B6555A118BE}
Microsoft-Windows-Search-ProtocolHandlers {DAB065A9-620F-45BA-B5D6-D6BB8EFEDEE9}
Microsoft-Windows-Security-Audit-Configuration-Client {08466062-AED4-4834-8B04-CDDB414504E5}
Microsoft-Windows-Security-Auditing      {54849625-5478-4994-A5BA-3E3B0328C30D}
Microsoft-Windows-Security-EnterpriseData-FileRevocationManager {2CD58181-0BB6-463E-828A-056FF837F966}
Microsoft-Windows-Security-ExchangeActiveSyncProvisioning {9249D0D0-F034-402F-A29B-92FA8853D9F3}
Microsoft-Windows-Security-IdentityListener {3C6C422B-019B-4F48-B67B-F79A3FA8B4ED}
Microsoft-Windows-Security-IdentityStore {00B7E1DF-B469-4C69-9C41-53A6576E3DAD}
Microsoft-Windows-Security-Kerberos      {98E6CFCB-EE0A-41E0-A57B-622D4E1B30B1}
Microsoft-Windows-Security-Netlogon      {E5BA83F6-07D0-46B1-8BC7-7E669A1D31DC}
Microsoft-Windows-Security-SPP           {E23B33B0-C8C9-472C-A5F9-F2BDFEA0F156}
Microsoft-Windows-Security-SPP-UX        {6BDADC96-673E-468C-9F5B-F382F95B2832}
Microsoft-Windows-Security-SPP-UX-GC     {BBBDD6A3-F35E-449B-A471-4D830C8EDA1F}
Microsoft-Windows-Security-SPP-UX-GenuineCenter-Logging {FB829150-CD7D-44C3-AF5B-711A3C31CEDC}
Microsoft-Windows-Security-SPP-UX-Notifications {C4EFC9BB-2570-4821-8923-1BAD317D2D4B}
Microsoft-Windows-Security-UserConsentVerifier {40783728-8921-45D0-B231-919037B4B4FD}
Microsoft-Windows-Security-Vault         {E6C92FB8-89D7-4D1F-BE46-D56E59804783}
Microsoft-Windows-SendTo                 {35642CF5-DA5E-410B-9D9C-A45F3638042B}
Microsoft-Windows-Sens                   {BE69781C-B63B-41A1-8E24-A4FC7B3FC498}
Microsoft-Windows-Sensors                {D8900E18-36CB-4548-966F-13F068D1F78E}
Microsoft-Windows-Serial-ClassExtension  {47BC9477-A8BA-452E-B951-4F2ED3593CF9}
Microsoft-Windows-Serial-ClassExtension-V2 {EEE173EF-7ED2-45DE-9877-01C70A852FBD}
Microsoft-Windows-ServerEssentials-Deployment {AD9FC988-EB6F-43AF-9429-7BCDB78A7663}
Microsoft-Windows-ServerManager-ConfigureSMRemoting {6E27F02D-8A55-477E-88B5-6F1BA07E14B4}
Microsoft-Windows-ServerManager-DeploymentProvider {66AF9A38-2D94-11E0-A076-8534E0D72085}
Microsoft-Windows-ServerManager-ManagementProvider {C2E6D0D9-5DF8-4C77-A82B-C96C84579543}
Microsoft-Windows-ServerManager-MultiMachine {D8D37081-10BD-4A89-A971-1CDA6899BDB3}
Microsoft-Windows-ServiceReportingApi    {606A6A38-70EC-4309-B3A3-82FF86F73329}
Microsoft-Windows-Services               {0063715B-EEDA-4007-9429-AD526F62696E}
Microsoft-Windows-Services-Svchost       {06184C97-5201-480E-92AF-3A3626C5B140}
Microsoft-Windows-ServiceTriggerPerfEventProvider {6545939F-3398-411A-88B7-6A8914B8CEC7}
Microsoft-Windows-Servicing              {BD12F3B8-FC40-4A61-A307-B7A013A069C1}
Microsoft-Windows-SettingSync            {83D6E83B-900B-48A3-9835-57656B6F6474}
Microsoft-Windows-SettingSync-Azure      {9F973C1D-D056-4E38-84A5-7BE81CDD6AB6}
Microsoft-Windows-SettingSync-Desktop    {579402A2-883C-45D8-B70A-9BC856407751}
Microsoft-Windows-Setup                  {75EBC33E-997F-49CF-B49F-ECC50184B75D}
Microsoft-Windows-SetupCl                {75EBC33E-D017-4D0F-93AB-0B4F86579164}
Microsoft-Windows-SetupPlatform          {530FB9B9-C515-4472-9313-FB346F9255E3}
Microsoft-Windows-SetupQueue             {A615ACB9-D5A4-4738-B561-1DF301D207F8}
Microsoft-Windows-SetupUGC               {75EBC33E-0870-49E5-BDCE-9D7028279489}
Microsoft-Windows-SharedAccess_NAT       {A6F32731-9A38-4159-A220-3D9B7FC5FE5D}
Microsoft-Windows-Shell-AppWizCpl        {08D945EB-C8BD-44AA-994F-86079D8DCE35}
Microsoft-Windows-Shell-AuthUI           {63D2BB1D-E39A-41B8-9A3D-52DD06677588}
Microsoft-Windows-Shell-ConnectedAccountState {6DF57621-E7E4-410F-A7E9-E43EEB61B11F}
Microsoft-Windows-Shell-Core             {30336ED4-E327-447C-9DE0-51B652C86108}
Microsoft-Windows-Shell-DefaultPrograms  {65D99466-7A8E-489C-B8E1-962BC945031E}
Microsoft-Windows-Shell-LockScreenContent {A3C0D58A-9FE5-4F24-A2CE-E16DE8BAA0D2}
Microsoft-Windows-Shell-OpenWith         {11BD2A68-77FF-4991-9658-F451F2EB6CE1}
Microsoft-Windows-Shell-Search-UriHandler {606C6FE0-A9DC-4A9D-BDEA-830AFF6716E7}
Microsoft-Windows-Shell-Shwebsvc         {F61CEFC0-AA2E-11DA-A746-0800200C9A66}
Microsoft-Windows-Shell-ZipFolder        {1F84007D-19CE-4B15-9E81-8A3DD8EB9ECB}
Microsoft-Windows-Shsvcs                 {059C3E04-5535-4929-85E1-93030E78F47B}
Microsoft-Windows-SleepStudy             {D37687E7-8BF0-4D11-B589-A7ABE080756A}
Microsoft-Windows-SmartCard-Audit        {09AC07B9-6AC9-43BC-A50F-58419A797C69}
Microsoft-Windows-SmartCard-DeviceEnum   {AAEAC398-3028-487C-9586-44EACAD03637}
Microsoft-Windows-Smartcard-Server       {4FCBF664-A33A-4652-B436-9D558983D955}
Microsoft-Windows-SmartCard-TPM-VCard-Module {125F2CF1-2768-4D33-976E-527137D080F8}
Microsoft-Windows-Smartcard-Trigger      {AEDD909F-41C6-401A-9E41-DFC33006AF5D}
Microsoft-Windows-SMBClient              {988C59C5-0A1C-45B6-A555-0C62276E327D}
Microsoft-Windows-SMBDirect              {DB66EA65-B7BB-4CA9-8748-334CB5C32400}
Microsoft-Windows-SMBServer              {D48CE617-33A2-4BC3-A5C7-11AA4F29619E}
Microsoft-Windows-SMBWitnessClient       {32254F6C-AA33-46F0-A5E3-1CBCC74BF683}
Microsoft-Windows-SmbWmiProvider         {50B9E206-9D55-4092-92E8-F157A8235799}
Microsoft-Windows-SoftwareInventoryLogging-Provider {51F092C6-6573-4A9B-A7FC-A245AE653BD1}
Microsoft-Windows-SoftwareRestrictionPolicies {7D29D58A-931A-40AC-8743-48C733045548}
Microsoft-Windows-SPB-ClassExtension     {72CD9FF7-4AF8-4B89-AEDE-5F26FDA13567}
Microsoft-Windows-SPB-HIDI2C             {991F8FE6-249D-44D6-B93D-5A3060C1DEDB}
Microsoft-Windows-Speech-TTS             {74DCC47A-846E-4C98-9E2C-80043ED82B15}
Microsoft-Windows-Speech-UserExperience  {13480A22-D79F-4334-9D32-AA239398AD3C}
Microsoft-Windows-Spell-Checking         {D0E22EFC-AC66-4B25-A72D-382736B5E940}
Microsoft-Windows-SpellChecker           {B2FCD41F-9A40-4150-8C92-B224B7D8C8AA}
Microsoft-Windows-Spellchecking-Host     {1BDA2AB1-BBC1-4ACB-A849-C0EF2B249672}
Microsoft-Windows-SrumTelemetry          {48D445A8-2F64-4D49-B093-A5774D8DC531}
Microsoft-Windows-StackDB                {BF47012D-4413-4285-ACD3-278DF0342947}
Microsoft-Windows-StartLmhosts           {2D7904D8-5C90-4209-BA6A-4C08F409934C}
Microsoft-Windows-StartupRepair          {C914F0DF-835A-4A22-8C70-732C9A80C634}
Microsoft-Windows-StateRepository        {89592015-D996-4636-8F61-066B5D4DD739}
Microsoft-Windows-stobject               {86133982-63D7-4741-928E-EF1349B80219}
Microsoft-Windows-Storage-Tiering        {4A104570-EC6D-4560-A40F-858FA955E84F}
Microsoft-Windows-Storage-Tiering-IoHeat {990C55FC-2662-47F6-B7D7-EB3C027CB13F}
Microsoft-Windows-StorageManagement      {7E58E69A-E361-4F06-B880-AD2F4B64C944}
Microsoft-Windows-StorageManagement-WSP-FS {435F8E4B-8CC4-430E-9796-28CAE4976576}
Microsoft-Windows-StorageManagement-WSP-Host {595F33EA-D4AF-4F4D-B4DD-9DACDD17FC6E}
Microsoft-Windows-StorageManagement-WSP-Spaces {88C09888-118D-48FC-8863-E1C6D39CA4DF}
Microsoft-Windows-StorageSpaces-Driver   {595F7F52-C90A-4026-A125-8EB5E083F15E}
Microsoft-Windows-StorageSpaces-ManagementAgent {AA4C798D-D91B-4B07-A013-787F5803D6FC}
Microsoft-Windows-StorageSpaces-SpaceManager {69C8CA7E-1ADF-472B-BA4C-A0485986B9F6}
Microsoft-Windows-StorDiag               {F5D05B38-80A6-4653-825D-C414E4AB3C68}
Microsoft-Windows-Store                  {9C2A37F3-E5FD-5CAE-BCD1-43DAFEEE1FF0}
Microsoft-Windows-StorPort               {C4636A1E-7986-4646-BF10-7BC3B4A76E8E}
Microsoft-Windows-StorSqm                {1BE1A88D-8E34-4170-9123-F503375BBCEF}
Microsoft-Windows-Subsys-Csr             {E8316A2D-0D94-4F52-85DD-1E15B66C5891}
Microsoft-Windows-Subsys-SMSS            {43E63DA5-41D1-4FBF-ADED-1BBED98FDD1D}
Microsoft-Windows-Superfetch             {99806515-9F51-4C2F-B918-1EAE407AA8CB}
Microsoft-Windows-Sysprep                {75EBC33E-77B8-4BA8-9474-4F4A9DB2F5C6}
Microsoft-Windows-System-Profile-HardwareId {3419DE6D-5D7F-4668-ACC8-F80566814D96}
Microsoft-Windows-SystemEventsBroker     {B6BFCC79-A3AF-4089-8D4D-0EECB1B80779}
Microsoft-Windows-SystemSettingsThreshold {8BCDF442-3070-4118-8C94-E8843BE363B3}
Microsoft-Windows-TabletPC-CoreInkRecognition {C2FA0899-8A10-412B-A42E-9E5B284A2437}
Microsoft-Windows-TabletPC-InputPanel    {E978F84E-582D-4167-977E-32AF52706888}
Microsoft-Windows-TabletPC-InputPersonalization {A8106E5C-293A-4CD0-9397-2E6FAC7F9749}
Microsoft-Windows-TabletPC-MathInput     {8443CCB7-FEB0-4B8D-8E28-8D4C7CB814E8}
Microsoft-Windows-TabletPC-MathRecognizer {BDB462FC-A297-49A2-BF2E-4F1809E12ABC}
Microsoft-Windows-TabletPC-Platform-Input-Core {B5FD844A-01D4-4B10-A57F-58B13B561582}
Microsoft-Windows-TabletPC-Platform-Input-Ninput {2C3E6D9F-8298-450F-8E5D-49B724F1216F}
Microsoft-Windows-TabletPC-Platform-Input-Wisp {E5AA2A53-30BE-40F5-8D84-AD3F40A404CD}
Microsoft-Windows-TabletPC-Platform-Manipulations {2FD7A9A5-B1A1-4FC7-B95C-C32FED818F30}
Microsoft-Windows-TaskbarCPL             {05D7B0F0-2121-4EFF-BF6B-ED3F69B894D7}
Microsoft-Windows-TaskScheduler          {DE7B24EA-73C8-4A09-985D-5BDADCFA9017}
Microsoft-Windows-TCPIP                  {2F07E2EE-15DB-40F1-90EF-9D7BA282188A}
Microsoft-Windows-Tcpip-SQM-Provider     {C8F7689F-3692-4D66-B0C0-9536D21082C9}
Microsoft-Windows-Telephony-PhoneOm      {E08C85F4-C224-499D-B5B3-C1BCE960F096}
Microsoft-Windows-Telephony-PhoneProviders {1DB8DAD0-7CA6-4F18-B357-43BFDD8C9806}
Microsoft-Windows-Telephony-PhoneService {CBBBC22D-2EFE-4EAE-9AF5-F9C6CF113670}
Microsoft-Windows-Telephony-PhoneUtil    {04A490D4-84C6-4920-9C22-51C80825FF2C}
Microsoft-Windows-Telephony-TelephonyInteractiveUser {088A803B-578D-41B1-9402-92B7CEB380C8}
Microsoft-Windows-Telephony-VoipRT       {BD1A62ED-263B-4A66-A574-1F43C79C64BE}
Microsoft-Windows-TerminalServices-ClientActiveXCore {28AA95BB-D444-4719-A36F-40462168127E}
Microsoft-Windows-TerminalServices-ClientUSBDevices {6E400999-5B82-475F-B800-CEF6FE361539}
Microsoft-Windows-TerminalServices-LocalSessionManager {5D896912-022D-40AA-A3A8-4FA5515C76D7}
Microsoft-Windows-TerminalServices-MediaRedirection {3F7B2F99-B863-4045-AD05-F6AFB62E7AF1}
Microsoft-Windows-TerminalServices-PnPDevices {27A8C1E2-EB19-463E-8424-B399DF27A216}
Microsoft-Windows-TerminalServices-Printers {952773BF-C2B7-49BC-88F4-920744B82C43}
Microsoft-Windows-TerminalServices-RdpSoundDriver {127E0DC5-E13B-4935-985E-78FD508B1D80}
Microsoft-Windows-TerminalServices-RemoteConnectionManager {C76BAA63-AE81-421C-B425-340B4B24157F}
Microsoft-Windows-TerminalServices-ServerUSBDevices {DCBE5AAA-16E2-457C-9337-366950045F0A}
Microsoft-Windows-TerminalServices-SessionBroker-Client {2184B5C9-1C83-4304-9C58-A9E76F718993}
Microsoft-Windows-Tethering-Manager      {CC311F1F-623C-4CA4-BA44-A458016555E8}
Microsoft-Windows-TextPredictionEngine   {39A63500-7D76-49CD-994F-FFD796EF5A53}
Microsoft-Windows-ThemeCPL               {61F044AF-9104-4CA5-81EE-CB6C51BB01AB}
Microsoft-Windows-ThemeUI                {869FB599-80AA-485D-BCA7-DB18D72B7219}
Microsoft-Windows-Thermal-Polling        {E8A7C168-81EE-465C-8E8E-D39A2AC1CA41}
Microsoft-Windows-Time-Service           {06EDCFEB-0FD0-4E53-ACCA-A6F8BBF81BCB}
Microsoft-Windows-TimeBroker             {0657ADC1-9AE8-4E18-932D-E6079CDA5AB3}
Microsoft-Windows-TPM-WMI                {7D5387B0-CBE0-11DA-A94D-0800200C9A66}
Microsoft-Windows-TriggerEmulatorProvider {F230D19A-5D93-47D9-A83F-53829EDFB8DF}
Microsoft-Windows-TSF-msctf              {4FBA1227-F606-4E5F-B9E8-FAB9AB5740F3}
Microsoft-Windows-TSF-msutb              {74B655A2-8958-410E-80E2-3457051B8DFF}
Microsoft-Windows-TSF-UIManager          {4DD778B8-379C-4D8C-B659-517A43D6DF7D}
Microsoft-Windows-TunnelDriver           {4EDBE902-9ED3-4CF0-93E8-B8B5FA920299}
Microsoft-Windows-TunnelDriver-SQM-Provider {4214DCD2-7C33-4F74-9898-719CCCEEC20F}
Microsoft-Windows-TZSync                 {3527CB55-1298-49D4-AB94-1243DB0FCAFF}
Microsoft-Windows-TZUtil                 {2D318B91-E6E7-4C46-BD04-BFE6DB412CF9}
Microsoft-Windows-UAC                    {E7558269-3FA5-46ED-9F4D-3C6E282DDE55}
Microsoft-Windows-UAC-FileVirtualization {C02AFC2B-E24E-4449-AD76-BCC2C2575EAD}
Microsoft-Windows-UI-Input-Inking        {BF1DB390-3E67-4D4D-A287-8958044A3DB4}
Microsoft-Windows-UI-Search              {D8965FCF-7397-4E0E-B750-21A4580BD880}
Microsoft-Windows-UI-Shell               {E3EE1525-8742-4E05-871B-DD2A60330C53}
Microsoft-Windows-UIAnimation            {E0A40B26-30C4-4656-BC9A-74A5C3A0B2EC}
Microsoft-Windows-UIAutomationCore       {820A42D8-38C4-465D-B64E-D7D56EA1D612}
Microsoft-Windows-UIRibbon               {87D476FE-1A0F-4370-B785-60B028019693}
Microsoft-Windows-UniversalTelemetryClient {6489B27F-7C43-5886-1D00-0A61BB2A375B}
Microsoft-Windows-URLMon                 {245F975D-909D-49ED-B8F9-9A75691D6B6B}
Microsoft-Windows-USB-UCX                {36DA592D-E43A-4E28-AF6F-4BC57C5A11E8}
Microsoft-Windows-USB-USBHUB             {7426A56B-E2D5-4B30-BDEF-B31815C1A74A}
Microsoft-Windows-USB-USBHUB3            {AC52AD17-CC01-4F85-8DF5-4DCE4333C99B}
Microsoft-Windows-USB-USBPORT            {C88A4EF5-D048-4013-9408-E04B7DB2814A}
Microsoft-Windows-USB-USBXHCI            {30E1D284-5D88-459C-83FD-6345B39B19EC}
Microsoft-Windows-Usbstor                {77E27CE0-F816-4C53-B601-2C042A883A78}
Microsoft-Windows-User Device Registration {23B8D46B-67DD-40A3-B636-D43E50552C6D}
Microsoft-Windows-User Profiles General  {DB00DFB6-29F9-4A9C-9B3B-1F4F9E7D9770}
Microsoft-Windows-User Profiles Service  {89B1E9F0-5AFF-44A6-9B44-0A07A7CE5845}
Microsoft-Windows-User-ControlPanel      {319122A9-1485-4E48-AF35-7DB2D93B8AD2}
Microsoft-Windows-User-Diagnostic        {305FC87B-002A-5E26-D297-60223012CA9C}
Microsoft-Windows-User-Loader            {B059B83F-D946-4B13-87CA-4292839DC2F2}
Microsoft-Windows-UserAccessLogging      {7009DE1B-8648-4797-BCF4-CF0B4A7EC148}
Microsoft-Windows-UserAccountControl     {2683B597-3CCA-410A-97FE-6F7EE3D09B94}
Microsoft-Windows-UserDataAccess-CallHistoryClient {F5988ABB-323A-4098-8A34-85A3613D4638}
Microsoft-Windows-UserDataAccess-CEMAPI  {83A9277A-D2FC-4B34-BF81-8CEB4407824F}
Microsoft-Windows-UserDataAccess-PimIndexMaintenance {99C66BA7-5A97-40D5-AA01-8A07FB3DB292}
Microsoft-Windows-UserDataAccess-Poom    {0BD19909-EB6F-4B16-8074-6DCE803F091D}
Microsoft-Windows-UserDataAccess-UnifiedStore {56F519AB-9DF6-4345-8491-A4BA21AC825B}
Microsoft-Windows-UserDataAccess-UserDataApis {B9B2DE3C-3FBD-4F42-8FF7-33C3BAD35FD4}
Microsoft-Windows-UserDataAccess-UserDataService {FB19EE2C-0D22-4A2E-969E-DD41AE0CE1A9}
Microsoft-Windows-UserDataAccess-UserDataUtils {D1F688BF-012F-4AEC-A38C-E7D4649F8CD2}
Microsoft-Windows-UserModePowerService   {CE8DEE0B-D539-4000-B0F8-77BED049C590}
Microsoft-Windows-UserPnp                {96F4A050-7E31-453C-88BE-9634F4E02139}
Microsoft-Windows-UxInit                 {4154A29C-40D9-445F-8D65-24DA473E8F65}
Microsoft-Windows-UxTheme                {422088E6-CD0C-4F99-BD0B-6985FA290BDF}
Microsoft-Windows-VAN                    {01578F96-C270-4602-ADE0-578D9C29FC0C}
Microsoft-Windows-VDRVROOT               {E4480490-85B6-11DD-AD8B-0800200C9A66}
Microsoft-Windows-VerifyHardwareSecurity {F3F53C76-B06D-4F15-B412-61164A0D2B73}
Microsoft-Windows-VHDMP                  {E2816346-87F4-4F85-95C3-0C79409AA89D}
Microsoft-Windows-Video-For-Windows      {712ABB2D-D806-4B42-9682-26DA01D8B307}
Microsoft-Windows-Volume                 {9F7B5DF4-B902-48BC-BC94-95068C6C7D26}
Microsoft-Windows-VolumeControl          {07DE7879-1C96-41CE-AFBD-C659A0E8E643}
Microsoft-Windows-VolumeSnapshot-Driver  {67FE2216-727A-40CB-94B2-C02211EDB34A}
Microsoft-Windows-VPN-Client             {3C088E51-65BE-40D1-9B90-62BFEC076737}
Microsoft-Windows-W3LOGSVC               {FF6656CF-35A8-4194-A817-F79C7FDEF697}
Microsoft-Windows-WABSyncProvider        {17F14A23-551D-40CC-A086-E4194D64ED4C}
Microsoft-Windows-Wallet                 {6ED11B00-C1B5-48CB-AECC-FF72EBEFBAE8}
Microsoft-Windows-WAS                    {524B5D04-133C-4A62-8362-64E8EDB9CE40}
Microsoft-Windows-WAS-ListenerAdapter    {D60ACC81-2608-4617-BFB7-2452BF002430}
Microsoft-Windows-Wcmsvc                 {67D07935-283A-4791-8F8D-FA9117F3E6F2}
Microsoft-Windows-WCN-Config-Registrar   {C100BECF-D33A-4A4B-BF23-BBEF4663D017}
Microsoft-Windows-WCN-Config-Registrar-Secure {C100BECC-D33A-4A4B-BF23-BBEF4663D017}
Microsoft-Windows-WCNWiz                 {E8AA5402-26A1-455E-A21B-F240ED62D155}
Microsoft-Windows-WebAuth                {DB6972B6-DDDF-4820-84B1-2ED6AC0B96E5}
Microsoft-Windows-WebcamExperience       {9E12CEB1-E3FF-46AD-A0AA-11738B122D20}
Microsoft-Windows-WebIO                  {50B3E73C-9370-461D-BB9F-26F32D68887D}
Microsoft-Windows-WebServices            {E04FE2E0-C6CF-4273-B59D-5C97C9C374A4}
Microsoft-Windows-Websocket-Protocol-Component {CBA5F63C-E2CF-4B36-8305-BDE1311924FC}
Microsoft-Windows-WEPHOSTSVC             {D5F7235B-48E2-4E9C-92FE-0E4950ABA9E8}
Microsoft-Windows-WER-Diag               {AD8AA069-A01B-40A0-BA40-948D1D8DEDC5}
Microsoft-Windows-WER-SystemErrorReporting {ABCE23E7-DE45-4366-8631-84FA6C525952}
Microsoft-Windows-WFP                    {0C478C5B-0351-41B1-8C58-4A6737DA32E3}
Microsoft-Windows-WHEA-Logger            {C26C4F3C-3F66-4E99-8F8A-39405CFED220}
Microsoft-Windows-Win32k                 {8C416C79-D49B-4F01-A467-E56D3AA8234C}
Microsoft-Windows-Windeploy              {75EBC33E-C8AE-4F93-9CA1-683A53E20CB6}
Microsoft-Windows-Windows Defender       {11CD958A-C507-4EF3-B3F2-5FD9DFBD2C78}
Microsoft-Windows-Windows Firewall With Advanced Security {D1BC9AFF-2ABF-4D71-9146-ECB2A986EB85}
Microsoft-Windows-WindowsColorSystem     {D53270E3-C8CF-4707-958A-DAD20C90073C}
Microsoft-Windows-WindowsSystemAssessmentTool {11A75546-3234-465E-BEC8-2D301CB501AC}
Microsoft-Windows-WindowsToGo-StartupOptions {2E6CB42E-161D-413B-A6C1-84CA4C1E5890}
Microsoft-Windows-WindowsUIImmersive     {74827CBB-1E0F-45A2-8523-C605866D2F22}
Microsoft-Windows-WindowsUpdateClient    {945A8954-C147-4ACD-923F-40C45405A658}
Microsoft-Windows-WinHttp                {7D44233D-3055-4B9C-BA64-0D47CA40A232}
Microsoft-Windows-WinINet                {43D1A55C-76D6-4F7E-995C-64C711E5CAFE}
Microsoft-Windows-WinINet-Capture        {A70FF94F-570B-4979-BA5C-E59C9FEAB61B}
Microsoft-Windows-WinINet-Config         {5402E5EA-1BDD-4390-82BE-E108F1E634F5}
Microsoft-Windows-Wininit                {206F6DEA-D3C5-4D10-BC72-989F03C8B84B}
Microsoft-Windows-Winlogon               {DBE9B383-7CF3-4331-91CC-A3CB16A3B538}
Microsoft-Windows-WinMDE                 {77549803-7BB1-418B-A98E-F2E22F35A873}
Microsoft-Windows-WinNat                 {66C07ECD-6667-43FC-93F8-05CF07F446EC}
Microsoft-Windows-WinRM                  {A7975C8F-AC13-49F1-87DA-5A984A4AB417}
Microsoft-Windows-WinRT-Error            {A86F8471-C31D-4FBC-A035-665D06047B03}
Microsoft-Windows-Winsock-AFD            {E53C6823-7BB8-44BB-90DC-3F86090D48A6}
Microsoft-Windows-Winsock-NameResolution {55404E71-4DB9-4DEB-A5F5-8F86E46DDE56}
Microsoft-Windows-Winsock-SQM            {093DA50C-0BB9-4D7D-B95C-3BB9FCDA5EE8}
Microsoft-Windows-Winsock-WS2HELP        {D5C25F9A-4D47-493E-9184-40DD397A004D}
Microsoft-Windows-Winsrv                 {9D55B53D-449B-4824-A637-24F9D69AA02F}
Microsoft-Windows-Wired-AutoConfig       {B92CF7FD-DC10-4C6B-A72D-1613BF25E597}
Microsoft-Windows-WLAN-MediaManager      {323DAD74-D3EC-44A8-8B9D-CAFEB4999274}
Microsoft-Windows-WlanConn               {239CFB83-CBB7-4BBC-A02E-9BDB496AA7C2}
Microsoft-Windows-WLGPA                  {46098845-8A94-442D-9095-366A6BCFEFA9}
Microsoft-Windows-WMI                    {1EDEEE53-0AFE-4609-B846-D8C0B2075B1F}
Microsoft-Windows-WMI-Activity           {1418EF04-B0B4-4623-BF7E-D74AB47BBDAA}
Microsoft-Windows-WMP                    {F3F14FF3-7B80-4868-91D0-D77E497B025E}
Microsoft-Windows-WMP-Setup_WM           {0D759F0F-CFF9-4902-8867-EB9E29D7A98B}
Microsoft-Windows-WMPDMCUI               {3F9E07BD-0E26-4241-A5A5-28CAFA150A75}
Microsoft-Windows-wmvdecod               {55BACC9F-9AC0-46F5-968A-A5A5DD024F8A}
Microsoft-Windows-WMVENCOD               {313B0545-BF9C-492E-9173-8DE4863B8573}
Microsoft-Windows-Wordpad                {54FFD262-99FE-4576-96E7-1ADB500370DC}
Microsoft-Windows-Workplace Join         {76AB12D5-C986-4E60-9D7C-2A092B284CDD}
Microsoft-Windows-WPD-API                {31569DCF-9C6F-4B8E-843A-B7C1CC7FFCBA}
Microsoft-Windows-WPD-CompositeClassDriver {355C44FE-0C8E-4BF8-BE28-8BC7B5A42720}
Microsoft-Windows-WPD-MTPBT              {92AB58D3-F351-4AF5-9C72-D52F36EE2C92}
Microsoft-Windows-WPD-MTPClassDriver     {21B7C16E-C5AF-4A69-A74A-7245481C1B97}
Microsoft-Windows-WPD-MTPIP              {C374D21E-69B2-4CD7-9A25-62187C5A5619}
Microsoft-Windows-WPD-MTPUS              {DCFC4489-9CE0-403C-99DF-A05422C60898}
Microsoft-Windows-WPDClassInstaller      {AD5162D8-DAF0-4A25-88A7-01CBEB33902E}
Microsoft-Windows-WUSA                   {09608C12-C1DA-4104-A6FE-B959CF57560A}
Microsoft-Windows-WWAN-NDISUIO-EVENTS    {B3EEE223-D0A9-40CD-ADFC-50F1888138AB}
Microsoft-Windows-XAML                   {531A35AB-63CE-4BCF-AA98-F88C7A89E455}
Microsoft-Windows-XAML-Diagnostics       {59E7A714-73A4-4147-B47E-0957048C75C4}
Microsoft-Windows-XAudio2                {1EE3ABDB-C1FC-4B43-9E56-11064ABBA866}
Microsoft-Windows-XWizards               {777BA8FE-2498-4875-933A-3067DE883070}
Microsoft-WindowsPhone-CoreMessaging     {922CDCF3-6123-42DA-A877-1A24F23E39C5}
Microsoft-WindowsPhone-CoreUIComponents  {A0B7550F-4E9A-4F03-AD41-B8042D06A2F7}
Microsoft-WindowsPhone-LocationServiceProvider {4D13548F-C7B8-4174-BB7A-D7F64BF22D29}
Microsoft-WindowsPhone-Ufx               {E98EBDBF-3058-4784-8521-47860B1D2B8E}
Microsoft.Windows.ResourceManager        {4180C4F7-E238-5519-338F-EC214F0B49AA}
MMC                                      {9C88041D-349D-4647-8BFD-2C0A167BFE58}
Mobility Center Performance Trace        {8A8B5246-6EB6-4339-8B59-B0085B9F4890}
Mobility Center Trace                    {082DFF20-F430-11D9-8CD6-0800200C9A66}
Mount Manager Trace                      {467C1914-37F0-4C7D-B6DB-5CD7DFE7BD5E}
MSADCE.1                                 {76DBA919-5A36-FC80-2CAD-3185532B7CB1}
MSADCF.1                                 {101C0E21-EBBA-A60A-EC3D-58797788928A}
MSADCO.1                                 {5C6CE734-1B3E-705E-C2AB-B272D99AAF8F}
MSADDS.1                                 {13CD7F92-5BAA-8C7C-3D72-B69FAC139A46}
MSADOX.1                                 {6C770D53-0441-AFD4-DCAB-1D89155FECFC}
MSDADIAG.ETW                             {8B98D3F2-3CC6-0B9C-6651-9649CCE5C752}
MSDAPRST.1                               {64A552E0-6C60-B907-E59C-10F1DFF76B0D}
MSDAREM.1                                {564F1E24-FC86-28E1-74F8-5CA0D950BEE0}
MSDART.1                                 {CEB7253C-BB96-9DFE-51D1-53D966D0CF8B}
MSDASQL_1                                {B6501BA0-C61A-C4E6-6FA2-A4E7F8C8E7A0}
MSDATL3.1                                {87B93A44-1F73-EC83-7261-2DFC972D9B1E}
msiscsi_iScsi                            {1BABEFB4-59CB-49E5-9698-FD38AC830A91}
MUI Resource Trace                       {D3DE60B2-A663-45D5-9826-A0A5949D2CB0}
NetJoin                                  {9741FD4E-3757-479F-A3C6-FC49F6D5EDD0}
Network Location Awareness Trace         {1AC55562-D4FF-4BC5-8EF3-A18E07C4668E}
Network Profile Manager                  {D9131565-E1DD-4C9E-A728-951999C2ADB5}
NisDrvWFP Provider                       {49D6AD7B-52C4-4F79-A164-4DCD908391E4}
Ntfs                                     {DD70BC80-EF44-421B-8AC3-CD31DA613A4E}
Ntfs_NtfsLog                             {B2FC00C4-2941-4D11-983B-B16E8AA4E25D}
NTLM Security Protocol                   {C92CF544-91B3-4DC0-8E11-C580339A0BF8}
ODBC.1                                   {F34765F6-A1BE-4B9D-1400-B8A12921F704}
ODBCBCP.1                                {932B59F1-90C2-D8BA-0956-3975C344AE2B}
OLEDB.1                                  {0DD082C4-66F2-271F-74BA-2BF1F9F65C66}
Partition Manager Trace                  {0BEE3BC5-A50C-4EC3-A0E0-5AD11F2455A3}
PNPX AssocDB Trace                       {7311AD03-18D6-45AC-9B08-B020BDD6A590}
Portable Device Connectivity API Trace   {02FE721A-0725-469E-A26D-37B3C09FAAC1}
PrintFilterPipelineSvc_ObjectsGuid       {AEFE45F4-8548-42B4-B1C8-25673B07AD8B}
RdpCore Api Trace                        {D4199645-41BE-4FD5-9D71-A612C508FDC6}
RDPEncComTrace                           {D4199645-41BE-4FD5-9D71-A612C508FDC7}
Refsv1WppTrace                           {6D2FD9C5-8BD8-4A5D-8AA8-01E5C3B2AE23}
RefsWppTrace                             {740F3C34-57DF-4BAD-8EEA-72AC69AD5DF5}
RmClient_RestartManager                  {0888E5EF-9B98-4695-979D-E92CE4247224}
RowsetHelper.1                           {74A75B02-36D8-EDE6-D10E-95B691503408}
RSS Platform Backgroundsync Perf Trace   {CA1CF55C-9E49-4AD3-8038-39CB6F66AF11}
RSS Platform Backgroundsync Trace        {F59D1D86-CC03-4736-BC9C-4C7936871B3D}
RSS Platform Perf Trace                  {2B240425-3141-43EE-931F-EC9F997C7D7E}
RSS Platform Trace                       {8C50FA6E-394E-4B47-B6D1-A880A5F225A2}
SBP2 Port Driver Tracing Provider        {6710597F-7319-4AAE-9B85-C8D87136A56B}
Schannel                                 {1F678132-5938-4686-9FDC-C8FF68F15C85}
SD Bus Trace                             {3B9E3DA4-70B8-46D3-9EF2-3DDF128BDED8}
Security: Kerberos Authentication        {6B510852-3583-4E2D-AFFE-A67F9F223438}
Security: NTLM Authentication            {5BBB6C18-AA45-49B1-A15F-085F7ED0AA90}
Security: SChannel                       {37D2C3CD-C5D4-4587-8531-4696C44244C8}
Security: TSPkg                          {6165F3E2-AE38-45D4-9B23-6B4818758BD9}
Security: WDigest                        {FB6A424F-B5D6-4329-B9D5-A975B3A93EAD}
Sensor ClassExtension Trace              {A1E89BB0-EF73-4980-8C99-DD15F7271D7E}
Service Control Manager                  {555908D1-A6D7-4695-8E1E-26931D2012F4}
Service Control Manager Trace            {EBCCA1C2-AB46-4A1D-8C2A-906C2FF25F39}
SetupAPI Trace                           {A676B545-4CFB-4306-A067-502D9A0F2220}
SQLOLEDB_1                               {C5BFFE2E-9D87-D568-A09E-08FC83D0C7C2}
SQLSRV32.1                               {4B647745-F438-0A42-F870-5DBD29949C99}
TCPIP Service Trace                      {EB004A05-9B1A-11D4-9123-0050047759BC}
TerminalServer-MediaFoundationPlugin     {4199EE71-D55D-47D7-9F57-34A1D5B2C904}
Thread Pool                              {C861D0E2-A2C1-4D36-9F9C-970BAB943A12}
TPM                                      {1B6B0772-251B-4D42-917D-FACA166BC059}
TS Client ActiveX Control Trace          {DAA6CAF5-6678-43F8-A6FE-B40EE096E06E}
TS Client Trace                          {0C51B20C-F755-48A8-8123-BF6DA2ADC727}
TS Rdp Init Trace                        {C127C1A8-6CEB-11DA-8BDE-F66BAD1E3F3A}
TS RDP Shell Trace                       {BFA655DC-6C51-11DA-8BDE-F66BAD1E3F3A}
TS Rdp Sound End Point Trace             {5A966D1C-6B48-11DA-8BDE-F66BAD1E3F3A}
UMB Trace                                {96AB095A-9519-4F5C-81EE-C510B0A45463}
UmBus Driver Trace                       {F9BE9C98-10DB-4318-BB61-CB0DDEA08BF7}
UMDF - Driver Manager Trace              {485E7DEA-0A80-11D8-AD15-505054503030}
UMDF - Framework Trace                   {485E7DE9-0A80-11D8-AD15-505054503030}
UMDF - Host Process Trace                {485E7DF0-0A80-11D8-AD15-505054503030}
UMDF - Lpc Driver Trace                  {485E7DED-0A80-11D8-AD15-505054503030}
UMDF - Lpc Trace                         {485E7DEF-0A80-11D8-AD15-505054503030}
UMDF - Platform Library Trace            {485E7DE8-0A80-11D8-AD15-505054503030}
UMDF - Reflector Trace                   {485E7DEE-0A80-11D8-AD15-505054503030}
UMDF - Test Trace                        {485E7DEB-0A80-11D8-AD15-505054503030}
UMDF - WDF Core                          {485E7DE9-0A80-11D8-AD15-505054503030}
UMPass Driver Trace                      {FF9E2BDD-0E24-437C-84BE-7CFCAE635808}
USB Storage Driver Tracing Provider      {72FB9358-A9B3-41E0-AE41-E8DECA41E3A8}
User32                                   {B0AA8734-56F7-41CC-B2F4-DE228E98B946}
Volsnap                                  {CB017CD2-1F37-4E65-82BC-3E91F6A37559}
VSS tracing provider                     {9138500E-3648-4EDB-AA4C-859E9F7B7C38}
Windows Firewall API                     {28C9F48F-D244-45A8-842F-DC9FBC9B6E92}
Windows Firewall API - GP                {0EFF663F-8B6E-4E6D-8182-087A8EAA29CB}
Windows Firewall Driver                  {D5E09122-D0B2-4235-ADC1-C89FAAAF1069}
Windows Firewall NetShell Plugin         {28C9F48F-D244-45A8-842F-DC9FBC9B6E94}
Windows Firewall Service                 {5EEFEBDB-E90C-423A-8ABF-0241E7C5B87D}
Windows Kernel Trace                     {9E814AAD-3204-11D2-9A82-006008A86939}
Windows Media Player Trace               {A9C1A3B7-54F3-4724-ADCE-58BC03E3BC78}
Windows NetworkItemFactory Trace         {D2A60D61-0F87-4673-A86C-9C461457FE27}
Windows Notification Facility Provider   {42695762-EA50-497A-9068-5CBBB35E0B95}
Windows Remote Management Trace          {04C6E16D-B99F-4A3A-9B3E-B8325BBC781E}
Windows Wininit Trace                    {C2BA06E2-F7CE-44AA-9E7E-62652CDEFE97}
Windows Winlogon Trace                   {D451642C-63A6-11D7-9720-00B0D03E0347}
Windows-ApplicationModel-Store-SDK       {FF79A477-C45F-4A52-8AE0-2B324346D4E4}
WINSATAPI_ETW_PROVIDER                   {617853D6-728B-4B59-8A78-C3A9A5EADE92}
WLAN HC Diagnostics Trace                {6DA4DDCA-0901-4BAE-9AD4-7E6030BAB531}
WMI_Tracing                              {1FF6B227-2CA7-40F9-9A66-980EADAA602E}
WMI_Tracing_Client_Operations            {8E6B6962-AB54-4335-8229-3255B919DD0E}
WPD API Trace                            {C3C5D8AF-2FD5-4500-A8E7-379C2D0BBE2E}
WPD Bluetooth MTP Emumerator Driver Trace {4B6EFB94-30EA-49A7-BB29-E9ED9DCE67DA}
WPD BusEnumService Trace                 {0381564E-D5CB-4E48-AB35-BE24389B0F59}
WPD ClassExtension Trace                 {A0A352C5-B8EC-41E9-9936-8452C1C0A6CF}
WPD ClassInstaller Trace                 {45350D79-4497-42F1-BD1B-83587575B91A}
WPD Composite Driver Trace               {72891EE8-C088-4331-9745-5BF4AA7B344D}
WPD FSDriver Trace                       {1311095B-B9FF-497A-8560-2F43CA5438E4}
WPD ShellExtension Trace                 {A42C7BD1-5AF3-4B32-9BC6-B85EB31D3F4A}
WPD ShellServiceObject Trace             {1AB5AC29-037F-43A1-9484-78C9DB61F869}
WPD Types Trace                          {58E8F67D-29E9-456C-B23D-C6489E341BB0}
WPD WiaCompat Trace                      {B809F4FF-3023-473C-971B-AB594429EA57}
WPD WMDMCompat Trace                     {17ABF473-982C-4D0E-B502-3A59D89E71DE}
WSAT_TraceProvider                       {7F3FE630-462B-47C5-AB07-67CA84934ABD}
Wudfx02000_KmdfTraceGuid                 {485E7DE9-0A80-11D8-AD15-505054503030}
XWizard Framework                        {777BA8FF-2498-4875-933A-3067DE883070}
```
---

 There are also two special purpose sessions - `Global Logger Session` and` NT Kernel Logger Session`.
