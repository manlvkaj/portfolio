### Handling large videos
- Because the videos are large we had to move to cloudflare r2
- Go to cloudflare r2 account and check the portfolio bucket for the videos
- When using it from the code, use the full url e.g. https://anjolaaluko.com/vid/8_2.jpg
- To add new videos, upload to r2 and get the url.

### Steps to push new code to github from vscode

- Make sure all your changes are saved
- Open the vs code terminal
- `git add .`
- `git commit -m "<type any message for your commit>"`
- `git push`


#### Steps to push new code to github from terminal
- Open terminal app
- enter `cd Documents/WEB-DEVELOPMENT/AJ-Portfolio-Website`
- `git add .`
- `git commit -m "<type any message for your commit>"`
- `git push`