## D424 Capstone Project: VacayWise Android App

This project was completed as part of the **D424 Capstone in Software Development** and demonstrates proficiency in Android mobile application development using the Android Software Development Kit (SDK). Throughout the project, I gained experience configuring the SDK, designing and implementing user interfaces, managing persistent data, and deploying an Android application through GitHub Pages.

The final product, **VacayWise**, is a vacation planning application designed to help travelers efficiently organize vacations and their associated excursions. The app provides full CRUD (Create, Read, Update, Delete) functionality, validation rules, and enhanced usability through integrated search, alerts, and data-sharing options. It also includes a secure login page to protect user data. VacayWise uses **Room Database** as an abstraction layer over **SQLite**, ensuring a streamlined and reliable data management process. A signed APK was generated for distribution, configured with `minSdk 26` and `targetSdk 36`.

---

## Getting Started

To get started, clone the repository:

```
git clone https://gitlab.com/wgu-gitlab-environment/student-repos/tnail4/d424-software-engineering-capstone.git
```

Open the project in **Android Studio**.
The application can be run using an **emulator** or on a **physical Android device** connected via USB or wireless debugging.

The signed APK can also be downloaded directly from the release page or via the hosted link:
[Download VacayWise APK](https://github.com/tnail45/vacaywise/releases/download/v1.0/app-release.apk)

---

## Application Features

### Adding Vacations

Users can add a new vacation by tapping the **+** button on the Vacation List page.
On the Vacation Details screen, users can enter a **title**, **hotel name**, and **start and end dates**. Vacations are saved by selecting **Save Vacation** from the menu. Associated excursions will appear beneath the vacation details.

**Additional features:**

* Set **notifications** for vacation start and end dates.
* **Share vacation details** via the Share option.
* Edit or delete vacations directly from the list.

**Validation rule:** The vacation end date must occur after the start date.

---

### Managing Excursions

Excursions are managed within the Vacation Details page.
By tapping the **+** button, users can open the Excursion Details page to add a **title** and **date**. Excursions are saved through the menu.

**Additional features:**

* Set **alerts** for excursion dates.
* Excursion dates are validated to ensure they fall **within the vacation’s duration**.

---

### Searching

VacayWise includes **search bars** for both the Vacation and Excursion List screens, allowing users to quickly locate trips or activities by name or keyword. This helps users manage large lists of planned vacations and excursions with ease.

---

### Authentication

A **login screen** provides secure access to the app. This authentication feature ensures that only authorized users can view or modify stored vacation data, reinforcing VacayWise’s commitment to user privacy and security.

---

## Technologies Used

* **Language:** Java & XML
* **Database:** Room (abstraction over SQLite)
* **IDE:** Android Studio
* **Version Control & Hosting:** GitHub / GitHub Pages
* **Deployment:** Signed APK hosted via GitHub Releases

---

## Deployment

The signed APK is hosted via **GitHub Releases**, and a lightweight **HTML download page** is published using **GitHub Pages**.
Users can access the hosted link to download and sideload the APK directly onto their Android devices.

---

## Validation Rules Summary

* A vacation’s **end date** must be later than its **start date**.
* An excursion’s **date** must fall within its associated vacation’s **date range**.

---

## Author

**Tim Nail**
D424 Capstone Project – Western Governors University
GitLab Repository: [VacayWise](https://gitlab.com/wgu-gitlab-environment/student-repos/tnail4/d424-software-engineering-capstone.git)
