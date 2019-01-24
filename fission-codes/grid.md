---
layout: default
parent: FISSION Codes
title: Grid
nav_order: 5
---

|        | `0x0*` General                                 | `0x1*` Permission & Control                              | `0x2*` Find, Inequalities & Range          | `0x3*` Negotiation & Governance                | `0x4*` Availability & Time                                  | `0x5*` Tokens, Funds & Finance         | `0x6*` TBD        | `0x7*` TBD        | `0x8*` TBD        | `0x9*` TBD        | `0xA*` Application-Specific Codes             | `0xB*` TBD        | `0xC*` TBD        | `0xD*` TBD        | `0xE*` Encryption, Identity & Proofs       | `0xF*` Off-Chain                         |
|--------|------------------------------------------------|----------------------------------------------------------|--------------------------------------------|------------------------------------------------|-------------------------------------------------------------|----------------------------------------|-------------------|-------------------|-------------------|-------------------|-----------------------------------------------|-------------------|-------------------|-------------------|--------------------------------------------|------------------------------------------|
| `0x*0` | `0x00` Failure                                 | `0x10` Disallowed or Stop                                | `0x20` Not Found, Unequal, or Out of Range | `0x30` Sender Disagrees or Nay                 | `0x40` Unavailable                                          | `0x50` Transfer Failed                 | `0x60` [reserved] | `0x70` [reserved] | `0x80` [reserved] | `0x90` [reserved] | `0xA0` App-Specific Failure                   | `0xB0` [reserved] | `0xC0` [reserved] | `0xD0` [reserved] | `0xE0` Decrypt Failure                     | `0xF0` Off-Chain Failure                 |
| `0x*1` | `0x01` Success                                 | `0x11` Allowed or Go                                     | `0x21` Found, Equal or In Range            | `0x31` Sender Agrees or Yea                    | `0x41` Available                                            | `0x51` Transfer Successful             | `0x61` [reserved] | `0x71` [reserved] | `0x81` [reserved] | `0x91` [reserved] | `0xA1` App-Specific Success                   | `0xB1` [reserved] | `0xC1` [reserved] | `0xD1` [reserved] | `0xE1` Decrypt Success                     | `0xF1` Off-Chain Success                 |
| `0x*2` | `0x02` Awaiting Others                         | `0x12` Awaiting Other's Permission                       | `0x22` Awaiting Match                      | `0x32` Awaiting Ratification                   | `0x42` Paused                                               | `0x52` Awaiting Payment From Others    | `0x62` [reserved] | `0x72` [reserved] | `0x82` [reserved] | `0x92` [reserved] | `0xA2` App-Specific Awaiting Others           | `0xB2` [reserved] | `0xC2` [reserved] | `0xD2` [reserved] | `0xE2` Awaiting Other Signatures or Keys   | `0xF2` Awaiting Off-Chain Process        |
| `0x*3` | `0x03` Accepted                                | `0x13` Permission Requested                              | `0x23` Match Request Sent                  | `0x33` Offer Sent or Voted                     | `0x43` Queued                                               | `0x53` Hold or Escrow                  | `0x63` [reserved] | `0x73` [reserved] | `0x83` [reserved] | `0x93` [reserved] | `0xA3` App-Specific Acceptance                | `0xB3` [reserved] | `0xC3` [reserved] | `0xD3` [reserved] | `0xE3` Signed                              | `0xF3` Off-Chain Process Started         |
| `0x*4` | `0x04` Lower Limit or Insufficient             | `0x14` Too Open / Insecure                               | `0x24` Below Range or Underflow            | `0x34` Quorum Not Reached                      | `0x44` Not Available Yet                                    | `0x54` Insufficient Funds              | `0x64` [reserved] | `0x74` [reserved] | `0x84` [reserved] | `0x94` [reserved] | `0xA4` App-Specific Below Condition           | `0xB4` [reserved] | `0xC4` [reserved] | `0xD4` [reserved] | `0xE4` Unsigned or Untrusted               | `0xF4` Off-Chain Service Unreachable     |
| `0x*5` | `0x05` Receiver Action Required                | `0x15` Needs Your Permission or Request for Continuation | `0x25` Request for Match                   | `0x35` Receiver's Ratification Requested       | `0x45` Awaiting Your Availability                           | `0x55` Funds Requested                 | `0x65` [reserved] | `0x75` [reserved] | `0x85` [reserved] | `0x95` [reserved] | `0xA5` App-Specific Receiver Action Requested | `0xB5` [reserved] | `0xC5` [reserved] | `0xD5` [reserved] | `0xE5` Signature Required                  | `0xF5` Off-Chain Action Required         |
| `0x*6` | `0x06` Upper Limit                             | `0x16` Revoked or Banned                                 | `0x26` Above Range or Overflow             | `0x36` Offer or Vote Limit Reached             | `0x46` Expired                                              | `0x56` Transfer Volume Exceeded        | `0x66` [reserved] | `0x76` [reserved] | `0x86` [reserved] | `0x96` [reserved] | `0xA6` App-Specific Expiry or Limit           | `0xB6` [reserved] | `0xC6` [reserved] | `0xD6` [reserved] | `0xE6` Known to be Compromised             | `0xF6` Off-Chain Expiry or Limit Reached |
| `0x*7` | `0x07` [reserved]                              | `0x17` [reserved]                                        | `0x27` [reserved]                          | `0x37` [reserved]                              | `0x47` [reserved]                                           | `0x57` [reserved]                      | `0x67` [reserved] | `0x77` [reserved] | `0x87` [reserved] | `0x97` [reserved] | `0xA7` [reserved]                             | `0xB7` [reserved] | `0xC7` [reserved] | `0xD7` [reserved] | `0xE7` [reserved]                          | `0xF7` [reserved]                        |
| `0x*8` | `0x08` Duplicate, Unnessesary, or Inapplicable | `0x18` Not Applicatable to Current State                 | `0x28` Duplicate, Conflict, or Collision   | `0x38` Already Voted                           | `0x48` Already Done                                         | `0x58` Funds Not Required              | `0x68` [reserved] | `0x78` [reserved] | `0x88` [reserved] | `0x98` [reserved] | `0xA8` App-Specific Inapplicable Condition    | `0xB8` [reserved] | `0xC8` [reserved] | `0xD8` [reserved] | `0xE8` Already Signed or Not Encrypted     | `0xF8` Duplicate Off-Chain Request       |
| `0x*9` | `0x09` [reserved]                              | `0x19` [reserved]                                        | `0x29` [reserved]                          | `0x39` [reserved]                              | `0x49` [reserved]                                           | `0x59` [reserved]                      | `0x69` [reserved] | `0x79` [reserved] | `0x89` [reserved] | `0x99` [reserved] | `0xA9` [reserved]                             | `0xB9` [reserved] | `0xC9` [reserved] | `0xD9` [reserved] | `0xE9` [reserved]                          | `0xF9` [reserved]                        |
| `0x*A` | `0x0A` [reserved]                              | `0x1A` [reserved]                                        | `0x2A` [reserved]                          | `0x3A` [reserved]                              | `0x4A` [reserved]                                           | `0x5A` [reserved]                      | `0x6A` [reserved] | `0x7A` [reserved] | `0x8A` [reserved] | `0x9A` [reserved] | `0xAA` [reserved]                             | `0xBA` [reserved] | `0xCA` [reserved] | `0xDA` [reserved] | `0xEA` [reserved]                          | `0xFA` [reserved]                        |
| `0x*B` | `0x0B` [reserved]                              | `0x1B` [reserved]                                        | `0x2B` [reserved]                          | `0x3B` [reserved]                              | `0x4B` [reserved]                                           | `0x5B` [reserved]                      | `0x6B` [reserved] | `0x7B` [reserved] | `0x8B` [reserved] | `0x9B` [reserved] | `0xAB` [reserved]                             | `0xBB` [reserved] | `0xCB` [reserved] | `0xDB` [reserved] | `0xEB` [reserved]                          | `0xFB` [reserved]                        |
| `0x*C` | `0x0C` [reserved]                              | `0x1C` [reserved]                                        | `0x2C` [reserved]                          | `0x3C` [reserved]                              | `0x4C` [reserved]                                           | `0x5C` [reserved]                      | `0x6C` [reserved] | `0x7C` [reserved] | `0x8C` [reserved] | `0x9C` [reserved] | `0xAC` [reserved]                             | `0xBC` [reserved] | `0xCC` [reserved] | `0xDC` [reserved] | `0xEC` [reserved]                          | `0xFC` [reserved]                        |
| `0x*D` | `0x0D` [reserved]                              | `0x1D` [reserved]                                        | `0x2D` [reserved]                          | `0x3D` [reserved]                              | `0x4D` [reserved]                                           | `0x5D` [reserved]                      | `0x6D` [reserved] | `0x7D` [reserved] | `0x8D` [reserved] | `0x9D` [reserved] | `0xAD` [reserved]                             | `0xBD` [reserved] | `0xCD` [reserved] | `0xDD` [reserved] | `0xED` [reserved]                          | `0xFD` [reserved]                        |
| `0x*E` | `0x0E` [reserved]                              | `0x1E` [reserved]                                        | `0x2E` [reserved]                          | `0x3E` [reserved]                              | `0x4E` [reserved]                                           | `0x5E` [reserved]                      | `0x6E` [reserved] | `0x7E` [reserved] | `0x8E` [reserved] | `0x9E` [reserved] | `0xAE` [reserved]                             | `0xBE` [reserved] | `0xCE` [reserved] | `0xDE` [reserved] | `0xEE` [reserved]                          | `0xFE` [reserved]                        |
| `0x*F` | `0x0F` Informational or Metadata               | `0x1F` Permission Details or Control Conditions          | `0x2F` Matching Meta or Info               | `0x3F` Negotiation Rules or Participation Info | `0x4F` Availability Rules or Info (ex. time since or until) | `0x5F` Token or Fiunancial Information | `0x6F` [reserved] | `0x7F` [reserved] | `0x8F` [reserved] | `0x9F` [reserved] | `0xAF` App-Specific Meta or Info              | `0xBF` [reserved] | `0xCF` [reserved] | `0xDF` [reserved] | `0xEF` Cryptography, ID, or Proof Metadata | `0xFF` Off-Chain Info or Meta            |