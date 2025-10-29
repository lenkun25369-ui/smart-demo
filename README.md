# SMART on FHIR Demo (Full Dashboard)

This is a complete SMART on FHIR demo app with patient, medication, and observation visualization using Chart.js.

## 🚀 Local Test

```bash
npm install -g http-server
http-server .
```
Then open [http://localhost:8080](http://localhost:8080)

## 🌐 GitHub Pages Deployment

1. Create a new GitHub repository (e.g., smart-demo)
2. Upload `launch.html`, `index.html`, and `README.md`
3. Go to **Settings → Pages**
   - Source: `main` branch, `/ (root)`
4. Save and wait for the deployment link:
   ```
   https://<your-username>.github.io/smart-demo/launch.html
   ```

## 🧠 SMART Launcher Test

Use [SMART Launcher](https://launch.smarthealthit.org):
- App Launch URL: your GitHub Pages link above
- FHIR Server: https://r4.smarthealthit.org
- Launch Type: Provider EHR Launch

Enjoy!
