## Basic applescripts for day-to-day use

### Setup
The scripts are in binary form, so in order to only diff the textual parts of the scripts perform the following command in the repository,

```
cat .gitconfig >> .git/config
```

which appends the settings in .gitconfig to the config file for the repository.

## SwitchSoundOutput
Prompts the user the change the output speaker source. The script assumes that only to sources are available and chooses the one that is disabled.
