This code snippet calculates the average age of a group of people entered by the user. Below is the corrected and formatted version of the code:

#include <iostream>
using namespace std;

// Function to calculate the average age
double calculateAverage(int ages[], int size) {
    int sum = 0;
    for (int i = 0; i < size; i++) {
        sum += ages[i];
    }
    return static_cast<double>(sum) / size;
}

int main() {
    const int SIZE = 10; // Number of people
    int ages[SIZE];

    // Getting ages from the user
    cout << "Please enter the ages of 10 people:\n";
    for (int i = 0; i < SIZE; i++) {
        cout << "Age of person " << i + 1 << ": ";
        cin >> ages[i];
    }

    // Calculating and displaying the average age
    double average = calculateAverage(ages, SIZE);
    cout << "\nThe average age is: " << average << endl;

    return 0;
}
```

This version includes the necessary `#include <iostream>` directive and corrects some formatting issues.
