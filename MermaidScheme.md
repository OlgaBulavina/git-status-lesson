HEAD - STATUS OF FILES IN GIT

```mermaid
graph LR;
%%how changes status of files in git
A[untracked] --> B{git add} --> C[staged, tracked];
C -- some changes --> G[modified];
C --> D{git commit} --> E[tracked] -- some changes --> G[modified];
G --> F{git add} --> C;
```
<made by B_Olya>