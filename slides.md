---
theme: seriph
background: https://wallpaperaccess.com/full/702861.jpg
class: text-center
highlighter: shiki
lineNumbers: false
drawings:
  persist: false
transition: slide-left
title: Open Source licenses
mdc: true
---

# (Open Source) Licenses
# So boring ... isn't it?

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>


---

# The Small Print
Before we start: a short legal hint

<div style="display: flex; justify-content: space-between; gap: 10px; height: 75%">
   <iframe style="width: 80%; border-style: solid; border-width: medium;" src="be_social_license.txt"></iframe>
 
   <div style="width: 18%; align-self: center;">
      <h3>Be aware!</h3>
      By attending this session you consent to buying me a coffee ;P
   </div>
</div>

Source: https://sourcefranke.github.io/be_social_license


---

# Why care about licenses?
Once upon a time in the Executive Suite

<div style="display: flex; justify-content: space-between; gap: 10px; height: 75%">
    <img src="broadcom_vmware.png" width="75%" />
    <div style="width: 28%; align-self: center">
        <h3>VMware</h3>
        Developer of Spring Boot
        <p>Consequences expected for future development of Spring Boot?</p>
    </div>
</div>

Source: https://www.broadcom.com/blog/broadcom-announces-successful-acquisition-of-vmware

<!--
When did I last REALLY check the terms of:
- Open Source frameworks I use
- All my insurances
- The employment contract I  signed years ago
- etc.
-->


---

# What is a Software License?
Some short definition

<br>
<br>

<h3>
A software license is a document that provides legally binding guidelines for the use and distribution of software.

Software licenses typically provide end users with the right to one or more copies of the software without violating
copyrights. The license also defines the responsibilities of the parties entering into the license agreement and may
impose restrictions on how the software can be used.
</h3>

<br>
<br>
<br>

Source: https://www.techtarget.com/searchcio/definition/software-license

---

# Let's have a closer look
Tools and frameworks we use all the time

<div style="display: flex; justify-content: space-between; background-color: white; padding: 10px">
    <img src="Angular.svg" width="20%"/>
    <img src="Java.svg" width="20%"/>
    <img src="Typescript.svg" width="20%" />
    <img src="Spring_Boot.svg" width="20%"/>
</div>

Do you actually know about any license terms for your tools?

<!--
Usually, we use all these without wasting any thought about licensing.
-->


---

# Angular
MIT license

<div style="display: flex; justify-content: space-between; gap: 10px; height: 65%">
    <iframe style="width: 70%; border-style: solid; border-width: medium;" src="MIT.txt"></iframe>
    <div style="width: 28%; align-self: center">
        <h3>Pretty short, right?</h3>
        So much freedom!
    </div>
</div>

Source: https://angular.io/license

<!--
Massachusetts Institute of Technology (MIT)
-->


---

# Java
It depends! \:-D

<br>
<div style="display: flex; flex-flow: row; justify-content: space-around;">
    <div style="width: 45%">
        <img src="Oracle.svg" style="width: 100%; height: 50px" />
        <br>
        <ul>
            <li>Proprietary</li>
            <li>Oracle No-Fee Terms and Conditions License (NFTC, changed with JDK 17)</li>
        </ul>
        <br/>
        Source:
         <a href="https://www.oracle.com/downloads/licenses/no-fee-license.html">
            https://www.oracle.com/downloads/licenses/no-fee-license.html
         </a>
    </div>
    <div style="width: 45%">
        <img src="openjdk.png" style="width: 100%; height: 50px" />
        <br>
        <ul>
            <li>Open Source (starting with OpenJDK 7)</li>
        </ul>
         => let's have a closer look
    </div>
</div>

<!--
This is another note
-->


---

# Java - OpenJDK
GNU General Public License, Version 2 (GPLv2)

<div style="display: flex; justify-content: space-between; gap: 10px; height: 75%">
    <iframe style="width: 70%; border-style: solid; border-width: medium;" src="gpl-2.0.txt"></iframe>
    <div style="width: 28%; align-self: center">
        <h3>Point 2 b)</h3>
        If you copy code, you have to take the license with you
    </div>
</div>

Source: https://github.com/openjdk/jdk


---

# Speaking of GPL
It definitely has some real impact!

<br>

<div style="display: flex; justify-content: space-between">
    <img src="sfc_vizio_1.png" height="49%" width="49%" />
    <img src="sfc_vizio_2.png" height="49%" width="49%" />
</div>

<br>
<br>

Sources:
- https://www.zdnet.com/article/open-source-vizio-lawsuit-takes-an-ugly-turn/
- https://www.zdnet.com/article/software-freedom-conservancy-wins-big-step-forward-for-open-source-rights/


---

# TypeScript & Spring Boot
Apache License, Version 2.0

<div style="display: flex; justify-content: space-between; gap: 10px; height: 75%">
    <iframe style="width: 70%; border-style: solid; border-width: medium;" src="apache.txt"></iframe>
    <div style="width: 28%; align-self: center">
        <h3>4. Redistribution</h3>
        Changed have parts to be declared, but allowed to be licensed differently.
    </div>
</div>

Source: https://github.com/microsoft/TypeScript


---
layout: end
---

# Read The F***ing Small Print (RTFSP)
I am looking forward to receive a lot of coffee!!
