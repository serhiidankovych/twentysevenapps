# Privacy Policy

**Effective Date:** 2026-02-07

This Privacy Policy applies to the **Deadsign** mobile application (the **“Application”**) developed by **Serhii Dankovych** (the **“Service Provider”**) and provided as a **Free** service. The Application is provided **“AS IS”**, without warranties of any kind.

## 1. Information Collection and Use

The Application operates as a **strictly local, offline-first service**.

**The Application does not collect, store, transmit, or share any personal data.** No user information is sent to the Service Provider or to any third-party servers.

### User-Provided Data
All data you enter into the Application is stored **only on your device** via local storage mechanisms (AsyncStorage and FileSystem). This includes:
* Name
* Date of birth
* Country
* Life expectancy

From this information, the Application calculates derived values (such as age, weeks lived, and visual life tables) locally. 

### Log Data
The Application does **not** collect:
* Log data
* IP addresses
* Device identifiers (AdID, IDFA)
* Location data
* Analytics or usage statistics

## 2. Image Generation and Local File Storage

The Application includes features that allow you to generate visual representations (such as Life Table images).

### Local Processing
All image generation occurs **entirely on your device**. Images are temporarily cached in the Application’s internal sandbox storage.

### Media Library Access
If you choose to save a generated image to your device’s photo gallery, the Application will request permission to access your media library (e.g., `READ_MEDIA_IMAGES` or Photo Library permissions).

This permission is used **solely** to export the image you created to your local gallery. The Application:
* Does **not** scan or analyze your existing photos.
* Does **not** extract metadata from your library.
* Does **not** upload your photos to any server.

## 3. Notifications and Alarms

The Application uses **local notifications** to provide reminders.

On Android devices, permissions such as `POST_NOTIFICATIONS`, `SCHEDULE_EXACT_ALARM`, and `USE_EXACT_ALARM` are utilized. These permissions are required **only** to ensure notifications are delivered at the specific times scheduled by the user.

All notifications are scheduled locally. No notification data is sent to external push notification services (such as FCM or APNs).

## 4. Third-Party Services

The Application does **not** integrate with:
* Third-party analytics services (e.g., Google Analytics, Firebase)
* Advertising networks
* Cloud storage providers
* Tracking SDKs

## 5. Data Retention and Deletion

The Service Provider does not maintain any external database.

### Retention
All data remains on your device until you decide to remove it. Cloud backups are explicitly disabled in the Application configuration.

### Deletion
You may delete all user data instantly by:
1. Using the **Reset All Data** option inside the Application settings.
2. Uninstalling the Application.
3. Clearing the Application’s storage via your device’s system settings.

Once these actions are taken, the data is permanently removed from the device and cannot be recovered.

## 6. Children’s Privacy

The Application does not knowingly collect personal information from children under the age of 13. Since the Application functions offline and does not transmit data, no children's data is exposed to the Service Provider or third parties.

## 7. Security

Because all data is stored locally, the security of your information relies on your device’s security (screen lock, encryption). The Service Provider has configured the Application to disallow automatic cloud backups (`allowBackup: false`) to ensure your data remains strictly on your device.

## 8. Changes to This Privacy Policy

This Privacy Policy may be updated from time to time. Continued use of the Application after changes constitutes acceptance of the revised Privacy Policy.

## 9. Contact Information

If you have any questions about this Privacy Policy, please contact the Service Provider at:

📧 **[twentysevenapps@gmail.com](mailto:twentysevenapps@gmail.com)**
