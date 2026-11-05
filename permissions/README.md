# permissions

Scripts for Shell, permissions.

- 0-iam_betty: switches to the user betty
- 1-who_am_i: prints the effective username
- 2-groups: prints the groups of the current user
- 3-new_owner: changes the owner of hello to betty
- 4-empty: creates an empty file named hello
- 5-execute: adds owner execute permission on hello
- 6-multiple_permissions: adds execute for owner and group, and read for others, on hello
- 7-everybody: adds execute permission for owner, group, and others on hello
- 8-James_Bond: gives all permissions to others and none to owner and group
- 9-John_Doe: sets hello to mode rwxr-x-wx
- 10-mirror_permissions: copies the mode of olleh onto hello
- 11-directories_permissions: adds execute permission on subdirectories only
- 12-directory_permissions: creates my_dir with mode 751
- 13-change_group: changes the group of hello to school
- 14-change_owner_and_group: sets owner vincent and group staff on the working directory contents
- 15-symbolic_link_permissions: changes the owner and group of the _hello symlink
- 16-if_only: changes hello owner to vincent only when guillaume owns it
