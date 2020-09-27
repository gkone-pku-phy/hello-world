this is my first github code
i don't know what to say,so i'll copy some of my cpp code to "Hua Shui" ha ha ha...
#include <string>
#include <iostream>
#include <fstream>
#include <vector>
using namespace std;
int main() {
	vector<string> v;
	ifstream in("Fillvector.cpp");
	string line;
	while(getline(in,line))
	v.push_back(line);
	for(int i=0;i<v.size();i++)
	cout<<i<<":"<<v[i]<<endl;
}
