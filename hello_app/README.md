# hello_app

First application for this tutorial.

**Ruby version:** 2.6.3

## Initial file structure and purpose

| **File/Directory** | **Purpose**                                                                            |
| ------------------ | -------------------------------------------------------------------------------------- |
| app/	             | Core application (app) code, including models, views, controllers, and helpers         |
| app/assets         | Applications assets such as cascading style sheets (CSS), JavaScript files, and images |
| bin/	             | Binary executable files                                                                |
| config/	           | Application configuration                                                              |
| db/    	           | Database files                                                                         |
| doc/	             | Documentation for the application                                                      |
| lib/	             | Library modules                                                                        |
| lib/assets	       | Library assets such as cascading style sheets (CSS), JavaScript files, and images      |
| log/    	         | Application log files                                                                  |
| public/	           | Data accessible to the public (e.g., via web browsers), such as error pages            |
| bin/rails	         | A program for generating code, opening console sessions, or starting a local server    |
| test/		           | Application tests                                                                      |
| tmp/		           | Temporary files                                                                        |
| vendor/		         | Third-party code such as plugins and gems                                              |
| vendor/assets		   | Third-party assets such as cascading style sheets (CSS), JavaScript files, and images  |
| README.md		       | A brief description of the application                                                 |
| Rakefile		       | Utility tasks available via the rake command                                           |
| Gemfile		         | Gem requirements for this app                                                          |
| Gemfile.lock		   | A list of gems used to ensure that all copies of the app use the same gem versions     |
| config.ru		       | A configuration file for [Rack middleware](https://rack.github.io/)                    |
| .gitignore		     | Patterns for files that should be ignored by Git                                       |

## Gemfile Version notation

- `>=` installs latest version greater than specified. Example:
```
gem 'uglifier', '>= 1.3.0' # uses version greater than 1.3.0 (even 4.0 and above)
```

- `~>` installs version greater than specified but only in minor version number position. Example
```
gem 'rails', '~> 5.2.3' # uses version greater than 5.2.3 but less than 5.3
```

### `rails server` and versions
**Excercises**:
1. Ruby version: 2.6.3 (x86_64-darwin18)
```
$ ruby -v
ruby 2.6.3p62 (2019-04-16 revision 67580) [x86_64-darwin18]
```

2. Rails version: 5.2.3