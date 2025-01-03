# Elixir Enum.each Order Issue

This repository demonstrates a subtle issue with `Enum.each` in Elixir when dealing with long-running tasks within the enumeration.  The expected sequential output is not guaranteed if operations inside the function take a significant time to complete.