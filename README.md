**Compose Multiplatform**

Compose Multiplatform یک چارچوب UI اعلامی برای به اشتراک گذاشتن UI ها در چندین پلتفرم با Kotlin است. این بر اساس Jetpack Compose ساخته شده است و توسط JetBrains و مشارکت کنندگان متن باز توسعه یافته است.

با استفاده از Compose Multiplatform می توانید UI خود را در پلتفرم های زیر به اشتراک بگذارید:

* iOS (نسخه آزمایشی)
* Android
* دسکتاپ (Windows، macOS، Linux)
* وب (آزمایشی)

به عنوان مثال، می توانید UI ها را بین iOS و Android یا Windows و MacOS به اشتراک بگذارید.

## iOS

> پشتیبانی iOS در نسخه آزمایشی است. ممکن است ناسازگار تغییر کند و در آینده نیاز به مهاجرت دستی داشته باشد.
> ما از بازخورد شما در کانال Slack عمومی #compose-ios استقبال می کنیم.
> اگر با هر گونه مشکلی مواجه شدید، لطفاً در GitHub گزارش دهید.

Compose Multiplatform بیشتر API خود را با Jetpack Compose، چارچوب UI Android توسعه یافته توسط Google، به اشتراک می گذارد.
می توانید از همان API ها برای ایجاد رابط های کاربری برای هر دو Android و iOS استفاده کنید.

از آنجایی که Compose بر اساس Kotlin Multiplatform ساخته شده است،
می توانید به راحتی به API های بومی مانند Camera API و درج  رابط های UI بومی پیچیده مانند MKMapView دسترسی پیدا کنید.

**با Compose Multiplatform شروع کنید: [https://jb.gg/start-cmp](https://jb.gg/start-cmp)**

## اندروید

وقتی Android یکی از اهداف شما باشد، می توانید همان تجربه را برای Android داشته باشید مانند اینکه در حال توسعه یک برنامه Android با استفاده از Jetpack Compose هستید.

**با Compose Multiplatform شروع کنید: [https://jb.gg/start-cmp](https://jb.gg/start-cmp)**

## دسکتاپ

Compose Multiplatform از JVM پشتیبانی می کند و در تمام پلتفرم های اصلی دسکتاپ از جمله macOS، Windows و Linux، رابط های کاربری با عملکرد بالا را ارائه می دهد.

این دارای افزونه های دسکتاپ برای منوها، میانبرهای صفحه کلید، تغییر شکل پنجره و مدیریت اعلان ها است.

**با Compose Multiplatform شروع کنید: [https://jb.gg/start-cmp](https://jb.gg/start-cmp)**

> ما از بازخورد شما در کانال Slack عمومی #compose استقبال می کنیم.

## وب

> پشتیبانی وب در حال آزمایش است و ممکن است در هر زمان تغییر کند. فقط برای اهداف ارزیابی استفاده کنید.
> ما از بازخورد شما در کانال Slack عمومی #compose-web استقبال می کنیم.
> اگر با هر گونه مشکلی مواجه شدید، لطفاً در GitHub گزارش دهید.

می توانید با آزمایش Compose for Web UI های موبایل یا دسکتاپ خود را با وب به اشتراک بگذارید. Compose for Web بر اساس Kotlin/Wasm، جدیدترین هدف برای پروژه های Kotlin Multiplatform ساخته شده است. این به توسعه دهندگان Kotlin اجازه می دهد کد خود را در مرورگر با همه مزایایی که WebAssembly ارائه می دهد، مانند عملکرد خوب و قابل پیش بینی برای برنامه های خود، اجرا کنند.

**با Compose for Web شروع کنید: [https://kotl.in/wasm-compose-example](https://kotl.in/wasm-compose-example)**

## کتابخانه ها

### Compose HTML

Compose HTML یک کتابخانه است که برای Kotlin/JS هدف گرفته شده است و بلوک های سازنده Composable را برای ایجاد رابط های کاربری وب با HTML و CSS ارائه می دهد.

> توجه داشته باشید که Compose HTML یک کتابخانه چند پلتفرمی نیست. فقط می توان از آن با Kotlin/JS استفاده کرد.

## بیشتر بدانید

* پرسش های متداول: [https://jb.gg/cmp-faq](https://jb.gg/cmp-faq)
* نمونه ها: [https://jb.gg/cmp-samples](https://jb.gg/cmp-samples)
* آموزش ها: tutorials/README.md
* سازگاری و نسخه بندی: [https://jb.gg/cmp-versioning](https://jb.gg/cmp-versioning)
* سابقه تغییرات: CHANGELOG.md
