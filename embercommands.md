# Ember Commands and Workflow

## Workflow Overview

1) Follow Start Project and Install Dependencies

2) Create Application Template

3) Create Root View (Index - Find All Maybe)

4) Create Model

5) Create Services

6) Create Components, Computed Properties and Helpers (as Needed)

### Start a New Project and Install Dependences

#### Create Project

`ember new project-name`. Navigate to via `cd project-name`

#### Emberfire

Add emberfire for Database `ember install emberfire`

##### Emberfire Queries

[https://www.learnhowtoprogram.com/javascript/ember-extended/firebase-queries](https://www.learnhowtoprogram.com/javascript/ember-extended/firebase-queries)

#### Ember Bootstrap

Add Bootstrap for Styling `ember install ember-bootstrap`

#### SASS

ember install ember-cli-sass

### Create an Application Template

`ember g template application`

### Create an Index Route and Additional Routes as Needed

`ember g route index`

#### Additional Routes

`ember g route name`

[https://guides.emberjs.com/v2.9.0/routing/defining-your-routes/](https://guides.emberjs.com/v2.9.0/routing/defining-your-routes/)

### Create Model

`ember g model model-name`

### Services

`ember g service thing-name`

[https://guides.emberjs.com/v2.9.0/applications/services/](https://guides.emberjs.com/v2.9.0/applications/services/)

### Create Components, Computed Properties and Helpers

#### Create Components

`ember g component component-name`

#### Create Computed Properties

[https://www.learnhowtoprogram.com/javascript/ember-extended/basic-computed-properties](https://www.learnhowtoprogram.com/javascript/ember-extended/basic-computed-properties)

#### Create Helpers

`ember g helper helper-name`
