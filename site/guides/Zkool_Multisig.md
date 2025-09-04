# Zkool Multisig Guide

This guide provides a step-by-step walkthrough on how to perform multisig transactions using Zkool. It includes creating accounts, sending/receiving funds, and setting up distributed key generation (DKG) for multisig. Screenshots are included for each major step.

## 1. Creating an Account



1. Open the **Zkool app** and go to **New Account**.  
   ![Screenshot: New Account](screenshot-placeholder.png)



2. Enter an **Account Name** (e.g., *Anabelle*).  
   ![Screenshot: Enter Account Name](screenshot-placeholder.png)




3. Optionally toggle **Use Internal Change** or **Restore Account** if needed.



4. After creation, the account will appear in your **Account List**.  
   ![Screenshot: Account List](screenshot-placeholder.png)


## 2. Receiving Funds



Each account generates multiple address types:

- **Unified Address**  
- **Orchard-only Address**  
- **Sapling Address**  
- **Transparent Address**


Select the type you want to use and share it to receive funds.  
![Screenshot: Receiving Address](screenshot-placeholder.png)




## 3. Sending Funds

1. Go to the **Recipient** section.  
![Screenshot: Recipient Section](screenshot-placeholder.png)

2. Enter the **recipient’s address**.  

3. Specify the **amount** and optional **memo**.  

4. Review the transaction details and **confirm**.  


Once complete, the balance updates in your account list.  
![Screenshot: Transaction Confirmation](screenshot-placeholder.png)



## 4. Performing Multisig Transactions: Setting Up Distributed Key Generation (Multisig)

Multisig in Zkool uses **Distributed Key Generation (DKG)** to ensure multiple participants control a shared account.



### Step 1: Initiate DKG
- Choose a **Name** for the shared wallet (e.g., *Anabelle*).  
- Set the **Number of Participants**.  
- Choose your **Participant ID**.  
- Define the **Number of Signers Required (Threshold)**.  
- Select the **Funding Account**.  
![Screenshot: DKG Setup](screenshot-placeholder.png)




### Step 2: Add Participant Addresses
- Enter each participant’s **Unified Address** (recommended).


⚠️ **Note:** If you use an Orchard-only or Sapling-only address, the multisig will be limited to that pool only (Orchard or Sapling).  
This means the shared wallet cannot receive funds from other pools.  
For maximum compatibility and flexibility, always use **Unified Addresses**.  

![Screenshot: Add Participants](screenshot-placeholder.png)




### Step 3: Run DKG Rounds
- Wait for all participants to exchange **round 1** and **round 2** packages.  
![Screenshot: DKG Rounds](screenshot-placeholder.png)



### Step 4: Finalize Shared Address
- Once complete, a **shared address** is generated.  
![Screenshot: Shared Address](screenshot-placeholder.png)



## ✅ Conclusion

Using Zkool, you can:

- Create accounts  
- Send and receive funds  
- Set up a **multisig wallet** using Distributed Key Generation  

This ensures **enhanced security** and **collaborative fund management**.  

---
