# 100Days-of-DSA-
This Repo. contains the DSA codes I made while learning it in a day wise manner.


//  C++ program to reverse an array
#include <bits/stdc++.h>
#include <iostream>
using namespace std;

// Function to reverse arr[] from start to end
void reverseArray(int arr[], int start, int end) {
  while (start < end) {
    int temp = arr[start];
    arr[start] = arr[end];
    arr[end] = temp;
    start++;
    end--;
  }
}

// function to print an array
void printArray(int arr[], int size) {
  for (int i = 0; i < size; i++)
    cout << arr[i] << " ";

  cout << endl;
}
