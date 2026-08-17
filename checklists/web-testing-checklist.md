# Web Testing Checklist

This checklist covers the main areas of manual web application testing.

---

## 1. General

- [ ] Application loads successfully.
- [ ] Page title is correct.
- [ ] Favicon is displayed correctly.
- [ ] No unexpected errors are displayed.
- [ ] Links and navigation elements are present.
- [ ] Browser Back and Forward buttons work correctly.
- [ ] Page refresh works correctly.

---

## 2. UI Testing

- [ ] Layout matches the design specifications.
- [ ] Text is displayed correctly.
- [ ] Fonts and font sizes are correct.
- [ ] Buttons are displayed correctly.
- [ ] Icons and images are displayed correctly.
- [ ] Elements are properly aligned.
- [ ] No overlapping elements are present.
- [ ] No horizontal scrolling appears unexpectedly.
- [ ] Hover, focus, and active states work correctly.
- [ ] Disabled elements look and behave correctly.

---

## 3. Forms and Input Fields

- [ ] All required fields are marked appropriately.
- [ ] Required field validation works correctly.
- [ ] Valid input is accepted.
- [ ] Invalid input is rejected.
- [ ] Boundary values are tested.
- [ ] Maximum field length is enforced.
- [ ] Minimum field length is enforced where applicable.
- [ ] Special characters are handled correctly.
- [ ] Leading and trailing spaces are handled correctly.
- [ ] Error messages are clear and relevant.
- [ ] Error messages disappear after correcting the input.
- [ ] Form submission works correctly.
- [ ] Submit buttons prevent unintended duplicate submissions.

---

## 4. Authentication and Authorization

- [ ] User can log in with valid credentials.
- [ ] Invalid credentials are rejected.
- [ ] Empty login fields are validated.
- [ ] Password input is masked.
- [ ] Logout works correctly.
- [ ] Protected pages cannot be accessed by unauthorized users.
- [ ] User session is handled correctly.
- [ ] Browser Back button does not bypass logout.
- [ ] Password reset functionality works correctly.

---

## 5. Navigation and Links

- [ ] All navigation links work correctly.
- [ ] Internal links lead to the correct pages.
- [ ] External links open the correct destination.
- [ ] Links do not lead to unexpected error pages.
- [ ] Redirects work correctly.
- [ ] Breadcrumbs work correctly where applicable.
- [ ] Navigation is consistent across pages.

---

## 6. Functional Testing

- [ ] Main application features work as expected.
- [ ] User workflows can be completed successfully.
- [ ] Buttons perform the correct actions.
- [ ] Data is saved correctly.
- [ ] Data is displayed correctly.
- [ ] Add, edit, and delete operations work correctly.
- [ ] Success messages are displayed when appropriate.
- [ ] Error handling works correctly.
- [ ] Application state is preserved after page refresh where expected.

---

## 7. E-commerce

- [ ] Products are displayed correctly.
- [ ] Product details are correct.
- [ ] Products can be added to the shopping cart.
- [ ] Products can be removed from the shopping cart.
- [ ] Product quantities can be changed where applicable.
- [ ] Cart totals are calculated correctly.
- [ ] Cart state is preserved after page refresh where expected.
- [ ] Checkout process works correctly.
- [ ] Required checkout fields are validated.

---

## 8. Cross-Browser Testing

- [ ] Application works correctly in Google Chrome.
- [ ] Application works correctly in Mozilla Firefox.
- [ ] Application works correctly in Microsoft Edge.
- [ ] Layout is consistent across supported browsers.
- [ ] Forms work correctly across supported browsers.
- [ ] Navigation works correctly across supported browsers.

---

## 9. Responsive and Mobile Testing

- [ ] Application displays correctly on desktop screens.
- [ ] Application displays correctly on tablet-sized screens.
- [ ] Application displays correctly on mobile screens.
- [ ] Text remains readable on smaller screens.
- [ ] Buttons and interactive elements are easy to use.
- [ ] No unexpected horizontal scrolling occurs.
- [ ] Navigation adapts correctly to smaller screens.
- [ ] Forms remain usable on mobile devices.

---

## 10. Browser and Technical Checks

- [ ] No JavaScript errors are present in the browser console.
- [ ] Network requests return expected status codes.
- [ ] Failed requests are handled correctly.
- [ ] Images and other resources load correctly.
- [ ] No unexpected 404 errors are present.
- [ ] Browser DevTools can be used to investigate issues.
- [ ] Application behavior is consistent after clearing cache where applicable.

---

## 11. Regression Testing

- [ ] Previously working functionality still works after changes.
- [ ] Fixed defects are retested.
- [ ] Related functionality is checked after a fix.
- [ ] Critical user flows are tested after significant changes.
- [ ] No new defects were introduced by the changes.

---

## 12. Final Verification

- [ ] Critical functionality works correctly.
- [ ] No blocking defects remain.
- [ ] Known defects are documented.
- [ ] Main user flows have been tested.
- [ ] Application is ready for the next testing stage or release.

---

## Notes

This checklist is a general example of a manual web application testing checklist.  
The actual checklist should be adapted to the application's functionality, requirements, and testing scope.
