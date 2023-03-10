# Quick Start

## 1. Create

### 1.1 Filename
Create a text file called **`space.txt`**.
Always use lower-case formatting for the filename.

### 1.2 Encoding
Make sure that the **`space.txt`** file is UTF-8 encoded to avoid issues with special characters and multiple languages.

---

## 2. Place

### 2.1. well-known Directory
In principle, the **`space.txt`** file should be placed under the `/.well-known/` path of your website. For example:

```
https://example.com/.well-known/space.txt
```

### 2.2. Root Directory
If the `/.well-known/` directory cannot be used for technical reasons, or if you want to use a fallback option, the **`space.txt`** file can also be placed in the `root` directory of your website. For example:

```
https://example.com/space.txt
```

The **`space.txt`** file can be placed in both locations of a website at the same time. Hence, the final directory structure for your website could look like this:

```
example.com/
├── index.html
├── space.txt
└── .well-known
    └── space.txt
```

---


## 3. Link


### 3.1. Head

Place a reference to the file using a `“help”` tag to the `<head>` section of your website. For example:

```
<link type="text/plain" rel="help" href="https://example.com/space.txt"/>
```


### 3.2. Button
Embed a **`space.txt`** button to your site and link it to your **`space.txt`** file.


---


## 4. Serve


### 4.1. Internet Media Type
The **`space.txt`** file should have an Internet Media Type of `text/plain`.


### 4.2. Protocol
The **`space.txt`** file must be served over HTTPS.
