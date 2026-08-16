# Web Testing Checklist

This checklist contains examples of common checks performed during manual web application testing.

---

## 1. UI / Visual Testing

* [ ] Page layout is displayed correctly.
* [ ] Text is readable and properly aligned.
* [ ] Fonts, sizes, and styles are consistent.
* [ ] Buttons and links are displayed correctly.
* [ ] Images and icons are displayed correctly.
* [ ] No overlapping or cut-off elements are present.
* [ ] Hover and active states work correctly.
* [ ] Visual elements match the design specifications.
* [ ] No unexpected horizontal scrolling is present.

---

## 2. Navigation

* [ ] Main navigation links work correctly.
* [ ] Internal links lead to the correct pages.
* [ ] External links open the expected destination.
* [ ] Browser Back and Forward buttons work correctly.
* [ ] Breadcrumbs, if available, work correctly.
* [ ] Logo links to the expected page.
* [ ] Broken links are not present.

---

## 3. Forms & Validation

* [ ] Required fields are clearly indicated.
* [ ] Forms can be submitted with valid data.
* [ ] Invalid data is rejected.
* [ ] Empty required fields are validated.
* [ ] Validation messages are clear and informative.
* [ ] Field length limits are enforced.
* [ ] Special characters are handled correctly.
* [ ] Leading and trailing spaces are handled correctly.
* [ ] Submit buttons behave correctly.
* [ ] Form data is not unexpectedly lost.

---

## 4. Authentication

* [ ] User can register with valid data.
* [ ] Registration rejects invalid data.
* [ ] User can log in with valid credentials.
* [ ] Invalid credentials are rejected.
* [ ] Empty login fields are validated.
* [ ] Password visibility toggle works correctly.
* [ ] Password reset functionality works correctly.
* [ ] User can log out successfully.
* [ ] Protected pages require authentication.

---

## 5. Functional Testing

* [ ] Main application features work as expected.
* [ ] Create operations work correctly.
* [ ] Edit/update operations work correctly.
* [ ] Delete operations work correctly.
* [ ] Search functionality works correctly.
* [ ] Filters return the expected results.
* [ ] Sorting works correctly.
* [ ] Data is saved correctly.
* [ ] Data remains consistent after page refresh.
* [ ] Success and error messages are displayed correctly.

---

## 6. Negative Testing

* [ ] Required fields are left empty.
* [ ] Invalid data is entered.
* [ ] Boundary values are tested.
* [ ] Excessively long input is tested.
* [ ] Special characters are entered.
* [ ] Incorrect formats are tested.
* [ ] Multiple rapid clicks are tested where relevant.
* [ ] Invalid URLs or parameters are tested.
* [ ] Unexpected user actions do not break the application.

---

## 7. Compatibility Testing

* [ ] Application works correctly in Google Chrome.
* [ ] Application works correctly in Mozilla Firefox.
* [ ] Application works correctly in Microsoft Edge.
* [ ] Layout is consistent across supported browsers.
* [ ] Core functionality works across supported browsers.

---

## 8. Responsive / Mobile Testing

* [ ] Layout adapts correctly to different screen sizes.
* [ ] Content remains readable on mobile devices.
* [ ] Buttons and interactive elements are easy to use.
* [ ] Navigation works correctly on mobile.
* [ ] No important content is cut off.
* [ ] No unexpected horizontal scrolling is present.
* [ ] Forms remain usable on smaller screens.

---

## 9. Error Handling

* [ ] Error messages are clear and understandable.
* [ ] Server errors are handled appropriately.
* [ ] Invalid requests do not break the page.
* [ ] Empty search results are handled correctly.
* [ ] Network interruptions are handled appropriately where applicable.
* [ ] The user receives appropriate feedback after failed operations.

---

## 10. Basic Security Checks

* [ ] Password fields hide sensitive information.
* [ ] Protected pages cannot be accessed without authentication.
* [ ] Logout invalidates the user session.
* [ ] Sensitive information is not exposed in the UI.
* [ ] Users cannot access another user's data through simple URL manipulation.
* [ ] Authentication errors do not expose sensitive information.

---

## Notes

This checklist is a practical example and should be adapted according to the application's requirements, functionality, and testing scope.
