## Leaked and Detected In-The-Wild Intel OEM Key from MSI Leak (`bxt_dbg_priv_key.pem`):

```
2dc5d6d617fa0aa04f039b58391e4647b826889f0ea240cf2297198773b30fb5902c410f45f6d057b7fc8d7d8115a6b76d0f47ddb9b4ee223e403213822863864a5d5d9ad9a65230998c1db4483b86089b2c6bdcab664f6fc8b09c5c25e3005fcb3526585a76ad852dbe83c511b0d3248a4c22d90f6911b98eaea760e8ab1c1963da778d7f845d6bb793f30c3a414d363b59ed9223a36e8d6a8644f06df03a21f5d405c7b14735bc57f230b05e249ff4867b2c2afa84fd8de3e77209e78f7339b372d23c605a52c8633f44ce9e60d8bafda38aae181964002428251b59e3213f096da01988e805cc46100c10f2501260f7daacf5cdfaf1f5cb3f16d0c5b84b9e
```

Based on [Intel documentation](https://www.intel.com/content/www/us/en/developer/articles/technical/software-security-guidance/secure-coding/intel-debug-technology.html), it appears to be more powerful in comparison to Boot Guard keys.

```
Protection Class “OxM” (historically also known as “Orange” or “OEM Unlocked”) is where the debugger must authorize and unlock before the class is established and additional debug capabilities are enabled. Since this is limited to only using the Platform Manufacturer's authentication key, the only assumed set of debuggers is the Platform Manufacturer themselves. It is assumed that the Platform Manufacturer will not share their authentication key with any other set of debuggers. 
```

### Affected HP products:

```
hp-t430-thin-client
hp-t638-thin-client
```

### Affected Lenovo products:

```
aio-330-20igm
a340-24igm
v330
v130
310s-08igm
```

### Affected AOPEN products:

```
iAPLx-DE(TAA30 TEST)
```

### Affected CompuLab products:

```
flt2
```

### Affected Star Labs products:

```
StarLite MkIII
StarLite MkIV
```
