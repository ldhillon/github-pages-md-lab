---
layout: home
title: Home
permalink: /
---

# Welcome


This site is deployed using **GitHub Pages**.

All pages are written in **Markdown** and automatically converted to HTML.

## Navigation

[About](about/)
[Documentation](docs/)

---

## Example Content

Here is some Markdown formatting.

###  Bash code example
```bash
kubectl get pods

```

---

### Python code example

```python
import re

def find_words_with_alphabets_and_numbers(input_string):
    pattern = r'\b(?=\w*\d)(?=\w*[a-zA-Z])\w+\b'
    # Find all matches
    matches = re.findall(pattern, input_string)
    return matches

# Example usage
input_string = "Hello world123, this is a test string with 12345 and test1ng."
print(find_words_with_alphabets_and_numbers(input_string))
```

---

### Groovy code example

```groovy
//define the variable
def str = "Hello world"
def num = 10

println str
println num

//for loop in groovy
for(x in 1..5){
  println x //0,1,2,3,4,5
}

//Groovy also supports default parameter values:
def repeat(val, x=10){
  for(i in 0..<x){
    println val
  }
}

repeat("Lakhbir", 5)

//In Groovy, we can use scopes to define Collections or Arrays.

def arg = ["Groovy","Java","Python","nodeJS"]
println arg.class

println arg[3]

//Groovy also allows you to add or remove collections from collections.

def no = [1,2,3,4]
def no2 = no +5 //=[1,2,3,4,5]
def no3 = no - [2,3] //=[1,4]

//When adding elements to a collection, we can use the following methods

println arg.add("Ruby")
println arg << "Smalltalk"
println arg[5] = "C++"

// A further benefit to Groovy is its Operators:
String str1 = "123";
String str2 = new String("1234");
if(str1 == str2){
  println("equal");
}else{
  println("Not equal");
}

```

### Yaml code example

```yaml
---
apiVersion: v1
kind: PersistentVolumeClaim
metadata:
  name: energy-monitor-pvc
spec:
  accessModes:
    - ReadWriteOnce
  resources:
    requests:
      storage: 1Gi
  storageClassName: nfs-client

```

### JSON code example

```json
{
  "posts": [
    { "id": 1, "title": "json-server", "author": "typicode" }
  ],
  "comments": [
    { "id": 1, "body": "some comment", "postId": 1 }
  ],
  "profile": { "name": "typicode" }
} 
```
