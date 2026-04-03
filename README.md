# Twitter 2020 Bitcoin Scam Analysis

[cite_start]This repository hosts a detailed security analysis of the July 15, 2020, Twitter breach[cite: 3, 6]. [cite_start]The incident involved a sophisticated phone spear-phishing campaign that bypassed internal security to hijack high-profile accounts for a cryptocurrency scam[cite: 13, 14, 34].

## Incident Summary
[cite_start]On July 15, 2020, attackers used social engineering to manipulate Twitter employees[cite: 13, 28]. [cite_start]By gaining access to internal administrative tools—specifically the "agent tool"—they compromised 130 accounts[cite: 16, 72, 74].

* [cite_start]**Attack Type:** Phone spear-phishing and social engineering[cite: 13].
* [cite_start]**Target:** Twitter employees in Consumer Service and Tech Support units[cite: 30, 34].
* **Impact:** 130 accounts targeted; 45 accounts sent fraudulent tweets; 36 DM inboxes accessed; [cite_start]8 account data archives downloaded[cite: 16, 34].
* [cite_start]**Financial Loss:** Users lost over $118,000 in Bitcoin[cite: 43, 51].
* [cite_start]**Stock Market:** Twitter’s stock value dropped by 4% on the day of the attack[cite: 46].

## Key Affected Figures
[cite_start]The attackers targeted globally recognized accounts to maximize the scam's reach[cite: 24, 25, 41]:
* [cite_start]**Politics:** Barack Obama, Joe Biden[cite: 25].
* [cite_start]**Business:** Elon Musk, Jeff Bezos, Bill Gates[cite: 25].
* [cite_start]**Entertainment:** Kim Kardashian, Kanye West[cite: 25].
* [cite_start]**Corporations:** Apple, Uber, Binance[cite: 26].

## Technical Root Causes
* [cite_start]**Human Vulnerability:** Attackers scraped LinkedIn for employee contact details and called staff pretending to be IT helpdesk[cite: 29, 30].
* [cite_start]**VPN Exploitation:** Hackers directed employees to a fake VPN phishing page to capture credentials in real-time[cite: 32].
* [cite_start]**Lack of Leadership:** Twitter had been without a Chief Information Security Officer (CISO) for nearly six months[cite: 102].
* [cite_start]**Delayed Response:** Internal fraud alerts were reported by employees mid-morning, but significant action wasn't taken until the scam went public at 3:13 pm ET[cite: 14, 15, 79].

## Proposed Mitigations
[cite_start]The analysis suggests several "Monday-morning" actions to prevent recurrence[cite: 85, 86]:
* [cite_start]**Zero Trust Architecture:** Require every employee, including the CEO, to log in through a zero-trust environment[cite: 20].
* [cite_start]**IP Whitelisting:** Automatically block access attempts from IP addresses or locations not registered to the employee[cite: 101].
* [cite_start]**Strict Access Control:** Implement multi-level checks and high-level approvals for any changes made via administrative tools[cite: 94, 96].
* [cite_start]**Phishing Drills:** Conduct regular, unannounced social engineering tests and drills[cite: 78, 92].

## Threat Actors
[cite_start]The attack was carried out by four individuals[cite: 48]:
* [cite_start]**Joseph James O'Connor** (Mastermind)[cite: 48].
* [cite_start]**Graham Ivan Clark** (17-year-old co-conspirator)[cite: 48].
* [cite_start]**Mason John Sheppard** and **Nima Fazeli**[cite: 48].

[cite_start]All four were eventually apprehended[cite: 49].
