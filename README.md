body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #f4f7f9;
    color: #333;
    padding: 20px;
}

.container {
    max-width: 900px;
    margin: 0 auto;
    background: white;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
}

h1 { color: #0078d4; text-align: center; }

.upload-section, .list-section { margin-bottom: 30px; }

form {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
}

input[type="text"] {
    flex: 1;
    min-width: 200px;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

.file-input { width: 100%; margin: 10px 0; }

.btn-primary {
    background-color: #0078d4;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 4px;
    cursor: pointer;
}

.btn-primary:hover { background-color: #005a9e; }

table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 20px;
}

th, td {
    text-align: left;
    padding: 12px;
    border-bottom: 1px solid #eee;
}

th { background-color: #f8f9fa; }

.view-link { color: #0078d4; text-decoration: none; font-weight: bold; }
