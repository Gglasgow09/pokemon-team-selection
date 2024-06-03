# Pokemon Team Selection

## Overview

The Pokemon Team Selection project is a web application that allows users to create their own Pokemon team using data from the Pokemon API. Users can select up to 6 Pokemon from the first 100 Pokemon available in the API and receive a confirmation message of their final selection. The project includes additional challenges to enhance the user experience by allowing multiple selections of the same Pokemon, naming Pokemon, and swapping out team members.

## Features

1. **Pokemon List**: Retrieve and display the first 100 Pokemon from the API.
2. **Team Selection**: Allow users to select exactly 6 Pokemon for their team.
3. **Confirmation Message**: Provide a confirmation message displaying the final team selection.

### Extra Challenge

1. **Multiple Selections**: Allow users to select multiple instances of the same Pokemon.
2. **Naming Pokemon**: Allow users to assign names to each Pokemon in their team.
3. **Team Management**: Allow users to swap out Pokemon from their team.

## API Endpoint

The following endpoint is used to retrieve the first 100 Pokemon from the Pokemon API:
https://pokeapi.co/api/v2/pokemon?limit=100


## Setup and Installation

1. **Clone the Repository**: 
   ```bash
   git clone <git@github.com:Gglasgow09/pokemon-team-selection.git>


2. **Navigate to the Project Directory**:
cd pokemon-app

3. **Install Dependencies**:
Install any required dependencies using npm or yarn

4. **Run the Application**:
Open the app.js file in your web browser to run the app.

## Usage
1. Load Pokemon: When the page loads, the first 100 Pokemon will be fetched and displayed.
2. Select Pokemon: Click on a Pokemon to add it to your team. You must select exactly 6 Pokemon.
3. Confirmation: Once 6 Pokemon are selected, a confirmation message will appear displaying your final team.

## Extra Challenge Usage
1. Select Multiple Pokemon: You can select the same Pokemon multiple times if this feature is implemented.
2. Name Pokemon: Enter a name for each Pokemon after adding it to your team.
3. Change Pokemon: Remove a Pokemon from your team and select a different one if needed.



