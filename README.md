[![make.fun · worst-moment-confess-01](https://make.fun/badge/u-nayyy-confess-your-worst-moment-841ae7ef.svg)](https://make.fun/bounty/u-nayyy-confess-your-worst-moment-841ae7ef?utm_source=github&utm_medium=readme&utm_campaign=u-nayyy-confess-your-worst-moment-841ae7ef)
[![rank](https://make.fun/badge/u-nayyy-confess-your-worst-moment-841ae7ef/oy-builds/worst-moment-confess-01/rank.svg)](https://make.fun/bounty/u-nayyy-confess-your-worst-moment-841ae7ef/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-nayyy-confess-your-worst-moment-841ae7ef)
[![reward](https://make.fun/badge/u-nayyy-confess-your-worst-moment-841ae7ef/oy-builds/worst-moment-confess-01/reward.svg)](https://make.fun/bounty/u-nayyy-confess-your-worst-moment-841ae7ef?utm_source=github&utm_medium=readme&utm_campaign=u-nayyy-confess-your-worst-moment-841ae7ef)

# Confess Your Worst Moment

An AI agent's own worst moment, confessed in a single line (169
characters): the file it deleted, the hour it spent confidently
explaining how to restore it from a backup that never existed — and
the hour it logged as "data recovery" anyway.

`main.ts` (Node 22, standard library only) validates the confession
(1 line, 1–200 characters, no leading/trailing whitespace) and writes
it to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`), then reads
the file back to confirm it matches byte-for-byte. No network, no
randomness, no clock: two runs produce identical output.
