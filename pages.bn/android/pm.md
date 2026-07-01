# pm

> অ্যান্ড্রয়েড প্যাকেজ ম্যানেজার টুল।
> আরও তথ্য পাবেন: <https://developer.android.com/tools/adb#pm>।

- ইনস্টল করা প্যাকেজগুলোর তালিকা দেখুন:

`pm list packages`

- নির্দিষ্ট পাথ থেকে একটি অ্যাপ ইনস্টল করুন:

`pm install /{{path/to/app}}.apk`

- ডিভাইস থেকে একটি প্যাকেজ আনইনস্টল করুন:

`pm uninstall {{package}}`

- একটি প্যাকেজের সমস্ত অ্যাপ ডেটা মুছুন:

`pm clear {{package}}`

- একটি প্যাকেজ বা কম্পোনেন্ট এনেবল করুন:

`pm enable {{package_or_class}}`

- একটি প্যাকেজ বা কম্পোনেন্ট ডিজেবল করুন:

`pm disable-user {{package_or_class}}`

- একটি অ্যাপের জন্য পারমিশন প্রদান করুন:

`pm grant {{package}} {{android.permission.CAMERA|android.permission.ACCESS_FINE_LOCATION|android.permission.READ_CONTACTS|...}}`

- একটি অ্যাপের পারমিশন বাতিল করুন:

`pm revoke {{package}} {{android.permission.CAMERA|android.permission.ACCESS_FINE_LOCATION|android.permission.READ_CONTACTS|...}}`
