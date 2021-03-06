## Installation

You must have nodjs installed: https://nodejs.org. Make sure Python 2 is installed.

The following are instructions to download and install the repo.

```sh
git clone https://github.com/lupyanlab/RateTheseDrawings
cd RateTheseDrawings
npm install
pm2 start index.js --name RateTheseDrawings
```

## Development

If you are working on your local machinese, go to http://localhost:7100.

If you are working on Sapir, go to http://sapir.psych.wisc.edu/mturk/RateTheseDrawings/dev.

The static HTML, CSS, and JavaScript files are in the `dev/` directory, and the Node.js API server is located in the root `./index.js` file.

## Production

When you are done, run the following command on Sapir and go to http://sapir.psych.wisc.edu/mturk/RateTheseDrawings/prod.

```sh
npm run prod
```
