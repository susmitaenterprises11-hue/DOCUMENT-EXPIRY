कागजात म्याद व्यवस्थापन - Android परियोजना

यो Android Studio मा खोल्न मिल्ने source project हो। यस वातावरणमा Android SDK/Gradle build tool उपलब्ध नभएकाले तयार APK कम्पाइल गरिएको छैन।

APK बनाउने तरिका:
1. Android Studio स्थापना गर्नुहोस्।
2. यस ZIP लाई Extract गर्नुहोस्।
3. Android Studio बाट DocumentExpiry फोल्डर खोल्नुहोस्।
4. Gradle sync पूरा हुन दिनुहोस् र आवश्यक Android SDK (API 35) स्थापना गर्नुहोस्।
5. Build > Build Bundle(s) / APK(s) > Build APK(s) छान्नुहोस्।
6. सफल भएपछि APK app/build/outputs/apk/debug/app-debug.apk मा हुनेछ।

नोट:
- यो पहिलो संस्करण हो; कागजातको विवरण WebView/ब्राउजरको स्थानीय भण्डारणमा राखिन्छ।
- एप अनइन्स्टल गर्दा वा app data मेटाउँदा विवरण हराउन सक्छ। एपको Export सुविधा प्रयोग गरी ब्याकअप राख्नुहोस्।
- सूचना अहिले एपभित्र देखाइने रिमाइन्डर हो; बन्द एप हुँदा स्वतः Android push notification पठाउने सुविधा यस संस्करणमा छैन।
