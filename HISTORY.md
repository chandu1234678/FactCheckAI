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

## 2026-04-15 21:55 - feat: structured AI scoring, stance evidence, meta-decision model, UI improvements (items 1-13)

## 2026-04-16 05:13 - feat: uncertainty detection, contradiction meter, source credibility tags, analyze-page button

## 2026-04-16 06:16 - feat: ablation study with F1 results, add to README

## 2026-04-16 13:51 - feat: user feedback system â€” store corrections in DB for retraining, inline UI

## 2026-04-17 13:03 - feat: manipulation/bias detection â€” sensational language, emotional amplification, urgency signals

## 2026-04-18 05:32 - feat: PostgreSQL support + Brevo email + all fixes

## 2026-04-18 17:07 - fix: popup.js duplicate explHtml, add subclaim styles, feedback styles

## 2026-04-18 20:43 - feat: calibrated ML model, adversarial test gen, feedback retraining, drift detection, model versioning

## 2026-04-20 10:08 - feat: suspicious phrase highlighting, temporal claim tracking, verdict change detection

## 2026-04-20 18:28 - feat: dynamic source credibility scoring, detail.js full upgrade with all new fields

## 2026-04-21 08:12 - docs: updated TODO with accurate completion status

## 2026-04-22 21:13 - feat: dashboard upgrade (model metrics, drift monitor, top sources), saved page badges, detail feedback button

## 2026-04-23 01:02 - feat: adversarial evaluation script, calibration+robustness API, dashboard robustness score

## 2026-04-23 19:07 - publish-ready: updated README, rate limiting on /message, manifest v2.0.0, LICENSE, history msg fix

## 2026-04-24 09:11 - fix: mark 38/39/40/46 complete, data quality filter in train.py

## 2026-04-24 15:54 - fix: 60s timeout + waking hint for Google OAuth cold start

## 2026-04-24 21:03 - perf: pre-warm Google auth token silently on login page load

## 2026-04-25 02:16 - design: Apple-style OTP email â€” pure white, SF Pro, minimal

## 2026-04-27 01:26 - fix: UnboundLocalError â€” move highlights after verdict assignment

## 2026-04-27 05:04 - feat: one-step-at-a-time loading indicator, typewriter effect on explanation and chat replies

## 2026-04-27 13:30 - security: centralized rate limiting middleware, security headers, input validation, stress test

## 2026-04-27 19:59 - test: 22/22 stress test passing â€” rate limiting, auth, validation, concurrent load all verified

## 2026-04-28 15:45 - feat: word-by-word typewriter on chat replies, instant on fact card explanation

## 2026-04-28 16:37 - fix: no typewriter on history load, animate only new messages

## 2026-04-28 20:13 - feat: skeleton loader, spin ring on init, markdown rendering, save feedback, no typewriter on history

## 2026-04-29 06:32 - fix: reduce ML weight for short claims, AI dominates on factual statements

## 2026-04-29 15:12 - fix: health endpoint safe drift import, revert side panel, skeleton loader, markdown rendering, save feedback

## 2026-04-29 19:13 - docs: add mermaid architecture diagrams, fix project structure, improve local setup

## 2026-04-29 19:13 - feat: RoBERTa ML model (primary) + TF-IDF fallback + Colab training notebook with 5 HF datasets

## 2026-04-29 19:23 - chore: retrained models - 98.5% accuracy, brier 0.0119, 27k samples from 5 HF datasets

## 2026-04-30 13:57 - feat: industry-level hardening â€” security, logging, migrations, retry, pagination, indexes

## 2026-05-01 12:49 - fix: remove RoBERTa startup preload â€” was blocking port bind on Render free tier; add RAM guard

## 2026-05-01 13:42 - fix: revert authFetch content-type guard (breaks on proxy 503s); pin scikit-learn==1.6.1

## 2026-05-02 04:17 - feat: god-level DeBERTa fine-tuning notebook (10 datasets, ~130k samples) + configurable model via DEBERTA_MODEL env var

## 2026-05-02 15:32 - feat: Level 70+90 â€” cross-encoder evidence reranking + Wikidata entity verification

## 2026-05-02 20:35 - feat: real-time Brave Search API + publisher bias DB (100+ sources) + bias-weighted evidence scoring

## 2026-05-04 04:42 - feat: image+text consistency, multi-language support, cross-platform fact-check tracker

## 2026-05-04 05:14 - fix: clean DeBERTa notebook + explainability + continuous learning + stats route fix

## 2026-05-05 03:06 - feat: add verification checks to every cell in DeBERTa notebook

## 2026-05-05 07:09 - feat: attach menu (+) with image/PDF/txt support in chat input

## 2026-05-07 13:53 - fix: rewrite notebook with DistilBERT - no version issues, fp16 only on GPU, zero NaN

## 2026-05-09 06:37 - fix: remove pinned transformers version - use whatever Colab has

## 2026-05-09 20:03 - fix: pin transformers==4.41.3 + huggingface_hub==0.23.4 together - eliminates DryRunError

## 2026-05-09 20:29 - fix: remove all version pinning - use Colab's transformers 5.x as-is

## 2026-05-10 01:18 - Created using Colab

## 2026-05-10 06:53 - chore: update model_version.json - DistilBERT 98.91% accuracy

## 2026-05-10 17:51 - chore: add DEBERTA_MODEL + BRAVE_API_KEY + SERPAPI_KEY + GOOGLE_FACTCHECK_API_KEY to render.yaml and .env

## 2026-05-10 21:01 - fix: OOM - cap workers at 3, make Wikidata/platform conditional, fix req scope bug, increase body limit to 512KB

## 2026-05-11 04:52 - chore: trigger redeploy after history rewrite - repo now 4MB

## 2026-05-11 11:48 - fix: compress images to JPEG 800px before send, PDF text extraction, body limit 2MB, add .doc/.docx support

## 2026-05-12 12:26 - fix: allow image-only messages, auto-generate prompt when image sent without text

## 2026-05-13 01:56 - fix: allow send with image+no text, fix DOCX binary garbage, ensure sendText never empty

## 2026-05-13 20:01 - fix: image analysis - Gemini Vision retry with flash-lite fallback, fix rate limiting, fix error handling

## 2026-05-14 04:14 - Complete P1.1: Add all 7 training notebooks for transformer pipeline
