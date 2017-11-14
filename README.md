# AutoTemplate
สคริปสำหรับสร้างโปรเจคเทมเพลทอัตโนมัติจากไฟล์ที่เรากำหนดไว้เอง โดยสคริปจะก็อปปี้ไฟล์เทมเพลทที่เราเก็บไว้ใน "C:\Source" (สามารถเปลี่ยนได้เองในเวอร์ชั่น ahk) มายังโฟลเดอร์ใหม่ที่คุณต้องการ นอกจากนี้ยังจะเปลี่ยนชื่อไฟล์เทมเพลทงานของคุณ (template.*)  ที่อยู่ใน Root Directory เป็น...
```
01_วันที่สร้างโปรเจ็ค_ชื่อโปรเจ็ค.* 
```
โดยอัตโนมัติอีกด้วย
## สคริป AutoTemplate แยกเป็นสองตัว
* AutoTemplate_activefolder 
วิธีใช้สคริปตัวนี้คุณจำเป็นที่จะต้องนำไฟล์ AutoTemplate ที่ดาวน์โหลดไป ไปก๊อปปี้ไว้ที่ Folder Project งานของคุณ จากนั้นเมื่อคุณดับเบิลคลิกไฟล์นี้ สคริปจะก๊อปปี้ไฟล์จาก "C:\Source" ให้คุณอัตโนมัติ
* AutoTemplate_withShortcut
วิธีใช้สคริปตัวนี้เพียงเปิดใช้งานสคริป (ดับเบิลคลิก) สคริปจะ Remap ปุ่ม Pause เพื่อเรียกใช้งาน AutoTemplate
## วิธีการติดตั้ง
ไฟล์เวอร์ชั่น exe คุณสามารถใช้สคริปได้เลย ส่วนไฟล์ ahk คุณจำเป็นที่จะต้องดาวน์โหลดและติดตั้ง [AutoHotkey](https://www.autohotkey.com/)  ก่อน
## วิธีการแก้ไข Shortcut และ Source Folder 
ในไฟล์เวอร์ชั่น ahk คุณสามารถแก้ไขไฟล์ ahk ใน Text Editor ได้ตามบรรทัดด้านล่างนี้
```
; Set Shortcut (ในที่นี้คือปุ่ม pause)
pause::
```
```
; Set Source Folder Here
source = C:\Source
```
## สร้างด้วย
* [AutoHotkey](https://www.autohotkey.com/) - The ultimate automation scripting language for Windows.
## โดย
**Adul Kokapan** - [underpk.com](http://underpk.com/)
## ขอขอบคุณ
**Rapte_Of_Suzaku** - [Get paths of selected items in an explorer window](https://autohotkey.com/board/topic/60985-get-paths-of-selected-items-in-an-explorer-window/

