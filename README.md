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
{% tab title="First Tab" %}
Hello
{% endtab %}

{% tab title="Second Tab" %}
Bye
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

