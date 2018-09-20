# Functions

Functions are blocks of code that can do a task as many times as you ask it to. They take an input and return an output.

Here's a function that doubles a number:

```javascript
function double(number) {
  return number * 2;
}
```

To use the function we need to: a\) _call_ it with an input and b\) assign the returned value to a variable

```javascript
var result = double(2);

console.log(result); // 4
```

## Exercise

* Complete the function in exercise.js so that it halves the input
* Try calling the function more than once with some different numbers

> Remember to use the return keyword to get a value out of the function

## Expected result

```text
6
```

## Exercise 2

* Complete the function in exercise2.js so that it triples the input

## Expected result

```text
24
```

{% tabs %}
{% tab title="Second Tab" %}
Bye
{% endtab %}

{% tab title="" %}
{% embed data="{\"url\":\"https://runkit.com/djgrant/5ba2df9592bf930012ae2470\",\"type\":\"rich\",\"title\":\"RunKit\",\"description\":\"RunKit notebooks are interactive javascript playgrounds connected to a complete node environment right in your browser. Every npm module pre-installed.\",\"icon\":{\"type\":\"icon\",\"url\":\"https://runkit.com/favicon.ico\",\"aspectRatio\":0},\"embed\":{\"type\":\"reader\",\"html\":\"<iframe style=\\\"width: calc\(100% + 200px\); padding: 0; margin: 0 0 0 -100px; background: transparent;\\\" src=\\\"https://runkit.com/e?name=dde80286-ec7c-43db-9d19-7dcd2db6e217&base64source=LyogCkNvbXBsZXRlIHRoZSBgYWRkYCBmdW5jdGlvbiBzbyB0aGF0IGl0IHJldHVybnMgdGhlIHN1bSBvZiB0aGUgdHdvIHBhcmFybWV0ZXJzLgoqLwpmdW5jdGlvbiBhZGQoYSwgYikgewogICAgcmV0dXJuIGEgKyBiOwp9CgphZGQoMSwgMik7Ci8qIApIZXJlJ3Mgc29tZSBjb2RlIHRoYXQgY291bGQgYmUgaGlkZGVuIGF3YXkuLi4KKi8KY29uc3QgZXhwZWN0ID0gcmVxdWlyZSgnZXhwZWN0Jyk7IApjb25zdCB7IFZhbHVlVmlld2VyU3ltYm9sIH0gPSByZXF1aXJlKCJAcnVua2l0L3ZhbHVlLXZpZXdlciIpOyAKCmxldCB0ZXN0c1J1biA9IDA7IApsZXQgdGVzdHNQYXNzZWQgPSAwOyAKY29uc3QgcmVzdWx0cyA9IFtdOyAKCmZ1bmN0aW9uIGl0KGRlc2MsIGZuKSB7IAogICAgdGVzdHNSdW4rKzsgCiAgICB0cnkgeyAKICAgICAgICBmbigpOyAKICAgICAgICB0ZXN0c1Bhc3NlZCsrOyAKICAgICAgICByZXN1bHRzLnB1c2goJzxkaXY%2B4pyFIDxzcGFuIHN0eWxlPSJjb2xvcjogZ3JlZW4iPlBBU1NFRDogJyArIGRlc2MgKyAnPC9zcGFuPjwvZGl2PicpOyAKICAgIH0gY2F0Y2goZXJyKSB7IAogICAgICAgIHJlc3VsdHMucHVzaCgnPGRpdj7inYwgPHNwYW4gc3R5bGU9ImNvbG9yOiBkYXJrcmVkIj5GQUlMRUQ6ICcgKyBkZXNjICsgJzwvc3Bhbj48cHJlIHN0eWxlPSJjb2xvcjogIzQ0NCI%2BJyArIGVyciArICc8L3ByZT48L2Rpdj4nKTsgCiAgICB9IAogICAgCiAgICBjb25zdCBhbGxQYXNzZWQgPSB0ZXN0c1J1biA9PT0gdGVzdHNQYXNzZWQ7IAogICAgCiAgICByZXR1cm4geyAKICAgICAgICBbVmFsdWVWaWV3ZXJTeW1ib2xdOiB7IAogICAgICAgICAgICB0aXRsZTogJ1Rlc3QgcmVzdWx0JywgCiAgICAgICAgICAgIEhUTUw6IGA8ZGl2PgogICAgICAgICAgICAgICAgJHtyZXN1bHRzLmpvaW4oJycpfSAKICAgICAgICAgICAgICAgIDxkaXYgc3R5bGU9ImZvbnQtd2VpZ2h0OiBib2xkIj4KICAgICAgICAgICAgICAgICAgICAke3Rlc3RzUGFzc2VkfSBvZiAke3Rlc3RzUnVufSB0ZXN0cyBwYXNzZWQuCiAgICAgICAgICAgICAgICAgICAgPGRpdiBzdHlsZT0iY29sb3I6ICR7YWxsUGFzc2VkID8gImdyZWVuIiA6ICJkYXJrcmVkIn0iPlRlc3Qgc3VpdGUgJHthbGxQYXNzZWQgPyAicGFzc2VkIiA6ICJmYWlsZWQifTwvZGl2PgogICAgICAgICAgICAgICAgPC9kaXY%2BCiAgICAgICAgICAgIDwvZGl2PmAgCiAgICAgICAgfSAgICAKICAgIH0KfQovKiAKLi4uc28gdGhhdCB3ZSBjYW4gcnVuIHRlc3RzIGZvciB0aGUgc29sdXRpb24KKi8KaXQoJ3Nob3VsZCBhZGQgdHdvIG51bWJlcnMgdG9nZXRoZXInLCAoKSA9PiB7IAogICAgY29uc3QgcmVzdWx0ID0gYWRkKDEsMik7IAogICAgZXhwZWN0KHJlc3VsdCkudG9FcXVhbCgzKTsgCn0pOyAKCml0KCdzaG91bGQgaGFuZGxlIGludm9jYXRpb25zIHdpdGggb25lIHBhcmFtZXRlcicsICgpID0%2BIHsgCiAgICBjb25zdCByZXN1bHQgPSBhZGQoMSk7IAogICAgZXhwZWN0KHJlc3VsdCkudG9FcXVhbCgxKTsgCn0pOwovKiAKVGhlIHNvbHV0aW9uIGVkaXRvciBhbmQgdGhlIHRlc3RzIGNvdWxkIGJlIGVtYmVkZWQgaW4gdGhlIHN5bGxhYnVzIHVzaW5nIHJ1bmtpdCBlbWJlZGRpbmcgKGh0dHBzOi8vcnVua2l0LmNvbS9kb2NzL2VtYmVkKS4gCgpUaGUgcnVua2l0IEFQSSB3b3VsZCBsZXQgdXMgc2VjcmV0bHkgaW1wb3J0IHRoZSBgdGVzdGAgbWV0aG9kIHVzaW5nIHRoZSBgcHJlYW1ibGVgIG9wdGlvbiwgYW5kIHRvIHBhc3MgdGhlIHNvbHV0aW9uIHRvIHRoZSB0ZXN0IHNjcmlwdCB1c2luZyB0aGUgYGdldFNvdXJjZWAgYW5kIGBzZXRQcmVhbWJsZWAgbWV0aG9kcy4KKi8%3D&minHeight=1302&fixedHeight=1442&location=&title=&oembed=true\\\" height=\\\"1442\\\" width=\\\"900\\\" scrolling=\\\"no\\\" frameborder=\\\"0\\\" allowfullscreen></iframe>\",\"width\":900,\"height\":1442,\"aspectRatio\":1.6022222222222222}}" %}
{% endtab %}
{% endtabs %}

{% api-method method="get" host="" path="" %}
{% api-method-summary %}
posts
{% endapi-method-summary %}

{% api-method-description %}
Get posts
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="sorted" type="string" required=false %}
in order
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% hint style="info" %}
Watch out!
{% endhint %}

{% embed data="{\"url\":\"https://runkit.com/djgrant/5ba2df9592bf930012ae2470\",\"type\":\"rich\",\"title\":\"RunKit\",\"description\":\"RunKit notebooks are interactive javascript playgrounds connected to a complete node environment right in your browser. Every npm module pre-installed.\",\"icon\":{\"type\":\"icon\",\"url\":\"https://runkit.com/favicon.ico\",\"aspectRatio\":0},\"embed\":{\"type\":\"reader\",\"html\":\"<iframe style=\\\"width: calc\(100% + 200px\); padding: 0; margin: 0 0 0 -100px; background: transparent;\\\" src=\\\"https://runkit.com/e?name=dde80286-ec7c-43db-9d19-7dcd2db6e217&base64source=LyogCkNvbXBsZXRlIHRoZSBgYWRkYCBmdW5jdGlvbiBzbyB0aGF0IGl0IHJldHVybnMgdGhlIHN1bSBvZiB0aGUgdHdvIHBhcmFybWV0ZXJzLgoqLwpmdW5jdGlvbiBhZGQoYSwgYikgewogICAgcmV0dXJuIGEgKyBiOwp9CgphZGQoMSwgMik7Ci8qIApIZXJlJ3Mgc29tZSBjb2RlIHRoYXQgY291bGQgYmUgaGlkZGVuIGF3YXkuLi4KKi8KY29uc3QgZXhwZWN0ID0gcmVxdWlyZSgnZXhwZWN0Jyk7IApjb25zdCB7IFZhbHVlVmlld2VyU3ltYm9sIH0gPSByZXF1aXJlKCJAcnVua2l0L3ZhbHVlLXZpZXdlciIpOyAKCmxldCB0ZXN0c1J1biA9IDA7IApsZXQgdGVzdHNQYXNzZWQgPSAwOyAKY29uc3QgcmVzdWx0cyA9IFtdOyAKCmZ1bmN0aW9uIGl0KGRlc2MsIGZuKSB7IAogICAgdGVzdHNSdW4rKzsgCiAgICB0cnkgeyAKICAgICAgICBmbigpOyAKICAgICAgICB0ZXN0c1Bhc3NlZCsrOyAKICAgICAgICByZXN1bHRzLnB1c2goJzxkaXY%2B4pyFIDxzcGFuIHN0eWxlPSJjb2xvcjogZ3JlZW4iPlBBU1NFRDogJyArIGRlc2MgKyAnPC9zcGFuPjwvZGl2PicpOyAKICAgIH0gY2F0Y2goZXJyKSB7IAogICAgICAgIHJlc3VsdHMucHVzaCgnPGRpdj7inYwgPHNwYW4gc3R5bGU9ImNvbG9yOiBkYXJrcmVkIj5GQUlMRUQ6ICcgKyBkZXNjICsgJzwvc3Bhbj48cHJlIHN0eWxlPSJjb2xvcjogIzQ0NCI%2BJyArIGVyciArICc8L3ByZT48L2Rpdj4nKTsgCiAgICB9IAogICAgCiAgICBjb25zdCBhbGxQYXNzZWQgPSB0ZXN0c1J1biA9PT0gdGVzdHNQYXNzZWQ7IAogICAgCiAgICByZXR1cm4geyAKICAgICAgICBbVmFsdWVWaWV3ZXJTeW1ib2xdOiB7IAogICAgICAgICAgICB0aXRsZTogJ1Rlc3QgcmVzdWx0JywgCiAgICAgICAgICAgIEhUTUw6IGA8ZGl2PgogICAgICAgICAgICAgICAgJHtyZXN1bHRzLmpvaW4oJycpfSAKICAgICAgICAgICAgICAgIDxkaXYgc3R5bGU9ImZvbnQtd2VpZ2h0OiBib2xkIj4KICAgICAgICAgICAgICAgICAgICAke3Rlc3RzUGFzc2VkfSBvZiAke3Rlc3RzUnVufSB0ZXN0cyBwYXNzZWQuCiAgICAgICAgICAgICAgICAgICAgPGRpdiBzdHlsZT0iY29sb3I6ICR7YWxsUGFzc2VkID8gImdyZWVuIiA6ICJkYXJrcmVkIn0iPlRlc3Qgc3VpdGUgJHthbGxQYXNzZWQgPyAicGFzc2VkIiA6ICJmYWlsZWQifTwvZGl2PgogICAgICAgICAgICAgICAgPC9kaXY%2BCiAgICAgICAgICAgIDwvZGl2PmAgCiAgICAgICAgfSAgICAKICAgIH0KfQovKiAKLi4uc28gdGhhdCB3ZSBjYW4gcnVuIHRlc3RzIGZvciB0aGUgc29sdXRpb24KKi8KaXQoJ3Nob3VsZCBhZGQgdHdvIG51bWJlcnMgdG9nZXRoZXInLCAoKSA9PiB7IAogICAgY29uc3QgcmVzdWx0ID0gYWRkKDEsMik7IAogICAgZXhwZWN0KHJlc3VsdCkudG9FcXVhbCgzKTsgCn0pOyAKCml0KCdzaG91bGQgaGFuZGxlIGludm9jYXRpb25zIHdpdGggb25lIHBhcmFtZXRlcicsICgpID0%2BIHsgCiAgICBjb25zdCByZXN1bHQgPSBhZGQoMSk7IAogICAgZXhwZWN0KHJlc3VsdCkudG9FcXVhbCgxKTsgCn0pOwovKiAKVGhlIHNvbHV0aW9uIGVkaXRvciBhbmQgdGhlIHRlc3RzIGNvdWxkIGJlIGVtYmVkZWQgaW4gdGhlIHN5bGxhYnVzIHVzaW5nIHJ1bmtpdCBlbWJlZGRpbmcgKGh0dHBzOi8vcnVua2l0LmNvbS9kb2NzL2VtYmVkKS4gCgpUaGUgcnVua2l0IEFQSSB3b3VsZCBsZXQgdXMgc2VjcmV0bHkgaW1wb3J0IHRoZSBgdGVzdGAgbWV0aG9kIHVzaW5nIHRoZSBgcHJlYW1ibGVgIG9wdGlvbiwgYW5kIHRvIHBhc3MgdGhlIHNvbHV0aW9uIHRvIHRoZSB0ZXN0IHNjcmlwdCB1c2luZyB0aGUgYGdldFNvdXJjZWAgYW5kIGBzZXRQcmVhbWJsZWAgbWV0aG9kcy4KKi8%3D&minHeight=1302&fixedHeight=1442&location=&title=&oembed=true\\\" height=\\\"1442\\\" width=\\\"900\\\" scrolling=\\\"no\\\" frameborder=\\\"0\\\" allowfullscreen></iframe>\",\"width\":900,\"height\":1442,\"aspectRatio\":1.6022222222222222}}" %}

