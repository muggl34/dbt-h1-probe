Security test project (Bugcrowd researcher muggl3, Fivetran/dbt program). Contains no real data.
- models/h1_baseline.sql  : plain model (baseline)
- models/h1_ctrl.sql      : symlink to a file INSIDE the repo (positive control)
- models/h1_host.sql      : symlink to /etc/hostname (outside-root discriminator)
