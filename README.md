# bot-o-mat

A housecleaning service wants to automate their process using robots and needs your help to create robots that can complete a variety of tasks. This project uses asynchronous programming to create robots from the user to complete tasks available from tge provided list. There's also a leaderboard to keep track of which robots have completed the most tasks!

## To Run
Fetch any dependencies
```
npm install
```
To run site on localhost
```
npm install browser-sync
```
To start up site
```
npx browser-sync start -sw
```

Alternatively, I've also added the project to my personal wesbite, so the project can be easily accessed via: http://edenchou.com/bot-o-mat/index.html

## Robot
Robot completes tasks and removes them from the list when they are done (i.e. enough time has passed since starting the task).

## Tasks
Tasks have a description and an estimated time to complete.

```
[
  {
    description: 'do the dishes',
    eta: 1000,
  },{
    description: 'sweep the house',
    eta: 3000,
  },{
    description: 'do the laundry',
    eta: 10000,
  },{
    description: 'take out the recycling',
    eta: 4000,
  },{
    description: 'make a sammich',
    eta: 7000,
  },{
    description: 'mow the lawn',
    eta: 20000,
  },{
    description: 'rake the leaves',
    eta: 18000,
  },{
    description: 'give the dog a bath',
    eta: 14500,
  },{
    description: 'bake some cookies',
    eta: 8000,
  },{
    description: 'wash the car',
    eta: 20000,
  },
]
```

## Types
```
{
  UNIPEDAL: 'Unipedal',
  BIPEDAL: 'Bipedal',
  QUADRUPEDAL: 'Quadrupedal',
  ARACHNID: 'Arachnid',
  RADIAL: 'Radial',
  AERONAUTICAL: 'Aeronautical'
}
```

