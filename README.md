
Project to demonstrate deployment of multiple pages on Vercel



Added file `vercel.json`in project root to fix file not found problem on vercel


{
  "rewrites": [{ "source": "/(.*)", "destination": "/" }]
}

Redirects to search subdirectories}
