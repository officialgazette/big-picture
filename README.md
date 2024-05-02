# Big Picture
This Page provides an overview of all available open source artifacts and how they play together. The official gazette. In the sense of the domain driven design approach, the official gazette ecosystem consists of several domains, whereby the core domain is the publication of legally binding announcements.

```mermaid
block-beta
columns 1
block:core["Core"]
create ["Create"]
publish ["Publish"]
identify ["Identify
and authorize"]
search ["Search
and Find"]
end
space:3
block:support["Support"]
columns 3
config ["Configure"]
customer ["Customer/
Partner Support"]
archive ["Store
and Archive"]
end
space:3
block:generic["Generic"]
columns 3
accounting ["Accounting"]
operate ["Operate"]
standards ["Standards"]
end
 style standards fill:#696;
```
