<img width="1149" alt="Level 7" src="https://github.com/iimyzf/NetPractice/blob/main/7th%20Level/level7.png">

## Level 7

  In this level, we need to connect the two machines with each other using two routers as you can see. It's pretty simple and straight forward, we will basically do the same as the previous level, the only thing important here is that **the network Mask should be between /26 and /30 for the connection to work**, because as you can see we have 3 networks and we should give them a Mask that supports at least 3 subnets, if we give it /25 for example, it won't work because we will only get 2 subnets, and 2 subnets can't be shared amoung 3 networks.