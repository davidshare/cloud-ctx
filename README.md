# Cloudctx
A GUI app to help you switch your cloud context

### To run the application

##### Clone the repository
`git clone git@github.com:davidshare/cloudctx.git`

##### Get into the directory for the project
`cd cloudctx`

##### Install node modules
`npm install`

##### Rebuild electron to make sure that the electron packages are compartible with your node version
`npm run rebuild`

##### Start the app
`npm start`
### Todos

##### Style interface

- [ ] Create a dashboard with a side bar where the contexts will be listed
- [ ] Adjust the window size to be 100% 
- [ ] Change the themes for the terminal - we can explore using vscode themes  

###### Functionality
- [ ] get list of kubernetes contexts from the .kube directory
- [ ] get list of aws profiles from the .aws directory
- [ ] set each tab switch to the context upon click
- [ ] Add copy and past functionality to terminal
- [ ] ... Add any functionality you can think of.