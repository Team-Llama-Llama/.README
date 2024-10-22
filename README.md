# .README

Initial setup
1. Git clone from main into your local directory

To resolve issue
1. Open VS code locally to target repository (front/back)
2. Create branch from issue ticket
3. On your VS code, make sure on main and then git pull to get most updated version
L "git pull"
4. Switch branch to issue branch
L "git branch checkout <branchname>"
5. Work on code and push

Static Site Info
- Link: https://llama-llama-lms-live.onrender.com
- Root Directory: Default
- Build Command: npm run build
- Publish Directory: dist
- Environment Variables:
  - VITE_API_URL: https://llama-llama-lms.onrender.com

Web Service Info
- Link: https://llama-llama-lms.onrender.com
- Name: llama-llama-lms
- Root Directory: Default
- Build Command: npm install; npm run build
- Start Command: npm start
- Environment Variables:
  - DB_URL: postgresql://llama:Zx9DIDMuVmZlDla9BDZDhXE8Q036k0z7@dpg-csbmos9u0jms73ff3l80-a/lms_db_rj7i

Database Info
- Name: llama-llama-lms-db
- Internal Database URL: postgresql://llama:Zx9DIDMuVmZlDla9BDZDhXE8Q036k0z7@dpg-csbmos9u0jms73ff3l80-a/lms_db_rj7i
