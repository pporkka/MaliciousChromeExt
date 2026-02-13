# Malicious or suspicious Chrome Extensions
Malicious or suspicious Chrome Extensions for defenders.

There exists many lists for malicious chrome extensions and this is another one on top of those. The main point for collecting these was that the information from original articles / research was inside MD or HTML that could not be used for automatic detection with for example DefenderXDR or Sentinel. Feel free to clone the repo. 

This readme contains information on the date collected and the source of the files. 

## Fake AI list
Collected: 2025-02-13  
Original source: https://layerxsecurity.com/blog/aiframe-fake-ai-assistant-extensions-targeting-260000-chrome-users-via-injected-iframes/  
Description: Contains extensions that pretend to be AI related extensions. From the source: "a coordinated campaign of Chrome extensions posing as AI assistants for summarization, chat, writing, and Gmail assistance. While these tools appear legitimate on the surface, they hide a dangerous architecture: instead of implementing core functionality locally, they embed remote, server-controlled interfaces inside extension-controlled surfaces and act as privileged proxies, granting remote infrastructure access to sensitive browser capabilities."

## Chrome extensions spying
Collected: 2025-02-13  
Original source: https://github.com/qcontinuum1/spying-extensions/tree/main  
Description: Not necessarily MALICIOUS, but suspicious extensions that leak information on varying levels. "We should note that probably not all of the browser history leaking extensions have malicious intent. ... Some of the extensions might be benign and may need collect browser history for functionallity such as 'Avast Online Security & Privacy' for example."


## ALL collections in the same file
Updated: 2025-02-13  
Description: All the CSV files concatenated for easy search. May end up consuming defender/sentinel/whatever capacity, so use carefully.  
