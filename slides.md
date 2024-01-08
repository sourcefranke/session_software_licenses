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

<!--
I am not a legal expert

Please give feedback on how to improve
-->


---

# The Small Print
Before we start: a short legal hint

<div style="display: flex; justify-content: space-between; gap: 10px; height: 75%">
   <iframe style="width: 80%; border-style: solid; border-width: medium;" src="be_social_license.txt"></iframe>
 
   <div style="width: 18%; align-self: center;">
      <h3>Be aware!</h3>
      By attending this session you consent to buying me a cup of coffee ;P
   </div>
</div>

Source: https://sourcefranke.github.io/be_social_license


---

# Start with a little quiz
Do you know all the answers?

<div style="display: flex; justify-content: center; align-items: center; height: 75%">
    <ol>
        <li>How long have you been working at your company?</li>
        <li>When did you the last time read your employment contract?</li>
        <li>Without looking it up: what details can you remember from your employment contract? ... Don't tell us!</li>
    </ol>
</div>

---

# Why care about licenses?
Once upon a time in the Executive Suite

<div style="display: flex; justify-content: space-between; gap: 10px; height: 75%">
    <img src="/broadcom_vmware.png" style="width: 75%; border-style: solid; border-width: medium;" />
    <div style="width: 28%; align-self: center">
        <h3>VMware</h3>
        Developer of Spring Boot
        <br><br>
        Nothing spectacular at first sight, or?
    </div>
</div>

Source: https://www.broadcom.com/blog/broadcom-announces-successful-acquisition-of-vmware


---

# Why care about licenses? (2)
So what?

<br>

<div style="display: flex; justify-content: space-between; gap: 10px;">
    <img src="/broadcom_vmware_2.png" style="width: 60%; height: 60%; border-style: solid; border-width: medium;" />
    <div style="width: 38%; align-self: center">
        <h3>Turning the whole business inside out!</h3>
        Does that potentally lead to any unpleasant consequences for Spring Boot, too?
    </div>
</div>

<br>
<br>
<br>

Source: https://rcpmag.com/articles/2023/12/13/broadcom-kills-vmware-perpetual-licenses.aspx


---

# What is a Software License?
Some short definition

<br>
<br>

<h3 style="border-style: solid; border-width: medium; padding: 5px;">
A software license is a document that provides legally binding guidelines for the use and distribution of software.

Software licenses typically provide end users with the right to one or more copies of the software without violating
copyrights. The license also defines the responsibilities of the parties entering into the license agreement and may
impose restrictions on how the software can be used.
</h3>

<br>
<br>
<br>
<br>

Source: https://www.techtarget.com/searchcio/definition/software-license

---

# Let's have a closer look
Behind the scenes

<div style="display: flex; justify-content: space-between; background-color: white; padding: 10px">
    <img src="/Angular.svg" width="20%"/>
    <img src="/Java.svg" width="20%"/>
    <img src="/Typescript.svg" width="20%" />
    <img src="/Spring_Boot.svg" width="20%"/>
</div>

Do you actually know about any license terms for tools you regularly use at work?


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

<br>
<br>

Source: https://angular.io/license


---

# Java
It depends! \:-D

<br>
<div style="display: flex; flex-flow: row; justify-content: space-around;">
    <div style="width: 45%">
        <img src="/Oracle.svg" style="width: 100%; height: 50px" />
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
        <img src="/openjdk.png" style="width: 100%; height: 50px" />
        <br>
        <ul>
            <li>Open Source (starting with OpenJDK 7)</li>
        </ul>
         => let's have a closer look
    </div>
</div>
<br>
<p style="text-align: center">
    So, there is not THAT ONE Java
</p>

<!--
Java first released in 1995

OpenJDK 7 released on November 13, 2006

Acquisition of Sun Microsystems by ORACLE in 2009-10
-->


---

# Java - OpenJDK
GNU General Public License, Version 2 (GPLv2)

<div style="display: flex; justify-content: space-between; gap: 10px; height: 75%">
    <iframe style="width: 70%; border-style: solid; border-width: medium;" src="gpl-2.0.txt"></iframe>
    <div style="width: 28%; align-self: center">
        <h3>Point 2 b)</h3>
        If you copy parts of the source code, you have to take the license with you for your whole product!
        <br><br>
        So you never get out ouf there again ...
    </div>
</div>

Source: https://github.com/openjdk/jdk


---

# Speaking of GPL
It definitely has some real impact!

<br>

<div style="display: flex; justify-content: space-between">
    <img src="/sfc_vizio_1.png" height="49%" width="49%" />
    <img src="/sfc_vizio_2.png" height="49%" width="49%" />
</div>

<br>
<br>
<br>

Sources:
- https://www.zdnet.com/article/open-source-vizio-lawsuit-takes-an-ugly-turn/
- https://www.zdnet.com/article/software-freedom-conservancy-wins-big-step-forward-for-open-source-rights/


---

# TypeScript & Spring Boot
Apache License, Version 2.0

<div style="display: flex; justify-content: space-between; gap: 10px; height: 60%">
    <iframe style="width: 70%; border-style: solid; border-width: medium;" src="apache.txt"></iframe>
    <div style="width: 28%; align-self: center">
        <h3>4. Redistribution</h3>
        Changed parts have to be declared, but are allowed to be licensed differently.
    </div>
</div>

Sources:
- https://github.com/microsoft/TypeScript
- https://github.com/spring-projects/spring-boot


---
layout: end
---

# Read The F***ing Small Print (RTFSP)
I am really looking forward to drinking a lot of coffee!!
