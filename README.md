## file_indexer

FileIndexer is a Dart CLI tool designed to simplify file organization within your project. This lightweight utility not only seamlessly copies files from various directories into a centralized "Project Files" folder but also integrates with GPT (Generative Pre-trained Transformer) for intelligent file analysis and assistance. GPT provides context-aware insights and valuable assistance tailored to your project files.

---

## In Progress Features

1- `Efficient File Copying:` Copy files from multiple directories to a designated "Project Files" folder effortlessly.

2- `Automatic Indexing:` Each copied file is numerically indexed, preserving the order in which they are added.

3- `Integration with GPT:` Leverage the power of GPT for enhanced project management. GPT analyzes your project files, providing insightful and context-aware assistance.


## Getting Started 🚀

Clone the project, open it, and then you can run it locally via:

```sh
dart pub global activate --source path .
```

## Usage

```sh
# Sample command
$ file_indexer sample

# Sample command option
$ file_indexer sample --cyan

# Show CLI version
$ file_indexer --version

# Show usage help
$ file_indexer --help
```

## Running Tests with coverage 🧪

To run all unit tests use the following command:

```sh
$ dart pub global activate coverage 1.2.0
$ dart test --coverage=coverage
$ dart pub global run coverage:format_coverage --lcov --in=coverage --out=coverage/lcov.info
```

To view the generated coverage report you can use [lcov](https://github.com/linux-test-project/lcov)
.

```sh
# Generate Coverage Report
$ genhtml coverage/lcov.info -o coverage/

# Open Coverage Report
$ open coverage/index.html
```

---

[coverage_badge]: coverage_badge.svg
[license_badge]: https://img.shields.io/badge/license-MIT-blue.svg
[license_link]: https://opensource.org/licenses/MIT
[very_good_analysis_badge]: https://img.shields.io/badge/style-very_good_analysis-B22C89.svg
[very_good_analysis_link]: https://pub.dev/packages/very_good_analysis
[very_good_cli_link]: https://github.com/VeryGoodOpenSource/very_good_cli
