Compatibility Testing Report – E-com Website

 **TC_001 – Verify Website Launch

 **Test Scenario:** Verify website opens successfully.

**Steps:**

1. Open the website URL.
2. Wait for the homepage to load.

**Expected Result:** Homepage should load without errors.

**Actual Result:** Homepage loaded successfully.

**Status:** Pass

---

## TC_002 – Verify Navigation Menu

**Test Scenario:** Verify all navigation menu items are clickable.

**Steps:**

1. Open the homepage.
2. Click each menu item.

**Expected Result:** Corresponding pages should open.

**Actual Result:** Menu items are clickable.

**Status:** Pass

---

## TC_003 – Verify Home Page Layout

**Test Scenario:** Check homepage layout across browsers.

**Steps:**

1. Open the website in Chrome.
2. Open the website in Firefox.
3. Open the website in Edge.

**Expected Result:** Layout should remain consistent.

**Actual Result:** Layout displayed correctly.

**Status:** Pass

---

## TC_004 – Verify Product Listing

**Test Scenario:** Verify products are displayed correctly.

**Steps:**

1. Open homepage.
2. Scroll through products.

**Expected Result:** Products should display with image, name, and price.

**Actual Result:** Products displayed correctly.

**Status:** Pass

---

## TC_005 – Verify Product Details Page

**Test Scenario:** Verify product details open correctly.

**Steps:**

1. Click any product.
2. View product details.

**Expected Result:** Product details page should load.

**Actual Result:** Product details displayed correctly.

**Status:** Pass

---

## TC_006 – Verify Search Functionality

**Test Scenario:** Verify search works correctly.

**Steps:**

1. Enter a product name in search box.
2. Click search.

**Expected Result:** Relevant products should be displayed.

**Actual Result:** Search returned matching products.

**Status:** Pass

---

## TC_007 – Verify Add to Cart Functionality

**Test Scenario:** Verify users can add products to cart.

**Steps:**

1. Select a product.
2. Click Add to Cart.

**Expected Result:** Product should be added to cart.

**Actual Result:** Product added successfully.

**Status:** Pass

---

## TC_008 – Verify Cart Page

**Test Scenario:** Verify cart page displays selected products.

**Steps:**

1. Add products to cart.
2. Open cart page.

**Expected Result:** Added products should appear in cart.

**Actual Result:** Products displayed correctly.

**Status:** Pass

---

## TC_009 – Verify Quantity Update

**Test Scenario:** Verify quantity can be updated.

**Steps:**

1. Open cart.
2. Increase/decrease quantity.

**Expected Result:** Quantity and total price should update.

**Actual Result:** Updated successfully.

**Status:** Pass

---

## TC_010 – Verify Remove from Cart

**Test Scenario:** Verify products can be removed.

**Steps:**

1. Open cart.
2. Click remove.

**Expected Result:** Product should be removed.

**Actual Result:** Product removed successfully.

**Status:** Pass

---

## TC_011 – Verify Cloth Category

**Test Scenario:** Verify Cloth category navigation.

**Steps:**

1. Open homepage.
2. Click Cloth category.

**Expected Result:** Cloth products page should open.

**Actual Result:** 404 Page Not Found displayed.

**Status:** Fail

**Bug ID:** BUG_001

**Severity:** High

---

## TC_012 – Verify Accessories Category

**Test Scenario:** Verify Accessories category navigation.

**Steps:**

1. Open homepage.
2. Click Accessories category.

**Expected Result:** Accessories products page should open.

**Actual Result:** 404 Page Not Found displayed.

**Status:** Fail

**Bug ID:** BUG_002

**Severity:** High

---

## TC_013 – Verify Broken Links

**Test Scenario:** Verify all links work correctly.

**Steps:**

1. Click all available links.
2. Observe navigation.

**Expected Result:** No broken links.

**Actual Result:** Cloth and Accessories links are broken.

**Status:** Fail

---

## TC_014 – Verify Mobile Responsiveness

**Test Scenario:** Verify website on mobile devices.

**Steps:**

1. Open Developer Tools.
2. Switch to mobile view.
3. Test different screen sizes.

**Expected Result:** Layout should adjust properly.

**Actual Result:** Layout responsive.

**Status:** Pass

---

## TC_015 – Verify Tablet Responsiveness

**Test Scenario:** Verify website on tablet screens.

**Steps:**

1. Open tablet view.
2. Navigate pages.

**Expected Result:** Content should be properly aligned.

**Actual Result:** Displayed correctly.

**Status:** Pass

---

## TC_016 – Verify Browser Compatibility

**Test Scenario:** Verify website across browsers.

**Browsers Tested:**

* Chrome
* Firefox
* Microsoft Edge

**Expected Result:** Functionality should be same across browsers.

**Actual Result:** Website works similarly except broken category links.

**Status:** Pass

---

# Defect Summary

| Bug ID  | Description                                | Severity | Status |
| ------- | ------------------------------------------ | -------- | ------ |
| BUG_001 | Cloth category redirects to 404 page       | High     | Open   |
| BUG_002 | Accessories category redirects to 404 page | High     | Open   |

# Final Conclusion

* Website loads successfully.
* Product pages and cart functionality work correctly.
* Responsive design works on desktop, tablet, and mobile views.
* Cross-browser compatibility is good.
* Two critical issues were found:

  1. Cloth category link is broken.
  2. Accessories category link is broken.
* Recommendation: Fix routing/navigation for Cloth and Accessories pages before deployment.
