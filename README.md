# Wordlists
A collection of my custom/every day wordlists and web fuzzing lists

# Breakdown

| Path | Description | Count | 
| ---- | ----------- | ----- |
| quick.txt | Small list of quick wins and common indicators, built over time when bugs have been found and some paths taken from public nuclei templates | 1,507 |
| ext/jsp.txt | A collection of `.jsp` filenames scraped from a large collection of `.war` archives | 13,350 |
| ext/properties.txt | A collection of `.properties` filenames scraped from a large collection of `.war` archives | 5030 |
| ext/xml.txt | A collection of `.xml` filenames scraped from a large collection of `.war` archives | 33,240 |
| ext/yaml.txt | A collection of `.yaml` filenames scraped from a large collection of `.war` archives | 17 |
| ext/config.txt | A collection of `.config` filenames scraped from a large collection of `.war` archives | 23 |
| technologies/openam.txt | A collection of common paths used by OpenAM | 500 | 
| technologies/aem.txt | A collection of common and bad paths when attacking websites built on Adobe Experience Manager (AEM) | 543 | 
| technologies/tomcat/usernames.txt | A collection of usernames used in `tomcat-users.xml` configurations scraped from GitHub | 95 |
| technologies/tomcat/password.txt | A collection of passwords used in `tomcat-users.xml` configurations scraped from GitHub | 63 |
| technologies/tomcat/combos.txt | A `user:pass` list of the above two wordlists | 159 |
| technologies/tomcat/combos_all.txt | A `user:pass` list applying every observed password with every observed username | 6,048 |
| fuzz/Custom - Command Injection (small) | A fuzzing list of easy win command injection payloads, all payloads call out to a canary server. You will need to replace `intruder.dns.canary.domain` with your own canary or Burp Collaborator URL | 66 |
| fuzz/java-trav-endpoints.txt | A list of handy/juicy services to reach if you're able to traverse backwards on a java host or if you're able to fuzz on a secondary context | 71 | 
| fuzz/waf-bypass-ext.txt | A small/common list of extensions that can be used to bypass WAFs with weak/misconfigures rules | 12 |
| technologies/java/url-patterns.txt | A list of URL patterns extracted from `web.xml` and similar files | 5,834 |

Anything not listed here should be self explanatory :)
