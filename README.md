<!DOCTYPE html>

<head>
    <title>List-Example</title>
    <link rel = "stylesheet" type = "text/css" href = "Example.css">
</head>
<body>
    <header>
        <h1>List Example</h1>
    </header>
    <ol class = "the">
        <li>List Item 1</li>
            <ol type = "A">
                <li>Nested Item 1.1</li>
                <li>Nested Item 1.2</li>
            </ol>
        <li>List Item 2</li>
        <ol type = "i">
            <li>Nested item 2.1</li>
            <li>Nested item 2.2</li>
            <ul>
                <li>Nested item 2.2.1</li>
                <li>Nested item 2.2.2</li>
                <ul type = "circle">
                    <li>Nested item 2.2.2.1</li>
                    <li>Nested item 2.2.2.2</li>
                </ul>
                <li>Nested item 2.2.3</li>
            </ul>
            <li>Nested item 2.3</li>
        </ol>
        <li>List Item 3</li>
        <ul type = "disc">
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
        </ul>
        
    </ol>
</body>
