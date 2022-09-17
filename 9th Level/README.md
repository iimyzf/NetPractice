<img width="1149" alt="Level 9" src="https://github.com/iimyzf/NetPractice/blob/main/9th%20Level/level9.png">

## Level 9

  This level is pretty much the hardest one of them all, and it's a little bit complicated as well. What I did here is that first of all, we have **the Mask /18**, and as you know this mask can be divided into 4 subnets `(2^2 = 4)`, the IP addresses will be like this:

  * **1st one** starts from 0 and ends at 63 `(30.85.0.0)`
  * **2nd one** from 64 till 127 `(30.85.64.0)` for this one exactly, I did divide it by 2 as well:
    1. **1st one** from 0 till 63 `(30.85.64.0)`
    2. **2nd one** from 64 till 128 `(30.85.64.128)`
  * **3rd one** from 128 till 191 `(30.85.128.0)`
  * **4th and last one** from 192 till 254 `(30.85.192.0)` and that's exactly what I did, I divide it into 4 different subnets so I can work with it in the whole network.

  *I really don't know if I explain this level, but this is all I did, to be honest*
