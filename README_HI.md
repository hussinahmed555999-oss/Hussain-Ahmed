# MyGPT WhatsApp — Android prototype

यह Android Studio का शुरुआती प्रोजेक्ट है। इसमें डार्क UI, AI Assistant स्क्रीन,
Android speech-to-text intent और फोन के Text-to-Speech से जवाब सुनाने का डेमो है।

## ज़रूरी सीमाएँ
- यह अभी **पूरा WhatsApp-जैसा ऐप नहीं** है।
- चैट के जवाब फिलहाल डेमो टेक्स्ट हैं; असली AI के लिए सुरक्षित backend और AI API जोड़ना होगा।
- असली यूज़र-टू-यूज़र चैट, अकाउंट, मीडिया, ग्रुप, कॉलिंग, पुश नोटिफिकेशन और end-to-end encryption अभी शामिल नहीं हैं।
- पुरुष/महिला आवाज़ का चयन फोन में उपलब्ध TTS voices पर निर्भर है; हर फोन/भाषा में दोनों विकल्प उपलब्ध नहीं होंगे।
- Speech recognition के लिए Android पर समर्थित speech service और माइक्रोफ़ोन अनुमति/सेटअप चाहिए।

## APK बनाने का तरीका
1. कंप्यूटर पर Android Studio इंस्टॉल करें।
2. इस ZIP को extract करें और Android Studio में `MyGPTWhatsApp` फ़ोल्डर खोलें।
3. Gradle sync पूरा होने दें।
4. फोन में Developer options और USB debugging चालू करके USB से जोड़ें, या emulator चलाएँ।
5. Run दबाएँ। APK के लिए: **Build > Build Bundle(s) / APK(s) > Build APK(s)**।
6. APK आम तौर पर `app/build/outputs/apk/debug/app-debug.apk` में बनेगी।

यह प्रोजेक्ट Android Studio/Gradle से build करने के लिए source code है; इस ZIP में पहले से बनी APK शामिल नहीं है।
