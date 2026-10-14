# codeAlpha_cgpacalculatorinclude <iostream>
#include <string>
using namespace std;

int main() {
    int n;
    cout << "Enter number of courses: ";
    cin >> n;

    string course[100];
    float grade[100], credit[100];
    float totalCredits = 0, totalPoints = 0;

    for (int i = 0; i < n; i++) {
        cout << "\nEnter course name: ";
        cin >> course[i];

        cout << "Enter grade point: ";
        cin >> grade[i];

        cout << "Enter credit hours: ";
        cin >> credit[i];

        totalCredits += credit[i];
        totalPoints += grade[i] * credit[i];
    }

    float GPA = totalPoints / totalCredits;

    // Assume previous CGPA and credits
    float previousCGPA, previousCredits;

    cout << "\nEnter previous CGPA (0 if none): ";
    cin >> previousCGPA;

    cout << "Enter previous total credits (0 if none): ";
    cin >> previousCredits;

    float CGPA;

    if (previousCredits == 0) {
        CGPA = GPA;
    } else {
        CGPA = (previousCGPA * previousCredits + totalPoints)
               / (previousCredits + totalCredits);
    }

    cout << "\n--- Course Details ---\n";

    for (int i = 0; i < n; i++) {
        cout << course[i]
             << " | Grade: " << grade[i]
             << " | Credits: " << credit[i] << endl;
    }

    cout << "\nSemester GPA = " << GPA;
    cout << "\nOverall CGPA = " << CGPA << endl;

    return 0;
}include <iostream>
#include <string>
using namespace std;

int main() {
    int n;
    cout << "Enter number of courses: ";
    cin >> n;

    string course[100];
    float grade[100], credit[100];
    float totalCredits = 0, totalPoints = 0;

    for (int i = 0; i < n; i++) {
        cout << "\nEnter course name: ";
        cin >> course[i];

        cout << "Enter grade point: ";
        cin >> grade[i];

        cout << "Enter credit hours: ";
        cin >> credit[i];

        totalCredits += credit[i];
        totalPoints += grade[i] * credit[i];
    }

    float GPA = totalPoints / totalCredits;

    // Assume previous CGPA and credits
    float previousCGPA, previousCredits;

    cout << "\nEnter previous CGPA (0 if none): ";
    cin >> previousCGPA;

    cout << "Enter previous total credits (0 if none): ";
    cin >> previousCredits;

    float CGPA;

    if (previousCredits == 0) {
        CGPA = GPA;
    } else {
        CGPA = (previousCGPA * previousCredits + totalPoints)
               / (previousCredits + totalCredits);
    }

    cout << "\n--- Course Details ---\n";

    for (int i = 0; i < n; i++) {
        cout << course[i]
             << " | Grade: " << grade[i]
             << " | Credits: " << credit[i] << endl;
    }

    cout << "\nSemester GPA = " << GPA;
    cout << "\nOverall CGPA = " << CGPA << endl;

    return 0;
}include <iostream>
#include <string>
using namespace std;

int main() {
    int n;
    cout << "Enter number of courses: ";
    cin >> n;

    string course[100];
    float grade[100], credit[100];
    float totalCredits = 0, totalPoints = 0;

    for (int i = 0; i < n; i++) {
        cout << "\nEnter course name: ";
        cin >> course[i];

        cout << "Enter grade point: ";
        cin >> grade[i];

        cout << "Enter credit hours: ";
        cin >> credit[i];

        totalCredits += credit[i];
        totalPoints += grade[i] * credit[i];
    }

    float GPA = totalPoints / totalCredits;

    // Assume previous CGPA and credits
    float previousCGPA, previousCredits;

    cout << "\nEnter previous CGPA (0 if none): ";
    cin >> previousCGPA;

    cout << "Enter previous total credits (0 if none): ";
    cin >> previousCredits;

    float CGPA;

    if (previousCredits == 0) {
        CGPA = GPA;
    } else {
        CGPA = (previousCGPA * previousCredits + totalPoints)
               / (previousCredits + totalCredits);
    }

    cout << "\n--- Course Details ---\n";

    for (int i = 0; i < n; i++) {
        cout << course[i]
             << " | Grade: " << grade[i]
             << " | Credits: " << credit[i] << endl;
    }

    cout << "\nSemester GPA = " << GPA;
    cout << "\nOverall CGPA = " << CGPA << endl;

    return 0;
}include <iostream>
#include <string>
using namespace std;

int main() {
    int n;
    cout << "Enter number of courses: ";
    cin >> n;

    string course[100];
    float grade[100], credit[100];
    float totalCredits = 0, totalPoints = 0;

    for (int i = 0; i < n; i++) {
        cout << "\nEnter course name: ";
        cin >> course[i];

        cout << "Enter grade point: ";
        cin >> grade[i];

        cout << "Enter credit hours: ";
        cin >> credit[i];

        totalCredits += credit[i];
        totalPoints += grade[i] * credit[i];
    }

    float GPA = totalPoints / totalCredits;

    // Assume previous CGPA and credits
    float previousCGPA, previousCredits;

    cout << "\nEnter previous CGPA (0 if none): ";
    cin >> previousCGPA;

    cout << "Enter previous total credits (0 if none): ";
    cin >> previousCredits;

    float CGPA;

    if (previousCredits == 0) {
        CGPA = GPA;
    } else {
        CGPA = (previousCGPA * previousCredits + totalPoints)
               / (previousCredits + totalCredits);
    }

    cout << "\n--- Course Details ---\n";

    for (int i = 0; i < n; i++) {
        cout << course[i]
             << " | Grade: " << grade[i]
             << " | Credits: " << credit[i] << endl;
    }

    cout << "\nSemester GPA = " << GPA;
    cout << "\nOverall CGPA = " << CGPA << endl;

    return 0;
}include <iostream>
#include <string>
using namespace std;

int main() {
    int n;
    cout << "Enter number of courses: ";
    cin >> n;

    string course[100];
    float grade[100], credit[100];
    float totalCredits = 0, totalPoints = 0;

    for (int i = 0; i < n; i++) {
        cout << "\nEnter course name: ";
        cin >> course[i];

        cout << "Enter grade point: ";
        cin >> grade[i];

        cout << "Enter credit hours: ";
        cin >> credit[i];

        totalCredits += credit[i];
        totalPoints += grade[i] * credit[i];
    }

    float GPA = totalPoints / totalCredits;

    // Assume previous CGPA and credits
    float previousCGPA, previousCredits;

    cout << "\nEnter previous CGPA (0 if none): ";
    cin >> previousCGPA;

    cout << "Enter previous total credits (0 if none): ";
    cin >> previousCredits;

    float CGPA;

    if (previousCredits == 0) {
        CGPA = GPA;
    } else {
        CGPA = (previousCGPA * previousCredits + totalPoints)
               / (previousCredits + totalCredits);
    }

    cout << "\n--- Course Details ---\n";

    for (int i = 0; i < n; i++) {
        cout << course[i]
             << " | Grade: " << grade[i]
             << " | Credits: " << credit[i] << endl;
    }

    cout << "\nSemester GPA = " << GPA;
    cout << "\nOverall CGPA = " << CGPA << endl;

    return 0;
}include <iostream>
#include <string>
using namespace std;

int main() {
    int n;
    cout << "Enter number of courses: ";
    cin >> n;

    string course[100];
    float grade[100], credit[100];
    float totalCredits = 0, totalPoints = 0;

    for (int i = 0; i < n; i++) {
        cout << "\nEnter course name: ";
        cin >> course[i];

        cout << "Enter grade point: ";
        cin >> grade[i];

        cout << "Enter credit hours: ";
        cin >> credit[i];

        totalCredits += credit[i];
        totalPoints += grade[i] * credit[i];
    }

    float GPA = totalPoints / totalCredits;

    // Assume previous CGPA and credits
    float previousCGPA, previousCredits;

    cout << "\nEnter previous CGPA (0 if none): ";
    cin >> previousCGPA;

    cout << "Enter previous total credits (0 if none): ";
    cin >> previousCredits;

    float CGPA;

    if (previousCredits == 0) {
        CGPA = GPA;
    } else {
        CGPA = (previousCGPA * previousCredits + totalPoints)
               / (previousCredits + totalCredits);
    }

    cout << "\n--- Course Details ---\n";

    for (int i = 0; i < n; i++) {
        cout << course[i]
             << " | Grade: " << grade[i]
             << " | Credits: " << credit[i] << endl;
    }

    cout << "\nSemester GPA = " << GPA;
    cout << "\nOverall CGPA = " << CGPA << endl;

    return 0;
}include <iostream>
#include <string>
using namespace std;

int main() {
    int n;
    cout << "Enter number of courses: ";
    cin >> n;

    string course[100];
    float grade[100], credit[100];
    float totalCredits = 0, totalPoints = 0;

    for (int i = 0; i < n; i++) {
        cout << "\nEnter course name: ";
        cin >> course[i];

        cout << "Enter grade point: ";
        cin >> grade[i];

        cout << "Enter credit hours: ";
        cin >> credit[i];

        totalCredits += credit[i];
        totalPoints += grade[i] * credit[i];
    }

    float GPA = totalPoints / totalCredits;

    // Assume previous CGPA and credits
    float previousCGPA, previousCredits;

    cout << "\nEnter previous CGPA (0 if none): ";
    cin >> previousCGPA;

    cout << "Enter previous total credits (0 if none): ";
    cin >> previousCredits;

    float CGPA;

    if (previousCredits == 0) {
        CGPA = GPA;
    } else {
        CGPA = (previousCGPA * previousCredits + totalPoints)
               / (previousCredits + totalCredits);
    }

    cout << "\n--- Course Details ---\n";

    for (int i = 0; i < n; i++) {
        cout << course[i]
             << " | Grade: " << grade[i]
             << " | Credits: " << credit[i] << endl;
    }

    cout << "\nSemester GPA = " << GPA;
    cout << "\nOverall CGPA = " << CGPA << endl;

    return 0;
}include <iostream>
#include <string>
using namespace std;

int main() {
    int n;
    cout << "Enter number of courses: ";
    cin >> n;

    string course[100];
    float grade[100], credit[100];
    float totalCredits = 0, totalPoints = 0;

    for (int i = 0; i < n; i++) {
        cout << "\nEnter course name: ";
        cin >> course[i];

        cout << "Enter grade point: ";
        cin >> grade[i];

        cout << "Enter credit hours: ";
        cin >> credit[i];

        totalCredits += credit[i];
        totalPoints += grade[i] * credit[i];
    }

    float GPA = totalPoints / totalCredits;

    // Assume previous CGPA and credits
    float previousCGPA, previousCredits;

    cout << "\nEnter previous CGPA (0 if none): ";
    cin >> previousCGPA;

    cout << "Enter previous total credits (0 if none): ";
    cin >> previousCredits;

    float CGPA;

    if (previousCredits == 0) {
        CGPA = GPA;
    } else {
        CGPA = (previousCGPA * previousCredits + totalPoints)
               / (previousCredits + totalCredits);
    }

    cout << "\n--- Course Details ---\n";

    for (int i = 0; i < n; i++) {
        cout << course[i]
             << " | Grade: " << grade[i]
             << " | Credits: " << credit[i] << endl;
    }

    cout << "\nSemester GPA = " << GPA;
    cout << "\nOverall CGPA = " << CGPA << endl;

    return 0;
}
