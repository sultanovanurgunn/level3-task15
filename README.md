# level3-task15
#include <iostream>
using namespace std;

int main() {
    int N, cem = 0, a;
    cout << "Nece eded? ";
    cin >> N;

    for (int i = 0; i < N; i++) {
        cin >> a;
        cem += a;
    }

    cout << "Cem = " << cem;
    return 0;
}
