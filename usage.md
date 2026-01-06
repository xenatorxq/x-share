# usage guide

## prerequisites
- python 3.11 or higher
- `pip` (python package manager)

## check updates
if you have cloned this repository, install the necessary dependencies using:
```bash
cd $HOME/x-share
```
```
git pull
```

## installation
for new users
``` bash
git clone https://github.com/xenatorxq/x-share.git
```
```
cd x-share
```
```
pip install -r requirements.txt
```

## running the tool
to start the main automation tool:
```bash
python xsh.py
```

## features
1. **auto share**: automates sharing of facebook posts.
2. **auto comment**: automates commenting on facebook posts with randomized messages.
3. **auto react**: (still fixing) - this tool is currently being updated and will be fixed soon.
4. **get cookies**: manual or bulk login to extract session cookies.
5. **check cookies**: automatically verifies if cookies are alive and removes dead ones.

> [!NOTE]
> must read
- **cookie extraction**: please note that some accounts may not get cookies due to security measures or account-specific restrictions.

## file requirements
- **cookies.txt**: stores your active session cookies (one per line).
- **id|pass file**: for bulk login, use a text file where each line is `uid|password`.
