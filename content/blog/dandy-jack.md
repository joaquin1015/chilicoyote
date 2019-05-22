---
title: "Dandy Jack"
date: 2019-01-20T15:25:19+02:00
publishdate: 2019-02-20T11:17:14+02:00
lastmod: 2018-10-08T18:55:29+02:00
image: "/images/workbuydie.jpg"
tags: ["interesting", "locations", "television", "zombies", "food", "albuquerque"]
type: "post"
comments: false
author: "John Doe"
---

### Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean semper 

libero quis dictum dapibus. 
Nulla egestas vitae augue eu rutrum. Duis ullamcorper dictum ipsum. Interdum et malesuada fames ac 
ante ipsum primis in faucibus. Suspendisse tortor dui, fermentum non dapibus id, volutpat non odio.

> Suspendisse tortor dui, fermentum non dapibus id, volutpat non odio.

{{< tweet 877500564405444608 >}}

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean semper 
> libero quis dictum dapibus. 
Nulla egestas vitae augue eu rutrum. Duis ullamcorper dictum ipsum. Interdum et malesuada fames ac This is [an example](/blog/hank/ "Title") inline link.
Ante ipsum primis in faucibus. Suspendisse tortor dui, fermentum non dapibus id, volutpat non odio.

{{< bootstrap-table "table table-hover table-striped table-sm" >}}
|       | First  | Second|Third |Four  | Five |
| ----- | ------ | ----- | ---- | ---- | ---- |
|   1   | ifidf  | idsf  | idsf | idsf | idsf |
|   2   | idfi   | idf   | idsf | idsf | idsf |
|   3   | isdf   | isdf  | idsf | idsf | idsf |
{{< /bootstrap-table >}}



#  H1

## H2

### H3

#### H4

##### H5

###### H6

<!-- This is a code block (must include the three tildas, top & bottom-->

{{< codeblock "rounded text-muted" >}}
```
{{ $htmlTable := .Inner | markdownify }}
{{ $class := .Get 0 }}
{{ $old := "<table>" }}
{{ $new := printf "<table class=\"%s\">" $class }}
{{ $htmlTable := replace $htmlTable $old $new }}
{{ $htmlTable | safeHTML }}

{{ $htmlTable := .Inner | markdownify }}
{{ $class := .Get 0 }}
{{ $old := "<table>" }}
{{ $new := printf "<table class=\"%s\">" $class }}
{{ $htmlTable := replace $htmlTable $old $new }}
{{ $htmlTable | safeHTML }}
```
{{< /codeblock >}}

<!-- This is a another code block (must include the three tildas, top & bottom-->

{{< codeblock "rounded text-muted" >}}
```
<div class="row">
  <div class="col-4">
    <div class="list-group" id="list-tab" role="tablist">
      <a class="list-group-item list-group-item-action active" id="list-home-list" data-toggle="list" href="#list-home" role="tab" aria-controls="home">Home</a>
      <a class="list-group-item list-group-item-action" id="list-profile-list" data-toggle="list" href="#list-profile" role="tab" aria-controls="profile">Profile</a>
      <a class="list-group-item list-group-item-action" id="list-messages-list" data-toggle="list" href="#list-messages" role="tab" aria-controls="messages">Messages</a>
      <a class="list-group-item list-group-item-action" id="list-settings-list" data-toggle="list" href="#list-settings" role="tab" aria-controls="settings">Settings</a>
    </div>
  </div>
  <div class="col-8">
    <div class="tab-content" id="nav-tabContent">
      <div class="tab-pane fade show active" id="list-home" role="tabpanel" aria-labelledby="list-home-list">...</div>
      <div class="tab-pane fade" id="list-profile" role="tabpanel" aria-labelledby="list-profile-list">...</div>
      <div class="tab-pane fade" id="list-messages" role="tabpanel" aria-labelledby="list-messages-list">...</div>
      <div class="tab-pane fade" id="list-settings" role="tabpanel" aria-labelledby="list-settings-list">...</div>
    </div>
  </div>
</div>
```
{{< /codeblock >}}


1. Red
2. Green
3. Blue
4. Yellow
5. Mango
6. Rust
7. Canary
8. Teal

- [x] hello
- [x] nope
- [x] writer

You can create footnotes like this[^1]

[^1]: Help this footnote


neither ~~here~~ nor ~~there~~

_fml_

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean semper libero quis dictum dapibus. 
Nulla egestas vitae augue eu rutrum. Duis ullamcorper dictum ipsum. Interdum et malesuada fames ac 
ante ipsum primis in faucibus. Suspendisse tortor dui, fermentum non dapibus id, volutpat non odio.

{{< vimeo 146022717 >}} 

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean semper libero quis dictum dapibus. 
Nulla egestas vitae augue eu rutrum. Duis ullamcorper dictum ipsum. Interdum et malesuada fames ac 
ante ipsum primis in faucibus. Suspendisse tortor dui, fermentum non dapibus id, volutpat non odio.

> Suspendisse tortor dui, fermentum non dapibus id, volutpat non odio.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean semper libero quis dictum dapibus. 
Nulla egestas vitae augue eu rutrum. Duis ullamcorper dictum ipsum. Interdum et malesuada fames ac 
ante ipsum primis in faucibus. Suspendisse tortor dui, fermentum non dapibus id, volutpat non odio.

> Suspendisse tortor dui, fermentum non dapibus id, volutpat non odio.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean semper libero quis dictum dapibus. 
Nulla egestas vitae augue eu rutrum. Duis ullamcorper dictum ipsum. Interdum et malesuada fames ac 
ante ipsum primis in faucibus. Suspendisse tortor dui, fermentum non dapibus id, volutpat non odio.

{{< youtube w7Ft2ymGmfc >}}

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean semper libero quis dictum dapibus. 
Nulla egestas vitae augue eu rutrum. Duis ullamcorper dictum ipsum. Interdum et malesuada fames ac 
ante ipsum primis in faucibus. Suspendisse tortor dui, fermentum non dapibus id, volutpat non odio.

> Suspendisse tortor dui, fermentum non dapibus id, volutpat non odio.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean semper libero quis dictum dapibus. 
Nulla egestas vitae augue eu rutrum. Duis ullamcorper dictum ipsum. Interdum et malesuada fames ac 
ante ipsum primis in faucibus. Suspendisse tortor dui, fermentum non dapibus id, volutpat non odio.

> Suspendisse tortor dui, fermentum non dapibus id, volutpat non odio.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean semper libero quis dictum dapibus. 
Nulla egestas vitae augue eu rutrum. Duis ullamcorper dictum ipsum. Interdum et malesuada fames ac 
ante ipsum primis in faucibus. Suspendisse tortor dui, fermentum non dapibus id, volutpat non odio.

> Suspendisse tortor dui, fermentum non dapibus id, volutpat non odio.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean semper libero quis dictum dapibus. 
Nulla egestas vitae augue eu rutrum. Duis ullamcorper dictum ipsum. Interdum et malesuada fames ac 
ante ipsum primis in faucibus. Suspendisse tortor dui, fermentum non dapibus id, volutpat non odio.

> Suspendisse tortor dui, fermentum non dapibus id, volutpat non odio.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean semper libero quis dictum dapibus. 
Nulla egestas vitae augue eu rutrum. Duis ullamcorper dictum ipsum. Interdum et malesuada fames ac 
ante ipsum primis in faucibus. Suspendisse tortor dui, fermentum non dapibus id, volutpat non odio.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean semper libero quis dictum dapibus. 
Nulla egestas vitae augue eu rutrum. Duis ullamcorper dictum ipsum. Interdum et malesuada fames ac 
ante ipsum primis in faucibus. Suspendisse tortor dui, fermentum non dapibus id, volutpat non odio.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean semper libero quis dictum dapibus. 
Nulla egestas vitae augue eu rutrum. Duis ullamcorper dictum ipsum. Interdum et malesuada fames ac 
ante ipsum primis in faucibus. Suspendisse tortor dui, fermentum non dapibus id, volutpat non odio.

> Suspendisse tortor dui, fermentum non dapibus id, volutpat non odio.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean semper libero quis dictum dapibus. 
Nulla egestas vitae augue eu rutrum. Duis ullamcorper dictum ipsum. Interdum et malesuada fames ac 
ante ipsum primis in faucibus. Suspendisse tortor dui, fermentum non dapibus id, volutpat non odio.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean semper libero quis dictum dapibus. 
Nulla egestas vitae augue eu rutrum. Duis ullamcorper dictum ipsum. Interdum et malesuada fames ac 
ante ipsum primis in faucibus. Suspendisse tortor dui, fermentum non dapibus id, volutpat non odio.
