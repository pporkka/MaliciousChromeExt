# Malicious or suspicious Chrome Extensions

Malicious or suspicious Chrome Extensions for defenders.

<<<<<<< HEAD
There exists many lists for malicious chrome extensions and this is another one on top of those. The main point for collecting these was that the information from original articles / research was inside MD or HTML that could not be used for automatic detection with for example DefenderXDR or Sentinel. Feel free to clone the repo.
=======
DISCLAIMER: I do not claim to have a comprehensive list. I do not claim to have an update-to-date list, it is updated on ad-hoc basis (this may change to become more methodological, but no guarantees). The list is provided as-is and is currently collected from public news articles. The list *may* provide a visibility to most recent larger scale campaigns abusing chrome extensions.

There exists many lists for malicious chrome extensions and this is another one on top of those. The main point for collecting these was that the information from original articles / research was inside MD or HTML that could not be used for automatic detection with for example DefenderXDR or Sentinel. Feel free to clone the repo. 
>>>>>>> a3cb50c6363cd46c87d568ea9732d31d7d719d61

Detection in DefenderXDR query in here: https://github.com/pporkka/DefenderXDRQueries/blob/main/KQL\_SuspiciousChromeExtensions.kql

This readme contains information on the date collected and the source of the files.

Content aims to have the: Identifier of chrome extension, a name for it, downloaded amount and the type of risk.

Risks at the moment: Leak, FakeAI, BrowserHijack, CryptoStealer, RAT

## Updates

From March 2026 onwards, the updates are available separately in "Updates" folder.
Everything is always added to the "master" list in the "\_all.csv", but it may get a bit too heavy to handle some day.

Latest Updates: 2026-03-10 with 323 extensions.

## Fake AI list

Collected: 2026-02-13

Updated to contain march 2026 update 2 - 2x FakeAI
Original source: https://layerxsecurity.com/blog/aiframe-fake-ai-assistant-extensions-targeting-260000-chrome-users-via-injected-iframes/  
Description: Contains extensions that pretend to be AI related extensions. From the source: "a coordinated campaign of Chrome extensions posing as AI assistants for summarization, chat, writing, and Gmail assistance. While these tools appear legitimate on the surface, they hide a dangerous architecture: instead of implementing core functionality locally, they embed remote, server-controlled interfaces inside extension-controlled surfaces and act as privileged proxies, granting remote infrastructure access to sensitive browser capabilities."

## Chrome extensions spying

Collected: 2026-02-13  
Original source: https://github.com/qcontinuum1/spying-extensions/tree/main  
Description: Not necessarily MALICIOUS, but suspicious extensions that leak information on varying levels. "We should note that probably not all of the browser history leaking extensions have malicious intent. ... Some of the extensions might be benign and may need collect browser history for functionallity such as 'Avast Online Security \& Privacy' for example."

## Chrome extensions march 2026 update 1

Collected: 2026-03-10
Original source: https://thehackernews.com/2026/03/chrome-extension-turns-malicious-after.html
Description: Update contains latest malicious extensions from a public source.

## Chrome extensions march 2026 update 2

Collected: 2026-03-18
Original source: https://www.microsoft.com/en-us/security/blog/2026/03/05/malicious-ai-assistant-extensions-harvest-llm-chat-histories/
Description: Update contains latest malicious extensions from a single public source.





## ALL collections in the same file

Updated: 2025-02-13  
Description: All the CSV files concatenated for easy search. May end up consuming defender/sentinel/whatever capacity, so use carefully.

