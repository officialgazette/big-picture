# Big Picture
This Page provides an overview of all available open source artifacts and how they play together. The official gazette. In the sense of the domain driven design approach, the official gazette ecosystem consists of several domains, whereby the core domain is the publication of legally binding announcements.

```mermaid
block-beta
columns 3
block:core["Core"]
columns 1
block:shared["Shared Kernel"]
columns 1
create ["Create"]
space
publish ["Publish"] 
end
space
identify ["Identify
and authorize"]
search ["Search
and Find"]
end
block:support["Support"]
columns 1
config ["Configure"]
space:2
archive ["Store
and Archive"]
end
block:generic["Generic"]
columns 1
customer ["Customer/
Partner Support"]
space:2
accounting ["Accounting"]
operate ["Operate"]
end
%% columns auto (default)
standards 
accounting--"x"-->core
style standards fill:#696;
```
