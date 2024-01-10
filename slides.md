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

<div class="abs-br m-6 flex gap-2 items-baseline opacity-50">
    <span class="text-sm">v2024-01-10</span>
    <a href="https://github.com/sourcefranke/session_software_licenses" target="_blank" alt="GitHub"
        class="text-xl slidev-icon-btn !border-none !hover:text-white">
        <carbon-logo-github />
    </a>
</div>


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

<div class="flex justify-end text-xs align-self-end mt-10">
    <span>Source: <a href="https://sourcefranke.github.io/be_social_license">https://sourcefranke.github.io/be_social_license</a></span>
</div>


---

# Warm-up Quiz
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

<div class="flex justify-end text-xs align-self-end mt-10">
    <span>Source: <a href="https://www.broadcom.com/blog/broadcom-announces-successful-acquisition-of-vmware">
        https://www.broadcom.com/blog/broadcom-announces-successful-acquisition-of-vmware
    </a></span>
</div>


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

<div class="flex justify-end text-xs align-self-end mt-30">
    <span>Source: <a href="https://rcpmag.com/articles/2023/12/13/broadcom-kills-vmware-perpetual-licenses.aspx">
        https://rcpmag.com/articles/2023/12/13/broadcom-kills-vmware-perpetual-licenses.aspx
    </a></span>
</div>


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

<div class="flex justify-end text-xs align-self-end mt-32">
    <span>Source: <a href="https://www.techtarget.com/searchcio/definition/software-license">
        https://www.techtarget.com/searchcio/definition/software-license
    </a></span>
</div>


---

# Let's have a closer look
Behind the scenes

<div style="display: flex; justify-content: space-between; background-color: white; padding: 10px">
    <img src="/angular.png" width="20%"/>
    <img src="/java.png" width="20%"/>
    <img src="/typescript.png" width="20%" />
    <img src="/spring-boot.png" width="20%"/>
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

<div class="flex justify-end text-xs align-self-end mt-20">
    <span>Source: <a href="https://angular.io/license">
        https://angular.io/license
    </a></span>
</div>


---

# Java
It depends! \:-D

<br>
<div style="display: flex; flex-flow: row; justify-content: space-around;">
    <div style="width: 45%">
        <img src="/oracle.png" style="width: 100%; height: 50px" />
        <br>
        <ul>
            <li>Proprietary</li>
            <li>Acquired Sun Microsystems in 2010</li>
            <li>Oracle No-Fee Terms and Conditions License (NFTC, changed with JDK 17)</li>
        </ul>
    </div>
    <div style="width: 45%">
        <img src="/openjdk.png" style="width: 100%; height: 50px" />
        <br>
        <ul>
            <li>Open Source (starting with OpenJDK 7)</li>
            <li>Starting with OpenJDK 7 in 2006</li>
        </ul>
         => let's have a closer look
    </div>
</div>
<br>
<p style="text-align: center">
    So, there is not THAT ONE Java
</p>
<div class="flex justify-end text-xs align-self-end mt-25">
    <span>Source: <a href="https://www.oracle.com/downloads/licenses/no-fee-license.html">
        https://www.oracle.com/downloads/licenses/no-fee-license.html
    </a></span>
</div>


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

<div class="flex justify-end text-xs align-self-end mt-10">
    <span>Source: <a href="https://github.com/openjdk/jdk">
        https://github.com/openjdk/jdk
    </a></span>
</div>


---

# Speaking of GPL
It definitely has some real impact!

<br>

<div style="display: flex; justify-content: space-between">
    <img src="/sfc_vizio_1.png" height="49%" width="49%" />
    <img src="/sfc_vizio_2.png" height="49%" width="49%" />
</div>

<div class="flex justify-end text-xs align-self-end mt-40">
    <div>
        Sources:
        <ul>
            <li><a href="https://www.zdnet.com/article/open-source-vizio-lawsuit-takes-an-ugly-turn/">
                https://www.zdnet.com/article/open-source-vizio-lawsuit-takes-an-ugly-turn/
            </a></li>
            <li><a href="https://www.zdnet.com/article/software-freedom-conservancy-wins-big-step-forward-for-open-source-rights/">
                https://www.zdnet.com/article/software-freedom-conservancy-wins-big-step-forward-for-open-source-rights/
            </a></li>
        </ul>
    </div>
</div>


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

<div class="flex justify-end text-xs align-self-end mt-15">
    <div>
        Sources:
        <ul>
            <li><a href="https://github.com/microsoft/TypeScript">
                https://github.com/microsoft/TypeScript
            </a></li>
            <li><a href="https://github.com/spring-projects/spring-boot">
                https://github.com/spring-projects/spring-boot
            </a></li>
        </ul>
    </div>
</div>


---
layout: end
---

# Read The F***ing Small Print (RTFSP)
I am really looking forward to drinking a lot of coffee ;-P
