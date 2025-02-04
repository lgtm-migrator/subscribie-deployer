# v0.0.3 (Tue Nov 01 2022)

#### ⚠️ Pushed to `main`

- Update deploy.yml ([@chrisjsimpson](https://github.com/chrisjsimpson))

#### Authors: 1

- [@chrisjsimpson](https://github.com/chrisjsimpson)

---

# v0.0.2 (Mon Oct 31 2022)

#### ⚠️ Pushed to `main`

- Update .autorc ([@chrisjsimpson](https://github.com/chrisjsimpson))

#### Authors: 1

- [@chrisjsimpson](https://github.com/chrisjsimpson)

---

# v0.0.1 (Mon Oct 31 2022)

:tada: This release contains work from new contributors! :tada:

Thanks for all your work!

:heart: null[@chrisjsimpson](https://github.com/chrisjsimpson)

:heart: null[@joeltejeda](https://github.com/joeltejeda)

#### 🐛 Bug Fix

- Fix #78 set SUPPORTED_CURRENCIES during shop deploy [#79](https://github.com/Subscribie/subscribie-deployer/pull/79) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- rename systemd service [#77](https://github.com/Subscribie/subscribie-deployer/pull/77) ([@joeltejeda](https://github.com/joeltejeda))
- update readme apache and nginx config [#77](https://github.com/Subscribie/subscribie-deployer/pull/77) ([@joeltejeda](https://github.com/joeltejeda))
- Fix #69 adding the default_country_code to database and optimizing the code [#75](https://github.com/Subscribie/subscribie-deployer/pull/75) ([@joeltejeda](https://github.com/joeltejeda))
- #71 bring back .env.example [#72](https://github.com/Subscribie/subscribie-deployer/pull/72) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- Fix #71 improve debugging [#72](https://github.com/Subscribie/subscribie-deployer/pull/72) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- #71 remove uneeded .new-shop.env.example because read from https://github.com/Subscribie/subscribie/blob/master/.envsubst.template [#72](https://github.com/Subscribie/subscribie-deployer/pull/72) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- wip Fix #71 .env.example -> .new-shop.env.example [#72](https://github.com/Subscribie/subscribie-deployer/pull/72) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- Fix #69 adding currencies and countries lists [#70](https://github.com/Subscribie/subscribie-deployer/pull/70) ([@joeltejeda](https://github.com/joeltejeda))
- Fix #63 update systemd subscribie-deployer.service example [#64](https://github.com/Subscribie/subscribie-deployer/pull/64) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- wip fix #63 migrate to starlette and uvicorn [#64](https://github.com/Subscribie/subscribie-deployer/pull/64) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- #58 remove breakpoint [#64](https://github.com/Subscribie/subscribie-deployer/pull/64) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- #58 black format tidy [#59](https://github.com/Subscribie/subscribie-deployer/pull/59) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- Fix #58 set default_currency [#59](https://github.com/Subscribie/subscribie-deployer/pull/59) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- Fix #53 use python-dotenv to load env settings [#54](https://github.com/Subscribie/subscribie-deployer/pull/54) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- #49 move logto = /var/log/vassal-%n.log to common vassals-inject-config [#50](https://github.com/Subscribie/subscribie-deployer/pull/50) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- Fix #49 remove uneeded content from app.skel [#50](https://github.com/Subscribie/subscribie-deployer/pull/50) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- fix #47 changing typo MAIL to EMAIL env seeting [#48](https://github.com/Subscribie/subscribie-deployer/pull/48) ([@joeltejeda](https://github.com/joeltejeda))
- adding systemctl file config [#46](https://github.com/Subscribie/subscribie-deployer/pull/46) ([@joeltejeda](https://github.com/joeltejeda) [@chrisjsimpson](https://github.com/chrisjsimpson))
- adding rename script variables into env [#44](https://github.com/Subscribie/subscribie-deployer/pull/44) ([@joeltejeda](https://github.com/joeltejeda))
- use .envsubst.template #34 [#42](https://github.com/Subscribie/subscribie-deployer/pull/42) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- Revert "ref #34 use .envsubst.template over .env" [#41](https://github.com/Subscribie/subscribie-deployer/pull/41) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- ref #34 use .envsubst.template over .env [#35](https://github.com/Subscribie/subscribie-deployer/pull/35) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- #34 during site build, set telegram logging [#35](https://github.com/Subscribie/subscribie-deployer/pull/35) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- #34 flake8 main.py [#35](https://github.com/Subscribie/subscribie-deployer/pull/35) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- #34 set the TELEGRAM_PYTHON_LOG_LEVEL during build [#35](https://github.com/Subscribie/subscribie-deployer/pull/35) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- #34 remove python-dotenv [#35](https://github.com/Subscribie/subscribie-deployer/pull/35) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- #34 remove test TELEGRAM_TOKEN (not real) [#35](https://github.com/Subscribie/subscribie-deployer/pull/35) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- wip #34 replace dotenv with envsubst for speed [#35](https://github.com/Subscribie/subscribie-deployer/pull/35) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- remove ssh-keygen , PRIVATE_KEY , PUBLIC_KEY from deploy step #34 [#35](https://github.com/Subscribie/subscribie-deployer/pull/35) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- Fix #38 set envs needed for shop owner self activation [#39](https://github.com/Subscribie/subscribie-deployer/pull/39) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- Fix #32 preseed login_token [#33](https://github.com/Subscribie/subscribie-deployer/pull/33) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- add uWSGI==2.0.20 for vassel emperor loading [#33](https://github.com/Subscribie/subscribie-deployer/pull/33) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- Fix #27 remove uneeded old mail settings / set email queue settings [#28](https://github.com/Subscribie/subscribie-deployer/pull/28) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- Fix #25 dont require description during signup [#26](https://github.com/Subscribie/subscribie-deployer/pull/26) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- correct cron refresh subscriptions to 10 mins ([@chrisjsimpson](https://github.com/chrisjsimpson))
- Merge branch 'master' into 12-use-shared-repo [#14](https://github.com/Subscribie/subscribie-deployer/pull/14) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- removed GOOGLE_REDIRECT_URI from .env.example as is set dynamically [#14](https://github.com/Subscribie/subscribie-deployer/pull/14) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- add google oauth settings env and .env.example [#14](https://github.com/Subscribie/subscribie-deployer/pull/14) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- #12 update readme [#13](https://github.com/Subscribie/subscribie-deployer/pull/13) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- wip #12 pin requirements.txt and remove undeeded Migrate [#13](https://github.com/Subscribie/subscribie-deployer/pull/13) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- #12 update readme & .env.example [#13](https://github.com/Subscribie/subscribie-deployer/pull/13) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- #12 wip Rather copy empty db schema to speedup deploy [#13](https://github.com/Subscribie/subscribie-deployer/pull/13) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- #12 use shared repo when deploying sites wip [#13](https://github.com/Subscribie/subscribie-deployer/pull/13) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- #9 keep old stripe env settings during deploy migration to stripe connect [#10](https://github.com/Subscribie/subscribie-deployer/pull/10) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- fix #9 updated main.py to deploy stripe test/live mode keys [#10](https://github.com/Subscribie/subscribie-deployer/pull/10) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- wip #9 .env.example add STRIPE_LIVE/STRIPE_TEST connect examples [#10](https://github.com/Subscribie/subscribie-deployer/pull/10) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- wip #9 pep8 and format main.py [#10](https://github.com/Subscribie/subscribie-deployer/pull/10) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- generate public/private kets for jwt auth token [#7](https://github.com/Subscribie/subscribie-deployer/pull/7) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- rename item->plan [#6](https://github.com/Subscribie/subscribie-deployer/pull/6) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- support interval_unit and interval_amount [#5](https://github.com/Subscribie/subscribie-deployer/pull/5) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- remove clone of subscription-management-software [#5](https://github.com/Subscribie/subscribie-deployer/pull/5) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- seed users table with hashed password during deployment [#4](https://github.com/Subscribie/subscribie-deployer/pull/4) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- add dotenv calls to setup .env [#3](https://github.com/Subscribie/subscribie-deployer/pull/3) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- wip use dotenv for settings environment loading [#3](https://github.com/Subscribie/subscribie-deployer/pull/3) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- fix #1 seed integration, sellingpoints tables [#2](https://github.com/Subscribie/subscribie-deployer/pull/2) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- wip #1 seed database during deployment [#2](https://github.com/Subscribie/subscribie-deployer/pull/2) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- wip #1 remove jamla [#2](https://github.com/Subscribie/subscribie-deployer/pull/2) ([@chrisjsimpson](https://github.com/chrisjsimpson))

#### ⚠️ Pushed to `main`

- Update .autorc ([@chrisjsimpson](https://github.com/chrisjsimpson))
- create deploy.yml workflow ([@chrisjsimpson](https://github.com/chrisjsimpson))
- create autorc release.yml workflow ([@chrisjsimpson](https://github.com/chrisjsimpson))
- create .issue_template ([@chrisjsimpson](https://github.com/chrisjsimpson))
- create .autorc ([@chrisjsimpson](https://github.com/chrisjsimpson))
- #53 actually load the env settings into flask ([@chrisjsimpson](https://github.com/chrisjsimpson))
- Remove old mod_wsgi example in favour of uwsgi ([@chrisjsimpson](https://github.com/chrisjsimpson))
- remove dead code GOOGLE auth settings ([@chrisjsimpson](https://github.com/chrisjsimpson))
- Update app.skel ([@chrisjsimpson](https://github.com/chrisjsimpson))
- update readme mod_wsgi apache python venv ([@chrisjsimpson](https://github.com/chrisjsimpson))
- auto refresh subscription statuses via uwsgi cron ([@chrisjsimpson](https://github.com/chrisjsimpson))
- create custom_pages_path during deployment ([@chrisjsimpson](https://github.com/chrisjsimpson))
- create custom_pages dir during deploy ref ([@chrisjsimpson](https://github.com/chrisjsimpson))
- store description during site creation not selling points ([@chrisjsimpson](https://github.com/chrisjsimpson))
- enable-threads uwsgi ([@chrisjsimpson](https://github.com/chrisjsimpson))
- update config.ini.example ([@chrisjsimpson](https://github.com/chrisjsimpson))
- correct seed plans table prepared statement ([@chrisjsimpson](https://github.com/chrisjsimpson))
- seed hidden plans none by default ([@chrisjsimpson](https://github.com/chrisjsimpson))
- seed plans table trial_period_days 0 ([@chrisjsimpson](https://github.com/chrisjsimpson))
- correct osmkdirs -> os.makedirs ([@chrisjsimpson](https://github.com/chrisjsimpson))
- mkdir upload directory upon site build ([@chrisjsimpson](https://github.com/chrisjsimpson))
- env GOOGLE_SCOPE may contain spaces ([@chrisjsimpson](https://github.com/chrisjsimpson))
- Merge branch '12-use-shared-repo' ([@chrisjsimpson](https://github.com/chrisjsimpson))
- removed GOOGLE_REDIRECT_URI from .env.example as is set dynamically ([@chrisjsimpson](https://github.com/chrisjsimpson))
- add google oauth settings env and .env.example ([@chrisjsimpson](https://github.com/chrisjsimpson))
- fix duplication of [uwsi] config ([@chrisjsimpson](https://github.com/chrisjsimpson))
- terminate uwsgi config with newline char ([@chrisjsimpson](https://github.com/chrisjsimpson))
- use shared venv for sites ([@chrisjsimpson](https://github.com/chrisjsimpson))
- set SQLALCHEMY_DATABASE_URI & DB_FULL_PATH during deploy ([@chrisjsimpson](https://github.com/chrisjsimpson))
- remove unused STRIPE_SECRET_KEY and STRIPE_PUBLISHABLE_KEY ([@chrisjsimpson](https://github.com/chrisjsimpson))
- update .env.example and improve deployment speed ([@chrisjsimpson](https://github.com/chrisjsimpson))
- remove unused imports ([@chrisjsimpson](https://github.com/chrisjsimpson))
- add cron to app skel for stripe connect announce ([@chrisjsimpson](https://github.com/chrisjsimpson))
- update app.skel default threads=2 and processes=1 for each site ([@chrisjsimpson](https://github.com/chrisjsimpson))
- set HONEYCOMB_API_KEY during site deploys ([@chrisjsimpson](https://github.com/chrisjsimpson))
- correct keyerror enumerate selling points ([@chrisjsimpson](https://github.com/chrisjsimpson))
- correct paths UPLOADED_IMAGES_DEST UPLOADED_FILES_DEST ([@chrisjsimpson](https://github.com/chrisjsimpson))
- add apache style log formating with host for each site ([@chrisjsimpson](https://github.com/chrisjsimpson))
- removed module_seo_page_title module since its now in core ([@chrisjsimpson](https://github.com/chrisjsimpson))
- remove module_style_shop as its in core now ([@chrisjsimpson](https://github.com/chrisjsimpson))
- remove pages module inject as in core now ([@chrisjsimpson](https://github.com/chrisjsimpson))
- add stripe connect keys during deploy STRIPE_PUBLISHABLE_KEY STRIPE_SECRET_KEY ([@chrisjsimpson](https://github.com/chrisjsimpson))
- set SERVER_NAME ([@chrisjsimpson](https://github.com/chrisjsimpson))
- remove MAX_CONTENT_LENGTH="52428800" as should be in subscribie .env.example ([@chrisjsimpson](https://github.com/chrisjsimpson))
- comment .env.example Stripe connect api keys (not keys of shop owner) ([@chrisjsimpson](https://github.com/chrisjsimpson))
- set MAX_CONTENT_LENGTH="52428800" 50mb ([@chrisjsimpson](https://github.com/chrisjsimpson))
- add STRIPE_SECRET_KEY & STRIPE_PUBLISHABLE_KEY during deploy ([@chrisjsimpson](https://github.com/chrisjsimpson))
- set UPLOADED_FILES_DEST during site creation ([@chrisjsimpson](https://github.com/chrisjsimpson))
- add module style shop as default module ([@chrisjsimpson](https://github.com/chrisjsimpson))
- add cli to dotenv ([@chrisjsimpson](https://github.com/chrisjsimpson))
- Fix #179 lowercase email during signup ([@chrisjsimpson](https://github.com/chrisjsimpson))
- add module_pages as default module seed database ([@chrisjsimpson](https://github.com/chrisjsimpson))
- correct auth login url ([@chrisjsimpson](https://github.com/chrisjsimpson))
- correctly decode login token ([@chrisjsimpson](https://github.com/chrisjsimpson))
- remove config.py not needed ([@chrisjsimpson](https://github.com/chrisjsimpson))
- added .env.example and update readme ([@chrisjsimpson](https://github.com/chrisjsimpson))
- update config.py.example defaults ([@chrisjsimpson](https://github.com/chrisjsimpson))
- update readme ([@chrisjsimpson](https://github.com/chrisjsimpson))
- Create deployer only repo taken from module_builder ([@chrisjsimpson](https://github.com/chrisjsimpson))

#### 🔩 Dependency Updates

- Bump uvicorn from 0.18.3 to 0.19.0 [#80](https://github.com/Subscribie/subscribie-deployer/pull/80) ([@dependabot[bot]](https://github.com/dependabot[bot]))
- Bump python-dotenv from 0.20.0 to 0.21.0 [#67](https://github.com/Subscribie/subscribie-deployer/pull/67) ([@dependabot[bot]](https://github.com/dependabot[bot]))
- Bump uvicorn from 0.18.2 to 0.18.3 [#66](https://github.com/Subscribie/subscribie-deployer/pull/66) ([@dependabot[bot]](https://github.com/dependabot[bot]))
- Bump werkzeug from 2.2.1 to 2.2.2 [#65](https://github.com/Subscribie/subscribie-deployer/pull/65) ([@dependabot[bot]](https://github.com/dependabot[bot]))
- Bump starlette from 0.20.4 to 0.21.0 [#68](https://github.com/Subscribie/subscribie-deployer/pull/68) ([@dependabot[bot]](https://github.com/dependabot[bot]))
- Upgrade to GitHub-native Dependabot [#18](https://github.com/Subscribie/subscribie-deployer/pull/18) ([@dependabot-preview[bot]](https://github.com/dependabot-preview[bot]))
- Bump python-dotenv[cli] from 0.13.0 to 0.15.0 [#11](https://github.com/Subscribie/subscribie-deployer/pull/11) ([@dependabot-preview[bot]](https://github.com/dependabot-preview[bot]))

#### Authors: 4

- [@chrisjsimpson](https://github.com/chrisjsimpson)
- [@dependabot-preview[bot]](https://github.com/dependabot-preview[bot])
- [@dependabot[bot]](https://github.com/dependabot[bot])
- [@joeltejeda](https://github.com/joeltejeda)
