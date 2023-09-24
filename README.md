<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1DFOupqyidN_zv20pintUAV1y1FLW-LqD" alt="Your Image" />
</p>

# Google Summer Of Code'23 With LibreHealth
This document constitutes my submission for the Google Summer of Code'23 final report. Over the course of GSoC'23, I had the privilege of collaborating with LibreHealth and making significant contributions to their NeoRoo application.

Throughout this period, I embarked on a journey of innovation and collaboration, pushing the boundaries of what the NeoRoo application could achieve. My work spanned various critical aspects, from enhancing user experience to implementing intricate functionalities. This report outlines the key milestones and accomplishments achieved during this enriching experience.

## Project Overview
Around 15 million premature infants are born annually, predominantly in low and middle-income nations, where the risk of neonatal mortality is notably higher. A prevalent issue among preterm births is neonatal hypothermia, a condition that can be effectively mitigated through Kangaroo Mother Care/Skin-to-Skin care (KMC/STS). Nevertheless, the widespread adoption of KMC/STS faces barriers including limited healthcare personnel and the labor-intensive nature of neonatal care. These constraints impede the consistent implementation of KMC/STS on a larger scale.

This project aims to create an automated system for monitoring vital signs, managing multiple patients simultaneously, and enabling collaborative goal setting for education, KMC, and discharge planning. The core objective of this application revolves around issuing prompt alerts to parents and caregivers whenever irregularities in vital signs are detected, thereby preempting adverse outcomes. The feasibility and acceptance of this innovation within US healthcare facilities are currently under evaluation.

# [Proposal Link](https://docs.google.com/document/d/1q9DTqlZz-uUOLluArAkdCrcy4aYDVFAjvMgzSmtjT50/edit?usp=sharing)
# [GSoC Project Page](https://summerofcode.withgoogle.com/programs/2023/projects/QKyiu6a7)
# [GitLab Organization Repository](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo)
# [GitLab Personel Repository](https://gitlab.com/Mehul-Kumar-27/lh-mhbs-neoroo)

***

# Key Milestones Achieved ⭐

### ✅ Preparing NeoRoo Applications To Work with Any Dhis2 Server.
- Each tracked entity and its attributes are linked to a distinct UID, which varies across different Dhis2 servers. To enhance flexibility, we incorporated a feature to retrieve these UIDs from the server and generate them if absent. This dynamic implementation transformed the NeoRoo application, enabling seamless compatibility with any Dhis2 server. Previously, these UIDs were hardcoded for a specific Dhis2 server within the application.
  
<div align="center">

| [Related Issue](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/issues/38)         | [Related Merge Request](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/merge_requests/40) |
|-----------------------|-----------------------|

</div>

### ✅ Enhancing Authentication Flow  by adding UserRoles.
- During authentication, we implemented functionality to obtain the user's role, such as Caregiver or Parent. This helps us ensure that users see the relevant data for their assigned role.

<div align="center">

| [Related Issue](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/issues/38)         | [Related Merge Request](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/merge_requests/40) |
|-----------------------|-----------------------|

</div>

### ✅ Feature to add and fetch infants from the DHIS2 server.
- The feature to add and fetch the infants from the dhis2 server are the fundamentals of the NeoRoo application. With this the user can so this without any problem.
 
<div align="center">

| [Related Issue](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/issues/47) | [Related Merge Request](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/merge_requests/47) |
|-----------------------|-----------------------|

</div>

### ✅ Feature to Update the infant details.
- The feature to update the infant details would help us the track the progress of the infant health and would help us in stay uptaded with the current information.

<div align="center">

| [Related Issue](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/issues/48) | [Related Merge Request](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/merge_requests/48) |
|-----------------------|-----------------------|

</div>

### ✅ Functionality to scan for the Bluetooth devices nearby.
- Establishing connection with the bluetooth device would be a key component of the NeoRoo application. This summer we added the functionqality to scan for the available bluetooth devices nearby and show o user.

<div align="center">

| [Related Issue](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/issues/49) | [Related Merge Request](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/merge_requests/58) |
|-----------------------|-----------------------|

</div>

### ✅ Added Chat feature withing the NeoRoo application.
- Communication between the parents and the caregivers would be a vital for the success of the NeoRoo program. With this feature the communication ca be done within the NeoRoo platform and would avoid any delay.

<div align="center">

| [Related Issue](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/issues/81) | [Related Merge Request](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/merge_requests/68) |
|-----------------------|-----------------------|

</div>

### ✅ Added the feature to import infants from the ECEB program to NeoRoo program.
- ECEB (Essential Care for Ever Baby),  is another program of LibreHealth which focuses on again monitoring the infants health. With addition of this feature caregivers can now add any infant already enrolled in the ECEB program to NeoRoo program.

<div align="center">

| [Related Issue](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/issues/83) | [Related Merge Request](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/merge_requests/54) |
|-----------------------|-----------------------|

</div>

### ✅ Added a ToDo functionality for Caregivers.
- Caregivers all around the world have a very demanding day. It is essential to add a functionality so that they can better organize their day and time. This feature is focused to fulfil this goal.

<div align="center">

| [Related Issue](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/issues/89) | [Related Merge Request](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/merge_requests/61) |
|-----------------------|-----------------------|

</div>

### ✅ Feature to Set and Edit Skin-To-Skin and Non Skin-To-Skin Goals of Infant and Prepare Graph.
- This feature helps parents and caregivers set and update the STS and NSTS goals for the infant. It is essential that parents and caregivers know exactly how many KMC hours are being dedicated to the infant. To track this, we have also added graphs that visually display the amount of KMC hours given to the infant.

<div align="center">

| Related Issue         | Related Merge Request |
|-----------------------|-----------------------|
| [Graph](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/issues/90)               | [Merge Request](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/merge_requests/62)                  |
| [Edt Goals](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/issues/91)               | [Merge Request](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/merge_requests/65)                  |

</div>

### ✅ Adding Parent of Infant to Dhis2 Server using unique QR Code for infant.
- To esure that the parents assigned to the infants are correct we have added the functonality to generate qr code for a particular infant unique to them. This qr code would be generated by the caregiver and would be scanned by the parents to register themselves and created their account on the DHIS2 server.

<div align="center">

| Related Issue         | Related Merge Request |
|-----------------------|-----------------------|
| [Create User](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/issues/92)               | [Merge Request](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/merge_requests/68)                  |
| [Generate QR Code](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/issues/95)               | [Merge Request](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/merge_requests/72)                  |

</div>

### ✅ Adding On Call Doctor Programs in the application.
- On call doctor program helps the parents to see the nurses, doctors and other caregivers who are currently doing their shifts and are available.

<div align="center">

| [Related Issue](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/issues/84) | [Related Merge Request](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/merge_requests/59) |
|-----------------------|-----------------------|

</div>

### ✅ Added Unit Test Cases Using Mokito.

<div align="center">

| [Related Issue](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/issues/101) | [Related Merge Request](https://gitlab.com/librehealth/incubating-projects/mhbs/lh-mhbs-neoroo/-/merge_requests/76) |
|-----------------------|-----------------------|

</div>
***

# What left ? 🤔

- [ ] Sending Emails to the User for conformation, password changes etc.
- [ ] Adding feature to obtain data from the NeoWarm device. This feature would be implemented once the final design of NeoWarm jacket is available.
- [ ] Integrating UI of some pages with the BLoC architecture.
- [ ] Fixing bugs in the application.

<details>
<summary><h1>Uncover My Archive of Weekly Blogs 📝</h1></summary>
<br>
  
- [Week 1](https://mehulkumar.hashnode.dev/week-1-gsoc23-with-librehealth)
  
- [Week 2](https://mehulkumar.hashnode.dev/week-2-gsoc23-with-librehealth)
  
- [Week 3](https://mehulkumar.hashnode.dev/week-3-gsoc23-with-librehealth)
  
- [Week 4](https://mehulkumar.hashnode.dev/week-4-gsoc23-with-librehealth)

- [Week 5](https://mehulkumar.hashnode.dev/week-5-gsoc23-with-librehealth)

- [Week 6](https://mehulkumar.hashnode.dev/week-6-gsoc23-with-librehealth)

- [Week 7](https://mehulkumar.hashnode.dev/week-7-gsoc23-with-librehealth)

- [Week 8](https://mehulkumar.hashnode.dev/week-8-gsoc23-with-librehealth)

- [Week 9](https://mehulkumar.hashnode.dev/week-9-gsoc23-with-librehealth)

- [Week 10](https://mehulkumar.hashnode.dev/week-10-gsoc23-with-librehealth)

- [Week 11](https://mehulkumar.hashnode.dev/week-11-gsoc23-with-librehealth)

- [Week 12](https://mehulkumar.hashnode.dev/week-12-gsoc23-with-librehealth)
  
</details>

### References
- [Flutter Documentaton](https://docs.flutter.dev/)
- [DHIS2 Documentation](https://docs.dhis2.org/en/develop/using-the-api/dhis-core-version-239/introduction.html)

