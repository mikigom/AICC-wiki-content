---
title: FQAs
description: 
published: true
date: 2025-09-12T05:10:18.121Z
tags: 
editor: markdown
dateCreated: 2025-08-29T08:11:39.457Z
---

# Field FQA

## "Can a 'regular/private' car sign up or charge here?"

**Clarify intent**

* Confirm whether "regular car" means a **non-commercial/private vehicle** (not a taxi, truck, or fleet vehicle).

**What to verify**

* Vehicle use type (commercial vs. private).
* If commercial: business registration, operator name, contact.

**First response (example)**

* "You're welcome to charge here. Our **membership** is for **commercially licensed vehicles** (taxis, trucks, fleets). **Private vehicles** can still use the stations as **non-members** at the standard public rate. For private use, you can pay with a **personal credit or debit card**."

**Actions**

* If **commercial**: proceed with membership enrollment steps.
* If **private**: explain pay-as-you-go (non-member) flow; show where to view rates; confirm supported payment methods (including **personal credit/debit cards**);

---

## Post-issuance of 신용카드매출전표 (Credit Card Sales Slip)

**What to verify**

* Charging session details: date/time, station/site, payer name/email.

**First response (example)**

* “I can help with a 신용카드매출전표 (credit card sales slip). I’ll locate the transaction and confirm the session details. You can obtain the slip via your card issuer as card usage history (카드 사용 내역), or I can issue one from our office after verification.”

**Actions**

* Locate the transaction in the ledger and confirm payer ownership.
* Provide issuance paths: Upon verification, **issue from our office** and send as a PDF via email (or share an SMS link).
* Share an expected delivery timeframe (about 1 hour).

---

## Lost card — payment card vs. membership card

**Clarify intent**

* Ask whether the customer lost their **payment card** (credit/debit) or their **membership card** (our access card).

### A) Lost **payment card**

**What to verify**

* Customer identity, contact.

**First response (example)**

* “I’m sorry that happened. For your security, please contact your card issuer to block the card. I’ll also help update your payment method on our side.”

**Actions**

* Verify ID and **add the replacement card** when available.

### B) Lost **membership card**

**Policy**

* Reissue of a new card required.
* **Deposit / reissue fee:** **KRW 30,000 (standard).**
  * If there is **temporary-card stock from former (withdrawn) members**, issue at **KRW 20,000**. **Staff must manually confirm current stock availability.**
* For the previous membership card, the deposit is not refunded. If the previously lost card is later found and **returned**, the **deposit is refunded**.

**What to verify**

* Holder name, contact.

**First response (example)**

* “I can reissue your membership card right now. The deposit is KRW 30,000—or KRW 20,000 if we have temporary-card stock available (staff will check it out). If you find and return the missing old card later, we’ll refund that deposit for the old card.”

**Actions**

* Mark old card **lost/blocked** immediately to prevent misuse.
* **Check temporary-card stock** (from former members):
  * If available, apply **KRW 20,000**; otherwise **KRW 30,000**.
* Collect the deposit and issue a **new card ID**; update CRM/account.

## Charging feels too slow — why is it taking so long?

**Key facts (typical power in SOC 20–80% range)**
* **Lower-voltage vehicles** (e.g., Niro, Bongo): **\~70 kW** typical.
* **Higher-voltage vehicles** (e.g., IONIQ 5, EV6): **\~100 kW** typical.

**Factors that reduce actual speed**
* **Battery state:** cell/pack **voltage**, **temperature**, and **SOC**.
* **Ambient temperature:** in **cold conditions**, electrolyte mobility drops, the BMS limits current, and charging power decreases.
* **Power sharing:** simultaneous charging on shared hardware can **divide available power**.

**When output is \~20 kW (very slow)**
* This is often **normal at high SOC (≥80%)** due to tapering.
  1. **Battery protection:** voltage rises sharply above \~80%; high current risks **over-voltage** and degrades battery life, so the BMS reduces current.
  2. **Charging method (CC/CV profile):** fast **constant-current** charging typically applies up to \~80%; above that, the charger holds **constant voltage** and **reduces current**, slowing power.
  3. **Safety & thermal management:** higher SOC increases internal heat generation; lowering current controls temperature and protects the pack.

## Driving range is too short — what causes this?

**Factors**
* **Driving behavior and route:** rapid acceleration/braking, **sustained high speeds**, and frequent **climbs** increase energy use and reduce range.

**Efficiency tips**
* Use **smooth acceleration/braking** and maintain **steady speeds**.
* Use **regenerative braking** to recover energy; this can increase the **estimated remaining range**.
* Check **tire pressure**, enable **ECO modes**, and moderate **HVAC** usage.


## “I canceled the payment — why isn’t my refund immediate?”

**Explanation**

* After a sales reversal, the **card-issuer settlement process** typically takes **2–3 days** before the refund appears on the statement or balance.
