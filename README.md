<p align="center"><img src="https://d7team.com/icon-512.png" width="88" alt="Delta Seven"></p>
<h1 align="center">Advanced MDT</h1>
<p align="center"><b>FiveM Police MDT for QBCore, QBox & CFW</b></p>
<p align="center"><a href="#english">English</a> · <a href="#arabic">العربية</a></p>

<p align="center"><a href="https://d7team.com/products/advanced-mdt"><img src="https://img.youtube.com/vi/OyMPzluRDQQ/maxresdefault.jpg" alt="Advanced MDT" width="860"></a></p>

<a id="english"></a>

## Advanced MDT — FiveM Police MDT for QBCore, QBox & CFW

FiveM police MDT for QBCore, QBox & CFW: cases, citizen search, wanted records, an evidence camera, charges, fingerprints and officer points.

MDT system built for QBCore & QBox, for official roles such as police, investigations and military affairs — case management, search, wanted records, evidence, and organised information inside your server.

> This repository is documentation only. The resource is sold on our store and downloaded from the Client Area after you redeem your code.

[Website](https://d7team.com/products/advanced-mdt) · [Installation guide](https://d7team.com/guides/advanced-mdt) · [Store](https://store.d7team.com/advanced-mdt/p911730490) · [Discord](https://discord.gg/d-7)

### At a glance

| | |
|---|---|
| **Works with** | QBCore and QBox servers, CFW included |
| **Inventories** | ox_inventory, qb-inventory, qs-inventory, ps-inventory and lj-inventory |
| **Housing** | qb-houses, ps-housing and qs-housing |
| **Opening** | Laptop item, /mdt command or a key |
| **Interaction** | Target, Interact or marker |
| **Departments** | Any job — police, sheriff, DOJ and more |

### Features

#### Search and citizen profiles

- Search citizens, cases, phone numbers, citizen IDs, fingerprints and properties.
- Citizen profile: personal details, photo, phone, bank balance, vehicles, properties, wanted status and case history.
- Vehicle lookup by plate, or the nearest vehicle.

#### Cases

- Create, view, edit, close and approve cases.
- Case notes, and charges that total the fine and jail time automatically.
- Case approval and editing limited by job grade.
- Share cases between departments, or keep each department's cases to itself.

#### Evidence

- Evidence with notes, images and attachments inside the case.
- Evidence camera: take a photo in game and attach it to the case.
- Attach items from your inventory as evidence.

#### Wanted, charges and fingerprints

- Wanted records with a wanted level, a reason and an archive.
- Charges list with categories, fines and jail time, editable from the MDT.
- Fingerprint scan of a nearby person, who is asked to give their print, showing name, citizen ID, phone, birth date, wanted status and crime history.

#### Officers

- Officers page: members, on-duty status, points, wings and case activity.
- Go on and off duty from the MDT.
- Officer points and wings shared with Advanced BossMenu.
- Wing permissions for extra access control inside the MDT.

#### Configuration and logs

- One profile per department with its own name, logo, features and grade permissions.
- Turn each feature on or off per department: search, cases, charges, wanted, fingerprint, notes, points and wings.
- Discord logs for cases, evidence, wanted records, charges, notes, points and wings — per department or in one channel.
- A clean laptop-style interface.

### Video

[![Advanced MDT](https://img.youtube.com/vi/OyMPzluRDQQ/hqdefault.jpg)](https://www.youtube.com/watch?v=OyMPzluRDQQ)

### Requirements

- A QBCore or QBox server, CFW included
- oxmysql
- ox, qb, qs, ps or lj-inventory
- Optional: qb-houses, ps-housing or qs-housing
- An Advanced MDT licence or the scripts subscription

### Installation

1. Buy Advanced MDT or the scripts subscription on our store.
2. Sign in at panel.d7team.com with Discord.
3. Client Area → Redeem Code: enter the code and your server's public IP.
4. Download d7-mdt from the Client Area and put it in resources.
5. Add the mdtlaptop item to your inventory's items.
6. Set your framework, inventory and departments in config/config.lua.
7. In server.cfg, start it after your database, framework and inventory:

   ```cfg
   ensure oxmysql
   ensure qb-core
   ensure qb-inventory
   ensure d7-mdt
   ```

8. Restart the server.

Configuration, first start, updates and every console message explained: [Installation guide](https://d7team.com/guides/advanced-mdt)

### Pricing

- **$34.99** — [One-time purchase of this script](https://store.d7team.com/advanced-mdt/p911730490)
- **$7.99 / month** — [Scripts subscription (Advanced MDT and Advanced BossMenu)](https://store.d7team.com/scripts-monthly-subscription/p1713646054): every script, free IP change during the subscription, and free updates

[Store](https://store.d7team.com/advanced-mdt/p911730490)

### FAQ

<details>
<summary><b>Which servers does Advanced MDT work on?</b></summary>

QBCore and QBox servers, CFW included, with ox_inventory, qb-inventory, qs-inventory, ps-inventory or lj-inventory.

</details>

<details>
<summary><b>Can departments other than police use it?</b></summary>

Yes. Every department is a profile tied to a job — police, sheriff and the Department of Justice ship configured — each with its own features, grade permissions and logs.

</details>

<details>
<summary><b>Does it work with Advanced BossMenu?</b></summary>

Yes. Officer points and wings from Advanced BossMenu show in the MDT's officers page and wing permissions.

</details>

<details>
<summary><b>How is it opened in game?</b></summary>

With the laptop item, the /mdt command or a key, and it can be placed in the world with Target, Interact or a marker.

</details>

<details>
<summary><b>How much does it cost?</b></summary>

$34.99 once, or $7.99 a month with the scripts subscription, which covers Advanced MDT and Advanced BossMenu together.

</details>

### Support

Support is on our Discord: [discord.gg/d-7](https://discord.gg/d-7). Issues are closed on this repository so no request waits unread.

### More from Delta Seven

- [Delta Panel](https://github.com/d7teamdev/delta-panel) — FiveM Admin Panel for QBCore, QBox & CFW Servers
- [Advanced BossMenu](https://github.com/d7teamdev/advanced-bossmenu) — FiveM Boss Menu for QBCore, QBox & CFW
- [Add-on FiveM cars](https://d7team.com/cars)

---

<a id="arabic"></a>

<div dir="rtl">

## Advanced MDT — سكربت MDT للشرطة في فايف ام لـ QBCore و QBox و CFW

سكربت MDT للشرطة في فايف ام لـ QBCore و QBox و CFW: القضايا، البحث عن المواطنين، المطلوبين، كاميرا الأدلة، التهم، البصمات ونقاط العساكر.

نظام MDT احترافي ومخصص لسيرفرات QBCore و QBox، مصمم للجهات الرسمية مثل الشرطة، المباحث، الشؤون العسكرية، والقطاعات اللي تحتاج إدارة قضايا، بحث، مطلوبين، أدلة، ونظام معلومات منظم داخل السيرفر.

> هذا المستودع للتعريف والشرح فقط. الريسورس يُباع في متجرنا، وتحمّله من منطقة العميل بعد ما تفعّل الكود

[الموقع](https://d7team.com/ar/products/advanced-mdt) · [شرح التثبيت](https://d7team.com/ar/guides/advanced-mdt) · [المتجر](https://store.d7team.com/advanced-mdt/p911730490) · [الدسكورد](https://discord.gg/d-7)

### نظرة سريعة

| | |
|---|---|
| **يشتغل مع** | سيرفرات QBCore و QBox، ومعها CFW |
| **الإنفنتري** | ox_inventory و qb-inventory و qs-inventory و ps-inventory و lj-inventory |
| **العقارات** | qb-houses و ps-housing و qs-housing |
| **طريقة الفتح** | آيتم اللابتوب، أمر ⁦/mdt⁩، أو زر |
| **التفاعل** | Target أو Interact أو ماركر |
| **القطاعات** | أي وظيفة — الشرطة، الشريف، العدل وغيرها |

### المميزات

#### البحث وملفات المواطنين

- بحث في المواطنين والقضايا وأرقام الجوال والآيدي والبصمات والعقارات
- ملف المواطن: البيانات الشخصية، الصورة، الجوال، رصيد البنك، المركبات، العقارات، حالة المطلوبية وسجل القضايا
- البحث عن المركبة باللوحة، أو أقرب مركبة

#### القضايا

- إنشاء وعرض وتعديل وإغلاق واعتماد القضايا
- ملاحظات القضية، والتهم تحسب مجموع الغرامة ومدة السجن تلقائياً
- اعتماد وتعديل القضايا محصور حسب الرتبة
- مشاركة القضايا بين القطاعات، أو كل قطاع قضاياه له

#### الأدلة

- أدلة بالملاحظات والصور والمرفقات داخل القضية
- كاميرا الأدلة: تصوّر داخل اللعبة وترفق الصورة بالقضية
- إرفاق أغراض من الإنفنتري كأدلة

#### المطلوبين والتهم والبصمات

- سجلات المطلوبين بمستوى المطلوبية والسبب والأرشفة
- قائمة تهم بتصنيفات وغرامات ومدة سجن، تتعدل من داخل الـ MDT
- فحص بصمة شخص قريب، يُطلب منه يعطي بصمته، ويعرض الاسم والآيدي والجوال وتاريخ الميلاد وحالة المطلوبية والسجل الجنائي

#### العساكر

- صفحة العساكر: الأعضاء، حالة الدوام، النقاط، الونقات وعدد القضايا
- تسجيل الدخول والخروج من الدوام من الـ MDT
- نقاط العساكر والونقات مرتبطة مع Advanced BossMenu
- صلاحيات الونقات للتحكم بالوصول داخل الـ MDT

#### الإعداد واللوقات

- بروفايل لكل قطاع باسمه وشعاره ومميزاته وصلاحيات رتبه
- تفعيل أو تعطيل كل ميزة لكل قطاع: البحث، القضايا، التهم، المطلوبين، البصمة، الملاحظات، النقاط والونقات
- لوقات دسكورد للقضايا والأدلة والمطلوبين والتهم والملاحظات والنقاط والونقات — لكل قطاع أو بروم واحد
- واجهة لابتوب نظيفة ومرتبة

### الفيديو

[![Advanced MDT](https://img.youtube.com/vi/OyMPzluRDQQ/hqdefault.jpg)](https://www.youtube.com/watch?v=OyMPzluRDQQ)

### المتطلبات

- سيرفر QBCore أو QBox، ومعها CFW
- oxmysql
- ox أو qb أو qs أو ps أو lj-inventory
- اختياري: qb-houses أو ps-housing أو qs-housing
- ترخيص Advanced MDT أو اشتراك السكربتات

### التثبيت

1. اشترِ Advanced MDT أو اشتراك السكربتات من متجرنا.
2. سجّل دخولك في panel.d7team.com عن طريق دسكورد.
3. منطقة العميل ← تفعيل كود: اكتب الكود وآيبي سيرفرك العام.
4. حمّل d7-mdt من منطقة العميل وحطه في مجلد resources حقك.
5. أضف آيتم mdtlaptop لآيتمات الإنفنتري حقك.
6. حدّد في config/config.lua الفريم وورك والإنفنتري والقطاعات.
7. في server.cfg، شغّله بعد قاعدة البيانات والفريم وورك والإنفنتري:

</div>

```cfg
ensure oxmysql
ensure qb-core
ensure qb-inventory
ensure d7-mdt
```

<div dir="rtl">

8. سوّ ريستارت للسيرفر.

الإعدادات، أول تشغيل، التحديثات، وشرح كل رسالة بالكونسول: [شرح التثبيت](https://d7team.com/ar/guides/advanced-mdt)

### الأسعار

- **⁦$34.99⁩** — [شراء هذا السكربت مرة وحدة](https://store.d7team.com/advanced-mdt/p911730490)
- **⁦$7.99⁩ بالشهر** — [اشتراك السكربتات (Advanced MDT و Advanced BossMenu)](https://store.d7team.com/scripts-monthly-subscription/p1713646054): كل السكربتات، تغيير الآيبي مجاناً خلال مدة الاشتراك، وتحديثات مجانية

[المتجر](https://store.d7team.com/advanced-mdt/p911730490)

### الأسئلة الشائعة

<details>
<summary><b>على أي سيرفرات يشتغل Advanced MDT؟</b></summary>

سيرفرات QBCore و QBox، ومعها CFW، مع ox_inventory أو qb-inventory أو qs-inventory أو ps-inventory أو lj-inventory

</details>

<details>
<summary><b>يقدر يستخدمه قطاع غير الشرطة؟</b></summary>

إيه. كل قطاع عبارة عن بروفايل مربوط بوظيفة — الشرطة والشريف ووزارة العدل جاهزين بالإعداد — وكل واحد له مميزاته وصلاحيات رتبه ولوقاته.

</details>

<details>
<summary><b>يشتغل مع Advanced BossMenu؟</b></summary>

إيه. نقاط العساكر والونقات من Advanced BossMenu تظهر في صفحة العساكر وصلاحيات الونقات داخل الـ MDT

</details>

<details>
<summary><b>كيف ينفتح داخل اللعبة؟</b></summary>

بآيتم اللابتوب، أو أمر ⁦/mdt⁩، أو زر، وتقدر تحطه بمكان بالماب عن طريق Target أو Interact أو ماركر.

</details>

<details>
<summary><b>كم سعره؟</b></summary>

⁦$34.99⁩ مرة وحدة، أو ⁦$7.99⁩ بالشهر مع اشتراك السكربتات الي يشمل Advanced MDT و Advanced BossMenu مع بعض.

</details>

### الدعم

الدعم على الدسكورد حقنا: [discord.gg/d-7](https://discord.gg/d-7). الـ Issues مقفلة بهذا المستودع عشان ما يضيع أي طلب بدون رد

### منتجات ثانية من دلتا سفن

- [لوحة تحكم دلتا](https://github.com/d7teamdev/delta-panel) — لوحة تحكم سيرفرات فايف ام لـ QBCore و QBox و CFW
- [Advanced BossMenu](https://github.com/d7teamdev/advanced-bossmenu) — سكربت بوس منيو فايف ام لـ QBCore و QBox و CFW
- [سيارات فايف ام مضافة](https://d7team.com/ar/cars)

</div>

---

<p align="center">© Delta Seven (D7 Team) · <a href="https://d7team.com">d7team.com</a></p>
