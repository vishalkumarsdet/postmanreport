## Repository for run test cases on every merge request cam to main branch.
Step to perfrom:
1. Frist upload you postman collection and environment variable to you repository.
2. Create a workflow e.g: .github/workflows
3. Create yml at this location.
4. You can define your rules as per your requirements.
Now you are done.

Steps to Test:

Create a branch to your main branch.
Make a merge request to main.
Go to GitHub Action section.
You can able to see the peipeline is runnig.
Once run completed click on run.
And top botton you will RunReports.
Click on RunReports and it'll download the report in the from of HTML.

