ERB
===
---
ere
---
```
<% execute %>
```



erp
---
```
<%= print %>
```


erpi
---
```
<%= print %>
```


if
---
```
<% if [condition] %>
  []
<% end %>
```


unless
---
```
<% unless [condition] %>
  []
<% end %>
```


ife
---
```
<% if [condition] %>
  []
<% else %>

<% end %>
```


ifeif
---
```
<% if [condition] %>
  []
<% elsif [condition] %>

<% end %>
```


ifeife
---
```
<% if [condition] %>
  []
<% elsif [condition] %>

<% else %>

<% end %>
```


for
---
```
<% for [item] in [collection] %>
  []
<% end %>

```


each
---
```
<% [collection].each do |[item]| %>
  []
<% end %>
```


content
---
```
<%= content_tag, :[el], [] %>[]
```


field
---
```
<%= f.[tag], :[attribute] %>[]
```


linkto
---
```
<%= link_to '[text]', [url], class: '[class]'[] %>[]
```


tag
---
```
<%= [type]_tag, [options] %>[]
```


formfor
---
```
<%= form_for [subject], [options] do |f| %>
  []
<% end %>
```
