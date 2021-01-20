---
title: Hello World
---
## Hello World!!
Before we start, see this video:

{{< youtube w7Ft2ymGmfc >}}

### Named Parameters
{{< youtube id="w7Ft2ymGmfc" autoplay="true" >}}

### Raw string Parameter

{{<  rawstringshortcode `This is some <b>HTML</b>,
and a new line with a "quoted string".` >}}

### enclosing text, result is inserted into page directly

{{< highlight go >}} A bunch of code here {{< /highlight >}}

### enclosing text, result is inserted to content file, and then gets rendered as markdown.

{{% markdownshortcode %}} 
Markdown to `process` in the *center*. 
{{% /markdownshortcode %}}

### Self closing 

{{<myshortcode>}}{{</myshortcode>}}

{{< myshortcode />}}