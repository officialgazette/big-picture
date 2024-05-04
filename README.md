# Big Picture
This Page provides an overview of all available open source artifacts and how they play together. The official gazette. In the sense of the domain driven design approach, the official gazette ecosystem consists of several domains, whereby the core domain is the publication of legally binding announcements.

```mermaid
block-beta

columns 1

block:core["Core"]

block:shared["Shared Kernel"]
create ["Create"]

publish ["Publish"]

end

identify ["Identify
and authorize"]

search ["Search
and Find"]

end

block:support["Support"]

config ["Configure"]

archive ["Store
and Archive"]

end

block:generic["Generic"]

customer ["Customer/
Partner Support"]

accounting ["Accounting"]

operate ["Operate"]

end

standards["Standards"]

accounting --> core
style standards fill:#696;
```

The individual (sub)domains and their entities are described in more detail below
