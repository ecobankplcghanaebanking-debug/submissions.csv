# My Customer Dashboard

## Setup
1. Fork/clone this repo into your GitHub account.  
2. Make sure you have these files/folders:  
   - `dashboard/index.html`  
   - `api/submit.js`  
   - `submissions.csv`  

## Deployment
- Use **Vercel** (recommended):
  1. Go to https://vercel.com and import your repo.
  2. Add an Environment Variable:
     - `GITHUB_TOKEN` = your personal access token (with `repo` scope).
  3. Deploy.

- Or use **Netlify** with similar setup.  

## How it works
- Users fill out the form in `dashboard/index.html`.  
- The form posts to `/api/submit`.  
- `api/submit.js` adds the data to `submissions.csv` in your repo.  
