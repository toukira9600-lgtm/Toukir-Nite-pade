# মোবাইল দিয়ে APK তৈরি করার নির্দেশনা

এই সংস্করণটি অফলাইন ডেমো: SIM/মোবাইল নম্বর/ওয়ালেটের অ্যাকাউন্টের নাম ও নোট ফোনে সেভ করে। PIN/OTP/পাসওয়ার্ড রাখবেন না। Gmail লগইন ও ক্লাউড সিঙ্ক এখনো যুক্ত নয়।

## GitHub Actions দিয়ে APK বানান (মোবাইল Chrome)
1. github.com এ অ্যাকাউন্ট খুলে লগইন করুন।
2. New repository তৈরি করুন; নাম দিন `toukir-cloud-diary` এবং Public বা Private বেছে Create করুন।
3. Add file > Upload files থেকে ZIP ফাইলটি আগে ফোনে Extract করে ভেতরের ফাইল/ফোল্ডারগুলো আপলোড করুন। `.github` ফোল্ডারটিও অবশ্যই আপলোড করবেন।
4. Commit changes চাপুন।
5. Repository-র Actions ট্যাবে যান। `Build Android APK` workflow চলবে। প্রথমবার GitHub Actions অনুমতি চাইলে Enable করুন।
6. কাজ শেষ হলে সবুজ টিকসহ run খুলুন; নিচের Artifacts থেকে `Toukir-Cloud-Diary-APK` ডাউনলোড করুন। ZIP extract করে `app-debug.apk` ইনস্টল করুন। Android চাইলে browser/file manager-কে Install unknown apps অনুমতি দিন।

Build ব্যর্থ হলে Actions-এর লাল error-এর screenshot দিন।
