# tijmenb/yard_markdown

- [`Generator`](#class-yardmarkdowngenerator)
 - [`generate`](#generategithub_repo)

- [`ExampleClass`](#class-yardmarkdownexampleclass)
 - [`initialize`](#initializesomething)
 - [`some_instance_method`](#some_instance_methodwith_arg--)
 - [`something_that_raises`](#something_that_raises)
 - [`send_email`](#send_emailopts---end)
 - [`some_deprecated_method`](#some_deprecated_method)
 - [`method_that_yields`](#method_that_yields)

- [`ExampleModule`](#module-yardmarkdownexamplemodule)
 - [`method_on_module`](#method_on_module)

---

## `class YardMarkdown::Generator`

**See**:

### `.generate(github_repo:)`

Create docs/readme.md for the current project

**Params**:

- `github_repo` (`String`) — the GitHub repo for this project, eg. "tijmenb/yard_markdown".
Needed to create the "Source on GitHub" link.
  

**Examples**:

```ruby

YardMarkdown::Generator.generate(
  github_repo: "tijmenb/yard_markdown",
)
```

**See**:
- https://github.com/tijmenb/yard_markdown
- [Source on GitHub](https://github.com/tijmenb/yard_markdown/blob/master/lib/yard_markdown/generator.rb#L16)

---

## `class YardMarkdown::ExampleClass`

A description for the ExampleClass

**Something really important for the class**

⚠️ **Don't use this class anymore.**

**See**:
- https://www.example.org/class-see

### `#initialize(something)`

Some description for the `initialize` method

**Params**:

- `something` (`Hash`) — this is my param, it should be a hash
  

**Returns**:

- (`Hash`) — your response


**See**:
- [Source on GitHub](https://github.com/tijmenb/yard_markdown/blob/master/lib/yard_markdown/test_classes/example_class.rb#L14)

### `#some_instance_method(with_arg = {})`

**Something really important for this method**


**See**:
- [Source on GitHub](https://github.com/tijmenb/yard_markdown/blob/master/lib/yard_markdown/test_classes/example_class.rb#L18)

### `#something_that_raises`


**Raises**:

- `ArgumentError` if something is wrong

**See**:
- [Source on GitHub](https://github.com/tijmenb/yard_markdown/blob/master/lib/yard_markdown/test_classes/example_class.rb#L22)

### `#send_email(opts = {}) end`

**Params**:

- `opts` (`Hash`) — the options to create a message with.
  
  - `:subject` (`String`) — The subject
  - `:from` (`String`) — From address
  - `:to` (`String`) — Recipient email
  - `:body` (`String`) — '') The email's body


**See**:
- [Source on GitHub](https://github.com/tijmenb/yard_markdown/blob/master/lib/yard_markdown/test_classes/example_class.rb#L30)

### `#some_deprecated_method`

⚠️ **Don't use this method anymore.**


**See**:
- [Source on GitHub](https://github.com/tijmenb/yard_markdown/blob/master/lib/yard_markdown/test_classes/example_class.rb#L33)

### `#method_that_yields`


**Yields**:

- (`a, b, c`) — Gives 3 random numbers to the block

**See**:
- [Source on GitHub](https://github.com/tijmenb/yard_markdown/blob/master/lib/yard_markdown/test_classes/example_class.rb#L37)

---

## `module YardMarkdown::ExampleModule`

**See**:

### `.method_on_module`



**See**:
- [Source on GitHub](https://github.com/tijmenb/yard_markdown/blob/master/lib/yard_markdown/test_classes/example_class.rb#L42)

---

