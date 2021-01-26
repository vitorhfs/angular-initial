# AngularFirstTutorial

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.1.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Project Overview

It shows the structure and design pattern that Angular adopts in a concise and complete tutorial. It uses a fake API that maintain the data mutable during the session, and the API just contain a bunch of registers of names ordered by ID, named here as "heroes". 
The UI has two main screens, one showing the first 4 heroes in cards and another one showind every one of them in smaller cards, and it also comes with a input to add a new hero and a delete button. Each of the screens have a link in the button that redirects to the specific hero that the user clicked, making possible to change the hero's name. Aside there is a search bar that fetches the API with a certain delay to prevent overfetching and presents autocomplete options underneath for selection into that editable hero page, and also in the aside session there is a log of every change occurred in the session, with the possibility to clean the log.