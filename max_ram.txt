#include <iostream>
#include <cstdlib>

int main(int argc, char* argv[]) {

    int n;
    std::cout << "n: ";
    std::cin >> n;

    int* tombp = new int[n];

    for (int i = 0; i < n; ++i) {
        tombp[i] = i;
    }

    while (true) {}

    delete[] tombp;

    return 0;
}