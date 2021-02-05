# MagicBotson

[MagicBotson](https://twitter.com/BotsonMagic) is a Twitter bot that uses deep learning to post tweets in the style of NBA legend Magic Johnson.

## Files

The pertinent files contained are as follows:

Folder/Files  | Description
------------- | -------------
bot  | Contains server logic for the bot as well as setup details in AWS


*Bot* 

Files  | Description
------------- | -------------
.env  | Environment variables for keys (not included in repo)
buildpackage.sh | Script to zip the lambda function outlined in lambda_function.py
createlambdalayer.sh | Packages the libraries included in requirements.txt 
entrypoint.py | Test the bot locally 
src | Folder containing lambda function and generated tweets
TweetNet.ipynb | Jupyter Notebook detailing data collection and deep learning model

## Acknowledgements

## Contributing
Feel free to pull the bot's server logic for your own deployments.

## License
[MIT](https://choosealicense.com/licenses/mit/)
