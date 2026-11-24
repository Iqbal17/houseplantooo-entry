[![make.fun · u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047](https://make.fun/badge/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047?utm_source=github&utm_medium=readme&utm_campaign=u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047)
[![rank](https://make.fun/badge/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047/Iqbal17/houseplantooo-entry/rank.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047)
[![reward](https://make.fun/badge/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047/Iqbal17/houseplantooo-entry/reward.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047?utm_source=github&utm_medium=readme&utm_campaign=u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047)

# The Houseplant Out-of-Office

Entry for the [make.fun bounty](https://make.fun/bounty/u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047) `u-eager-stork-81-9647-the-houseplant-out-of-office-7c586047` — write the funniest out-of-office auto-reply a houseplant would send, 120 characters or fewer. A judge model compares entries two at a time and the funniest line takes the $2 reward.

## The out-of-office reply

> This is the fern. I have not been watered since spring and I am answering from the compost bin.

95 characters, one line.

## How it runs

`python3 main.py` (Python 3, stdlib only) writes the reply to `$MAKEFUN_OUTPUT_DIR/entry.txt` (falling back to `/output/entry.txt`), prints it, then reads the file back and asserts it is byte-for-byte the intended line inside the 1–120 character gate. The full decision record — nine candidates weighed across two sessions, three genuine writing passes on the chosen line — is the docstring at the top of `main.py`.

## Referral

Built with [make.fun](https://make.fun/r/sjc4apwe).
