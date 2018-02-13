# Generate Index Files
Auto generates recursively an index.html file indexing folder's content.

## Usage
Download this python script from https://cdn.byjokese.com/python/generate-index.py or from the lastest version in this repository: https://github.com/byjokese/Generate-Index-Files/releases.
1. Place the script into the root folder (root will be indexed also).
2. Execute the script.

The generated `index.html` file will look like:
```html
<!DOCTYPE html>
<html>
<head><title>Index of ./folderName</title></head>
<body>
    <h2>Index of ./folderName</h2>
    <hr>
    <ul>
        <li>
            <a href='../'>../</a>
        </li>
        <li>
            <a href='folder'>folder</a>
        </li>
        <li>
            <a href='folder2'>folder2</a>
        </li>
        <li>
            <a href='file.txt'>file.txt</a>
        </li>
    </ul>
</body>
</html>
```
