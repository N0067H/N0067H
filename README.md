```cpp
#include <iostream>
#include <string>
#include <vector>

class Me {
private:
	std::string name;
	std::vector<std::string> tech;
	std::vector<std::string> favorites;

public:
	  Me()
        : name{	"SeungYup Ryu" },
		      tech{ "C++", "C#", "Node.js" },
		      favorites{ "C++", "Rust", "Go", "Haskell" }
    {}

    static friend auto operator<<(std::ostream& os, const Me& me) -> std::ostream& {
        os << "Me {\n";
        os << "    name: \"" << me.name << "\",\n";
        os << "    tech: [\n";
        for (std::size_t i = 0; i < me.tech.size(); ++i) {
            os << "        \"" << me.tech[i] << "\"";
            if (i < me.tech.size() - 1) {
                os << ",";
            }
            os << "\n";
        }
        os << "    ]\n";
        os << "    favorites: [\n";
        for (std::size_t i = 0; i < me.favorites.size(); ++i) {
            os << "        \"" << me.favorites[i] << "\"";
            if (i < me.favorites.size() - 1) {
                os << ",";
            }
            os << "\n";
        }
        os << "    ]\n";
        os << "}\n";
        return os;
    }
};

int main() {
	Me me{};
	std::cout << me << '\n';
}
```
