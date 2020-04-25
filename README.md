# Educational standards

In education, it is often useful to define learning goals. Teachers do this all of the time, but so do organizations, such as governments. When large organizations do it, the goals are often called **standards** because they want service providers (e.g., teachers and schools) to align their services to those goals.

For edtech product developers, educational standards are important to consider. Consumers want to know which content goes with which standards. Unfortunately, mapping content to standards can be difficult because standards aren't standardized.

1. They are scattered across the internet, often living on government websites.
2. Naming conventions differ from one set to another.

The goal of this repository is to compile simple lists of standards from around the world. Each set of standards belongs in a separate JSON file that follows a common structure and common naming conventions. Here is how the US Common Core State Standars look:

```json
{
  "name": "Common Core State Standards, Mathematics",
  "url": "http://www.corestandards.org/wp-content/uploads/Math_Standards.pdf",
  "standards": [
    "ccss.math.k.cc.a.1",
    "ccss.math.k.cc.a.2",
    "ccss.math.k.cc.a.3",
  ]
}
```

## How will edtech developers use this data?

The most common use case will be tagging content. For example, and question on itempool might be tagged `"ccss.math.k.cc.a.1"`, which would come from this repo. 

## How to contribute

Simply submit a pull request that either updates an existing JSON file or adds a new one to the code base.

## Mapping standards to standards

Many people want there to be mappings between sets of standards. Wouldn't it be cool to know which German math standards relate to which Brazilian math standards? Maybe someday this repository will evolve to include such mappings.
