# 💬 Wegap Widget for React Native / ویجت ویگپ برای React Native

This repository contains the official React Native version of the Wegap widget.  
این مخزن شامل نسخه رسمی ویجت ویگپ برای اپلیکیشن‌های React Native است. با استفاده از این ویجت می‌توانید قابلیت‌هایی مانند **چت، تماس صوتی/تصویری و دانشیار هوش مصنوعی** را به اپ موبایل خود اضافه کنید.

---

## 📦 Installation / نصب

```bash
npm install @wegapnet/widget-react-native
# or
yarn add @wegapnet/widget-react-native
```

---

## 🚀 Quick Usage / استفاده سریع

```jsx
import React from 'react';
import { SafeAreaView, Text } from 'react-native';
import WegapWidget from '@wegapnet/widget-react-native';

const App = () => {
  return (
    <SafeAreaView style={{ flex: 1 }}>
      <Text>My App / اپلیکیشن من</Text>
      <WegapWidget
        authKey="YOUR_AUTH_KEY"
        theme="light"
        position="bottom-right"
        language="fa"
      />
    </SafeAreaView>
  );
};

export default App;
```

---

## ⚙️ Config Options / تنظیمات

| Prop Name | Type   | Description EN                                      | توضیح فارسی |
|-----------|--------|------------------------------------------------------|--------------|
| authKey   | string | Your unique authentication key                      | کلید احراز هویت شما |
| theme     | string | Theme mode: `light` or `dark`                       | تم: روشن یا تیره |
| position  | string | Widget position: `bottom-right`, `bottom-left`, etc | موقعیت ویجت |
| language  | string | Default widget language (fa, en, ar, ...)           | زبان پیش‌فرض |

---

## 📄 Documentation / مستندات کامل

- [See full guide in Wegap Wiki](https://wegap.net/wiki/react-native/نصب-و-راه-اندازی/راهنمای-ویجت-ویگپ/دانشیار-ویگپ-id-8916)
- مشاهده راهنما در ویکی ویگپ ↑
