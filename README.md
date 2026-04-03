# Twitter 2020 Bitcoin Scam Analysis

 This repository hosts a detailed security analysis of the July 15, 2020, Twitter breach[cite: 3, 6].  The incident involved a sophisticated phone spear-phishing campaign that bypassed internal security to hijack high-profile accounts for a cryptocurrency scam[cite: 13, 14, 34].

## Incident Summary
 On July 15, 2020, attackers used social engineering to manipulate Twitter employees[cite: 13, 28].  By gaining access to internal administrative tools—specifically the "agent tool"—they compromised 130 accounts[cite: 16, 72, 74].

*  **Attack Type:** Phone spear-phishing and social engineering[cite: 13].
*  **Target:** Twitter employees in Consumer Service and Tech Support units[cite: 30, 34].
* **Impact:** 130 accounts targeted; 45 accounts sent fraudulent tweets; 36 DM inboxes accessed;  8 account data archives downloaded[cite: 16, 34].
*  **Financial Loss:** Users lost over $118,000 in Bitcoin[cite: 43, 51].
*  **Stock Market:** Twitter’s stock value dropped by 4% on the day of the attack[cite: 46].

## Key Affected Figures
 The attackers targeted globally recognized accounts to maximize the scam's reach[cite: 24, 25, 41]:
*  **Politics:** Barack Obama, Joe Biden[cite: 25].
*  **Business:** Elon Musk, Jeff Bezos, Bill Gates[cite: 25].
*  **Entertainment:** Kim Kardashian, Kanye West[cite: 25].
*  **Corporations:** Apple, Uber, Binance[cite: 26].

## Technical Root Causes
*  **Human Vulnerability:** Attackers scraped LinkedIn for employee contact details and called staff pretending to be IT helpdesk[cite: 29, 30].
*  **VPN Exploitation:** Hackers directed employees to a fake VPN phishing page to capture credentials in real-time[cite: 32].
*  **Lack of Leadership:** Twitter had been without a Chief Information Security Officer (CISO) for nearly six months[cite: 102].
*  **Delayed Response:** Internal fraud alerts were reported by employees mid-morning, but significant action wasn't taken until the scam went public at 3:13 pm ET[cite: 14, 15, 79].

## Proposed Mitigations
 The analysis suggests several "Monday-morning" actions to prevent recurrence[cite: 85, 86]:
*  **Zero Trust Architecture:** Require every employee, including the CEO, to log in through a zero-trust environment[cite: 20].
*  **IP Whitelisting:** Automatically block access attempts from IP addresses or locations not registered to the employee[cite: 101].
*  **Strict Access Control:** Implement multi-level checks and high-level approvals for any changes made via administrative tools[cite: 94, 96].
*  **Phishing Drills:** Conduct regular, unannounced social engineering tests and drills[cite: 78, 92].

## Threat Actors
 The attack was carried out by four individuals[cite: 48]:
*  **Joseph James O'Connor** (Mastermind)[cite: 48].
*  **Graham Ivan Clark** (17-year-old co-conspirator)[cite: 48].
*  **Mason John Sheppard** and **Nima Fazeli**[cite: 48].

 All four were eventually apprehended[cite: 49].
