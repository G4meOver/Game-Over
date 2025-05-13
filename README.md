<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Top Up Game - OverYourLimits</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
      color: white;
    }
    header, footer {
      text-align: center;
      padding: 1rem;
      background-color: #111;
    }
    .container {
      padding: 2rem;
      max-width: 700px;
      margin: auto;
    }
    .card {
      background-color: #1e2a38;
      padding: 2rem;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.4);
      margin-bottom: 2rem;
    }
    input, select, button {
      width: 100%;
      padding: 1rem;
      margin-top: 1rem;
      border: none;
      border-radius: 8px;
    }
    button {
      background-color: #00c6ff;
      color: white;
      cursor: pointer;
      transition: background 0.3s;
    }
    button:hover {
      background-color: #007acc;
    }
    .status {
      font-size: 1.2rem;
      padding: 1rem;
      margin-top: 1rem;
      border-radius: 8px;
      text-align: center;
    }
    .success {
      background-color: #28a745;
    }
    .failed {
