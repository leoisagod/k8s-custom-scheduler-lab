# 02. Ubuntu Virtual Machine setup

This guide demonstrates how to setup ubuntu VM on VMware Workstation 17

## Target

- Create virtual machine that runs ubuntu on VMware Workstation 17

---

## Step 1: Download ubuntu image

Download ubuntu from: 
https://ubuntu.com/download/desktop

1. Search for ubuntu desktop  
2. Click `Download`  
![ubuntu](../images/圖2_1.png)

---

## Step 2: Create virtual machine

1. Open Vmware workstation  
2. Click `File` and then `New Virtual Machine...`  
![create_vm](../images/圖2_2.png)

## Step 3: Configuration

1. Choose `Custom`  
2. Click `next`  
![create_vm](../images/圖2_3.png)  

3. Keep clicking `next` until you see this page:
4. Select `I will install the operating system later.` Then click `next`
![create_vm](../images/圖2_4.png)  
5. Select `Linux`  
6. Choose `Ubuntu-64-bit`. Then click `next`  
![create_vm](../images/圖2_5.png)
7. Name the virtual machine. Since we are setting up for Kubernetes cluster with one master node and one worker node. Name it with something related.
8. Click `next`  
![create_vm](../images/圖2_6.png)
9. Refer to the following configuration:  
![create_vm](../images/圖2_7.png)  
![create_vm](../images/圖2_8.png)
10. Config and click `next` until this page. Click `Customize Hardware...`  
11. Find `New CD/DVD (SATA)`  
12. Select `Use ISO image file:`  
13. Click `Browse...`
14. Find the file that we've download in **step 2**  
![create_vm](../images/圖2_9.png)
![create_vm](../images/圖2_10.png)  
![create_vm](../images/圖2_11.png)
![create_vm](../images/圖2_12.png)  
