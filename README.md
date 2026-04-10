# Ruby Programming Language – Source Code Repository

**Learn Elegant Programming, Web Development with Ruby, Automation, and Building Real Applications from Scratch**

This repository contains every code example from the book, organized by chapter. Each folder maps directly to a chapter so you can find any example in seconds without searching through the text.

---

## How to Use This Repository

1. **Clone the repository** to your local machine:

```bash
git clone https://github.com/ey11gen/ruby-programming-codes.git
cd ruby-programming-codes
```

2. **Make sure Ruby is installed.** All examples require Ruby 3.0 or later. Run the following command to check:

```bash
ruby --version
```

3. **Navigate to any chapter folder** and run a file:

```bash
cd chapter_01
ruby 01_hello_world.rb
```

4. **For Chapter 17 (RSpec tests)**, install RSpec first:

```bash
gem install rspec
rspec calculator_spec.rb
```

5. **For Chapter 20 (RubyTask application)**, run from inside the rubytask directory:

```bash
cd chapter_20/rubytask
ruby rubytask.rb help
ruby rubytask.rb add "My first task" --priority high
ruby rubytask.rb list
```

---

## Repository Structure

```
ruby-programming-codes/
├── chapter_01/   Getting Started with Ruby
├── chapter_02/   Variables, Data Types, and Operators
├── chapter_03/   Strings and Text Processing
├── chapter_04/   Control Flow and Decision Making
├── chapter_05/   Loops, Iterators, and Blocks
├── chapter_06/   Arrays and Hashes
├── chapter_07/   Methods and Program Structure
├── chapter_08/   OOP: Classes and Objects
├── chapter_09/   OOP: Inheritance and Polymorphism
├── chapter_10/   Modules, Mixins, and Code Organization
├── chapter_11/   Error Handling and Exceptions
├── chapter_12/   File I/O and the File System
├── chapter_13/   The Ruby Standard Library
├── chapter_14/   RubyGems, Bundler, and Dependencies
├── chapter_15/   Functional Programming Patterns
├── chapter_16/   Metaprogramming in Ruby
├── chapter_17/   Testing with RSpec and Minitest
├── chapter_18/   Web Development with Ruby on Rails
├── chapter_19/   Automation and Scripting
└── chapter_20/   Building a Complete Ruby Application
    └── rubytask/ ← Fully runnable CLI task manager
```

---

## Chapter-by-Chapter File Guide

### Chapter 01 – Getting Started with Ruby
| File | Description |
|------|-------------|
| `01_hello_world.rb` | Your first Ruby program using `puts` |
| `02_output_methods.rb` | Difference between `puts`, `print`, and `p` |
| `03_irb_arithmetic.rb` | Arithmetic expressions for IRB exploration |
| `04_sequence_demo.rb` | How Ruby executes code line by line |
| `05_error_demo.rb` | Understanding Ruby error messages |
| `06_comments_demo.rb` | Single-line and multi-line comments |

### Chapter 02 – Variables, Data Types, and Operators
| File | Description |
|------|-------------|
| `01_variables.rb` | Assignment, snake_case naming, compound operators |
| `02_numbers.rb` | Integers, floats, arithmetic, number methods |
| `03_booleans_nil_symbols.rb` | Booleans, nil, and symbols explained |
| `04_operators.rb` | Arithmetic, comparison, and logical operators |
| `05_type_conversion.rb` | `to_i`, `to_f`, `to_s` and edge cases |
| `06_user_input.rb` | `gets.chomp` for reading from the terminal |

### Chapter 03 – Strings and Text Processing
| File | Description |
|------|-------------|
| `01_string_literals.rb` | Single quotes, double quotes, heredocs, freeze |
| `02_string_interpolation.rb` | Embedding expressions inside strings |
| `03_string_methods.rb` | upcase, strip, include?, gsub, split, join, center |
| `04_regular_expressions.rb` | Patterns, match?, gsub with regex, capture groups |

### Chapter 04 – Control Flow and Decision Making
| File | Description |
|------|-------------|
| `01_truthiness.rb` | Only `false` and `nil` are falsy in Ruby |
| `02_if_statements.rb` | `if`, `elsif`, `else`, `unless`, return values |
| `03_case_statement.rb` | `case`/`when` with values and ranges |
| `04_inline_ternary.rb` | One-line `if`/`unless` and the ternary operator |
| `05_combining_conditions.rb` | `&&`, `||`, `!` in real conditional logic |

### Chapter 05 – Loops, Iterators, and Blocks
| File | Description |
|------|-------------|
| `01_while_until_loop.rb` | `while`, `until`, `loop`, `break`, `next` |
| `02_times_upto_downto.rb` | Counted iteration with block parameters |
| `03_each_map_select_reject.rb` | Collection iterators with blocks |
| `04_reduce_chaining.rb` | `reduce`/`inject` and chained pipelines |
| `05_blocks_procs_lambdas.rb` | `yield`, `Proc.new`, lambda syntax |

### Chapter 06 – Arrays and Hashes
| File | Description |
|------|-------------|
| `01_arrays_basics.rb` | Creating arrays, indexes, slice, first, last |
| `02_array_methods.rb` | push/pop/shift/unshift, sort, uniq, flatten |
| `03_hashes.rb` | Hash creation, access, update, delete, iterate |
| `04_nested_structures.rb` | Arrays of hashes, hashes of hashes |
| `05_ranges.rb` | Inclusive/exclusive ranges, step, iteration |

### Chapter 07 – Methods and Program Structure
| File | Description |
|------|-------------|
| `01_methods_basics.rb` | Defining methods, implicit/explicit return |
| `02_parameters.rb` | Required, optional, keyword, splat parameters |
| `03_predicate_bang_alias.rb` | `?` and `!` conventions, `alias` keyword |
| `04_scope.rb` | Variable scope boundaries around methods |
| `05_multi_method_program.rb` | Receipt generator: single-responsibility design |

### Chapter 08 – OOP: Classes and Objects
| File | Description |
|------|-------------|
| `01_classes_objects.rb` | Defining classes, creating instances with `.new` |
| `02_initialize_instance_vars.rb` | Constructor and `@` instance variables |
| `03_accessors.rb` | `attr_reader`, `attr_writer`, `attr_accessor` |
| `04_instance_methods_self_to_s.rb` | `self`, `to_s`, method chaining with `scale!` |
| `05_class_methods.rb` | `self.method_name` factory pattern |
| `06_visibility_public_private.rb` | `public`/`private` with BankAccount |

### Chapter 09 – OOP: Inheritance and Polymorphism
| File | Description |
|------|-------------|
| `01_inheritance.rb` | `<` operator, inherited methods, `is_a?` |
| `02_method_override_super.rb` | Overriding methods, calling `super` |
| `03_polymorphism_duck_typing.rb` | Duck typing: speak on Dog, Cat, Parrot, Robot |
| `04_shapes_polymorphism.rb` | Shape hierarchy with `NotImplementedError` |
| `05_comparable_module.rb` | `include Comparable` and the `<=>` operator |

### Chapter 10 – Modules, Mixins, and Code Organization
| File | Description |
|------|-------------|
| `01_modules_mixins.rb` | `include` for sharing behavior across classes |
| `02_enumerable_module.rb` | Custom `Library` class with full Enumerable |
| `03_namespaces.rb` | `module Geometry` with `::` namespace operator |
| `04_extend_prepend.rb` | `extend` for class methods, `prepend` for wrapping |
| `05_require_example.rb` | `require`/`require_relative`, nested namespaces |

### Chapter 11 – Error Handling and Exceptions
| File | Description |
|------|-------------|
| `01_exception_hierarchy.rb` | Exploring the exception ancestor chain |
| `02_begin_rescue.rb` | Catching exceptions with multiple rescue clauses |
| `03_ensure_else.rb` | Guaranteed cleanup with `ensure`, success with `else` |
| `04_raising_exceptions.rb` | `raise`, guard clauses, re-raising with bare `raise` |
| `05_custom_exceptions.rb` | Full custom exception hierarchy for a payment system |
| `06_retry.rb` | Resilient retry loop with counter and `sleep` |

### Chapter 12 – File I/O and the File System
| File | Description |
|------|-------------|
| `01_reading_files.rb` | `File.read`, `foreach`, `File.open` block pattern |
| `02_writing_files.rb` | Writing with `"w"`, appending with `"a"`, `File.write` |
| `03_filesystem.rb` | `File.exist?`, `Dir.glob`, `mkdir`, `chdir` |
| `04_csv_processing.rb` | Reading and writing CSV with headers |
| `05_json_files.rb` | `JSON.generate`, `JSON.pretty_generate`, `JSON.parse` |

### Chapter 13 – The Ruby Standard Library
| File | Description |
|------|-------------|
| `01_date_time.rb` | `Time.now`, `Date.today`, `strftime`, date arithmetic |
| `02_math_securerandom.rb` | `Math` module, `SecureRandom` for tokens and UUIDs |
| `03_benchmark.rb` | Comparing implementations with `Benchmark.bm` |
| `04_set_struct.rb` | `Set` for unique collections, `Struct` for data objects |
| `05_network_requests.rb` | `open-uri` GET and `Net::HTTP` POST requests |

### Chapter 14 – RubyGems, Bundler, and Dependencies
| File | Description |
|------|-------------|
| `01_gem_usage.rb` | Using the `colorize` gem after `gem install colorize` |
| `Gemfile` | Example Gemfile with version constraints and groups |
| `my_utility_gem/` | Complete gem skeleton with gemspec and lib structure |

### Chapter 15 – Functional Programming Patterns
| File | Description |
|------|-------------|
| `01_pure_methods.rb` | Writing side-effect-free pure methods |
| `02_immutability.rb` | `freeze`, immutable-style programming |
| `03_method_chaining.rb` | Transformation pipelines with `group_by` |
| `04_query_builder.rb` | Chainable DSL returning `self` |
| `05_lazy_evaluation.rb` | `lazy`, infinite ranges, custom `Enumerator` |
| `06_function_composition.rb` | `&` prefix with Procs, `>>` composition operator |

### Chapter 16 – Metaprogramming in Ruby
| File | Description |
|------|-------------|
| `01_open_classes.rb` | Adding `prime?`, `factorial`, `titleize` to built-ins |
| `02_reflection.rb` | `respond_to?`, `instance_variables`, `public_methods` |
| `03_method_missing.rb` | `FlexibleRecord` with dynamic attributes |
| `04_define_method.rb` | Generating 15 methods with a loop and `define_method` |
| `05_html_builder_dsl.rb` | Full HTML DSL using `instance_eval` and blocks |

### Chapter 17 – Testing with RSpec and Minitest
| File | Description |
|------|-------------|
| `calculator.rb` | The Calculator class under test |
| `test_calculator.rb` | Full Minitest suite (`ruby test_calculator.rb`) |
| `calculator_spec.rb` | Full RSpec specification (`rspec calculator_spec.rb`) |
| `test_with_mocks.rb` | Dependency injection and `Minitest::Mock` |

### Chapter 18 – Web Development with Ruby on Rails
| File | Description |
|------|-------------|
| `config/routes.rb` | `resources :tasks` and `root` route |
| `app/controllers/tasks_controller.rb` | All 7 RESTful actions with `before_action` |
| `app/models/task.rb` | Validations, scopes, `complete!` method |
| `db/migrate/..._create_tasks.rb` | Database migration with all column types |
| `app/views/tasks/index.html.erb` | ERB list view with link helpers |
| `app/views/tasks/_form.html.erb` | Form partial with error display |

> **Note:** Rails files require a full Rails application to run. Generate one with `rails new taskmanager` and copy these files into the appropriate directories.

### Chapter 19 – Automation and Scripting with Ruby
| File | Description |
|------|-------------|
| `01_option_parser_tool.rb` | CLI tool with flags, help text, and exit codes |
| `02_file_organizer.rb` | Sorts files by extension with dry-run mode |
| `03_web_scraping.rb` | Nokogiri CSS selectors and attribute access |
| `04_external_commands.rb` | `system`, `%x()`, `$?`, `Open3` |
| `05_log_monitor.rb` | Log parser with grouping and analysis report |

### Chapter 20 – Building a Complete Ruby Application
The complete RubyTask CLI application lives in `chapter_20/rubytask/`.

| File | Description |
|------|-------------|
| `rubytask.rb` | Entry point with shebang |
| `lib/task.rb` | Task domain model with validation and serialization |
| `lib/task_repository.rb` | JSON persistence with full CRUD and stats |
| `lib/cli.rb` | Command dispatch, output formatting, option parsing |
| `spec/task_spec.rb` | 8-test Minitest suite for the Task class |
| `spec/task_repository_spec.rb` | Repository tests with temp file isolation |
| `data/tasks.json` | Persistent storage file (auto-created on first `add`) |

**Running RubyTask:**

```bash
cd chapter_20/rubytask
ruby rubytask.rb help
ruby rubytask.rb add "Write chapter 20" --priority high
ruby rubytask.rb add "Review pull requests" --priority normal
ruby rubytask.rb add "Fix critical bug" --priority urgent --desc "Production is down"
ruby rubytask.rb list
ruby rubytask.rb list --status pending
ruby rubytask.rb show 1
ruby rubytask.rb complete 1
ruby rubytask.rb stats
ruby rubytask.rb delete 2

# Run the test suite
ruby spec/task_spec.rb
ruby spec/task_repository_spec.rb
```

---

## Requirements

- Ruby 3.0 or later (Ruby 3.3 recommended, matching the book)
- Bundler (`gem install bundler`) for managing gem dependencies
- For Chapter 16 colorize example: `gem install colorize`
- For Chapter 17 RSpec examples: `gem install rspec`
- For Chapter 19 web scraping: `gem install nokogiri`
- For Chapter 18 Rails examples: `gem install rails` then `rails new taskmanager`

---

## Ruby Version Check

```bash
ruby --version
# Expected: ruby 3.3.x or any 3.x version
```

---

## Book Information

**Ruby Programming Language**
Learn Elegant Programming, Web Development with Ruby,
Automation, and Building Real Applications from Scratch

All code examples updated through **March 2026** using **Ruby 3.3**.

Repository: [https://github.com/ey11gen/ruby-programming-codes](https://github.com/ey11gen/ruby-programming-codes)

---

*Happy coding in Ruby!*
