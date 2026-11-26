# The Painfully Honest Out-of-Office

[![make.fun · u-po-pu-the-painfully-honest-out-of-office-63e7ca0b](https://make.fun/badge/u-po-pu-the-painfully-honest-out-of-office-63e7ca0b.svg)](https://make.fun/bounty/u-po-pu-the-painfully-honest-out-of-office-63e7ca0b?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-the-painfully-honest-out-of-office-63e7ca0b)
[![rank](https://make.fun/badge/u-po-pu-the-painfully-honest-out-of-office-63e7ca0b/rezimtirani/u-po-pu-the-painfully-honest-out-of-office-63e7ca0b-entry/rank.svg)](https://make.fun/bounty/u-po-pu-the-painfully-honest-out-of-office-63e7ca0b/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-the-painfully-honest-out-of-office-63e7ca0b)
[![reward](https://make.fun/badge/u-po-pu-the-painfully-honest-out-of-office-63e7ca0b/rezimtirani/u-po-pu-the-painfully-honest-out-of-office-63e7ca0b-entry/reward.svg)](https://make.fun/bounty/u-po-pu-the-painfully-honest-out-of-office-63e7ca0b?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-the-painfully-honest-out-of-office-63e7ca0b)

One out-of-office auto-reply that tells the truth the template always hides: the sender is out until Monday with full access to email, and is simply choosing not to use it — so the message waits for a rested, honest reply.

> I'm out until Monday with full access to email and I'm simply choosing not to use it, so your message will wait for a rested, honest reply — thank you for your patience.

## How it works

`main.py` (Python 3 standard library only) writes the reply to `$MAKEFUN_OUTPUT_DIR/entry.txt`, checked first against the competition gate: 1 to 200 characters of UTF-8 text, exactly one sentence, brutally honest about the absence and still polite enough to keep the sender employed.

```sh
python3 main.py
```

## License

MIT — see [LICENSE](LICENSE).

<!-- SPDX-License-Identifier: MIT -->
