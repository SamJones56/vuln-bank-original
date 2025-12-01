
Testing /home/kali/Documents/AppSec/vuln-bank-original ...

Open Issues

 ✗ [LOW] Sensitive Cookie in HTTPS Session Without 'Secure' Attribute
   Finding ID: 10301f10-e0ba-4000-8e86-f9532f4223e8
   Path: app.py, line 313
   Info: Cookie's Secure flag is set to False by default. Set it to true to protect the cookie from man-in-the-middle attacks.

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: b4d83956-2955-4984-9b16-61d3a72b6192
   Path: static/dashboard.js, line 112
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: e5de7129-3881-4c74-a781-d7c377862a97
   Path: static/dashboard.js, line 122
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: 36eb8c9c-591c-4e20-87d3-b536d42dcf13
   Path: static/dashboard.js, line 188
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: 6709a291-86c0-47a6-9158-acdd6bc2d630
   Path: static/dashboard.js, line 300
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: c7f5fe9a-8942-4bdb-b7ee-9b20edb37daa
   Path: static/dashboard.js, line 340
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: c2828d1a-281c-45e5-86d6-2b1c9a10a958
   Path: static/dashboard.js, line 380
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: 214069a4-de90-4147-8e3f-3a910d4e970b
   Path: static/dashboard.js, line 446
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: 2242c694-4372-4bd8-b54d-e91620485938
   Path: static/dashboard.js, line 468
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: c3fd9c9e-7724-4663-ab0d-796335420238
   Path: static/dashboard.js, line 496
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: 924c1f22-0ee7-49e5-ad63-85bbdef36d06
   Path: static/dashboard.js, line 513
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: 8a190b81-f112-4bab-8a58-48cb701b09bf
   Path: static/dashboard.js, line 530
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: f7c91081-8448-4272-ab72-66ebaf33d55d
   Path: static/dashboard.js, line 575
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: 7de9cbaf-7b0d-48c7-b82e-489e0634d656
   Path: static/dashboard.js, line 607
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: 6abd2246-b5df-4760-9ec0-b6a9a119e069
   Path: static/dashboard.js, line 696
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: 582c0290-a7ae-4252-a24d-07aa095150f3
   Path: static/dashboard.js, line 753
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: efee13f7-ccd4-4df1-bd00-f4ed8eb48bf1
   Path: static/dashboard.js, line 780
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: 13ac2ed8-25a6-4c53-a0bb-7cb9649402fd
   Path: static/dashboard.js, line 938
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: d44c6fd1-e027-4585-a2d1-747494f65b30
   Path: templates/admin.html, line 155
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: 2d8e7587-5646-4ace-a7a8-564b81bea059
   Path: templates/admin.html, line 187
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: 5ac4f786-3759-4215-b031-738ed31ff9c8
   Path: templates/admin.html, line 225
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: 69cee2b4-0de1-4f86-9c20-958ec404d51d
   Path: templates/forgot_password.html, line 56
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: d01979f5-ef61-472b-a17a-f1686b20e9b0
   Path: templates/forgot_password.html, line 65
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: 6aa5be53-73ef-4d99-a220-17852b4b2390
   Path: templates/index.html, line 1058
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: 6c808c3b-9548-430f-9e07-05ac35cafa95
   Path: templates/login.html, line 57
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: 4d3f6460-e5c0-4fa4-88c8-c862090dca2b
   Path: templates/register.html, line 53
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: 0bd2b798-db73-4c9e-a0d4-8f40f6d55bda
   Path: templates/register.html, line 62
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] DOM-based Cross-site Scripting (XSS)
   Finding ID: 369661ca-a772-432b-9f5d-7bc3a97f82dc
   Path: templates/reset_password.html, line 70
   Info: Unsanitized input from data from a remote resource flows into innerHTML, where it is used to dynamically construct the HTML page on client side. This may result in a DOM Based Cross-Site Scripting attack (DOMXSS).

 ✗ [MEDIUM] SQL Injection
   Finding ID: 723fddfd-4347-4666-8456-c8df29281130
   Path: app.py, line 829
   Info: Unsanitized input from a database flows into database.execute_transaction, where it is used in an SQL query. This may result in an SQL Injection vulnerability.

 ✗ [MEDIUM] Debug Mode Enabled
   Finding ID: 17e45506-92d8-488b-aa85-04660510b6a1
   Path: app.py, line 1923
   Info: Running the application in debug mode (debug flag is set to True in run) is a security risk if the application is accessible by untrusted parties.

 ✗ [HIGH] Use of Hardcoded Cryptographic Key
   Finding ID: 24ed6957-74ca-4f0a-8f7c-eb16033193ab
   Path: auth.py, line 10
   Info: A hardcoded string value is used as a cipher key in jwt.decode. Generate the value with a cryptographically strong random number generator instead.

 ✗ [HIGH] Hardcoded Non-Cryptographic Secret
   Finding ID: 77e96a54-8770-4792-bcc0-8af2e63bc899
   Path: app.py, line 47
   Info: Avoid hardcoding values that are meant to be secret. Found a hardcoded string used in field assignment with hardcoded key.

 ✗ [HIGH] Improper Certificate Validation - SSL Verification Bypass
   Finding ID: b999daec-dfe2-4d48-9098-d4c7c96d9f93
   Path: app.py, line 590
   Info: Certificate verification is disabled by setting verify to False in requests.get. This may lead to Man-in-the-middle attacks.

 ✗ [HIGH] SQL Injection
   Finding ID: 82085958-0ef4-49b2-b472-d1020b817750
   Path: app.py, line 233
   Info: Unsanitized input from the HTTP request body flows into execute, where it is used in an SQL query. This may result in an SQL Injection vulnerability.

 ✗ [HIGH] SQL Injection
   Finding ID: 16410ae3-9fcf-4d9f-bb76-e5791d4c4f1a
   Path: app.py, line 1301
   Info: Unsanitized input from the HTTP request body flows into execute, where it is used in an SQL query. This may result in an SQL Injection vulnerability.

 ✗ [HIGH] SQL Injection
   Finding ID: 6833c737-f4dc-4ada-a835-6257b0cad395
   Path: app.py, line 1461
   Info: Unsanitized input from the HTTP request body flows into execute, where it is used in an SQL query. This may result in an SQL Injection vulnerability.

 ✗ [HIGH] SQL Injection
   Finding ID: 119763a6-04a1-4374-979f-93cd12b1211a
   Path: app.py, line 1630
   Info: Unsanitized input from the HTTP request body flows into execute, where it is used in an SQL query. This may result in an SQL Injection vulnerability.

 ✗ [HIGH] SQL Injection
   Finding ID: d54563d3-a57c-4d9b-bb5e-083f3f03266f
   Path: auth.py, line 120
   Info: Unsanitized input from the HTTP request body flows into execute, where it is used in an SQL query. This may result in an SQL Injection vulnerability.

 ✗ [HIGH] SQL Injection
   Finding ID: 47913d04-d599-44f2-af5c-6f23ae76776f
   Path: auth.py, line 187
   Info: Unsanitized input from the HTTP request body flows into execute, where it is used in an SQL query. This may result in an SQL Injection vulnerability.

 ✗ [HIGH] SQL Injection
   Finding ID: e67fe46d-397c-4acf-8d51-9ad0f669afec
   Path: auth.py, line 191
   Info: Unsanitized input from the HTTP request body flows into execute, where it is used in an SQL query. This may result in an SQL Injection vulnerability.

 ✗ [HIGH] SQL Injection
   Finding ID: 27b557b8-59e9-4def-ad11-5ba1beb7bc16
   Path: app.py, line 287
   Info: Unsanitized input from the HTTP request body flows into database.execute_query, where it is used in an SQL query. This may result in an SQL Injection vulnerability.

 ✗ [HIGH] SQL Injection
   Finding ID: fd3da157-3624-4f12-b182-33abcac25e81
   Path: app.py, line 913
   Info: Unsanitized input from the HTTP request body flows into database.execute_query, where it is used in an SQL query. This may result in an SQL Injection vulnerability.

 ✗ [HIGH] SQL Injection
   Finding ID: 863d9091-68ae-4ce0-8737-42d542cb9435
   Path: app.py, line 940
   Info: Unsanitized input from the HTTP request body flows into database.execute_query, where it is used in an SQL query. This may result in an SQL Injection vulnerability.

 ✗ [HIGH] SQL Injection
   Finding ID: a2513ae7-ee2a-4fbc-b115-99bfab600948
   Path: app.py, line 1039
   Info: Unsanitized input from the HTTP request body flows into database.execute_query, where it is used in an SQL query. This may result in an SQL Injection vulnerability.

 ✗ [HIGH] SQL Injection
   Finding ID: bc0fade8-42b7-4165-8846-4893366d96e5
   Path: app.py, line 1089
   Info: Unsanitized input from the HTTP request body flows into database.execute_query, where it is used in an SQL query. This may result in an SQL Injection vulnerability.

 ✗ [HIGH] SQL Injection
   Finding ID: e5cbf94a-0507-481b-a1ed-3f156e39673a
   Path: app.py, line 1565
   Info: Unsanitized input from the HTTP request body flows into database.execute_query, where it is used in an SQL query. This may result in an SQL Injection vulnerability.

 ✗ [HIGH] SQL Injection
   Finding ID: d72ee6ed-c7cb-4d09-bf87-5608cc5dec50
   Path: app.py, line 388
   Info: Unsanitized input from an HTTP parameter flows into database.execute_query, where it is used in an SQL query. This may result in an SQL Injection vulnerability.

 ✗ [HIGH] SQL Injection
   Finding ID: fc39cd80-bc77-4d44-a4a5-addd28b8c4d6
   Path: app.py, line 1251
   Info: Unsanitized input from an HTTP parameter flows into database.execute_query, where it is used in an SQL query. This may result in an SQL Injection vulnerability.

 ✗ [HIGH] SQL Injection
   Finding ID: b46bd00b-6ea1-4bc1-862d-8de8b224c355
   Path: app.py, line 452
   Info: Unsanitized input from the HTTP request body flows into database.execute_transaction, where it is used in an SQL query. This may result in an SQL Injection vulnerability.

 ✗ [HIGH] SQL Injection
   Finding ID: 9698acb3-4389-43e4-b682-903501978b33
   Path: app.py, line 497
   Info: Unsanitized input from an HTTP parameter flows into execute, where it is used in an SQL query. This may result in an SQL Injection vulnerability.

 ✗ [HIGH] SQL Injection
   Finding ID: e0ea33ad-f667-4da0-9ac0-b33732492ec5
   Path: auth.py, line 153
   Info: Unsanitized input from an HTTP parameter flows into execute, where it is used in an SQL query. This may result in an SQL Injection vulnerability.



╭────────────────────────────────────────────────────────────────────────╮
│ Test Summary                                                           │
│                                                                        │
│   Organization:      samjones56                                        │
│   Test type:         Static code analysis                              │
│   Project path:      /home/kali/Documents/AppSec/vuln-bank-original    │
│                                                                        │
│   Total issues:   51                                                   │
│   Ignored issues: 0 [ 0 HIGH  0 MEDIUM  0 LOW ]                        │
│   Open issues:    51 [ 21 HIGH  29 MEDIUM  1 LOW ]                     │
╰────────────────────────────────────────────────────────────────────────╯
    
💡 Tip

   To view ignored issues, use the --include-ignores option.
                                                            

