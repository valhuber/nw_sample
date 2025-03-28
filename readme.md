Find this at: https://github.com/valhuber/nw_sample

Explore admin support - `ui/admin/authentication_admin.yaml`

This is als app - not a wg app.  
* WG support will require (at least) substitution into the ui/admin/authentication_admin.yaml

This includes admin_loader fix from Thomas (multiple versions)...

Unclear about 01.... the following both were tried with: http://127.0.0.1:5656/01/auth-admin/index.html
1. ui/admin/admin_loader_working_01.py
2. ui/admin/admin_loader_working_no_01.py

The test above worked ***from cache,***, but not incognito...

Url from the past used `load=`

http://localhost:5656/admin-app/index.html#/Configuration?load=https://g.apifabric.ai/01JQ98NVZ3JJHD0B9XJPNARKKG/ui/admin/admin.yaml?v=1743095703093

