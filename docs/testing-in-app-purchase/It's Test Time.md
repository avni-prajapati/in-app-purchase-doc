---
sidebar_position: 1
---

![testing_meme](/img/testing_meme.jpg)

## Android 

- To test in-app purchases for products and subscriptions you need a **physical device**. 📱

1. First upload a build with code integration into internal testing and add testers to internal testing by following **[this](docs/internal-test-google-play/internal_test.md)** steps.
2. Access the build and install application via gmail in your android device.
3. After successfully purchasing product you can verify it in your **Google Play account/Payments and subscriptions/Subscriptions**.
4. And for subscription you can verify at **Google Play account/Payments and subscriptions/Budget and history**.

:::info Note that...
- Google Play will automatically identify your tester-email and mimic the purchase.
:::

## iOS

- To test in-app purchases for products and subscriptions you need a **physical device** 📱 as simulator does not support testing. ❌

1. First upload a build with code integration into testflight and add testers to internal testing group by following **[this](docs/internal-test-release-app-store/Step1.md)** steps.
2. Access the build and install application in TestFlight application .
3. After successfully purchasing product you can verify it in your **Apple account/Purchase History**.

:::info Note that...
- App store will automatically identify your tester-email and mimic the purchase with apple credentials.
- You can test the application via SendBox user too but, for that you have to first add the user in SendBox section on App Store connect. 
:::