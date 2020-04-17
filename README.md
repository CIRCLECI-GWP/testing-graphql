# Automated Testing in Graphql with CircleCI

[![CircleCI](https://circleci.com/gh/CIRCLECI-GWP/ci-cd-android.svg?style=svg)](https://circleci.com/gh/CIRCLECI-GWP/ci-cd-android)

## Running the server

- Have Node installed
- Run
    ```bash
    npm install
    ```
- Run 
    ```bash
    npm start
    ```
- Navigate to [http://localhost:4000/playground](http://localhost:4000/playground)

- Input the following query and press the play button to test it the API:

    ```
    {
      users {
        name
        email
        posts {
          title
          published
        }
      }
    }
    ```



## Running tests

Run 
```bash
npm test
```