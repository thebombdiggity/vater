# Environment 
![Range Diagram](diagram/range.svg)

## Old OCO Network Map
![Old OCO Network Map](diagram/Old_OCO_practice.svg)

## Instructor Experience
![Instructor Experience Diagram](diagram/instructorExperience.svg)

## Day 0 Deployment
- **Manually** provision `Control` VM
- **Manually** git clone `shoe-rack` into `~`
- **Manually** run ` ~/shoe-rack/control-services/bin/setup.sh`
- `setup.sh` will create a RSA key pair if one does not exist and print the public key to the terminal
- **Manually** copy the public RSA key
- **Manually** input public RSA key into `uwardlaw/rous` as a deploy key 
- `setup.sh` will pull `uwardlaw/rous` locally
- `setup.sh` will execute `pythohn3 setupGitea.py`
- `setupGitea.py` will locally import `uwardlaw/rous` into `config/rous`

(Developed in Nano)
