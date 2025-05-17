🐞 Bug Report: Date Picker Doesn't Open on First Click (Mobile Safari / iOS 18.3.1)
Summary
On iPhone 13 (iOS 18.3.1, Safari browser), the date picker in the application form does not open on the first click. It only works after switching focus to another input field and then returning to the date field.

Environment
Device: iPhone 13

OS: iOS 18.3.1

Browser: Safari

Page: Application Form – https://career.check24.de/junior-test-automation-quality-assurance-engineer-mwd-app--de-f11917.html?agid=263&utm_source=xing.com)

Steps to Reproduce
Open the application form page in Safari on iPhone 13.

Scroll to the Date Picker input field.

Tap once on the field.

Expected: Calendar should appear for date selection.

Actual: Nothing happens.

Tap another input field.

Tap the date field again.

Now the calendar appears.

Observed on Other Devices
Windows 11 (Chrome, Firefox, Edge): ✅ No issues – picker opens immediately.

Android (Pixel 7, Android 14, Chrome): ⚠ Picker opens only on second tap.

Expected Result
The calendar should appear immediately upon the first click/tap on the date input field.

Actual Result
On iPhone Safari, the first click does not trigger the calendar.

On Android, the first click is ignored; second tap works.

Impact
Low severity bug: Does not block form submission but may confuse or frustrate users.

Could be perceived as broken functionality, especially on mobile.

Possible Causes
JavaScript event listeners (e.g., onClick or onFocus) not triggering correctly on iOS Safari.

CSS overlay or DOM focus issues.

Inconsistent browser handling of native <input type="date"> or custom date pickers.

Bug Category
UI/UX Issue

Priority
Low (non-blocking but user experience is negatively affected)

Supporting Material
🎥 Video Evidence (iOS 18.3.1, Safari):
https://drive.google.com/file/d/1acxfM-lFTXOidNJUlBhjnOVPTpDX0tL1/view?usp=drivesdk
https://drive.google.com/file/d/1wAueyMsWTd_rnKGiLq3yG73D9zTcAD4X/view?usp=drivesdk
Android:
https://drive.google.com/file/d/15PCFpFQu077IQskat8tCo6dvLJFCL9Zu/view?usp=drivesdk

✅ Recommendation
Review JavaScript and focus handlers for mobile compatibility.

Consider adding a fallback or forcing focus/redraw on mobile devices.
