

# Creating and Resolving Merge conflict

1. Create a new repository with README.md in GitHub

2. Clone that repository into your local machine

3. Edit the READ.md file

4. Save the changes

5. Make some changes in commited repo using your home laptop

6. make same changes in commited repo using work laptop

7. Commit change in home laptop

8. Try to push that commit in worklaptop it will lead you pull command

9. At that time you find MERGE CONFLICT

10. Open the offending file (referenced in the conflict error) in VS Code. You'll find the following string highlighted on the page:

       <<<<<<< HEAD (Current Change)

    This is your local change. It conflicts with the Incoming Change (from GitHub) listed below it

       * Accept Current Change

       * Accept Incoming Change

       * Accept Both Changes

       * Compare changes

11. Add the file that caused the conflict

12. Commit your changes..

13. Now you can push your changes..!
