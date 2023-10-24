#include <bits/stdc++.h>

using namespace std;

string encode(string &s, int j)
{
    j++;
    string result = "";
    for (int i = 0; i < s.length(); i++) {
        if(i % j == j - 1) {
            result += char(s[i] + 2);
        }
        else {
            result += s[i];
        }
    }
    return result;
}

string decode(string &s, int j)
{
    j++;
    string result = "";
    for (int i = 0; i < s.length(); i++) {
        if(i % j == j - 1) {
            result += char(s[i] - 2);
        }
        else {
            result += s[i];
        }
    }
    return result;
}

int main()
{
    string s = "I am a student";
    int j = 2;
    cout << "Sample string: " << s << endl;

    string encoded = encode(s, j);
    cout << "Encoded string: " << encoded << endl;

    string decoded = decode(encoded, j);
    cout << "Decoded string: " << decoded << endl;
}
