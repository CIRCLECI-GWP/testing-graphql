# Automated Testing in Graphql with CircleCI

[![CircleCI](https://circleci.com/gh/CIRCLECI-GWP/testing-graphql.svg?style=svg)](https://app.circleci.com/pipelines/github/CIRCLECI-GWP/testing-graphql?branch=master)

<p align="center"><img src="https://avatars3.githubusercontent.com/u/59034516"></p>

## Details

This repo is a Nuxt.js project built following a tutorial published on *NewStack blog* under the CircleCI Guest Writer Program.

- Blog post: [Automated Testing in Graphql with CircleCI][blog]
- Author's GitHub profile: [Fikayo Adepoju][author]

### About CircleCI Guest Writer Program

Join a team of freelance writers and write about your favorite technology topics for the CircleCI blog. Read more about the program [here][gwp-program].

Reviewers: [Ron Powell][ron], [Stanley Ndagi][stan]

[blog]: https://thenewstack.io/automatic-testing-for-graphql-apis/
[author]: https://github.com/coderonfleek

[gwp-program]: https://circle.ci/3ahQxfu
[ron]: https://github.com/ronpowelljr
[stan]: https://github.com/NdagiStanley

---

## Application

### Build set up

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
