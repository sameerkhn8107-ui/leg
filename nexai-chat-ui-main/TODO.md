# TODO: Fix CORS and API Calls for Production Deployment

## Tasks
- [x] Update CORS middleware in server.py to allow only Vercel frontend origin
- [x] Update CORS middleware in api/main.py for consistency
- [ ] Deploy updated backend to Render
- [ ] Set REACT_APP_BACKEND_URL=https://leg-z2fp.onrender.com in Vercel environment variables
- [ ] Test CORS and API functionality in production

## Notes
- Backend is FastAPI (not Flask as initially mentioned)
- Frontend deployed on Vercel: https://leg-jade.vercel.app
- Backend deployed on Render: https://leg-z2fp.onrender.com
- Removed localhost and "*" origins for security
- HTTPS-only configuration enforced
