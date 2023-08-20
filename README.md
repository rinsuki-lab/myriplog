# riplog

XLD ripping log

## Q. What I can do with those logs??

with this repository's files, you can:
* **VERIFY** your audio data by checksums
  * NOTICE: I don't have a proof about my discs are genuine and not corrupted.
    * but I believe my disc is a genuine one
      * I'm mostly purchasing from Amazon.co.jp (but not market place), TOWER RECORD, or another physical store that looks decent.
      * some of logs are coming from disk that rentaled, those logs have a `.rental.log` suffix in file name.
    * sadly, some of discs are not correctly readable.
      * If [Pioneer PureRead](https://jpn.pioneer/ja/pcperipherals/bdd/pureread/)'s Perfect Mode will not able to read discs, or fail to AccurateRip, I will add `.damaged` suffix in file name.
        * If they are rentaled disc, it would be like `.damaged.rental.log`.
* you can find CD's ToC (table of contents)
  * which means you can find CDDB's record from my logs
* you may able to get ISRC code from my logs

but **YOU CAN'T GET AUDIO DATA depends only to those logs.**
for get actual data, you always need to original CD (or purchase audio data in online store).

## Q. Why you are publishing those logs??

some of discs are not have a enough number of AccurateRip hashes (e.g. [Splatoon 3 ORIGINAL SOUNDTRACK](./game/soundtrack/nintendo/splatoon)).

also AccurateRip server _may_ gone or shutdown in the any point of future (theres no server that immortal in the world).

so I'm making a sub-set backup of AccurateRip server, for my ripped discs.

## suffixes

first

* `.discN`
  * (`N` will be replaced with `/[0-9]+/`)
  * multi-disc album (starting from 1).
* `.damaged`
  * Pioneer PureRead Perfect Mode, or AccurateRip will not passed.
* `.rental`: 
  * Logs are generated from rentaled disc.

last