---
title: "`eosc system` Commands"
linktitle: "`eosc system`"
description:
date: 2018-09-05
publishdate: 2018-09-05
lastmod: 2018-09-05
keywords: []
menu:
  docs:
    parent: "eosc-commands"
    weight: 30
weight: 30
sections_weight: 30
draft: false
aliases: []
toc: true


---

```
Usage:
  eosc system [command]
  
Available Commands:
  bidname      Bid on a premium account name
  buyrambytes  Buy RAM at market price, for a given number of bytes.
  claimrewards Claim block production rewards. Once per day, don't forget it!
  delegatebw   Delegate some CPU and Network bandwidth, to yourself or others.
  deleteauth   Removes a permission currently set on an account. See --help for more details.
  linkauth     Assign a permission to the given code::action pair
  newaccount   Create a new account
  regproducer  Register an account as a block producer candidate
  regproxy     Register an account as a voting proxy
  sellram      Sell the [num bytes] amount of bytes of RAM on the RAM market.
  setabi       Set ABI only on an account
  setcode      Set code only on an account
  setcontract  Set both code and ABI on an account
  undelegatebw Undelegate some CPU and Network bandwidth.
  unlinkauth   Unassign a permission currently active for the given code::action pair
  unregprod    Unregister producer account temporarily.
  unregproxy   Unregister account as voting proxy.
  updateauth   Set or update a permission on an account. See --help for more details.

Flags:
  -h, --help   help for system
```