# 📱 MDM Device Inventory and Security Assessment

## 1. Project Overview

This exercise focuses on identifying, reviewing, and assessing device information through the ManageEngine Mobile Device Management (MDM) platform.

The objective is to understand how organisations monitor enrolled mobile devices, maintain device inventories, and assess their security posture.

## 2. Tools Used

- ManageEngine Mobile Device Manager Plus
- ManageEngine MDM Self Service (Android)
- Android smartphone (Infinix)
- Web-based administration dashboard

## 3. Device Inventory Information

The following information was identified as available through the ManageEngine device inventory dashboard.

| Inventory Field | Device Information |
|---|---|
| Username | Advanced Breed |
| Device Name | Infinix Note 30 Pro |
| Email | nsi*****@gmail |
| Device Type | Smartphone |
| Platform | Andriod |
| OS Version | 14 |
| Device Model | NOTE30 PRO |
| Free Space (GB) | 29.89GB |
| Carrier Setting Version | -- (Android devices don’t report this; it showed “--” in the dashboard) |
| Management Type | Profile Owner (Work Profile) |
| Device Location Status | Geo-Tracking is off by default(Not Tracked) |
| Last Connected Through | Wifi |

## 4. Security Assessment

The inventory information provides useful insights into mobile device security and management.

**A. Device Identification**

Username, device name, email, and device model help administrators identify devices and associate them with their respective users.

**B. Operating System Assessment**

The platform and OS version help administrators determine whether devices are running supported operating systems and identify potential patching requirements.

**C. Storage Monitoring**

Available storage helps administrators monitor device capacity and identify potential storage-related operational issues.

**D. Device Management**

Management type helps administrators understand how a device is enrolled and managed within the organisation.

**E. Connectivity Monitoring**

Last connected through provides useful information about the device's most recent management communication.

**F. Location Monitoring**

Device location status helps administrators understand whether location reporting is available.

## 5. Security Relevance

Mobile Device Management helps organisations:

- Maintain visibility over enrolled devices.
- Monitor device operating systems.
- Manage mobile security configurations.
- Enforce organisational security policies.
- Monitor device connectivity.
- Improve endpoint security and compliance.

## 6. Current Lab Progress

- [x] ManageEngine environment configured.
- [x] Android device enrolled.
- [x] Device group created.
- [x] Passcode configuration profile created.
- [x] Profile published.
- [x] Device inventory fields identified.
- [x] Actual device inventory values documented.
- [x]  Security assessment completed using actual device information.
- [x]  Profile deployment independently verified.

## 7. Conclusion

This exercise demonstrates how MDM platforms provide administrators with centralised visibility into enrolled mobile devices.

Understanding device inventory information is an important part of endpoint security, asset management, and mobile device compliance.

The next stage will involve examining device compliance, installed applications, and security policy enforcement.
