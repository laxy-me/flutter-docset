# Flutter Docset for Dash

## How to build the docset by yourself (draft)

1. Clone the flutter repository to your local machine or use the `flutter` installted on your machine.
2. If you already have flutter environment use `flutter update-packages` to get packages.
3. Install dashing with either of the following approaches (Reference: [https://github.com/technosophos/dashing](https://github.com/technosophos/dashing)):
    - For Mac users: `brew install dashing`
    - For other users: `go get -u github.com/technosophos/dashing`
4. Run the script `dev/bots/docs.sh` to build the flutter docs locally. It should take more than 10 minutes.
5. If commond interrupted with an exception like Dashing docset generation failed you should generate docsets by your self.It should take more than 10 minutes.
