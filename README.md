# edu-standards

In education, it is often useful to define learning goals. Sometimes teachers do this. Other times, large organizations, such as national departments of education, do it. When organizations define learning goals, those goals are often called **standards**.

For edtech product developers, these standards are important to consider. People want to know which content goes with which standards. But mapping content to standards is difficult for a few reasons:

1. Standards are scattered across the internet, often living on government websites.
2. Standards aren't standardized. Naming conventions differ from one set of standards to the next.

The goal of this repository is to compile simple lists of standards from around the world. Each set of standards belongs in a separate JSON file that follows a common structure and common naming conventions. Here is how the US Common Core State Standars look:

```json
{
  "name": "Common Core State Standards, Mathematics",
  "url": "http://www.corestandards.org/wp-content/uploads/Math_Standards.pdf",
  "standards": [
    "ccss.math.k.cc.a.1",
    "ccss.math.k.cc.a.2",
    "ccss.math.k.cc.a.3",
    ...
    "ccss.math.hss.md.b.7"
  ]
}
```

## How to contribute

Simply submit a pull request that either updates an existing JSON file or adds a new one to the code base.

## Mapping standards to standards

Many people want there to be mappings between sets of standards. Wouldn't it be cool to know which German math standards relate to which Brazilian math standards? Maybe someday this repository will evolve to include such mappings.
