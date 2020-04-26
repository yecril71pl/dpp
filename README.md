# dpp
This is a sample decimal floating point library for c++17. You should view it with suspicion. It serves what I want it for, but you might have a different experience.

# example
```c++
int main()
{
  auto const a(dpp::to_decimal<dpp::dec32>("1.23"));
  auto const b(dpp::to_decimal<dpp::dec32>("45.6"));

  std::cout << a + b << std::endl;
  std::cout << a - b << std::endl;
  std::cout << a * b << std::endl;
  std::cout << a / b << std::endl;
  std::cout << b / a << std::endl;

  return 0;
}
```