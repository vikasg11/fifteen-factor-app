### XII.	Admin Processes

The principle suggests running admin/management tasks as one-off processes. One-off admin processes should be run in an identical environment as the regular long-running processes of the app. Admin code must ship with application code to avoid synchronization issues. Developers need to make sure that one-off scripts are automated so that these are not executed manually before releasing the build.




