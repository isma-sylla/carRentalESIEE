# carRentalEsiee

## PUT Request

curl --header "Content-Type: application/json" --request PUT --data '{"debut":"4/11/2024","fin":"20/11/2024"}' 'http://localhost:8080/cars/11AA22?rent=true'

### Launch a workflow when the code is updated

The script is there: https://github.com/charroux/carRentalEsiee/blob/main/.github/workflows/action.yml

Create a new branch on your machine:
```
git branch newcarservice
```
Move to the new branch:
```
git checkout newcarservice
```
Update the code and commit changes:
```
git commit -a -m "newcarservice"
```
Push the changes to GitHub:
```
git push -u origin newcarservice
```
Create a Pull request on GitHub and follow the workflow.

Merge the branch on Github is everything is OK.

Then pull the new main version:

```
git checkout main
```
```
git pull origin main
```

If necessary delete the branch:

```
git branch -D newcarservice
```
```
git push origin --delete newcarservice
```