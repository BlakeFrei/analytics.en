---
description: Adobe Report Builder supports the .xlsm format that lets you schedule macro-enabled workbooks.
seo-description: Adobe Report Builder supports the .xlsm format that lets you schedule macro-enabled workbooks.
seo-title: Schedule macro-enabled workbooks
solution: Analytics
title: Schedule macro-enabled workbooks
topic: Report builder
uuid: 97a291bf-45bf-453d-a4ae-3776f671c002
index: y
internal: n
snippet: y
translate: y
---

# Schedule macro-enabled workbooks

This can be useful if you need to safely schedule, process, and receive macro-enabled workbooks. 

>[!IMPORTANT]
>
>Even though Report Builder lets you schedule workbooks with macros, these macros are not exercised during each scheduled run. They are only exercised when the workbook is open within the native Microsoft Excel application.

Scheduled workbooks with macros can only be delivered in macro-enabled format (.xlsm), because all other supported formats (xls, xlsx, pdf, word, csv, or txt) would remove the macros from the workbook. 