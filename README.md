# The Ignite Academy — UI Design Kit

এই ZIP-এ Android Studio project-এর জন্য UI reference package আছে।

## ফোল্ডার
- `web-admin-reference/index.html` — browser-এ চালানো যায় এমন responsive UI prototype। Sidebar থেকে screen বদলানো যায় এবং Role selector দিয়ে Admin, Student, Teacher, Parent preview করা যায়।
- `android-compose/` — Jetpack Compose theme, reusable components এবং integration guide।
- `design-spec.md` — screen inventory, colors, typography, navigation ও implementation notes।

## Prototype চালানো
`web-admin-reference/index.html` ফাইলটি Chrome/Edge-এ খুলুন। এটি static front-end prototype; Firebase বা live payment সংযুক্ত নয়।

## Android Studio-তে ব্যবহার
1. নিজের Android project-এর package name অনুযায়ী Kotlin package path ঠিক করুন।
2. `android-compose/`-এর Theme ও Components ফাইল আপনার app module-এ কপি করুন।
3. `design-spec.md` অনুসারে প্রতিটি screen আলাদা Compose route হিসেবে তৈরি করুন।
4. Existing project structure/Gradle version না দেখে build files replace করবেন না।
5. UI prototype-এর sample data production data হিসেবে ব্যবহার করবেন না।

## গুরুত্বপূর্ণ
এই ZIP হলো UI design starter/reference, সম্পূর্ণ backend বা production app নয়। Authentication, Firestore, Storage, FCM, Security Rules এবং Admin API আলাদাভাবে configure ও test করতে হবে।
