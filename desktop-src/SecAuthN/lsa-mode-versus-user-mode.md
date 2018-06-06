---
Description: When an SSP/AP security package is functioning as an authentication package, it is loaded into the process space of the Local Security Authority (LSA) and is said to be in LSA mode.
ms.assetid: ff4e61be-dbaa-4cfa-8c72-43e99fe1c3cb
title: LSA Mode vs. User Mode
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# LSA Mode vs. User Mode

When an SSP/AP [*security package*](security.s_gly#-security-security-package-gly) is functioning as an [*authentication package*](security.a_gly#-security-authentication-package-gly), it is loaded into the process space of the [*Local Security Authority*](security.l_gly#-security-local-security-authority-gly) (LSA) and is said to be in LSA mode. Logon applications access authentication package functionality using the [LSA Logon Functions](authentication-functions.md#lsa-logon-functions). Developers can use LSA support functions available only to LSA-mode security packages to implement more sophisticated authentication packages than previously supported.

When a [*security package*](security.s_gly#-security-security-package-gly) provides security services to a client/server application, it is loaded into the client and server processes and is said to be in user mode. Client/server applications access the security package's security support services using Microsoft [*Security Support Provider Interface*](security.s_gly#-security-security-support-provider-interface-gly) (SSPI).

LSA support for SSP/APs includes functions that the LSA-mode and user-mode instances of a security package can use to communicate. Additionally, the user-mode instance of a security package can delegate selected requests for information to the LSA-mode instance of the package.

For details about how security packages are initialized for each mode, see [LSA-mode Initialization](lsa-mode-initialization.md) and [User-mode Initialization](user-mode-initialization.md).

 

 


