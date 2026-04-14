# Internship Project Development History

**Internship Period:** March 18, 2026 - May 18, 2026 (2 months)
**Organization:** Elevate Labs
**Project:** AI-Powered Fake News Detection System


## 2026-03-19 03:18 - Initial commit: fake news analyzer backend + extension

## 2026-03-19 09:28 - Initial commit: fake news analyzer backend + extension

## 2026-03-19 13:04 - Add gunicorn to requirements

## 2026-03-19 16:56 - Update requirements.txt

## 2026-03-20 12:49 - Sync local changes

## 2026-03-20 15:30 - changes in ai.py

## 2026-03-23 20:46 - changes in health.py

## 2026-03-23 22:18 - Refactor frontend to chat-based UI and stateless logic

## 2026-03-24 07:59 - Add README for Fake News Analyzer Chrome Extension

## 2026-03-24 10:57 - Update README formatting and content clarity

## 2026-03-26 03:46 - Add backend URL to README

## 2026-03-27 02:45 - made a new version

## 2026-03-27 05:06 - Removed the strict version pins on pandas, scikit-learn, groq, and cerebras-cloud-sdk

## 2026-04-01 23:24 - changed

## 2026-04-02 03:29 - main.py â€” lifespan instead of deprecated startup event ml.py â€” lazy load, won't crash on import evidence.py â€” correct .env path auth_routes.py â€” clean /me route decision.py â€” Optional type hints database.py â€” absolute SQLite path

## 2026-04-02 15:32 - add trained ML model artifacts

## 2026-04-03 00:11 - fix: accept HEAD requests on /health

## 2026-04-03 03:38 - fix: Kiwi OAuth fallback, HEAD health check, CSP update

## 2026-04-03 05:30 - feat: TruthScan context menu opens popup, new logo

## 2026-04-03 14:45 - feat: new square logo for all toolbar icons

## 2026-04-04 18:47 - fix: remove JWT expiry so tokens never expire + fix all nav to use chrome.runtime.getURL + remove CSP-violating inline scripts

## 2026-04-05 05:09 - fix: chrome.runtime.getURL + remove CSP-violating inline scripts

## 2026-04-06 00:09 - fix re size isuues

## 2026-04-06 08:34 - fix : Evidence weight and News bar is blue to visually distinguish it from ML (green/red) and AI (purple)

## 2026-04-06 14:04 - feat: parallel analysis pipeline, NewsAPI evidence, forgot password with OTP email

## 2026-04-07 05:54 - feat: production hardening â€” auth, OTP rate limiting, resend timer, deploy config

## 2026-04-08 21:20 - redesign: cleaner OTP email template matching app design system

## 2026-04-09 01:02 - RESEND_FROM was empty string in .env â€” or operator now falls back to default correctly Rate limit was too tight (3 per 10 min) â€” now 5 per 5 min Frontend now shows the 429 error clearly instead of a generic message

## 2026-04-09 15:15 - edo mail issue solve chesa anukunta

## 2026-04-09 23:25 - debug: add /auth/debug-email endpoint to diagnose Render SMTP

## 2026-04-10 05:42 - fix: revert to Resend HTTP API (SMTP blocked on Render), clear domain restriction error

## 2026-04-10 09:58 - fix: Gmail SMTP port 587 STARTTLS â€” works on Render, sends to any email

## 2026-04-10 10:30 - debug: TCP port test endpoint

## 2026-04-11 05:32 - fix: switch to Brevo HTTP API for OTP emails â€” works on Render, any recipient

## 2026-04-11 10:03 - fix: Brevo HTTP API for OTP emails â€” delivers to any email, verified on gitam.in

## 2026-04-12 14:57 - debug: expose email error detail on Render + config back to production

## 2026-04-12 17:25 - fix: clean error message for email failures

## 2026-04-12 22:01 - feat: PostgreSQL with production connection pooling

## 2026-04-13 02:44 - fix: remove hardcoded sqlite DATABASE_URL from render.yaml, add Brevo env vars

## 2026-04-13 05:05 - feat: retrain ML model on 98k samples (90% accuracy) with bigrams + 50k features

## 2026-04-13 13:34 - rewritten the README file

## 2026-04-13 18:52 - fix: remove CDATA wrapper from README

## 2026-04-14 03:53 - feat: replace extension icons with new logo

## 2026-04-14 13:19 - feat: replace extension icons with new logo with radme
