# Analysing the Disk Files

```
Register Number : 212222040121
Name : Praveen V
```
## AIM:

The primary aim of this report is to demonstrate the process of creating a disk partition, adding files, and analyzing them using Autopsy, a digital forensic tool.

## Step1: Creating a Disk Partition
## 1.Open File Manager

- Right-click This PC → Click Show More Options.
  ![Screenshot 2025-03-19 220523](https://github.com/user-attachments/assets/8a7b99d9-bd5d-4b41-ad35-6d1301b5ff82)

- Select Manage.
  ![Screenshot 2025-03-19 220537](https://github.com/user-attachments/assets/df827a18-3894-4dbd-bbd3-a1b6eb8ae0b8)


## 2.Access Disk Management

- In the new window, select Disk Management.
![Screenshot (173)](https://github.com/user-attachments/assets/a8e3c7ee-d3e1-4773-87cb-4e0be7a0a40d)



## 3.Shrink the C Drive to Allocate Space

- Locate C: drive → Right-click → Select Shrink Volume.

- Enter the amount of memory to allocate for the new disk.

- Click Shrink.
![Screenshot (174)](https://github.com/user-attachments/assets/4c3d593a-6a78-4f27-a95c-4b465a22d97e)



## 4.Create a New Volume

- Right-click on the newly unallocated space → Select New Simple Volume.
![Screenshot (175)](https://github.com/user-attachments/assets/37d2391b-201e-4e76-87b7-acb2959c6475)



- Follow the wizard and assign a disk name.
![Screenshot (177)](https://github.com/user-attachments/assets/f219055d-6c16-440e-ab84-72bf8b845c3e)



- Click Finish to complete the process.
 ![Screenshot (178)](https://github.com/user-attachments/assets/3cfe8a6d-87a5-4c24-bc46-ded6664607da)

  
- The new Disk Partition is created as.
 ![Screenshot (179)](https://github.com/user-attachments/assets/d011f3cf-c742-44c0-bcf0-070bbe89939b)


  
## Step2: Adding Files

## 1.Copy Files to the Partition:

- Open File Explorer → Navigate to the newly created drive (C: or D:).

- Transfer images or files into it.
![Screenshot (151)](https://github.com/user-attachments/assets/555a158a-4b80-4a5f-8535-22cef470da4c)


## Step3: Analysing Files using Autopsy
## 1. Install and Open Autopsy
- Download and install Autopsy from its official website.

- Open Autopsy and create a new case.

## 2. Create a Case
- Enter a case name and select a location to store the case data.
![Screenshot (154)](https://github.com/user-attachments/assets/bdaee702-8947-486a-99c1-03975d23486b)


- Provide a case number and investigator details if required.

## 3. Add a Data Source
- Click "Add Data Source" and choose the type:
![autopsy screenshot](https://github.com/user-attachments/assets/538d0c72-13a7-43a0-84b7-445cca91357d)


- Select the data source and let Autopsy process it.

## 4. File Analysis
- Application 
![Screenshot (160)](https://github.com/user-attachments/assets/718bb3a7-30c0-4d71-81be-0001852d8058)


- File Metadata
![Screenshot (181)](https://github.com/user-attachments/assets/ae20162c-f378-4f67-9a34-8a4bbaa44edb)
![Screenshot (182)](https://github.com/user-attachments/assets/4f394919-773a-4ac3-af69-230aec58c5aa)
![Screenshot (183)](https://github.com/user-attachments/assets/9a0618b9-8aa4-4e5c-800f-e5ea4c7fca63)



- OS Account
![Screenshot (184)](https://github.com/user-attachments/assets/292f5b4c-0ee8-47c3-b300-d61e729787f3)

## Result
The process successfully demonstrated disk partitioning, file storage, and forensic analysis using Autopsy. The analysis provided valuable insights into file metadata and system account details.







