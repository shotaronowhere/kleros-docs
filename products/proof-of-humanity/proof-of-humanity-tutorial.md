---
description: >-
  How to register your profile, vouch for others and monitor your profile
  validation progress.
---

# Proof of Humanity Tutorial (Register & Vouch)

❓ Check out the [FAQ ](https://kleros.gitbook.io/docs/products/proof-of-humanity/poh-faq)or [Part 2 of the PoH Tutorial](https://kleros.gitbook.io/docs/products/proof-of-humanity/proof-humanity-tutorial-remove-and-challenge) if you don't find your answer here.

![](../../.gitbook/assets/poh-updated-flow-chart\_.png)

{% tabs %}
{% tab title="1/ Register your profile" %}
#### 1/ Register your profile (5-10mn)

**1.a/ Go to the** [**Proof of Humanity**](https://app.proofofhumanity.id/) **app**

* You will see the homepage of the app with the recent profiles registered in PoH.

**1.b/ Connect your Ethereum / Web3 wallet**

* Click on the "Connect" button on the top right

![](<../../.gitbook/assets/image (58).png>)

* Select the wallet you want to use (We recommend [Metamask](https://metamask.io/faqs.html), [WalletConnect](https://walletconnect.org/) or [Authereum](https://authereum.com/welcome/))

![](<../../.gitbook/assets/image (64) (2).png>)

* Once you have connected the wallet to the app (the wallet will ask you to confirm the connection), you will need to ensure you have some Ether (ETH) loaded in the wallet to interact with the Ethereum blockchain (pays transaction fees) and to be able to lock the ETH deposit needed to enter the registry (it will be reimbursed to you).

{% hint style="danger" %}
**PRIVACY WARNING:** The Ethereum address you are using to submit your profile will be publicly linked to your identity. If you don't want your wallet holdings and transaction history to be linked to your identity, we recommend using a new Ethereum address that you seeded with funds from an exchange or from [Tornado.cash](https://tornado.cash/)
{% endhint %}

**1.c/ Click on "Submit profile" in the top banner**

* If you don't see the "Submit Profile" link in the top menu bar, it means you are either not connected (check section 1.b again) or that you have already created a profile (you should see "My profile" instead).

![](<../../.gitbook/assets/image (36).png>)

* You will be asked to fill out the information required to submit a profile

![](<../../.gitbook/assets/image (20) (1).png>)

{% hint style="warning" %}
**COMPLIANCE WARNING:** The information you submit about your profile will be checked and verified by the community to ensure you are not a not/fake and that you complied with all the guidelines. Please read thoroughly the instructions given on the submit page and check out the full [Proof of Humanity Guidelines](https://ipfs.kleros.io/ipfs/QmXDiiBAizCPoLqHvcfTzuMT7uvFEe1j3s4TgoWWd4k5np/proof-of-humanity-registry-policy-v1.3.pdf) to ensure the info you provide is correct.

You can only update information by withdrawing your profile and resubmitting it. There is no way to edit your profile (Evidences are there to argument that the case made against your profile is wrong, not to update your profile with a new video for example).

If you make a mistake in your submission (ex: Displaying a wrong address in the video), it could be interpreted as a malicious attack by the challengers verifying the entry into the registry and you could lose your deposit.\
\
**Advice**: Submissions are final and cannot be edited. Be sure to follow all submission rules to not lose your deposit.
{% endhint %}

* Once you have filled out your Name, First Name, Last Name & Short Bio, you will be asked to upload a front-facing profile picture and a video of yourself holding the Ethereum address you used for submission and saying "I certify that I am a real human and that I am not already registered in this registry"

![](<../../.gitbook/assets/image (35).png>)

![](<../../.gitbook/assets/image (33).png>)

{% hint style="success" %}
**TIP:** Browse through "Registered" profiles (that means they have been accepted into the registry) to have examples of what correct profiles look like.
{% endhint %}

* At the bottom of the submit page, you will have a choice between "Self-Funding" your deposit or "Crowdfunding" it. > "Self-Fund" means you will lock the deposit yourself (we recommend that option). > "Crowdfund" means you want to submit your profile without paying for the deposit or only partially (that means that your profile will be blocked in the starting phase of the validation process until someone pays the deposit for you). Only choose this option if you are sure someone will pay for your deposit in the future.

![](https://lh5.googleusercontent.com/zfhryjrgNlQfbd-SyG8RlXc\_6tLGwTQafnK3ep3gP21CkPsBMjfndHxaITfxEJsH7fl7Y95a4g73gQN3Jd8ahBieUHDUBWSqK6PqmbPRS2lunmuxKhzXw-eTYULGVgrcIGif8E82)

{% hint style="info" %}
**What is the Submitter Deposit?** The deposit is an amount of ETH you lock with the submission of your profile that will act as an incentive for potential challengers to prove you are a fake or bot and that will also pay for arbitration fees if a dispute is raised. If your profile goes through unchallenged, you are registered and get your deposit back. If you are a fake or have given incorrect information, someone can challenge your profile and a dedicated Kleros dispute will be opened to rule on your case.
{% endhint %}

* Once you are sure all of your submission information is good (check the [guidelines](https://ipfs.kleros.io/ipfs/QmXDiiBAizCPoLqHvcfTzuMT7uvFEe1j3s4TgoWWd4k5np/proof-of-humanity-registry-policy-v1.3.pdf)), you can click on the "Submit" button. This should trigger a transaction confirmation popup in your wallet after a few seconds. Send that transaction (ETH Deposit + blockchain fees) and wait for it to be validated.

![](<../../.gitbook/assets/image (45).png>)

* Once the transaction has been mined (it can take a long time depending on the gas price you selected), you should be redirected to your profile page. If you are not redirected, please check that your transaction has really gone through, and if yes, check that your profile is not already submitted by clicking on "Profiles" in the top banner. You don't want to submit your profile 2 times by mistake.

![](<../../.gitbook/assets/image (24) (1).png>)

Don't forget to subscribe to Profile Update Notifications (2nd tab at the top of this page)
{% endtab %}

{% tab title="2/ Subscribe to Notif." %}
#### 2/ Subscribe to Profile Update Notifications (1mn)

In order to be notified of your profile progress in the validation process, you might want to subscribe to email notifications.

* For this, click on the "Account" button on the top right and then on the "Notifications" tab.

![](<../../.gitbook/assets/image (27).png>)

* There, you can check the subscription option and fill out your email address.

![](<../../.gitbook/assets/image (28).png>)

* Once you click on "Save", your wallet will ask you to sign a message to confirm (no fee).
* Once you have confirmed, it is done: you will now receive email updates when your profile changes status or gets challenged.

***

**Notifications through EPNS**

In order to be notified of your profile progress in the validation process, you can also subscribe to email notifications through [Ethereum Push Notification Service (EPNS)](https://app.epns.io/). Check this [thread](https://twitter.com/epnsproject/status/1501611224517480451?s=21) for EPNS notification steps.
{% endtab %}

{% tab title="3/ Profile Validation Process" %}
#### 3/ Watch your profile go through the validation process and finalize registration (**≈** 3-5 days)

Your submitted profile will start in "**Vouching Phase**" status and will go through a "**Pending registration**" phase before reaching the "**Registered**" status which means you are a verified human.

You can check the current status of your profile by clicking on "My profile" in the top banner (if you're connected) or by searching for your name in the search bar and accessing your profile.

![](<../../.gitbook/assets/image (42).png>)

**3.a/ How to go from "Vouching Phase" to "Pending registration" status?**

* You need to find one person who is in "Registered" status and that knows you in real-life (or that can prove that you really are the person your profile describes) and ask that person to vouch for you.

![](<../../.gitbook/assets/image (25) (1) (2) (2) (1) (2) (1).png>)

* This person will need to go to your profile page and click on the "Gasless Vouch" button and sign a message from his wallet.

![](<../../.gitbook/assets/image (67).png>)

{% hint style="info" %}
**What is the difference between "Gasless Vouch" and "Vouch"?**

The "Gasless Vouch" is the new recommended way of vouching for people without having to pay transaction fees. The vouch will be recorded and the vouched profile will be moved to the next phase when other profiles finalize their registration (and it' is the vouched profile turn among all profiles vouched by his voucher).

The "Vouch" button is the old legacy way of vouching for someone with a transaction and its associated fee. We don't recommend using it except if you are the only vouched profile by your voucher and want to speed up the registration process.
{% endhint %}

{% hint style="danger" %}
**WARNING**: Vouching for someone means you know the person, that you are sure that they are not fake or impersonators and that you checked that their submitted information was correct (ex: the address in the video is correct and readable).\
You could get removed from the registry if you vouched for a bot or fake submission.\
You will not get removed if you vouch for a profile with simply incorrect information.
{% endhint %}

* Once a person has vouched for you, you will see it on your profile by checking the number of vouchers and the "Vouched by" list.

![](<../../.gitbook/assets/image (30).png>)

{% hint style="success" %}
Vouching for someone is a benevolent act to help them get into the registry. Currently, it requires the voucher to pay for gas fees for the transaction but, soon, the vouching could be made through a simple gasless signature.
{% endhint %}

* If you have the required number of vouchers, your deposit is at 100% and you are the only current vouched profile by your voucher, then your profile will be moved to "Pending Registration" status quite soon.

{% hint style="info" %}
**Why is my profile staying in "Vouching Phase"?** If you wonder why you still are not in "Pending Registration" status even though you have your deposit and vouches, it probably means the person that vouched for you has vouched for several persons at the same time. His vouches are processed sequentially and you will need to wait for the persons he vouched for before you to be validated (3.5 days for each) before it is your turn for his vouch to be processed.
{% endhint %}

**3.b/ How to go from "Pending Registration" to "Registered" status?**

* Once your Profile is in "Pending Registration" status, it will go through a challenge period of 3.5 days. That means that during 3.5 days people will check your profile to verify if you are a fake or if you provided incorrect information and, if yes, will try to challenge your registration to win part of your deposit.
* You can check how long you have left in this period in the bottom left of your profile.

![](<../../.gitbook/assets/image (32).png>)

* If you are not challenged during this period, you will be given the opportunity to transition to "Registered" status right after this 3.5 days period ends.
* In order to finalize your registration, you will need to click on the **"Finalize registration and start accruing UBI"** button and confirm the transaction with your wallet. _(Note that any other address can also send this transaction for you)_

![](<../../.gitbook/assets/image (68).png>)

* Once the transaction is validated, you will be in "Registered" status, accruing UBI and you will have the capacity to vouch for other people. Your deposit will also be refunded at this time.

![](<../../.gitbook/assets/image (21) (1) (1) (1).png>)

{% hint style="info" %}
**What if I am challenged?**

Then, a dispute will be created in [Kleros Court](https://kleros.gitbook.io/docs/products/court).\
You can provide evidence on your profile page to defend your case and monitor the progress of the dispute. Note that evidence is used to demonstrate that the reason for challenging the profile is or is not valid, it is not a tool to fix your submission mistakes.

You can also appeal when a ruling is given by jurors if you don't agree with it.

If the jury rules in your favor, your profile goes back to "Pending Registration" phase for 3.5 days.\
If the jury rules in favor of the challenger, your profile goes to "Removed" status.
{% endhint %}
{% endtab %}

{% tab title="4/ Vouch for a profile" %}
#### 4/ Vouch for another profile (2mn)

You can only vouch for another profile if you are connected to the app and your profile is in "Registered" status.

{% hint style="danger" %}
**WARNING**: Vouching for someone means you know the person, that you are sure that they are not fake or impersonators and that you checked that their submitted information was correct (ex: the address in the video is correct and readable).\
You could get removed from the registry if you vouched for a bot, fake or duplicate submission.
{% endhint %}

* If you meet these conditions, go to the profile page of the person you want to vouch for (they can share the link or you can search for their exact name in the search bar) and click on the button "Vouch" below their picture.

![](<../../.gitbook/assets/image (37).png>)

{% hint style="success" %}
Vouching for someone is a benevolent act to help them get into the registry. Currently, it requires the voucher to pay for gas fees for the transaction but, soon, the vouching could be made through a simple gasless signature.
{% endhint %}

* Once your vouching transaction is validated, your profile will appear in the "Vouched by" list below the video.

![](<../../.gitbook/assets/image (29).png>)

{% hint style="info" %}
**How many vouches can I give in parallel?**

You can vouch for as many people as you would like. However, your vouch will only count for one person at a time in the order they were given. This means a vouch can only be used for one submission at a time on a “first come, first served” basis.

For example, assume user A is registered. A vouches for user B. User B uses the vouch and moves to "Pending registration" phase. Then A vouches for user C. Since the vouching of A is already in use by B, C remains in the "Vouching Phase" for now, but will move to "Pending registration" phase once B is registered.
{% endhint %}

* You can remove your vouch at any time prior to the "Pending Registration" phase by going to the vouched person's profile and clicking on "Remove Vouch".

![](<../../.gitbook/assets/image (19) (1).png>)
{% endtab %}
{% endtabs %}
