---
title: Policy CSP - Authentication
description: Policy CSP - Authentication
ms.author: maricia
ms.topic: article
ms.prod: w10
ms.technology: windows
author: nickbrower
ms.date: 05/03/2018
---

# Policy CSP - Authentication



<hr/>

<!--Policies-->
## Authentication policies  

<dl>
  <dd>
    <a href="#authentication-allowaadpasswordreset">Authentication/AllowAadPasswordReset</a>
  </dd>
  <dd>
    <a href="#authentication-alloweapcertsso">Authentication/AllowEAPCertSSO</a>
  </dd>
  <dd>
    <a href="#authentication-allowfastreconnect">Authentication/AllowFastReconnect</a>
  </dd>
  <dd>
    <a href="#authentication-allowfidodevicesignon">Authentication/AllowFidoDeviceSignon</a>
  </dd>
  <dd>
    <a href="#authentication-allowsecondaryauthenticationdevice">Authentication/AllowSecondaryAuthenticationDevice</a>
  </dd>
</dl>


<hr/>

<!--Policy-->
<a href="" id="authentication-allowaadpasswordreset"></a>**Authentication/AllowAadPasswordReset**  

<!--SupportedSKUs-->
<table>
<tr>
	<th>Home</th>
	<th>Pro</th>
	<th>Business</th>
	<th>Enterprise</th>
	<th>Education</th>
	<th>Mobile</th>
	<th>Mobile Enterprise</th>
</tr>
<tr>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>3</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>3</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>3</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>3</sup></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
</table>

<!--/SupportedSKUs-->
<!--Scope-->
[Scope](./policy-configuration-service-provider.md#policy-scope):

> [!div class = "checklist"]
> * Device

<hr/>

<!--/Scope-->
<!--Description-->
Added in Windows 10, version 1709. Specifies whether password reset is enabled for Azure Active Directory accounts. This policy allows the Azure AD tenant administrators to enable self service password reset feature on the windows logon screen.

<!--/Description-->
<!--SupportedValues-->
The following list shows the supported values:

-   0 (default) – Not allowed.
-   1 – Allowed.

<!--/SupportedValues-->
<!--/Policy-->

<hr/>

<!--Policy-->
<a href="" id="authentication-alloweapcertsso"></a>**Authentication/AllowEAPCertSSO**  

<!--SupportedSKUs-->
<table>
<tr>
	<th>Home</th>
	<th>Pro</th>
	<th>Business</th>
	<th>Enterprise</th>
	<th>Education</th>
	<th>Mobile</th>
	<th>Mobile Enterprise</th>
</tr>
<tr>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
</table>

<!--/SupportedSKUs-->
<!--Scope-->
[Scope](./policy-configuration-service-provider.md#policy-scope):

> [!div class = "checklist"]
> * User

<hr/>

<!--/Scope-->
<!--Description-->
Allows an EAP cert-based authentication for a single sign on (SSO) to access internal resources.

<!--/Description-->
<!--SupportedValues-->
The following list shows the supported values:

-   0 – Not allowed.
-   1 (default) – Allowed.

<!--/SupportedValues-->
<!--/Policy-->

<hr/>

<!--Policy-->
<a href="" id="authentication-allowfastreconnect"></a>**Authentication/AllowFastReconnect**  

<!--SupportedSKUs-->
<table>
<tr>
	<th>Home</th>
	<th>Pro</th>
	<th>Business</th>
	<th>Enterprise</th>
	<th>Education</th>
	<th>Mobile</th>
	<th>Mobile Enterprise</th>
</tr>
<tr>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /></td>
</tr>
</table>

<!--/SupportedSKUs-->
<!--Scope-->
[Scope](./policy-configuration-service-provider.md#policy-scope):

> [!div class = "checklist"]
> * Device

<hr/>

<!--/Scope-->
<!--Description-->
Allows EAP Fast Reconnect from being attempted for EAP Method TLS.

Most restricted value is 0.

<!--/Description-->
<!--SupportedValues-->
The following list shows the supported values:

-   0 – Not allowed.
-   1 (default) – Allowed.

<!--/SupportedValues-->
<!--/Policy-->

<hr/>

<!--Policy-->
<a href="" id="authentication-allowfidodevicesignon"></a>**Authentication/AllowFidoDeviceSignon**  

<!--SupportedSKUs-->
<table>
<tr>
	<th>Home</th>
	<th>Pro</th>
	<th>Business</th>
	<th>Enterprise</th>
	<th>Education</th>
	<th>Mobile</th>
	<th>Mobile Enterprise</th>
</tr>
<tr>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>3</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>3</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>3</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>3</sup></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
	<td><img src="images/crossmark.png" alt="cross mark" /></td>
</tr>
</table>

<!--/SupportedSKUs-->
<!--Scope-->
[Scope](./policy-configuration-service-provider.md#policy-scope):

> [!div class = "checklist"]
> * Device

<hr/>

<!--/Scope-->
<!--Description-->
Preview release in Windows 10, version 1709. Supported in the next release. Specifies whether Fast Identity Online (FIDO) device can be used to sign on. This policy enables the Windows logon credential provider for FIDO 2.0

Value type is integer.

Here is an example scenario: At Contoso, there are a lot of shared devices and kiosks that employees throughout the day using as many as 20 different devices. To minimize the loss in productivity when employees have to login with username and password everytime they pick up a device, the IT admin deploys SharePC CSP and Authentication/AllowFidoDeviceSignon policy to shared devices. The IT admin provisions and distributes FIDO 2.0 devices to employees, which allows them to authenticate to various shared devices and PCs.

<!--/Description-->
<!--SupportedValues-->
The following list shows the supported values:

-   0 - Do not allow. The FIDO device credential provider disabled. 
-   1 - Allow. The FIDO device credential provider is enabled and allows usage of FIDO devices to sign into an Windows.

<!--/SupportedValues-->
<!--/Policy-->

<hr/>

<!--Policy-->
<a href="" id="authentication-allowsecondaryauthenticationdevice"></a>**Authentication/AllowSecondaryAuthenticationDevice**  

<!--SupportedSKUs-->
<table>
<tr>
	<th>Home</th>
	<th>Pro</th>
	<th>Business</th>
	<th>Enterprise</th>
	<th>Education</th>
	<th>Mobile</th>
	<th>Mobile Enterprise</th>
</tr>
<tr>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>1</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>1</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>1</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>1</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>1</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>1</sup></td>
	<td><img src="images/checkmark.png" alt="check mark" /><sup>1</sup></td>
</tr>
</table>

<!--/SupportedSKUs-->
<!--Scope-->
[Scope](./policy-configuration-service-provider.md#policy-scope):

> [!div class = "checklist"]
> * Device

<hr/>

<!--/Scope-->
<!--Description-->
Added in Windows 10, version 1607. Allows secondary authentication devices to work with Windows.

The default for this policy must be on for consumer devices (defined as local or Microsoft account connected device) and off for enterprise devices (such as cloud domain-joined, cloud domain-joined in an on-premise only environment, cloud domain-joined in a hybrid environment, and BYOD).

<!--/Description-->
<!--ADMXMapped-->
ADMX Info:  
-   GP English name: *Allow companion device for secondary authentication*
-   GP name: *MSSecondaryAuthFactor_AllowSecondaryAuthenticationDevice*
-   GP path: *Windows Components/Microsoft Secondary Authentication Factor*
-   GP ADMX file name: *DeviceCredential.admx*

<!--/ADMXMapped-->
<!--SupportedValues-->
The following list shows the supported values:

-   0 – Not allowed.
-   1 – Allowed.

<!--/SupportedValues-->
<!--/Policy-->
<hr/>

Footnote:

-   1 - Added in Windows 10, version 1607.
-   2 - Added in Windows 10, version 1703.
-   3 - Added in Windows 10, version 1709.
-   4 - Added in Windows 10, version 1803.

<!--/Policies-->

<!--StartHoloLens-->
## <a href="" id="hololenspolicies"></a>Authentication policies supported by Windows Holographic for Business  

-   [Authentication/AllowFastReconnect](#authentication-allowfastreconnect)  
<!--EndHoloLens-->

<!--StartIoTCore-->
## <a href="" id="iotcore"></a>Authentication policies supported by IoT Core  

-   [Authentication/AllowFastReconnect](#authentication-allowfastreconnect)  
<!--EndIoTCore-->

