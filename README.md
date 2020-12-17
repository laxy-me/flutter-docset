# Flutter Docset for Dash

Please note that is docset is not very optimal because the `dashing.json` is not perfectly written. Futher help needed.

## How to use

Open `Preferences` of the Dash menu, then navigate to the `Downloads` tab. After that, click the + button at the bottom of the window. Add this URL for 'Docset Feed URL':

```
https://github.com/talkeryang/flutter-docset@master/flutter.xml
```

Finally, click the 'Download' button of the newly added `flutter` docset.

## How to build the docset by yourself (draft)

1. Clone the flutter repository to your local machine or use the `flutter` installted on your machine.
2. if you already have flutter environment use `flutter update-packages` to get packages.
3. Run the script `dev/bots/docs.sh` to build the flutter docs locally. It should take more than 10 minutes.
4. Install dashing with either of the following approaches (Reference: [https://github.com/technosophos/dashing](https://github.com/technosophos/dashing)):
    - For Mac users: `brew install dashing`
    - For other users: `go get -u github.com/technosophos/dashing`
5. Copy the `dashing.json` from this repository.
6. Run `dashing build dashing.json` to build the docset. It should also take more than 10 minutes.
