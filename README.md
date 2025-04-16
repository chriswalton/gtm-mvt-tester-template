# MVT Tester – Google Tag Manager Template

**Free multivariate testing template for GTM**  
Built by [Net Impression](https://www.netimpression.co.uk)

## 🚀 Features
- Run A/B and multivariate tests directly in GTM
- No dependencies or third-party tools
- Works with GA4 via `data.variantAssigned` or custom tracking
- Supports `?mvt=variation1` URL overrides
- Cookie-based user consistency

## 📦 Fields
- `testCode`: Unique ID for your test
- `testVersion`: Optional version label
- `variantCount`: How many variations (excluding control)
- `controlCode`: Code to inject for control group
- `variation1Code` – `variation3Code`: Code to inject per variant

## 🛠️ Setup
1. Create a new Tag Template in GTM and import `MVT Tester.tpl`
2. Configure fields in the interface
3. Use triggers or variables based on `variantAssigned`
4. Publish and test it live

## 🙌 Credits
Developed by Net Impression  
https://www.netimpression.co.uk/tools/free-ab-testing-script
