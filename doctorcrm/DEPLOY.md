# Deploy — DoctorCRM

1. Push `doctorcrm-only/` to GitHub (`https://github.com/iqshamar8/doccrm`).
2. Import repo in Vercel.
3. Add env vars: `NEXT_PUBLIC_SUPABASE_URL`, `NEXT_PUBLIC_SUPABASE_ANON_KEY`, `SUPABASE_SERVICE_ROLE_KEY`, `WHATSAPP_ACCESS_TOKEN`, `WHATSAPP_PHONE_NUMBER_ID`, `WHATSAPP_VERIFY_TOKEN`, `CRON_SECRET`.
4. Deploy.

Files included: `.github/workflows/ci.yml`, `docs/DEPLOYMENT.md`, `.env`, `DOCTORCRM_PACKAGE.txt`.
