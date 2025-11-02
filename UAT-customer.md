# 🧪 Test Plan: Fuente Cloud – Customer App (`shop.staging.fuente.io`)

## 🎯 Purpose
This test plan outlines the core functionalities of the Fuente Cloud customer app. The goal is to validate usability, reliability, and payment flow to support a stable MVP rollout in Suriname.

---

## 🧩 Test Areas & Test Cases

### 1. Product Search & Display

| Test Case | Description |
|-----------|-------------|
| TC001     | Searching for a product by keyword (e.g., “bananas”) returns relevant results |
| TC002     | Category filters work correctly |
| TC003     | Product detail page displays image, price, and description accurately |

---

### 2. Cart & Order Placement

| Test Case | Description |
|-----------|-------------|
| TC010     | Product can be added to the cart |
| TC011     | Cart displays correct quantity and total price |
| TC012     | Order can be successfully placed |

---

### 3. Payment (Paisr)

| Test Case | Description |
|-----------|-------------|
| TC020     | Paisr payment is correctly initiated |
| TC021     | Successful payment is confirmed in the UI |
| TC022     | Failed payment triggers a clear error message |

---

### 4. Delivery Status (if available)

| Test Case | Description |
|-----------|-------------|
| TC030     | Order status shows “processing” after placement |
| TC031     | Delivery status updates (e.g., “on the way”) are visible to the customer |

---

## 🧰 Test Methods

- Manual testing via browser at [shop.staging.fuente.io](https://shop.staging.fuente.io)
- Screenshots and notes to document UI behavior
- Developer feedback for unclear flows or missing features

---

## 📌 Open Questions

- Is there a test environment with dummy products?
- How is Paisr payment simulated or tested?
- Is there frontend logging or error reporting?
- Which features are stable vs. experimental?

---

## 🧭 Next Steps

- Discuss open questions with the development team
- Extend test coverage to merchant, driver, and admin apps
- Build a test tracking system in GitHub Issues or Notion

---

*Prepared by Michael – Resonance Coordinator, Fuente Cloud (Paramaribo, November 2025)*