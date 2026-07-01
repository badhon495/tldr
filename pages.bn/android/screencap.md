# screencap

> একটি মোবাইল ডিসপ্লের স্ক্রিনশট নিন।
> এই কমান্ডটি শুধুমাত্র `adb shell` এর মাধ্যমে ব্যবহার করা যাবে।
> আরও তথ্য পাবেন: <https://developer.android.com/tools/adb#screencap>।

- একটি স্ক্রিনশট নিন:

`screencap {{path/to/image.png}}`

- ফাইলের বিষয়বস্তু PNG হিসাবে `stdout`-এ প্রিন্ট করুন:

`screencap -p`

- একটি `adb` সংযোগের মাধ্যমে স্ক্রিনশট নিন এবং সংরক্ষণ করুন:

`adb shell screencap -p > {{path/to/image.png}}`

- সাহায্য প্রদর্শন করুন:

`screencap -h`
