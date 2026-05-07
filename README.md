# homestock-privacy

Public privacy policy for the **Home stock** (Homestock) Android app.

## Publish on GitHub

1. Create a new repository (for example `homestock-privacy`) under your organization.
2. Push this folder:

   ```bash
   cd homestock-privacy
   git init
   git add PRIVACY_POLICY.md README.md
   git commit -m "Add privacy policy"
   git branch -M main
   git remote add origin https://github.com/<ORG>/homestock-privacy.git
   git push -u origin main
   ```

3. App / Play Console URL (human-readable):  
   `https://github.com/<ORG>/homestock-privacy/blob/main/PRIVACY_POLICY.md`

   Ensure `PRIVACY_POLICY_URL` in the Android app’s `build.gradle.kts` matches the final public URL.

## Optional: GitHub Pages

Enable Pages from the `main` branch and use a clean HTML mirror if you prefer a branded page; update the app URL accordingly.
