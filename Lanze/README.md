# Lanze Matthew C. Jallorina - Personal Portfolio

Portfolio website built with HTML and Tailwind CSS.

## 🚀 How to Deploy to Vercel

### Option 1: Direct GitHub Push (Recommended)
1. Initialize a git repository in this folder:
   ```bash
   git init
   git add .
   git commit -m "feat: portfolio site"
   ```
2. Create a new repository on your GitHub account (`lnzem`).
3. Link and push your repo:
   ```bash
   git remote add origin https://github.com/lnzem/<your-repo-name>.git
   git branch -M main
   git push -u origin main
   ```
4. Log into [Vercel](https://vercel.com), click **Add New...** > **Project**, and import your GitHub repository.
5. Vercel automatically detects `index.html` as a static site. Click **Deploy**.

---

### Option 2: Using the Vercel CLI
1. Open PowerShell or terminal in this folder (`c:\Users\Lanze\Desktop\Lanze`).
2. Run:
   ```bash
   npx vercel
   ```
3. Follow the CLI prompts to link to your Vercel account and deploy in seconds. To deploy to production:
   ```bash
   npx vercel --prod
   ```

---

## 📁 Project Structure

```text
├── index.html                       # Main portfolio markup & logic
├── picture.jpg                      # Profile picture
├── certificate-ibm-cloud.pdf        # Verified IBM Introduction to Cloud Certificate
├── certificate-cisco-networking.pdf # Verified Cisco Networking Basics Certificate
├── vercel.json                      # Vercel security headers & configuration
└── README.md                        # Documentation & deployment guide
```
