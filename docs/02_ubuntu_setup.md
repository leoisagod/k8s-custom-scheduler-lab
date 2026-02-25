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

---

## Step 3: Configuration

1. Choose `Custom`  
2. Click `next`  
![create_vm](../images/圖2_3.png)  

3. Keep clicking `next` until you see this page:
4. Select `I will install the operating system later.` Then click `next`
![create_vm](../images/圖2_4.png)

6. Select `Linux`  
7. Choose `Ubuntu-64-bit`. Then click `next`  
![create_vm](../images/圖2_5.png)

9. Name the virtual machine. Since we are setting up for Kubernetes cluster with one master node and one worker node. Name it with something related.
10. Click `next`  
![create_vm](../images/圖2_6.png)  

12. Refer to the following configuration:  
![create_vm](../images/圖2_7.png)

14. Config and click `next` until this page. Click `Customize Hardware...`  
15. Find `New CD/DVD (SATA)`  
16. Select `Use ISO image file:`  
17. Click `Browse...`
18. Find the file that we've download in **step 2**
![create_vm](../images/圖2_8.png)  

19. `Close` the widget  
20. `Finish` the configuration  
![create_vm](../images/圖2_9.png)

---

## Step 4: Intsall ubuntu

1. Power on the virtual machine  
![create_vm](../images/圖2_10.png)

2. When you see this page, you may config the settings whatever you want. Just notice the follows:
3. It is recommended to install third-party software for graphics  
![create_vm](../images/圖2_11.png)
4. Name the VM master or related name. We will use this VM as master node in the rest of the tutorial  
![create_vm](../images/圖2_12.png)  
