# 🚀 Subscription Admin Tester Dashboard

A standalone admin web dashboard for testing, managing, and inspecting the Subscription Engine, Plans, Offers, Journeys, Journey Days, Tasks, Creator Enrolments, and Support Audit Trails.

---

## 📌 Features

1. **Step 1: Subscription Plans Module**
   - Create, list, filter, update, deactivate/activate, and delete Subscription Plans.

2. **Step 2: Subscription Offers Module**
   - Create, list, filter, update, deactivate/activate, and delete Subscription Offers with rolling timers or fixed calendar windows.

3. **Step 3: Subscription Journeys Module**
   - Create, list, filter, update, clone versioned journeys, and kill switch Subscription Journeys with audience targeting criteria (`target_criteria`), `is_recurring`, and `max_repeat_count`.

4. **Step 4: Journey Days & Tasks Module**
   - Create Journey Days with atomic task creation in one request.
   - Configure repeat intervals (`repeat_interval_days`), max repeat counts (`max_repeat_count`), abandonment watchers, WABA/Push notification templates, and reveal modes.

5. **Step 5: Creator Enrolment Engine & Audit Trail Inspector**
   - Batch enroll eligible creators, manually enroll/transfer creators between journeys, update enrolment status, fast-forward creator journey days for rapid testing, and inspect full creator audit trail logs.

6. **Step 6: Subscription De-activation & Cancellation**
   - Auto-fetch active subscription UUID by Creator User ID / Bearer JWT token, and safely de-activate subscriptions via Admin API.

---

## 🚀 How to Run Locally

Simply open `index.html` (or `subscription_admin_tester.html`) in any web browser!

```bash
# Open directly in browser
google-chrome index.html
# or run local dev server
npx serve .
```

---

## 🔗 How to Connect & Push to a Different GitHub Repository

To connect this standalone project to your own separate GitHub repository:

```bash
# 1. Add your GitHub remote repository URL
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# 2. Push to GitHub
git branch -M main
git push -u origin main
```
