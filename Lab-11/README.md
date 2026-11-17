# Lab 11: Mutex, Thread Synchronization & Banker's Algorithm

Course: Operating Systems Lab (CSL-320)[cite: 1]  
Institution: Bahria University, Lahore Campus[cite: 1]  

## 📂 Overview
This folder contains the implementation and analysis for Lab 11, focusing on concurrent programming, thread synchronization using POSIX mutex locks[cite: 1], and the theoretical analysis of resource allocation in dynamic environments.

## 🛠️ Files in this Lab
- `lab11.c`: C program demonstrating thread synchronization using `pthread_mutex_t` to prevent race conditions on a shared counter[cite: 1].

## 🚀 How to Compile and Run
Open your terminal inside the `Lab-11` directory and run the following commands:

```bash
# Compile using gcc with the pthread flag
gcc -pthread lab11.c -o lab11.out

# Execute the program
./lab11.out
