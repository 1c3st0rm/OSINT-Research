## **Technical Case Study: Institutional Data Leakage \& Persona Verification**

##### **Analyst:** Thomas Judge



###### **Project code**: PII-SA-2026 (Personally Identifiable Information-South America-2026)

###### **Objective:** To analyze one specific vulnerability. How government mandated portals can be used to OSINT profile high-profile individuals.



I. The WHY?

&#x09;This project was done with the intention of figuring out how in emerging markets (in this case Ecuador) weaponize their government portals intended for transparency. Because most of South America works with a very centralized government it is vulnerable to high levels of corruption. That is why the government portals are that transparent. This with the intent to target a high-interest individual. This was done by cross-referencing Public tax, transit, and academic databases without the use of intrusive measures like malware or by fishing the intended target. Allowing me to fully map the target's physical and financial reality through a fully legal process.



II. The HOW?

&#x09;This investigation was done with a pivot-based Reconnaissance model:

1. Find a unique public identifier ("Cedula" ID number) utilizing legal portals.
2. Look at the national DMV (**Agencia Nacional de Transito** or ANT) to cross-reference with the ID, this was to spot any patterns in his vehicle history. Note in this stage I learned that the subject does not own a car while having violations on his record for not driving with a license (-B license which allows for the movement of cars and trucks). It was also found that the car that the subject uses is under his father's name. This can mean that the subject utilized his father's asset to "prove" for his lifestyle (high-level advisor).
3. Used the national IRS **(Servicio de Rentas Internas** or SRI) database to verify corporate status against professional claims. This "entrepreneurship teacher" in fact does not own any businesses. Which can mean A: The subject lied in his resume to get a job or B: All his ventures failed. In a security assessment this is a clear vulnerability that could be used as leverage over the target.





III.  Finding: Possible assessed vulnerability:

&#x09;There is a discrepancy between the subject's Public Persona and their institutional Footprint.

1. The target has claimed to be a high-level Political advisor; however, he also lacks a verified tax ID (RUC) and recent registration for a postgraduate (Oct. 2025) indicate a junior or intern level career stage. This can be either due to a low level qualification requirement to be an advisor in Ecuador. A false statement from the subject. Or even due to the lack of a verified tax ID possible tax evasion.



VI. Defensive recommendations:

The subject should request all possible personal data be removed from the databases. He should also register the vehicles or properties under corporate entities to disrupt the direct ID-asset link.



###### Additional Information:



**Operations Constraints and ethical boundaries:**

&#x09;Although I could have used a logger to get his home IP and used Shodan to perform a deeper level analysis especially when analyzing hardware in his environment that could have been exploited; I decided to forgo that option due to the target's proximity to the country's political infrastructure could have lead to unwanted 'collateral monitoring' by state security services. This ensured I got no unwanted attention from the state while maintaining a very good assessment on the target. The risk to reward was too uneven to execute that plan.

