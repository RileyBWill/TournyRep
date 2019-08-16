# tourney-rep

Application for managing tournaments. Specifically trying to fill gaps in common MTG tournament software currently.

See `../TournamentReportingSoftware` for design documents.

## Development

This project uses Typescript + React + Redux with `fp-ts` to assist with functional programming primitives.
There will likely be a need for a local `sqlite` database in the future for the application to persist to,
but that has not been added yet.

```
git clone THIS_REPO
cd TourneyRep/tourney-rep
npm install
npm start
```

You can type `rs` into the terminal that you ran `npm start` from at any time to restart the Electron application.

`main` and `renderer` are boilerplate to load the application into a window. `components` is where the actual App main is.
Additional logic and visual components should go in `components`.

## Release

unknown

## Deployment

unknown
