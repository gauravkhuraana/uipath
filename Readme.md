# MobileTestingProject1

This project was developed during a Hackathon organized by **The Test Tribe** on **26–27 April 2025**.

## Project Overview
This automation project is built using **UiPath** to perform end-to-end mobile testing on a **SauceLabs sample app**.  
The app allows users to log in, order products, and verify footer information.  
All automation test cases are structured for clarity and maintainability, with a focus on reusable components.

---

## Project Structure

- **Reusable Flows**
  - `CheckoutPersonDetailsWorkflow.xaml`: Handles checkout form details.
  - `LoginWorkFlow.xaml`: Manages user login flow.

- **TestCases**
  - **Filters**
    - `TC6_FilterValidation.xaml`: Validates product filter functionality.
  - **HomePage**
    - `TC2_HomePageValidation.xaml`: Verifies homepage elements and their correctness.
  - **LandingPage**
    - `TC1_LoginAndLogout.xaml`: Automates user login and logout scenarios.
    - `TC7_FooterValidations.xaml`: Validates footer links and texts.
  - **OrderProducts**
    - `TC3_Order1ProductCheckoutOrderId.xaml`: Places an order for a single product and checks the order ID.
    - `TC5_Add3Products_Checkout.xaml`: Adds three products and verifies checkout.
    - `TC8_Add3Remove1Product_Checkout.xaml`: Adds three products, removes one, and checks the cart.
    - `TC9_AddAllProducts_ChangeLayout_Checkout.xaml`: Adds all products, switches layout, and proceeds to checkout.
  - **SideBar**
    - `TC4_SideBarNavigation_8_Options.xaml`: Validates sidebar navigation with 8 options.

- **Others**
  - `project.json`: Project configuration and dependencies.
  - `Sequence.xaml`: Main sequence file (optional entry point or utility sequence).

---

## Tools & Technologies Used
- **UiPath Mobile Automation**
- **SauceLabs Device Cloud**
- **MobileDeviceConnection for App Testing**

---

## How to Run
1. Clone the repository or download the project.
2. Open it in **UiPath Studio**.
3. Connect to a mobile device via **SauceLabs**.
4. Run individual test cases or sequence files as required.

---

## Highlights
- Organized folder structure separating test cases and reusable components.
- Real-world e-commerce flows tested: Login, Product ordering, Sidebar navigation, and Footer validation.
- Designed for scalability and reuse, making it easy to add more test scenarios.

---
