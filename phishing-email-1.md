# Phishing Email Investigation #1

## Original Email

From: [microsoft-security-team@micr0soft-support.com](mailto:microsoft-security-team@micr0soft-support.com)

Subject: Urgent Security Alert

Dear User,

Your Microsoft account has been compromised.

Please verify your identity immediately:

https://micr0soft-support.com/verify

Failure to verify within 6 hours will result in permanent account suspension.

Microsoft Security Team

---

## Alert Summary

The email claims that the recipient's Microsoft account has been compromised and requests immediate verification through a provided link.

## Sender Analysis

The sender domain contains a lookalike Microsoft domain. The letter "o" in Microsoft has been replaced with the number "0" (zero), indicating a possible phishing attempt.

## URL Analysis

The URL points to micr0soft-support.com instead of an official Microsoft domain. This is a suspicious lookalike domain commonly used in phishing attacks.

## Indicators of Compromise (IOCs)

* Sender: [microsoft-security-team@micr0soft-support.com](mailto:microsoft-security-team@micr0soft-support.com)
* URL: https://micr0soft-support.com/verify
* Lookalike domain using "0" instead of "o"

## Social Engineering Tactics

* Creates urgency by claiming the account is compromised.
* Pressures the user to act immediately.
* Threatens account suspension if action is not taken.

## Verdict

Phishing Email (True Positive)

## Risk Level

High

## Recommendation

* Do not click the link.
* Verify account notifications through official Microsoft channels.
* Report the email to the security team.
* Block the sender and domain if confirmed malicious.
