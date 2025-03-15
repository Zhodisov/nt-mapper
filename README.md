<br/><br/>
<div align="center"> 
  <img src="https://profile-counter.glitch.me/Zhodisov/count.svg" alt="Visitor's Count" />
</div>
<br/><br/>

<div align="center">
  
[![YOUTUBE](https://img.shields.io/badge/Youtube-fc0000?style=for-the-badge&logo=YOUTUBE&logoColor=white)](https://www.youtube.com/@Jodis974)
[![Discord](https://img.shields.io/badge/Discord-6a85b9?style=for-the-badge&logo=discord&logoColor=white)](https://safemarket.xyz/discord)
[![Safemarket Email](https://img.shields.io/badge/safemarket_email-333333?style=for-the-badge&logo=gmail&logoColor=red)](mailto:support-checkout@safemarket.xyz)
[![safemarket.xyz](https://img.shields.io/badge/safemarket.xyz-0077B5?style=for-the-badge&logo=internet&logoColor=white)](https://safemarket.xyz/)

</div>


# nt-mapper
PE mapper in c++17

# Features
+ Relocate image
+ Fix import address table
  + Handle api-set
+ Export directory parsing (forwarded and normal)
+ Two execution modes: 'Thread creation' and 'Thread hijacking' 

# Thread Hijacker
+ Preserves all registers, volatile or not
  + Exception 1: SSE registers
  + Exception 2: AVX registers
+ Preserves all flags
+ Automatically frees hijack shellcode after execution
+ Arbitrary shadow-space for dllmain
+ Aligns stack in case of recusant code

# To-do
+ Static TLS
+ TLS callbacks
+ Loader entry
+ C++ exceptions

# Thanks
+ DarthTon
+ Daax
+ JustMagic
