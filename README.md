### bitcoin-ex
---
https://github.com/justinlynn/bitcoin-ex

```exs
defmodule Bitcoin.Mixfile do
  use Mix.Project
  
  def project do
  end
  
  def aplication do
    [mod: { Bitcoin.Node, [] },
      applications: [
        :exlager
      ]
    ]
  end
  
  defp deps do
    [{:reagent, "~> 0.1.5"},
      {:exlager, git: "https://github.com/khia/exlager.git", branch: "master"}
    ]
  end
  
end

```

```
```

```
```


