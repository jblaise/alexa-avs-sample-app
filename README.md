Please go to original [alexa avs sample](https://github.com/alexa/alexa-avs-sample-app) unless you know why you're here and what you're doing

# install
```bash
#edit .amazon-credentials
cp .amazon-credentials ~/
source ~/.amazon-credentials
./automated_install.sh
sudo ./update.sh
```
=> end


# short list of variations :
- avoid adding config dupes
- check java is already installed
- add domain support (=> nogui support)
- source domain, data, ssl data from .amazon-credentials (=> automation)
