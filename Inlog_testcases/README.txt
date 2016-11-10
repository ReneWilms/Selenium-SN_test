In the Inlog_testcase the steps to log into ServiceNow are stored.

These test cases will not be synchronised with GitHub.
That is done by having these lines in the .gitignore file of this folder.
   # ==========IMPORTANT FOR SECURITY REASONS=====
   # Testcases with login info
   *login*.*

Make sure that your personal testcase to be used for login to SN have in the testcase file name the string "login" only those files will remain local and be published on GitHub.
