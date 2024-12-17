# internet-basis-lab-task
my first github repository
COMMON SORTING ALGORITHUM IN C++
1. Bubble Sort
Bubble Sort is a simple comparison-based algorithm where each pair of adjacent elements is compared, and the elements are swapped if they are in the wrong order. This process is repeated until the list is sorted.
void bubbleSort(int arr[], int n)
{
for (int i = 0; i < n-1; i++) 
{
for (int j = 0; j < n-i-1; j++)
{
if (arr[j] > arr[j+1]) 
{
std::swap(arr[j], arr[j+1]);
}
}
}
}
