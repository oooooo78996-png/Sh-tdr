SHANTO CANDLE LEARNING — ANDROID PROJECT
=========================================

এই অ্যাপটি শিক্ষামূলক candle-pattern practice tool।
এটি Quotex-এ connect করে না, live price/candle data নেয় না, UP/DOWN trade signal দেয় না,
কোনো auto-click/auto-trade/overlay নেই এবং real-money trading-এর জন্য নয়।

যা আছে:
- Regular / OTC নামে demo-label selector (এগুলো শুধু UI label)
- 30-second practice label
- ৩টি candle-এর OHLC input
- সাধারণ bullish/bearish/mixed candle count
- শেষ candle-এর body-to-range বর্ণনা
- practice analysis count ও local screen history

GitHub দিয়ে APK build:
1. ZIP extract করুন।
2. GitHub-এ নতুন repository তৈরি করুন।
3. ZIP-এর ভেতরের সব file/folder repository root-এ upload করুন।
4. `.github/workflows/build.yml` path ঠিক আছে নিশ্চিত করুন।
5. Actions tab খুলুন।
6. `Build Shanto Candle Learning APK` workflow নির্বাচন করুন।
7. `Run workflow` চাপুন।
8. সফল run-এর Artifacts থেকে `Shanto-Candle-Learning-APK` download করুন।
9. Artifact ZIP extract করলে `app-debug.apk` পাবেন।

Android build:
- JDK 17
- Gradle 8.7
- Android Gradle Plugin 8.6.1
- Compile SDK 35

নোট:
এটি AI/ML predictor নয়। মাত্র ৩টি candle দিয়ে নির্ভরযোগ্য market prediction করা যায় না।
Quotex-এর Regular ও OTC live feed-এর সঙ্গে সংযোগ নেই। কোনো output-কে trade entry হিসেবে ব্যবহার করবেন না।
