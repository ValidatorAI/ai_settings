# ai_settings — Hermes profile distribution

Generated 2026-11-16T16:15:04+03:30 from /home/siavash/.hermes/profiles/ai_settings by to-profile-dist.sh.

Install on any machine:
    hermes profile install <this-repo-git-url>
    cp ~/.hermes/profiles/ai_settings/.env.EXAMPLE ~/.hermes/profiles/ai_settings/.env   # fill keys, chmod 600
    hermes -p ai_settings chat -Q -q "reply with exactly: PROFILE-OK"

Iterate: edit the files here, bump version in distribution.yaml, push; then on each machine:
    hermes profile update ai_settings
User data (memories, sessions, .env, auth) is never overwritten by updates;
config.yaml is preserved unless --force-config.
