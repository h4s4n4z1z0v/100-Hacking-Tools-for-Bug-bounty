# 🛡️ Web Security & Reconnaissance Tools

Bu sənəd web təhlükəsizliyi sahəsində istifadə olunan müxtəlif kateqoriyalara aid alətlərin geniş siyahısını, təsvirləri və rəsmi linklərini ehtiva edir. Məqsəd, penetration testerlər, təhlükəsizlik tədqiqatçıları və kiber mütəxəssislər üçün praktik və faydalı resurs yaratmaqdır.

---

## 📚 Table of Contents

* [Web Proxy Tools](#web-proxy-tools)
* [Web Hacking Tools](#web-hacking-tools)
* [Reconnaissance Tools](#reconnaissance-tools)
* [Subdomain & DNS Tools](#subdomain--dns-tools)
* [Mobile Hacking Tools](#mobile-hacking-tools)
* [Exploitation Tools](#exploitation-tools)
* [Scanners & Frameworks](#scanners--frameworks)
* [Datasets & Freemium Services](#datasets--freemium-services)
* [AI Hacking Tools](#ai-hacking-tools)
* [Miscellaneous Tools](#miscellaneous-tools)

---

## 🔍 Web Proxy Tools

| Alət               | Təsviri                                                                                                                                          | Rəsmi Link                                                                        |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------- |
| **Burp Suite**     | Web tətbiqlərinin hücum testlərində istifadə edilən ən məşhur vasitədir. HackerOne-da 500 reputasiya qazandıqda 3 aylıq Pro versiyası pulsuzdur. | [Burp Suite](https://portswigger.net/burp)                                        |
| **ActiveScan++**   | Burp-un aktiv və passiv scan imkanlarını genişləndirir.                                                                                          | [ActiveScan++](https://github.com/PortSwigger/activescan-plus-plus)               |
| **Autorepeater**   | HTTP istəklərini avtomatik təkrar edir.                                                                                                          | [Autorepeater](https://github.com/nccgroup/AutoRepeater)                          |
| **Autorize**       | Authorization zəifliklərinin tapılmasına yardım edir.                                                                                            | [Autorize](https://github.com/Quitten/Autorize)                                   |
| **js-link finder** | JS fayllarda endpoint linkləri axtarır.                                                                                                          | [js-link finder](https://github.com/GerbenJavado/LinkFinder)                      |
| **Flow**           | Bütün Burp alətləri üçün proxy tarixi kimi baxış imkanı verir.                                                                                   | [Flow](https://github.com/silentsignal/burp-flow)                                 |
| **Logger++**       | Ətraflı request/response loglama və filterləmə.                                                                                                  | [Logger++](https://github.com/PortSwigger/logger-plus-plus)                       |
| **WSDL Wizard**    | .wsdl fayllarını tapmaq üçün skan aparır.                                                                                                        | [WSDL Wizard](https://portswigger.net/bappstore/8bfb2cfa2b9a42a7b4cda78a5b6c4c39) |
| **Caido**          | Burp Suite-ya alternativ və modern web test platforması.                                                                                         | [Caido](https://github.com/caido/caido)                                           |

---

## 🕷️ Web Hacking Tools

| Alət                       | Təsviri                                                                | Rəsmi Link                                                                     |
| -------------------------- | ---------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| **Jsluice**                | JS fayllardan URL, path, secret kimi dataları çıxarır.                 | [Jsluice](https://github.com/BishopFox/jsluice)                                |
| **lazys3**                 | AWS S3 bucket-larını brute-force edir.                                 | [lazys3](https://github.com/nahamsec/lazys3)                                   |
| **teh\_s3\_bucketeers**    | S3 bucket-ların kəşfi üçün alət.                                       | [teh\_s3\_bucketeers](https://github.com/tomdev/teh_s3_bucketeers)             |
| **Virtual-host-discovery** | Virtual host-ları enumerasiya edir.                                    | [Virtual-host-discovery](https://github.com/jobertabma/virtual-host-discovery) |
| **wpscan**                 | WordPress tətbiqlərinin təhlükəsizliyini yoxlayır.                     | [wpscan](https://github.com/wpscanteam/wpscan)                                 |
| **webscreenshot**          | URL-lərdən screenshot çəkir.                                           | [webscreenshot](https://github.com/maaaaz/webscreenshot)                       |
| **asnlookup**              | IP-in ASN məlumatlarını göstərir.                                      | [asnlookup](https://github.com/yassineaboukir/asnlookup)                       |
| **unfurl**                 | Text fayllardaki domen məlumatlarını pars edir.                        | [unfurl](https://github.com/obsidianforensics/unfurl)                          |
| **waybackurls**            | Wayback Machine-dən əvvəlki URL-ləri çəkir.                            | [waybackurls](https://github.com/tomnomnom/waybackurls)                        |
| **httprobe**               | HTTP/S serverləri yoxlayır.                                            | [httprobe](https://github.com/tomnomnom/httprobe)                              |
| **meg**                    | Çox URL-i sərfəli formada çəkməyə imkan verir.                         | [meg](https://github.com/tomnomnom/meg)                                        |
| **gau**                    | OTX, Wayback Machine, Common Crawl-dan URL-lər toplayır.               | [gau](https://github.com/lc/gau)                                               |
| **ffuf**                   | Go dilində yazılmış sürətli fuzzer.                                    | [ffuf](https://github.com/ffuf/ffuf)                                           |
| **dirsearch**              | Web serverdə gizli fayl və qovluqları brute-force edir.                | [dirsearch](https://github.com/maurosoria/dirsearch)                           |
| **OWASP ZAP**              | OWASP tərəfindən təqdim edilən açıq mənbəli web təhlükəsizlik skaneri. | [OWASP ZAP](https://github.com/zaproxy/zaproxy)                                |

---

## 🧬 Reconnaissance Tools

| Alət               | Təsviri                                                         | Rəsmi Link                                                                        |
| ------------------ | --------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| **Recon-ng**       | Güclü və modul əsaslı OSINT framework.                          | [Recon-ng](https://github.com/lanmaster53/recon-ng)                               |
| **Jok3r**          | Şəbəkə və web tətbiq testlərini avtomatlaşdırır.                | [Jok3r](https://github.com/koutto/jok3r)                                          |
| **Lazyrecon**      | Recon və info gathering üçün avtomatlaşdırılmış bash script.    | [Lazyrecon](https://github.com/nahamsec/lazyrecon)                                |
| **Osmedeus**       | Recon və zəiflik skanlarını avtomatik həyata keçirən platforma. | [Osmedeus](https://github.com/j3ssie/Osmedeus)                                    |
| **Recon\_profile** | SSH vasitəsilə sadə recon əmrləri üçün aliaslar yaradır.        | [Recon\_profile](https://github.com/Knowledge-Wisdom-Understanding/recon_profile) |
| **BBHT**           | Bug bounty üçün lazım olan alətləri avtomatik quraşdırır.       | [BBHT](https://github.com/nahamsec/bbht)                                          |

---

## 🌐 Subdomain & DNS Tools

| Alət              | Təsviri                                                                    | Rəsmi Link                                                        |
| ----------------- | -------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| **Subfinder**     | Passiv subdomain aşkarlama aləti, sürətli və sadə.                         | [Subfinder](https://github.com/projectdiscovery/subfinder)        |
| **EyeWitness**    | Saytlardan screenshot çəkir, server başlıqları və default loginləri tapır. | [EyeWitness](https://github.com/FortyNorthSecurity/EyeWitness)    |
| **Nuclei**        | Template əsaslı sürətli vulnerability scanner.                             | [Nuclei](https://github.com/projectdiscovery/nuclei)              |
| **Naabu**         | Sürətli port scanner.                                                      | [Naabu](https://github.com/projectdiscovery/naabu)                |
| **Shuffledns**    | Massdns üzərində aktiv subdomain brute force və wildcard dəstəyi.          | [Shuffledns](https://github.com/projectdiscovery/shuffledns)      |
| **Dnsprobe**      | İstifadəçi tərəfindən verilmiş resolverlərlə DNS sorğuları aparır.         | [Dnsprobe](https://github.com/projectdiscovery/dnsprobe)          |
| **Chaos**         | İnternetdəki aktiv DNS resurslarını skan və izləyir.                       | [Chaos](https://github.com/projectdiscovery/chaos)                |
| **Subjack**       | Subdomain takeover risklərini yoxlayır.                                    | [Subjack](https://github.com/haccer/subjack)                      |
| **gitGraber**     | GitHub üzərində gizli məlumatları real vaxtda axtarır.                     | [gitGraber](https://github.com/michenriksen/gitGraber)            |
| **Shhgit**        | GitHub repos və gist-lərdə sirlər və gizli fayllar tapır.                  | [Shhgit](https://github.com/eth0izzle/shhgit)                     |
| **Commit-stream** | GitHub event API-dən real vaxt commit məlumatlarını çıxarır.               | [Commit-stream](https://github.com/eth0izzle/commit-stream)       |
| **Masscan**       | İnternet səviyyəsində sürətli port scan aləti.                             | [Masscan](https://github.com/robertdavidgraham/masscan)           |
| **Massdns**       | DNS sorgularını sürətlə yerinə yetirən resolver.                           | [Massdns](https://github.com/blechschmidt/massdns)                |
| **Findomain**     | Amazon üzərində host monitoring və subdomain izləmə xidməti.               | [Findomain](https://github.com/findomain/findomain)               |
| **Amass**         | Hücum səthi xəritələmə və aktiv/passiv kəşfiyyat üçün alət.                | [Amass](https://github.com/OWASP/Amass)                           |
| **Dnsgen**        | Domain kombinasiya generatoru.                                             | [Dnsgen](https://github.com/OWASP/Amass/tree/master/child/dnsgen) |
| **Dngrep**        | DNS məlumatlarında sürətli axtarış üçün utilit.                            | [Dngrep](https://github.com/jhspetersson/dngrep)                  |

---

## 📱 Mobile Hacking Tools

| Alət                             | Təsviri                                                                                              | Rəsmi Link                                                                          |
| -------------------------------- | ---------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| **MobSF**                        | Android/iOS/Windows mobil tətbiqlərin statik və dinamik analizini aparan avtomatlaşdırılmış çərçivə. | [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF)                   |
| **Jadx**                         | Android Dex və Apk fayllarını Java mənbə koduna dekompilyasiya edən vasitə.                          | [Jadx](https://github.com/skylot/jadx)                                              |
| **Dex2Jar**                      | Android `.dex` fayllarını Java `.class` fayllarına çevirən alət.                                     | [Dex2Jar](https://github.com/pxb1988/dex2jar)                                       |
| **Radare2**                      | Açıq mənbəli çoxfunksiyalı alət zənciri (forensika, reverse engineering, debugging və s.).           | [Radare2](https://github.com/radareorg/radare2)                                     |
| **Genymotion**                   | Cross-platform Android emulatoru, test və inkişaf üçün nəzərdə tutulub.                              | [Genymotion](https://www.genymotion.com/)                                           |
| **Frida**                        | Dinamik instrumetasiya və SSL unpinning üçün universal alət.                                         | [Frida](https://github.com/frida/frida)                                             |
| **Frida Universal SSL Unpinner** | SSL pinning bypass üçün Frida skriptləri toplusu.                                                    | [Frida SSL Unpinner](https://github.com/MTU0/frida-universal-android-ssl-unpinning) |

---

## 💥 Exploitation Tools

| Alət           | Təsviri                                                                                           | Rəsmi Link                                            |
| -------------- | ------------------------------------------------------------------------------------------------- | ----------------------------------------------------- |
| **SQLNinja**   | Microsoft SQL Server üçün SQL injection zəifliklərini exploit edən alət.                          | [SQLNinja](https://github.com/sqlninja/sqlninja)      |
| **NoSQLMap**   | NoSQL verilənlər bazalarında injection və konfiqurasiya zəifliklərini aşkar edir və exploit edir. | [NoSQLMap](https://github.com/codingo/NoSQLMap)       |
| **Ysoserial**  | Unsafe Java object deserialization zəifliklərini sübut edən payload generatoru.                   | [Ysoserial](https://github.com/frohoff/ysoserial)     |
| **Sqlmap**     | Avtomatlaşdırılmış SQL injection tapma və exploit vasitəsi, geniş xüsusiyyətlərə malikdir.        | [Sqlmap](https://github.com/sqlmapproject/sqlmap)     |
| **SSRFTest**   | Server Side Request Forgery (SSRF) zəifliklərinin test edilməsi üçün alət.                        | [SSRFTest](https://github.com/medvedev1088/SSRFTest)  |
| **Spiderfoot** | OSINT avtomatlaşdırma və kəşfiyyat aləti, zəifliklərin tapılması üçün məlumat toplayır.           | [Spiderfoot](https://github.com/smicallef/spiderfoot) |

---

## 🛠️ Scanners & Frameworks

Əlbəttə! Sənə tam, başdan sona qədər bütün yazdıqlarımı toplu şəkildə — linklərlə birlikdə, tam formatda, **kitab** kimi, **README.md** və ya başqa istənilən formatda GitHub-da paylaşa biləcəyin şəkildə təqdim edirəm. Üstəlik, yuxarıda dediyin kimi **Table of Contents** də daxil olacaq.

---

# 🛡️ Web Security & Reconnaissance Tools

Bu sənəd web təhlükəsizliyi sahəsində istifadə olunan müxtəlif kateqoriyalara aid alətlərin geniş siyahısını, təsvirləri və rəsmi linklərini ehtiva edir. Məqsəd, penetration testerlər, təhlükəsizlik tədqiqatçıları və kiber mütəxəssislər üçün praktik və faydalı resurs yaratmaqdır.

---

## 📚 Table of Contents

* [Web Proxy Tools](#web-proxy-tools)
* [Web Hacking Tools](#web-hacking-tools)
* [Reconnaissance Tools](#reconnaissance-tools)
* [Subdomain & DNS Tools](#subdomain--dns-tools)
* [Mobile Hacking Tools](#mobile-hacking-tools)
* [Exploitation Tools](#exploitation-tools)
* [Scanners & Frameworks](#scanners--frameworks)
* [Datasets & Freemium Services](#datasets--freemium-services)
* [AI Hacking Tools](#ai-hacking-tools)
* [Miscellaneous Tools](#miscellaneous-tools)

---

## 🔍 Web Proxy Tools

| Alət               | Təsviri                                                                                                                                          | Rəsmi Link                                                                        |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------- |
| **Burp Suite**     | Web tətbiqlərinin hücum testlərində istifadə edilən ən məşhur vasitədir. HackerOne-da 500 reputasiya qazandıqda 3 aylıq Pro versiyası pulsuzdur. | [Burp Suite](https://portswigger.net/burp)                                        |
| **ActiveScan++**   | Burp-un aktiv və passiv scan imkanlarını genişləndirir.                                                                                          | [ActiveScan++](https://github.com/PortSwigger/activescan-plus-plus)               |
| **Autorepeater**   | HTTP istəklərini avtomatik təkrar edir.                                                                                                          | [Autorepeater](https://github.com/nccgroup/AutoRepeater)                          |
| **Autorize**       | Authorization zəifliklərinin tapılmasına yardım edir.                                                                                            | [Autorize](https://github.com/Quitten/Autorize)                                   |
| **js-link finder** | JS fayllarda endpoint linkləri axtarır.                                                                                                          | [js-link finder](https://github.com/GerbenJavado/LinkFinder)                      |
| **Flow**           | Bütün Burp alətləri üçün proxy tarixi kimi baxış imkanı verir.                                                                                   | [Flow](https://github.com/silentsignal/burp-flow)                                 |
| **Logger++**       | Ətraflı request/response loglama və filterləmə.                                                                                                  | [Logger++](https://github.com/PortSwigger/logger-plus-plus)                       |
| **WSDL Wizard**    | .wsdl fayllarını tapmaq üçün skan aparır.                                                                                                        | [WSDL Wizard](https://portswigger.net/bappstore/8bfb2cfa2b9a42a7b4cda78a5b6c4c39) |
| **Caido**          | Burp Suite-ya alternativ və modern web test platforması.                                                                                         | [Caido](https://github.com/caido/caido)                                           |

---

## 🕷️ Web Hacking Tools

| Alət                       | Təsviri                                                                | Rəsmi Link                                                                     |
| -------------------------- | ---------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| **Jsluice**                | JS fayllardan URL, path, secret kimi dataları çıxarır.                 | [Jsluice](https://github.com/BishopFox/jsluice)                                |
| **lazys3**                 | AWS S3 bucket-larını brute-force edir.                                 | [lazys3](https://github.com/nahamsec/lazys3)                                   |
| **teh\_s3\_bucketeers**    | S3 bucket-ların kəşfi üçün alət.                                       | [teh\_s3\_bucketeers](https://github.com/tomdev/teh_s3_bucketeers)             |
| **Virtual-host-discovery** | Virtual host-ları enumerasiya edir.                                    | [Virtual-host-discovery](https://github.com/jobertabma/virtual-host-discovery) |
| **wpscan**                 | WordPress tətbiqlərinin təhlükəsizliyini yoxlayır.                     | [wpscan](https://github.com/wpscanteam/wpscan)                                 |
| **webscreenshot**          | URL-lərdən screenshot çəkir.                                           | [webscreenshot](https://github.com/maaaaz/webscreenshot)                       |
| **asnlookup**              | IP-in ASN məlumatlarını göstərir.                                      | [asnlookup](https://github.com/yassineaboukir/asnlookup)                       |
| **unfurl**                 | Text fayllardaki domen məlumatlarını pars edir.                        | [unfurl](https://github.com/obsidianforensics/unfurl)                          |
| **waybackurls**            | Wayback Machine-dən əvvəlki URL-ləri çəkir.                            | [waybackurls](https://github.com/tomnomnom/waybackurls)                        |
| **httprobe**               | HTTP/S serverləri yoxlayır.                                            | [httprobe](https://github.com/tomnomnom/httprobe)                              |
| **meg**                    | Çox URL-i sərfəli formada çəkməyə imkan verir.                         | [meg](https://github.com/tomnomnom/meg)                                        |
| **gau**                    | OTX, Wayback Machine, Common Crawl-dan URL-lər toplayır.               | [gau](https://github.com/lc/gau)                                               |
| **ffuf**                   | Go dilində yazılmış sürətli fuzzer.                                    | [ffuf](https://github.com/ffuf/ffuf)                                           |
| **dirsearch**              | Web serverdə gizli fayl və qovluqları brute-force edir.                | [dirsearch](https://github.com/maurosoria/dirsearch)                           |
| **OWASP ZAP**              | OWASP tərəfindən təqdim edilən açıq mənbəli web təhlükəsizlik skaneri. | [OWASP ZAP](https://github.com/zaproxy/zaproxy)                                |

---

## 🧬 Reconnaissance Tools

| Alət               | Təsviri                                                         | Rəsmi Link                                                                        |
| ------------------ | --------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| **Recon-ng**       | Güclü və modul əsaslı OSINT framework.                          | [Recon-ng](https://github.com/lanmaster53/recon-ng)                               |
| **Jok3r**          | Şəbəkə və web tətbiq testlərini avtomatlaşdırır.                | [Jok3r](https://github.com/koutto/jok3r)                                          |
| **Lazyrecon**      | Recon və info gathering üçün avtomatlaşdırılmış bash script.    | [Lazyrecon](https://github.com/nahamsec/lazyrecon)                                |
| **Osmedeus**       | Recon və zəiflik skanlarını avtomatik həyata keçirən platforma. | [Osmedeus](https://github.com/j3ssie/Osmedeus)                                    |
| **Recon\_profile** | SSH vasitəsilə sadə recon əmrləri üçün aliaslar yaradır.        | [Recon\_profile](https://github.com/Knowledge-Wisdom-Understanding/recon_profile) |
| **BBHT**           | Bug bounty üçün lazım olan alətləri avtomatik quraşdırır.       | [BBHT](https://github.com/nahamsec/bbht)                                          |

---

## 🌐 Subdomain & DNS Tools

| Alət              | Təsviri                                                                    | Rəsmi Link                                                        |
| ----------------- | -------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| **Subfinder**     | Passiv subdomain aşkarlama aləti, sürətli və sadə.                         | [Subfinder](https://github.com/projectdiscovery/subfinder)        |
| **EyeWitness**    | Saytlardan screenshot çəkir, server başlıqları və default loginləri tapır. | [EyeWitness](https://github.com/FortyNorthSecurity/EyeWitness)    |
| **Nuclei**        | Template əsaslı sürətli vulnerability scanner.                             | [Nuclei](https://github.com/projectdiscovery/nuclei)              |
| **Naabu**         | Sürətli port scanner.                                                      | [Naabu](https://github.com/projectdiscovery/naabu)                |
| **Shuffledns**    | Massdns üzərində aktiv subdomain brute force və wildcard dəstəyi.          | [Shuffledns](https://github.com/projectdiscovery/shuffledns)      |
| **Dnsprobe**      | İstifadəçi tərəfindən verilmiş resolverlərlə DNS sorğuları aparır.         | [Dnsprobe](https://github.com/projectdiscovery/dnsprobe)          |
| **Chaos**         | İnternetdəki aktiv DNS resurslarını skan və izləyir.                       | [Chaos](https://github.com/projectdiscovery/chaos)                |
| **Subjack**       | Subdomain takeover risklərini yoxlayır.                                    | [Subjack](https://github.com/haccer/subjack)                      |
| **gitGraber**     | GitHub üzərində gizli məlumatları real vaxtda axtarır.                     | [gitGraber](https://github.com/michenriksen/gitGraber)            |
| **Shhgit**        | GitHub repos və gist-lərdə sirlər və gizli fayllar tapır.                  | [Shhgit](https://github.com/eth0izzle/shhgit)                     |
| **Commit-stream** | GitHub event API-dən real vaxt commit məlumatlarını çıxarır.               | [Commit-stream](https://github.com/eth0izzle/commit-stream)       |
| **Masscan**       | İnternet səviyyəsində sürətli port scan aləti.                             | [Masscan](https://github.com/robertdavidgraham/masscan)           |
| **Massdns**       | DNS sorgularını sürətlə yerinə yetirən resolver.                           | [Massdns](https://github.com/blechschmidt/massdns)                |
| **Findomain**     | Amazon üzərində host monitoring və subdomain izləmə xidməti.               | [Findomain](https://github.com/findomain/findomain)               |
| **Amass**         | Hücum səthi xəritələmə və aktiv/passiv kəşfiyyat üçün alət.                | [Amass](https://github.com/OWASP/Amass)                           |
| **Dnsgen**        | Domain kombinasiya generatoru.                                             | [Dnsgen](https://github.com/OWASP/Amass/tree/master/child/dnsgen) |
| **Dngrep**        | DNS məlumatlarında sürətli axtarış üçün utilit.                            | [Dngrep](https://github.com/jhspetersson/dngrep)                  |

---

## 📱 Mobile Hacking Tools

| Alət                             | Təsviri                                                                                              | Rəsmi Link                                                                          |
| -------------------------------- | ---------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| **MobSF**                        | Android/iOS/Windows mobil tətbiqlərin statik və dinamik analizini aparan avtomatlaşdırılmış çərçivə. | [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF)                   |
| **Jadx**                         | Android Dex və Apk fayllarını Java mənbə koduna dekompilyasiya edən vasitə.                          | [Jadx](https://github.com/skylot/jadx)                                              |
| **Dex2Jar**                      | Android `.dex` fayllarını Java `.class` fayllarına çevirən alət.                                     | [Dex2Jar](https://github.com/pxb1988/dex2jar)                                       |
| **Radare2**                      | Açıq mənbəli çoxfunksiyalı alət zənciri (forensika, reverse engineering, debugging və s.).           | [Radare2](https://github.com/radareorg/radare2)                                     |
| **Genymotion**                   | Cross-platform Android emulatoru, test və inkişaf üçün nəzərdə tutulub.                              | [Genymotion](https://www.genymotion.com/)                                           |
| **Frida**                        | Dinamik instrumetasiya və SSL unpinning üçün universal alət.                                         | [Frida](https://github.com/frida/frida)                                             |
| **Frida Universal SSL Unpinner** | SSL pinning bypass üçün Frida skriptləri toplusu.                                                    | [Frida SSL Unpinner](https://github.com/MTU0/frida-universal-android-ssl-unpinning) |

---

## 💥 Exploitation Tools

| Alət           | Təsviri                                                                                           | Rəsmi Link                                            |
| -------------- | ------------------------------------------------------------------------------------------------- | ----------------------------------------------------- |
| **SQLNinja**   | Microsoft SQL Server üçün SQL injection zəifliklərini exploit edən alət.                          | [SQLNinja](https://github.com/sqlninja/sqlninja)      |
| **NoSQLMap**   | NoSQL verilənlər bazalarında injection və konfiqurasiya zəifliklərini aşkar edir və exploit edir. | [NoSQLMap](https://github.com/codingo/NoSQLMap)       |
| **Ysoserial**  | Unsafe Java object deserialization zəifliklərini sübut edən payload generatoru.                   | [Ysoserial](https://github.com/frohoff/ysoserial)     |
| **Sqlmap**     | Avtomatlaşdırılmış SQL injection tapma və exploit vasitəsi, geniş xüsusiyyətlərə malikdir.        | [Sqlmap](https://github.com/sqlmapproject/sqlmap)     |
| **SSRFTest**   | Server Side Request Forgery (SSRF) zəifliklərinin test edilməsi üçün alət.                        | [SSRFTest](https://github.com/medvedev1088/SSRFTest)  |
| **Spiderfoot** | OSINT avtomatlaşdırma və kəşfiyyat aləti, zəifliklərin tapılması üçün məlumat toplayır.           | [Spiderfoot](https://github.com/smicallef/spiderfoot) |

---

## 🛠️ Scanners & Frameworks

| Alət        | Təsviri                                                                                       | Rəsmi Link                              |
| ----------- | --------------------------------------------------------------------------------------------- | --------------------------------------- |
| **OpenVAS** | Tam xüsusiyyətli açıq mənbə zəiflik skaneri, unauthenticated və authenticated testlər aparır. | [OpenVAS](https://www.openvas.org/)     |
| **Nikto**   | Açıq mənbə web server skaneri, 6700-dən çox təhlükəli fayl və proqramları yoxlayır.           | [Nikto](https://github.com/sullo/nikto) |
| **Wapiti**  | Açıq mənbə web tətbiq zəiflik skaneri, black-box testi aparır.                              |[Wapiti](https://github.com/wapiti-scanner/wapiti)| |  
| **Nessus** | Təhlükəsizlik skaneri (proprietary, lakin pulsuz versiyası mövcuddur). | [Nessus](https://www.tenable.com/products/nessus) |
| **Metasploit Framework** | Populyar exploit development və penetration testing frameworku. | [Metasploit](https://github.com/rapid7/metasploit-framework) |

---

## 📊 Datasets & Freemium Services

| Alət               | Təsviri                                                                                 | Rəsmi Link                                    |
| ------------------ | --------------------------------------------------------------------------------------- | --------------------------------------------- |
| **Censys**         | İnternet aktiv hostlar, zəifliklər və açıq portlar haqqında məlumat toplayan platforma. | [Censys](https://censys.io/)                  |
| **Shodan**         | IoT cihazları, açıq serverlər və zəif nöqtələri tapmaq üçün axtarış motoru.             | [Shodan](https://www.shodan.io/)              |
| **VirusTotal**     | Faylların və URL-lərin zərərli proqram analizini təqdim edən onlayn xidmət.             | [VirusTotal](https://www.virustotal.com/)     |
| **HaveIBeenPwned** | E-poçt və istifadəçi məlumatlarının ifşa olub-olmadığını yoxlamaq üçün.                 | [HaveIBeenPwned](https://haveibeenpwned.com/) |
| **AlienVault OTX** | Açıq təhlükə intel platforması, indikatörlər və kiber hadisələr haqqında məlumat verir. | [AlienVault OTX](https://otx.alienvault.com/) |

---

## 🤖 AI Hacking Tools

| Alət                           | Təsviri                                                                                                                 | Rəsmi Link                                          |
| ------------------------------ | ----------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------- |
| **ChatGPT**                    | Hakerlərə brute force siyahıları yaratmaq, kod yazmaq və yeni hücum vektorları tapmaqda kömək edən süni zəka modeli.    | [ChatGPT](https://chat.openai.com/)                 |
| **Azure/PyRIT**                | Generative AI sistemlərində risklərin avtomatik aşkarlanması üçün Python Risk Identification Tool.                      | [PyRIT](https://github.com/Azure/PyRIT)             |
| **Arcanum Cyber Security Bot** | Etik təhlükəsizlik testçilərinə texniki mövzularda yardım edən, müasir araşdırmaları və yenilikləri təqdim edən AI bot. | [Arcanum Bot](https://github.com/arcanumappsec/bot) |

---

## 🧰 Miscellaneous Tools

| Alət                | Təsviri                                                                                     | Rəsmi Link                                                  |
| ------------------- | ------------------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| **Ettercap**        | Şəbəkə trafiki sniffing və aktiv/passiv protokol analizini təmin edən geniş funksiya dəsti. | [Ettercap](https://www.ettercap-project.org/)               |
| **Transformations** | Data gizlətmə üsullarını aşkar etməyə və bypass etməyə kömək edən vasitə.                   | [Transformations](https://github.com/OWASP/transformations) |
| **John the Ripper** | Populyar açıq mənbə parola qırma proqramı.                                                  | [John the Ripper](https://www.openwall.com/john/)           |
| **Wireshark**       | Şəbəkə protokol analizatoru, canlı trafik tutma və araşdırma üçün.                          | [Wireshark](https://www.wireshark.org/)                     |
| **Foxyproxy**       | Firefox üçün güclü proxy idarəetmə əlavəsi.                                                 | [Foxyproxy](https://getfoxyproxy.org/)                      |
| **Wappalyzer**      | Veb saytların istifadə etdiyi texnologiyaları müəyyən edən brauzer əlavəsi.                 | [Wappalyzer](https://www.wappalyzer.com/)                   |
| **BuiltWith**       | Veb saytların texnologiya stəklərini təhlil edən onlayn xidmət.                             | [BuiltWith](https://builtwith.com/)                         |
| **Altair**          | GraphQL sorğularını test etmək və debug etmək üçün müştəri tətbiq.                          | [Altair](https://altair.sirmuel.design/)                    |
| **CyberChef**       | Data analiz və dekodlaşdırma üçün sadə və güclü web tətbiq.                                 | [CyberChef](https://gchq.github.io/CyberChef/)              |
| **Swiftness X**     | Bug bounty və pentest qeydləri aparmaq üçün qeyd aparma aləti.                              | [Swiftness X](https://github.com/SwiftnessX/SwiftnessX)     |

---

Bu sənədi GitHub reposunda README.md kimi paylaşa, rahatlıqla yeniləyə və istənilən kiber təhlükəsizlik mütəxəssisinə faydalı bir resurs kimi təqdim edə bilərsən.

---

İstəsən sənə hazır GitHub reposu strukturunda da versə bilərəm (README.md + qovluq strukturu və s.). Başqa nəsə əlavə etmək istəyirsənsə, bildir.

---

**Sənə başqa necə kömək edə bilərəm?**


---

## 📊 Datasets & Freemium Services

| Alət               | Təsviri                                                                                 | Rəsmi Link                                    |
| ------------------ | --------------------------------------------------------------------------------------- | --------------------------------------------- |
| **Censys**         | İnternet aktiv hostlar, zəifliklər və açıq portlar haqqında məlumat toplayan platforma. | [Censys](https://censys.io/)                  |
| **Shodan**         | IoT cihazları, açıq serverlər və zəif nöqtələri tapmaq üçün axtarış motoru.             | [Shodan](https://www.shodan.io/)              |
| **VirusTotal**     | Faylların və URL-lərin zərərli proqram analizini təqdim edən onlayn xidmət.             | [VirusTotal](https://www.virustotal.com/)     |
| **HaveIBeenPwned** | E-poçt və istifadəçi məlumatlarının ifşa olub-olmadığını yoxlamaq üçün.                 | [HaveIBeenPwned](https://haveibeenpwned.com/) |
| **AlienVault OTX** | Açıq təhlükə intel platforması, indikatörlər və kiber hadisələr haqqında məlumat verir. | [AlienVault OTX](https://otx.alienvault.com/) |

---

## 🤖 AI Hacking Tools

| Alət                           | Təsviri                                                                                                                 | Rəsmi Link                                          |
| ------------------------------ | ----------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------- |
| **ChatGPT**                    | Hakerlərə brute force siyahıları yaratmaq, kod yazmaq və yeni hücum vektorları tapmaqda kömək edən süni zəka modeli.    | [ChatGPT](https://chat.openai.com/)                 |
| **Azure/PyRIT**                | Generative AI sistemlərində risklərin avtomatik aşkarlanması üçün Python Risk Identification Tool.                      | [PyRIT](https://github.com/Azure/PyRIT)             |
| **Arcanum Cyber Security Bot** | Etik təhlükəsizlik testçilərinə texniki mövzularda yardım edən, müasir araşdırmaları və yenilikləri təqdim edən AI bot. | [Arcanum Bot](https://github.com/arcanumappsec/bot) |

---

## 🧰 Miscellaneous Tools

| Alət                | Təsviri                                                                                     | Rəsmi Link                                                  |
| ------------------- | ------------------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| **Ettercap**        | Şəbəkə trafiki sniffing və aktiv/passiv protokol analizini təmin edən geniş funksiya dəsti. | [Ettercap](https://www.ettercap-project.org/)               |
| **Transformations** | Data gizlətmə üsullarını aşkar etməyə və bypass etməyə kömək edən vasitə.                   | [Transformations](https://github.com/OWASP/transformations) |
| **John the Ripper** | Populyar açıq mənbə parola qırma proqramı.                                                  | [John the Ripper](https://www.openwall.com/john/)           |
| **Wireshark**       | Şəbəkə protokol analizatoru, canlı trafik tutma və araşdırma üçün.                          | [Wireshark](https://www.wireshark.org/)                     |
| **Foxyproxy**       | Firefox üçün güclü proxy idarəetmə əlavəsi.                                                 | [Foxyproxy](https://getfoxyproxy.org/)                      |
| **Wappalyzer**      | Veb saytların istifadə etdiyi texnologiyaları müəyyən edən brauzer əlavəsi.                 | [Wappalyzer](https://www.wappalyzer.com/)                   |
| **BuiltWith**       | Veb saytların texnologiya stəklərini təhlil edən onlayn xidmət.                             | [BuiltWith](https://builtwith.com/)                         |
| **Altair**          | GraphQL sorğularını test etmək və debug etmək üçün müştəri tətbiq.                          | [Altair](https://altair.sirmuel.design/)                    |
| **CyberChef**       | Data analiz və dekodlaşdırma üçün sadə və güclü web tətbiq.                                 | [CyberChef](https://gchq.github.io/CyberChef/)              |
| **Swiftness X**     | Bug bounty və pentest qeydləri aparmaq üçün qeyd aparma aləti.                              | [Swiftness X](https://github.com/SwiftnessX/SwiftnessX)     |

---

