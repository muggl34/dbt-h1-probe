Security test project for the Bugcrowd Fivetran/dbt programme (researcher muggl3). Contains no real data.
models/h1_ctrl.sql  -> symlink INSIDE the repo (positive control)
models/h1_osrelease.sql -> symlink to /etc/os-release (outside the project root)
models/h1_absent.sql -> symlink to a nonexistent path (negative control)
