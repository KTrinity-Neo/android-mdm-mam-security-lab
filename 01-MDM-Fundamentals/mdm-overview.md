# Mobile Device Management (MDM)

## 1. Objective

Understand Mobile Device Management (MDM), its role in enterprise cybersecurity, and how organisations use MDM solutions to centrally manage, monitor, and secure mobile devices.

The practical objective is to explore ManageEngine MDM by enrolling and managing an Android device, configuring security policies, and examining device inventory information.

## 2. What is MDM?

Mobile Device Management (MDM) is a security and administration approach that enables organisations to centrally manage, monitor, configure, and secure mobile devices connected to their corporate environment.

MDM helps IT administrators maintain control over organisational devices, enforce security requirements, monitor compliance, and protect sensitive information.

## 3. Key Functions of MDM

- Device enrollment and registration.
- Centralised device administration.
- Security policy configuration and enforcement.
- Password and screen-lock requirements.
- Device compliance monitoring.
- Application inventory and device monitoring.
- Remote management of enrolled devices.
- Corporate data protection.

## 4. Tools and Technologies Used

- **ManageEngine Mobile Device Manager Plus:** MDM administration and device management.
- **ManageEngine MDM Self Service:** Android device enrollment and user-side interaction.
- **Android Smartphone (Infinix):** Enrolled test device.
- **GitHub:** Project documentation and practical evidence.

## 5. Practical Implementation

The following activities have been completed during the practical lab exercise:

### A. MDM Environment Setup

- Accessed and configured the ManageEngine MDM environment.
- Installed the ManageEngine MDM Self Service application on the Android test device.
- Logged into the administration dashboard.

### B. Device Enrollment

- Successfully enrolled an Infinix Android smartphone.
- Confirmed the device was visible in the ManageEngine administration dashboard.

### C. Device Group Management

- Created a device group.
- Added the enrolled Infinix device to the group.
- Explored how device grouping supports centralised administration and policy management.

### D. Security Profile Configuration

- Created an Android passcode security profile.
- Configured a minimum password length of 8 characters.
- Selected Low and High password complexity.
- Published the configured profile.

**Important:** Profile publication was confirmed, but association, deployment, and actual enforcement on the Android device have not yet been independently verified.

### E. Device Inventory Exploration

Explored the device inventory information available through the ManageEngine dashboard, including:

- Username
- Device Name
- Email
- Device Type
- Platform
- Operating System Version
- Device Model
- Available Storage
- Carrier Setting Version
- Management Type
- Device Location Status
- Last Connected Through

This exercise demonstrated how MDM platforms provide administrators with visibility into enrolled mobile devices.

## 6. Security Policies and Device Assessment

The following security areas have been explored or identified for practical testing:

| Security Area                 | Current Status       |
| ----------------------------- | -------------------- |
| Device enrollment             | Completed            |
| Device grouping               | Completed            |
| Passcode profile creation     | Completed            |
| Minimum password length (8)   | Configured           |
| Password complexity (Low)     | Configured           |
| Profile publication           | Completed            |
| Screen-lock enforcement       | Pending verification |
| Automatic screen-lock timeout | Pending              |
| Device compliance assessment  | Pending              |
| Work Profile security         | Pending              |

## 7. Security Relevance

The practical exercise demonstrates how MDM contributes to enterprise cybersecurity through:

- **Access Control:** Establishing authentication requirements for mobile devices.
- **Endpoint Security:** Managing and monitoring enrolled mobile endpoints.
- **Asset Management:** Maintaining visibility into device ownership, specifications, and status.
- **Security Compliance:** Monitoring whether devices satisfy organisational security requirements.
- **Data Protection:** Supporting the protection of sensitive corporate information.
- **Centralised Administration:** Allowing administrators to manage multiple devices through a central platform.

## 8. Lessons Learned

Through this practical exercise, I have developed a better understanding of:

- How MDM solutions support enterprise mobile security.
- How Android devices are enrolled into an MDM environment.
- How device groups simplify centralised administration.
- How administrators configure and publish security profiles.
- How device inventory information supports endpoint visibility.
- Why configuring and publishing a policy is different from deploying and verifying its enforcement.

## 9. Current Project Status

**Status: Practical implementation in progress.**

The MDM environment has been configured, an Android device successfully enrolled, a device group created, and a passcode security profile configured and published.

Device inventory exploration has also been initiated.

Further activities will focus on policy deployment and enforcement, device compliance assessment, automatic screen-lock verification, and Android Work Profile security.

## 10. Next Steps

- Verify security profile association and deployment.
- Test screen-lock and password policy enforcement.
- Explore device compliance monitoring.
- Investigate Android Work Profile configuration.
- Capture practical screenshots and document test results.
- Proceed to Mobile Application Management (MAM).

## 11. Conclusion

This project has provided practical exposure to Mobile Device Management and its importance in enterprise cybersecurity beyond understanding the theoretical concepts, the lab has introduced the process of enrolling Android devices, managing device groups, configuring security profiles, and examining device inventory information.

The project is ongoing, with further practical testing planned to strengthen my understanding of endpoint security, mobile device administration, and corporate data protection.
