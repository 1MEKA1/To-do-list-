!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Персональный трекер продуктивности</title>
    <link rel="stylesheet" href="style.css">
    <style>
    body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 20px;
}
h1 {
    text-align: center;
    color: #333;
}
.task-input {
    display: flex;
    justify-content: center;
    margin-bottom: 20px;
}
#new-task {
    padding: 10px;
    font-size: 16px;
    width: 300px;
}
button {
    padding: 10px;
    font-size: 16px;
    margin-left: 10px;
    cursor: pointer;
}
ul {
    list-style: none;
    padding: 0;
}
li {
    background-color: #fff;
    margin-bottom: 10px;
    padding: 15px;
    border-radius: 5px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}
li.completed {
    text-decoration: line-through;
    opacity: 0.6;
} 
</style>
</head>
<body>
    <h1>Персональный трекер продуктивности</h1>
    <div class="task-input">
        <input type="text" id="new-task" placeholder="Введите новую задачу">
        <button onclick="addTask()">Добавить задачу</button>
    </div>
    <ul id="task-list"></ul>
    <script src="script.js"> 
        
    </script>
</body>
</html>
