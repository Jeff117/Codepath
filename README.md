# Codepath

Vulnerability 1: Arbiturary file upload
Effected versions: 4.1 - 4.1.1
Description: Files with invalid or unsafe names could be uploaded
Fixed: Update 4.1.2

Vulnerability 2: MediaElement Cross-Site Scripting (XSS)
Effected versions: 3.7-4.9.1
Description: An XSS vulnerability was discovered in the Flash fallback files in MediaElement, a library that is included with WordPress.
Fixed: Update 4.9.2, The flash files were no longer needed so they were removed.

Vulnerability 3: WP_Query Injection
Effected versions: 4.2.1-4.2.11
Description: WP_Query had a vulerability to SQL injection when pass data. Wordpress core was not vulnerable.
Fixed: Update 4.2.12, added hardening to prevent plugins and themes from causing a vulnerability. 


Vulnerability 4: Authenticated SQL injection
Effected versions:2.3.0-4.7.4
Description: Due to bad resolution of the database abtraction library WP was exposed to SQL injection and validation. The issue had huge impact towards the entire system of WordPress.
Fixed: Up to 4.8.1 was vulnerable. The attacks were dependent on plugins, themes and setup. 


Vulnerability 5: Unauthenticated Stored Cross-Site Scripting (XSS)
Effected versions:4.2
Description: An unauthenticated attacker is able to inject JavaScript within the comments, then the script would be triggered by another user viewing the comment. If an admin were to trigger the script, the attacker could access anything the admin could, including passwords and gain access to priviledged abilities such as creating and deleting users.
Fixed: Update 4.2.1
