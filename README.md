# ktlint_accent_error

Repo created in order to show accent error in Ktlint plugin

To see the problem do the following steps:
```bash
git clone https://github.com/NarcAle/ktlint_accent_error.git
cd ktlint_accent_error 
cd ktlint_àccent_error 
gradlew ktlintCheck
```
Now into the root folder, you'll have another folder with the same name but with a special character instead of the accented letter.
The output folder "build" will contain the "reports" folder but it is empty. The report files will be into the twin folder wrongly generated. 
