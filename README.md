## AWS-AutoSubmit
This is a simple macro based on selenium for AWS DeepRacer. You can use it to submit the current month's AWS Summit Online module.

## Setup
When using it for the first time, please go to `config.ini` file to set up your own AWS account.

You just need to input you AUTH info and your Summit Model Name then you can use it to free your hand.


## Quick Start
Make Sure you chrome version is `85.0.4183.102`
If the version it not match please go to https://sites.google.com/a/chromium.org/chromedriver/downloads

For windows powershell
```bash
> git clone https://github.com/lshw54/AWS-AutoSubmit.git
> cd AWS-AutoSubmit
> python -m venv venv
> .\venv\Scripts\activate
> 
> pip install -r requirements.txt
> .\main.py
```