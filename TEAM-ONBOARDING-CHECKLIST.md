# Team Onboarding Checklist (OpenClaw)

Use this for each new teammate.

## A) Prerequisites
- [ ] macOS machine ready
- [ ] Node + npm installed
- [ ] Claude CLI installed + authenticated

## B) Local Setup
- [ ] `npm install -g openclaw`
- [ ] `openclaw --version` works
- [ ] `openclaw gateway start`
- [ ] `openclaw gateway status` = running

## C) Provider Onboarding
- [ ] Run `claude setup token`
- [ ] Token pasted into OpenClaw onboarding
- [ ] Provider status = connected

## D) Validation
- [ ] `openclaw status` healthy
- [ ] Prompt test works (model + health reply)

## E) Optional Integrations
- [ ] `gh auth status` / login complete
- [ ] `vercel login` complete (if needed)
- [ ] `railway login` complete (if needed)

## F) Security Checks
- [ ] No raw tokens in docs/chats/screenshots
- [ ] Secrets stored only in local secure env
- [ ] Screenshots are redacted

## G) Sign-off
- [ ] Teammate can independently run setup
- [ ] Troubleshooting section shared
- [ ] Backup repo bookmarked
